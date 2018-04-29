### Краткое руководство по сборке системы

> Information is out of date

Сборка из под иных, чем Windows NT, операционных систем, производится с помощью проекта [Wine](https://www.winehq.org).
Предполагается, что читатель знаком с утилитами **wine** и **winetricks**, настроил их и они готовы к работе.

The process is radically no different from
[such as in Windows](Build-Native.md),
except for a few nuances.

#### Downloading the source code repository

Репозиторий можно поместить в домашнюю папку (в wine это путь `Z:\home\username\`).
Perform the procedure identical to [the article](Build-Native.md).

#### Installing the Build Environment

Set the environment as in [the article](Build-Native.md).

#### Build, test and rebuild

Перед выполнением данной процедуры необходимо найти файл `configure.cmd` в папке с кодом, и отредактировать его через gedit:

* Закомментируйте строку, следующую за `REM Detect presence of cmake`, добавлением слова `REM` в начале строки:
<br/>`REM cmd /c cmake --version 2> .....продолжение строки`
* Найдите строку, следующую за `if "%BUILD_ENVIRONMENT%" == "MinGW"`
* В конце строки параметр `"%REACTOS_SOURCE_DIR%"` необходимо заменить на путь к репозиторию (в формате wine), например:
<br/>`"Z:/home/username/Greentea/Kernel"`

Теперь можно открыть через wine ярлык на рабочем столе и выполнить configure, и далее, полностью аналогично исходной статье.
