# Контроль версий

| [English](README.md) | [Russian](README.ru.md) |

В этом репозитории собраны ссылки, обучающие материалы и инфографика для тех, кто
учится использовать систему контроля версий Git в целях разработки своих приложений,
работы над совместными проектами с друзьями или одногруппниками или внесения своих
вкладов в существующие проекты с открытым исходным кодом.

Репозиторий поддерживают:

 * Алексей Орленко ([@aqrln](https://github.com/aqrln))
   &lt;eaglexrlnk@gmail.com&gt;
 * Тимур Шемсединов ([@tshemsedinov](https://github.com/tshemsedinov))
   &lt;timur.shemsedinov@gmail.com&gt;

Если вы считаете, что нечто важное упущено или что-то непонятно, вы можете
[открыть
issue](https://github.com/HowProgrammingWorks/VersionControl/issues/new) или
создать pull request со своими предложениями, однако если вы ещё не знаете, как
это сделать, и вам нужна помощь с самыми азами, не стесняйтесь написать нам по
одному из email-ов выше ;)

## Установка Git

### Общие ссылки

* Официальный сайт Git: <https://git-scm.com>
* Клиенты с графическим интерфейсом (опционально, только для тех, кому слишком
  сложно использовать ПО без графического интерфейса; мы рекомендуем всё же
  освоиться с командной строкой):
   - в большинство IDE (в том числе WebStorm, PyCharm и другие продукты
     JetBrains, Xcode, Visual Studio) встроены свои средства для работы с Git и
     гораздо лучше использовать их, чем устанавливать отдельный GUI-клиент, если
     вы используете одну из этих IDE;
   - [GitHub Desktop](https://desktop.github.com/) для Mac и Windows (очень
     простой в использовании, но чрезвычайно ограничен в функциональности);
   - [SourceTree](https://www.sourcetreeapp.com/) для Mac и Windows;
   - [Tortoise Git](https://tortoisegit.org/) для Windows;
   - другие примеры: <https://git-scm.com/downloads/guis>.

### Windows

Если вам нужен только Git, загрузите установочный пакет по адресу
<https://git-scm.com/download/win>.  Если же вы хотите использовать [десктопный
клиент от GitHub](https://windows.github.com), обратите внимание на то, что он
уже включает в себя Git, поэтому отдельно его устанавливать не нужно.

### macOS

Простейший способ установить Git на macOS &mdash; это установить Xcode Command
Line Tools.  Система автоматически спросит у вас разрешение это сделать в
первый раз, когда вы попытаетесь вызвать Git, так что, по сути, вам для
установки не нужно делать ничего.

Если вы всё же предпочитаете самостоятельно установить более новую версию,
можете взять официальный установочный пакет по ссылке
<https://git-scm.com/download/mac> или установить Git с использованием
пакетного менеджера [Homebrew](https://brew.sh) при помощи команды `$ brew
install git`.

### Linux

Используйте менеджер пакетов вашего дистрибутива для установки
соответствующего пакета.  Примеры:

* основанные на Debian системы (в том числе Ubuntu и её разновидности, а также
  Linux Mint):
  `$ sudo apt-get install git-all`;
* Fedora: `$ sudo dnf install git`;
* Arch: `$ sudo pacman -S git`.

## Для начинающих

* [Попробуйте основы Git прямо в браузере](https://try.github.io/levels/1/challenges/1)
* [Шпаргалка по Git](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
* [Начало работы с GitHub](https://guides.github.com/activities/hello-world/)
* [Игнорирование файлов в репозитории](https://help.github.com/articles/ignoring-files/)
* [Ассоциирование редактора с Git](https://help.github.com/articles/associating-text-editors-with-git/)

## Повседневное использование

* [Интерактивный обучающий материал по принципам работы Git и основным командам](http://learngitbranching.js.org/)
* [Более продвинутая шпаргалка по Git](http://ndpsoftware.com/git-cheatsheet.html)
* [Что делать, если случайно в репозитории всё пошло не так](http://justinhileman.info/article/git-pretty/git-pretty.png)
* [Неплохая коллекция материалов по Git от ЦРУ](https://wikileaks.org/ciav7p1/cms/space_1736707.html)

## Материалы для продвинутого использования

* [Git Book](https://git-scm.com/book/en/v2)
* [Git Reference Manual](https://git-scm.com/docs)
