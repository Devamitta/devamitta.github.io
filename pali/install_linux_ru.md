## Установка GoldenDict на Linux

[Начать загрузку последней версии словаря](https://github.com/sasanarakkha/study-tools/releases/latest/download/ru-pali-dict.zip)

### Создание папки GoldenDict

Рекомендуется создать легкодоступную папку GoldenDict, например /Documents/GoldenDict

![create new folder](https://user-images.githubusercontent.com/64521731/151519119-aee19fa1-6fcf-43e0-8395-85fe67398655.png)

Либо использйте командную строку:

`mkdir /home/your_user_name/Documents/GoldenDict`

(Замените your_user_name вашим фактическим именем пользователя)

### Распаковка

Щелкните правой кнопкой мыши ZIP-файл словаря в папке «Загрузки» и откройте его с помощью диспетчера архивов.

![archive manager](https://user-images.githubusercontent.com/64521731/151268770-60483e5a-ddee-45fd-852f-3573b9a7c5d2.png)

Нажмите Извлечь и выберите папку `/Documents/GoldenDict`

![extract](https://user-images.githubusercontent.com/64521731/151269003-33b8bff0-d5fe-4860-b7b6-4b7a3ef80c41.png)

Либо использйте командную строку:

`cd home/your_user_name/Downloads`\
`unzip /home/your_user_name/Downloads/prd.zip -d /home/your_user_name/Documents/GoldenDict`

### Установка GoldenDict

GoldenDict можно установить напрямую с помощью apt-get:

`sudo apt-get update`\
`sudo apt-get install goldendict`

Или выберите нужный дистрибутив из [https://pkgs.org/download/goldendict](https://pkgs.org/download/goldendict)

Или напрямую из Центра Приложений

![software manager](https://user-images.githubusercontent.com/64521731/151267260-93e3e1ce-61c8-4f09-a8d8-b8d3448cf694.png)

Убедитесь, что установлена версия 1.5, а не версия 1.0!

### Добавление словарей в GoldenDict

Запустите приложение GoldenDict.

Зайдите в Меню > Правка > Словари (Горячая клавиша **F3**)

![dictionaries F3](https://user-images.githubusercontent.com/64521731/151520353-72b82a7e-e27b-49bb-bb84-394ed7bac6f1.png)

Во вкладке Источники > Файлы.
Нажмите Добавить и выберите папку `/Documents/GoldenDict`

![add](https://user-images.githubusercontent.com/64521731/151520594-7fc56dd9-6413-4526-8474-28db75941a61.png)

Установите флажок Рекурсивно √ (это обеспечит поиск GoldenDict во вложенных папках)

![recursive](https://user-images.githubusercontent.com/64521731/151520889-a1b2a2a9-3530-4d19-a4fa-7f96956b6ff5.png)

Нажмите OK и подождите несколько секунд, пока словари индексируются.

Установка и настройка завершены!

Далее можно посмотреть статьи как  [настроить горячие клавиши](https://devamitta.github.io/pali/setup_hotkey_ru.html) или [всплывающее окно](https://devamitta.github.io/pali/setup_scan_popup_ru.html), настройка функции по одному щелчку открывать любое слово на Пали в словаре.

[Главная](https://devamitta.github.io/pali/index.html)
