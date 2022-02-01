## Install GoldenDict on Linux

First things first, download the latest version of Digital Pāḷi Dictionary [here](https://drive.google.com/drive/folders/1W66OXwX6KQHnK0b-7E1enZJQLjXehit4?usp=sharing).

### Make a GoldenDict folder

It is recommended to make an easily accessible GoldenDict folder, for example /Documents/GoldenDict

![create new folder](https://user-images.githubusercontent.com/64521731/151519119-aee19fa1-6fcf-43e0-8395-85fe67398655.png)

Or in the terminal\
`mkdir /home/your_user_name/Documents/GoldenDict`

(Obviously, substitute your_user_name with your actual user name)

### Unzip

Right-click the DPD zip file in your Downloads folder and open it with Archive Manager.

![archive manager](https://user-images.githubusercontent.com/64521731/151268770-60483e5a-ddee-45fd-852f-3573b9a7c5d2.png)

Click Extract and select the folder `/Documents/GoldenDict`

![extract](https://user-images.githubusercontent.com/64521731/151269003-33b8bff0-d5fe-4860-b7b6-4b7a3ef80c41.png)

Or in the terminal:

`cd home/your_user_name/Downloads`\
`unzip /home/your_user_name/Downloads/dpd.zip -d /home/your_user_name/Documents/GoldenDict`

### Install GoldenDict

GoldenDict can be installed directly with apt-get:

`sudo apt-get update`\
`sudo apt-get install goldendict`

Or choose the distribution of your choice from [https://pkgs.org/download/goldendict](https://pkgs.org/download/goldendict):

Or directly from the Software Manager:

![software manager](https://user-images.githubusercontent.com/64521731/151267260-93e3e1ce-61c8-4f09-a8d8-b8d3448cf694.png)

Make sure to install version 1.5, not version 1.0!

### Adding Dictionaries to GoldenDict

Launch the GoldenDict application

Go to Menu > Edit > Dictionaries (Shortcut **F3**)

![dictionaries F3](https://user-images.githubusercontent.com/64521731/151520353-72b82a7e-e27b-49bb-bb84-394ed7bac6f1.png)

Go to Sources > Files.\
Click Add and select folder `/Documents/GoldenDict`

![add](https://user-images.githubusercontent.com/64521731/151520594-7fc56dd9-6413-4526-8474-28db75941a61.png)

Click the recursive tick box √ (this makes sure GoldenDict searches in subfolders)

![recursive](https://user-images.githubusercontent.com/64521731/151520889-a1b2a2a9-3530-4d19-a4fa-7f96956b6ff5.png)

Click OK and wait a few moments while the dictionaries are indexing.

You're all setup!

Next learn the [set up the hotkey or scan pop](https://digitalpalidictionary.github.io/setup_hotkey.html) so you can click on any pāḷi word in any text and open it immediately in the dictionary.
## Install GoldenDict on Windows



Here's how to set it up on Windows.

First download the latest version of GoldenDict: 
https://sourceforge.net/projects/goldendict/files/early%20access%20builds/GoldenDict-1.5.0-RC2-372-gc3ff15f-Install.exe/download

Run GoldenDict-1.5.0-RC2-372-gc3ff15f-Install.exe 
(it should be in your Downloads folder)

Choose your language. Click __OK__

Click Next

Click I Agree

Choose your install location. C:\Program Files\GoldenDict is default. Click Next

Click Install

Installing …

Click Finish

Unzipping DPD

Find the DPD.zip file in your Downloads Folder

Right Click and Extract All

Click Extract

Extracting …

Done

Setting up GoldenDict 

Run GoldenDict from the Start Menu

Open Menu > Edit > Dictionaries

Click Add

Navigate to the DPD folder and click Select Folder

Tick the Recursive Check Box and click Rescan Now

Wait while the dictionary gets indexed.

Once it is done, click Apply

Now DPD should appear as a dictionary.

Searching

Go to Menu > View and click Search Pane (Ctrl-S)

Start typing in the Search Bar and click the word you are looking for.

Search results will display in the main window.

Setting up a Hotkey

You can set up a hotkey to look up a word in GoldenDict while using any other software.

Go to Menu > Edit > Preferences (F4)

Choose your preferred hotkey and click OK
 
Select any Pāḷi word in any software or pdf and press the hotkey. A small GoldenDict window will open. DPD will automatically find any inflected word in the dictionary. 

Auto-Start
You can set GoldenDict to auto-start when your computer boots up.

Enjoy!

Already a GoldenDict user?

Just add the DPD folder to the folder which GoldenDict currently uses. 

To find that, open Edit > Dictionaries  (Shortcut F3) and look for the path where your GoldenDict files are kept.




