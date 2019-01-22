# Настройка UBUNTU 18.04 для разработчика
Настройка системы делится на несколько этапов:
> Установка программ их настройка
> Установка утилит их настройка
> Установка виртуального сервера его настройка
> Синхронизация с приложениями

### Установка программ
  - Visual Studio Code
    ```
    $ sudo apt update
    $ sudo apt install software-properties-common apt-transport-https wget
    $ wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
    $ sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
    $ sudo apt install code
    ```
  - PhpStorm [инструкция](https://www.jetbrains.com/help/phpstorm/install-and-set-up-product.html)
  - Chrome скачать и установить с deb
  - Opera скачать и установить с deb
  - Telegramm скачать и установить с deb
  - Skype скачать и установить с deb
  - Viber скачать и установить с deb
  - Slack скачать и установить с deb
  - Avocode скачать и установить с deb

### Установка утилит
  - Htop  через магазин приложений
  - Gparted через магазин приложений
  - 
### Plugins

Dillinger is currently extended with the following plugins. Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| Github | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |
