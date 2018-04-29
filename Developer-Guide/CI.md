### Ночные сборки и CI

#### What is CI and nightly build?

Continuous Integration - методология регулярной пересборки и тестирования непосредственно в процессе разработки.
Проверяется практически каждое внесённое изменение. Таким образом это делает возможным ранний отклик о качестве продукта.

#### When does the build take place?

* When a developer makes changes to the GreenteaOS/Kernel repository
* When the contributor sends a request to merge changes (Pull Request)
* When the contributor makes commits to his pull request

#### Where can I see the build status?

* При запросе на слияние во вкладке Conversation внизу можно будет увидеть довольно яркую отметку Build
жёлтого (в процессе), красного (сборка не удалась или содержит ошибки) и зелёного (сборка проведена) цвета.
* Курсором мыши можно обнаружить ссылку на лог сборки
* Не путать со статусом возможности слияния (Merge)!
* По ссылке https://ci.appveyor.com/project/PeyTy/kernel-vwmh6

#### Where to download a build?

Go to the website of the CI system, select the build of interest, and click on the Artifacts tab.

Official GreenteaOS/Kernel nightly builds take place here https://ci.appveyor.com/project/PeyTy/kernel-vwmh6/build/artifacts
