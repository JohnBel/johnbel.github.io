# EfsTools
EfsTools - консольная программа для доступа к файловой системе EFS модемов Qualcomm

Программа позволяет:
- Получить информацию о подключенном устройстве
- Получить информацию о параметрах файловой сиситемы EFS
- Прочитать файл из устройства в компьютер
- Записать файл из компьютера в устройство
- Удалить файл с устройства
- Переименовать (переместить) файл на устройстве
- Создать каталог в устройстве
- Удалить каталог на устройстве
- Получить список файлов и каталогов 
- Загрузить каталог из устройства на компьютер
- Загрузить каталог с компьютера на утройство.

## Системные требования

- Windows 10 1607 и новее, Windows Server 2012 R2 и новее, Mac OS X 10.13 и новее, Red Hat Enterprise Linux 7 и новее, CentOS 7 и новее, Ubuntu 16.04 и новее, Fedora 30 и новее, Debian 9 и новее, OpenSUSE 15 и новее
- [DotNet 5.0](https://dotnet.microsoft.com/download/dotnet/5.0) и выше.


## Релизы

### [EFSTools 0.14](https://github.com/JohnBel/EfsTools/archive/0.14.zip)

* Исправлена ошибка BadCommand на современных устройствах
* Добавлена команда запуска WebDAV сервера

[Скачать](https://github.com/JohnBel/EfsTools/archive/0.14.zip)


### [EFSTools 0.13](https://github.com/JohnBel/EfsTools/archive/0.13.zip)

* Импортированы из QXDM классы конфигурации (команды getModemConfig и setModemConfig)
* Реализовано автоматическое определение COM-порта в Linux и OSX

[Скачать](https://github.com/JohnBel/EfsTools/archive/0.13.zip)