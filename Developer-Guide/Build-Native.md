### Краткое руководство по сборке системы

#### Downloading the source code repository

* Код репозитория займёт **до** 500 (пятисот) мегабайт на диске
* Убедитесь, что скачиваете код в папку **не содержащую пробелов** в пути!
* Перейдите [на страницу репозитория](https://github.com/GreenteaOS/Kernel)
* Если Вы *не* пользуетесь Git то скачайте архив с кодом: <br/> ![image](https://cloud.githubusercontent.com/assets/3642643/19634448/d98f79fa-99c3-11e6-9d3e-009db22395e1.png)
* Для пользователей [Github for Desktop](https://desktop.github.com): <br/> ![image](https://cloud.githubusercontent.com/assets/3642643/19634404/61125858-99c3-11e6-9c36-60f5a814fcc1.png)
* В этой же папке будут сгенерированы временные файлы в процессе сборки и образы дисков
* For Git users: `git clone --depth 10 --recursive https://github.com/GreenteaOS/Kernel.git`

#### Installing the Build Environment

* Скачайте :fire: Flame :fire: [по прямой ссылке](https://github.com/GreenteaOS/Flame/archive/master.zip) или [на странице репозитория](https://github.com/GreenteaOS/Flame) 
* Распакуйте в рекомендуемый путь `C:\Flame` или отредактируйте в `environment.cmd` параметр `TOOLS` при распаковке по нестандартному пути
* Должна получиться папка `C:\Flame` с файлами `version.txt` (версия архива) и остальными (но не вложенная `C:\Flame\Flame`!)

#### Build, test and rebuild

* Перед началом сборки убедитесь, что в наличии **не менее гигабайта** свободного места на диске!
* Запустите из корня репозитория Kernel скрипт `build-bootcd.cmd` (двойным кликом по файлу) или `build-livecd.cmd` для построения установочного или живого диска соответственно
от числа затронутых зависимостей и конфигурации ПК
* The initial build takes approximately 40 (forty) minutes, depending on the configuration of the PC
* To rebuild it is enough to repeat the same procedure again, it can take from five seconds to several minutes,
* In the folder `output-MinGW-i386` in the case of successful build appears `livecd.iso` or `bootcd.iso`
