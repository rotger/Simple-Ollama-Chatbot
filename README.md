# Simple Ollama Chatbot

## [EN]

A simple Ollama chatbot that is easy to install and use.

### Instructions
1. Install Ollama.
1. Install your favorite model. For example, you can use the following command to install the qwen3 model: ```ollama pull qwen3```.
1. Set environment variable ```OLLAMA_ORIGINS=*```. On windows, you can set it simply by running this powershell command: ```[Environment]::SetEnvironmentVariable("OLLAMA_ORIGINS","*","User")```.
1. Make sure Ollama is running. Either by doing ```ollama serve``` in a terminal or by opening ollama.exe.
1. Copy the file ```simple_chatbot_EN.html``` to your disk.
1. Open the file ```simple_chatbot_EN.html``` in a web browser.
1. If you want to set specific model on page load write it in URL. For example ```Folder/with_file/simple_chatbot_EN.html?model=qwen3:14b```
1. If you want to use this in Firefox AI sidebar, you can set ```browser.ml.chat.provider``` to ```folder/with_file/simple_chatbot_EN```

If you want to modify the chatbot, you can edit the file ```simple_chatbot_EN.html``` in a text editor. The chatbot is written in HTML and JavaScript, so you can easily change the code to suit your needs.
Also, you can copy the code in the chatbot interface and ask your favorite ai model to make it better! In fact, the entire code was created by an AI.

### Support
Support the following features:
- Markdown
- Mathjax
- Code bloc synthax highlighting
- Attaching files (including pdf)
- Attaching images
- Scrape URL content found in the user input and send it to the model
- Dark and light mode toggle
- Firefox AI sidebar support


## [RU]

Простой чат-бот Ollama, который легко установить и использовать.

### Инструкции
1. Установите Ollama.
1. Установите свою любимую модель. Например, вы можете использовать следующую команду для установки модели qwen3: ```ollama pull qwen3```.
1. Установите переменную окружения ```OLLAMA_ORIGINS=*```. В Windows вы можете сделать это, просто запустив эту команду PowerShell: ```[Environment]::SetEnvironmentVariable("OLLAMA_ORIGINS","*","User")```.
1. Убедитесь, что Ollama работает. Либо выполнив ```ollama serve``` в терминале, либо открыв ollama.exe.
1. Скопируйте файл ```simple_chatbot_RU.html``` на свой диск.
1. Откройте файл ```simple_chatbot_RU.html``` в веб-браузере.
1. Если вы хотите поставить определённую модель во время загрузки страницы, укажите её в URL. Для примера ```Папка/с_файлом/simple_chatbot_RU.html?model=qwen3:14b```
1. Если вы хотите использовать это в ИИ боковой панели Firefox, вы можете установить ```browser.ml.chat.provider``` на ```Папка/с_файлом/simple_chatbot_RU```

Если вы хотите модифицировать чат-бота, вы можете отредактировать файл ```simple_chatbot_RU.html``` в текстовом редакторе. Чат-бот написан на HTML и JavaScript, поэтому вы можете легко изменить код в соответствии со своими потребностями.
Также, вы можете скопировать код в интерфейсе чат-бота и попросить свою любимую ИИ модель сделать его лучше! На самом деле, весь код был создан ИИ.

### Поддерживаемые функции:
- Markdown
- Mathjax
- Подсветка синтаксиса для блоков кода
- Прикрепление файлов (включая PDF)
- Прикрепление изображений
- Извлечение содержимого URL, найденного во вводе пользователя, и отправка его модели
- Переключение между темной и светлой темами
- Поддержка ИИ боковой панели Firefox
