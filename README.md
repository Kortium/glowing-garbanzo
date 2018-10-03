# glowing-garbanzo
Проект менеджера календаря для Python+GTK

Входные данные для этой программы получаются путём "Выгрузки в Excel" информации по расписанию ИАСУ. Подходят расписания преподавателей, групп или аудиторий.

Чтобы обработать вашу выгрузку из ИАСУ под Linux:

* клонируйте репозиторий (git clone `https://github.com/nkapyrin/glowing-garbanzo`),
* положите XLS-файлы в `./groups`, `./rooms`, или `./profs`,
* удалите оттуда остальные папки,
* запустите sh `./run_all.sh`

Что бы обработать выгрузку из ИАСУ под Windows:

* клонируйте репозиторий (git clone `https://github.com/nkapyrin/glowing-garbanzo`),
* положите XLSX-файлы в `./groups`, `./rooms`, или `./profs` (конвертация XLS файлов под Windows не поддерживается в данной версии),
* удалите оттуда остальные папки,
* запустите `run_all.bat`

Системные требования
* python2.7

Необходимые библиотеки
* numpy
* openpyxl
* icalendar
* lxml
* qrcode
* matplotlib
* sys

