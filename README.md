# Анализ данных для DH, hw1: GitHub

В этом домашнем задании Вам придется познакомиться с реализацией системы контроля версий `git` на платформе <https://github.com>. Системы контроля версий позволяют отслеживать изменения в документах, производить вовзврат к предыдущим версиям, определять автора и время изменения и т. п. `GitHub` -- это крупнейшая платформа, которая позволяет использовать `git` для того, чтобы хранить и совместно разрабатывать свои проекты в интернете. Каждый отдельный проект хранят в отдельном **репозитории** (repository), например, эта домашняя работа -- это репозиторий. В репозитории могут храниться файлы любого формата (но размером меньше чем 50 Мб), однако некоторые форматы легче смотреть на гитхабе (файлы с кодом, .csv файлы, изображения, легкие файлы .pdf). Каждое изменение файлов, которое пользователь хочет, чтобы хранилось в системе контроля версий, называется **коммит** (commit). С каждым репозиторием ассоциировано доменное имя, которе позволит хранить и отображать .html файлы, например, сайт нашего курса <https://agricolamz.github.io/DS_for_DH/> храниться в репозитории <https://github.com/agricolamz/DS_for_DH>.

## Задание 0.
Зарегестрируйтесь на сайте <https://github.com> и примите приглашение в репозитрий с Вашим домашним заданием.

## Задание 1.
Напишите Ваше имя, исправив `README.md` файл, чтобы написать свое имя. Для этого нужно нажать на значок 🖉 в правом верхнем углу, а потом, когда все изменения внесены, нужно нажать на зеленную кнопку `Commit changes` внизу.

Имя и фамилия: Даша Максимова

> Файл `README.md` -- это текстовый файл с [markdown](https://ru.wikipedia.org/wiki/Markdown) разметкой, который автоматически отображается в каждом репозитории.

## Задание 2.
Нажав на кнопки `Create new file` или `Upload file`, cоздайте новый файл `sequence.R`, который будет содержать функцию на языке R, выводящую в консоль последовательность чисел от 1000 до 10000 с шагом 1234.

```
[1] 1000 2234 3468 4702 5936 7170 8404 9638
```

Можно взглянуть [сюда](https://github.blog/2012-12-05-creating-files-on-github/), если возникли какие-то проблемы.

## Задание 3.
Чтобы сообщить о каких-то проблемах, связанных с каким-то репозиторием используют раздел `Issues`. Для тренировки, прочитайте, [как правильно задавать вопросы](https://stackoverflow.com/questions/5963269/how-to-make-a-great-r-reproducible-example) и  воспользуйтесь этим разделом и задайте какой-нибудь вопрос с примером кода.

## Задание 4.
Создайте папку `data` и положите туда датасет `mtcars` в формате `mtcars.csv`.

Можно взглянуть [сюда](https://github.com/KirstieJane/STEMMRoleModels/wiki/Creating-new-folders-in-GitHub-repository-via-the-browser), если возникли какие-то проблемы.

## Post Scriptum

В целом `GitHub` изначально разрабатывался для программистов, поэтому предполагается, что люди работают над некоторой локальной версией на своем компьютере, а не в интернет браузере, а потом коммитят свои изменения через коммандную строку. В связи с этим каждое изменение хорошо бы сопровождать осмысленным сообщением (в браузер версии, GitHub автоматически генерит какие-то варианты, например, `Update README.md` и т. п.). Знаний полученных в этой домашней работе будет достаточно, чтобы сдавать домашние задания по нашему курсу R, однако есть еще много чего интересного:

* ветки (branches)
* создание копий чужих репозиториев (fork)
* предложить свои изменения чужим репозиториям (pull request)
* рендеринг .html страниц на GitHub Pages (мы будем обсуждать)

Полезно знать про раздел [GitHub Guides](https://guides.github.com/).
