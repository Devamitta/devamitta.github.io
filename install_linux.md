## Installing GoldenDict on Linux

First things first, dowload the latest version of Digital Pāḷi Dictionary [here]().

<!-- First things first, dowload the latest version of Digital Pāḷi Dictionary [here](https://drive.google.com/drive/folders/1W66OXwX6KQHnK0b-7E1enZJQLjXehit4?usp=sharing). -->

### Make a GoldenDict folder

It is recommended to make an easily accessible GoldenDict folder, for example /Documents/GoldenDict

![create new folder](https://user-images.githubusercontent.com/64521731/151519119-aee19fa1-6fcf-43e0-8395-85fe67398655.png)

Or in the terminal\
`mkdir /home/{your user name}/Documents/GoldenDict`

### Unzip

Right-click the DPD zip file in your Downloads folder and open with Archive Manager

![archive manager](https://user-images.githubusercontent.com/64521731/151268770-60483e5a-ddee-45fd-852f-3573b9a7c5d2.png)

Click Extract and select the folder `/Documents/GoldenDict`

![extract](https://user-images.githubusercontent.com/64521731/151269003-33b8bff0-d5fe-4860-b7b6-4b7a3ef80c41.png)

or in the terminal:

`cd home/{your user name}/Downloads`\
`unzip /home/{your user name}/Downloads/dpd.zip -d /home/{your user name}/Documents/GoldenDict`

### Install GoldenDict

GoldenDict can be installed directly with apt-get

`sudo apt-get update`\
`sudo apt-get install goldendict`

Or choose the distribution of your choice from [https://pkgs.org/download/goldendict](https://pkgs.org/download/goldendict)

Or directly from the Software Manager

![software manager](https://user-images.githubusercontent.com/64521731/151267260-93e3e1ce-61c8-4f09-a8d8-b8d3448cf694.png)

Make sure to install version 1.5, not version 1.0!

### Adding Dictionaries to GoldenDict

Launch the GoldenDict application

Go to Menu > Edit > Dictionaries (Shortcut **F3**)

![dictionaries F3](https://user-images.githubusercontent.com/64521731/151520353-72b82a7e-e27b-49bb-bb84-394ed7bac6f1.png)

Go to Sources > Files
Click Add and select folder /Documents/GoldenDict

![add](https://user-images.githubusercontent.com/64521731/151520594-7fc56dd9-6413-4526-8474-28db75941a61.png)

Click the recursive tick box √ (this makes sure GoldenDict searches in subfolders)

![recursive](https://user-images.githubusercontent.com/64521731/151520889-a1b2a2a9-3530-4d19-a4fa-7f96956b6ff5.png)

Click OK and wait a few moments while the dictionaries are indexing.

You're all setup!

Next learn the [set up the hotkey or scan pop](https://digitalpalidictionary.github.io/setup_hotkey.html) so you can click on any pāḷi word in any text and open it immediately in the dictionary.
