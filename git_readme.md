![Git](https://git-scm.com/images/logo@2x.png)

# [Git](https://git-scm.com/) 
Консольная утилита для хранения, сравнения и анализа истории изменения файлов в проекте (можно и для других файлов).

>Дооформить инструкцию по работе с Git, используя возможности Markdown (цитаты, картинки, ссылки и т.п.) и приложить свой проект в заархивированном виде (всю папку целиком).

## Команды:

git status - 
git init - папка становится репозиторием. появляется новая скрытая папка с названием «.git», чтобы из репозитория снова сделать папку, достаточно всего лишь удалить скрытую папку «.git».
git add README.md - проиндексировать изменения, то есть явно сказать Git-у, что этот файл нужно учитывать в следующем коммите
git commit - кратко описать изменение
git clone - клонировать репозиторий из GitHub на свой ПК. команда clone не только скачивает файлы из интернета, но и инициализирует репозиторий в скачанной папке




## Важно!

После установки необходимо «представиться» системе контроля версий. 
git config --global user.email "e-m,z*cx
'git help -a' и 'git help -g' перечисляют доступные подкоманды и некоторые
концептуальные руководства. См. «git help <команда>» или «git help <концепция>».
чтобы прочитать о конкретной подкоманде или концепции.
См. «git help git» для обзора системы.@example.com"
git config --global user.name "Your Name"

 
Репозиторий отслеживает изменения во всех вложенных в него папках. 
не нужно создавать репозиторий внутри репозитория

GitKraken, Sourcetree, GitAtomic.

# VS Code
Файл README.md подсветился желтым цветом, а рядом с ним появилась буква M (означает Modified — изменен).
На панели Source Code появилась цифра 1, означающая, что есть одно изменение, которое можно зафиксировать.
Перейдем на панель Source Code. Слева находится список файлов, которые были изменены. Если кликнем на файл, то увидим какие именно изменения мы внесли: в этом случае добавили новую строчку This is the second commit.
просмотр изменений в файле
Теперь давайте зафиксируем наши изменения. Рядом с названием файла нажмем на «плюс», чтобы проиндексировать его. Это аналогично команде git add, которую мы выполняли ранее. Затем в поле Message внесем комментарий и нажмем кнопку Commit. Это аналогично команде git commit.





# Markdown 
облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций (HTML, Rich Text и других).
## Примеры разметки:

# Заголовок первого уровня
### Заголовок третьего уровня
###### Заголовок шестого уровня
Заголовок первого уровня
========================
Заголовок второго уровня
------------------------

*выделение* (например, курсив)
необходимо сделать ~~одну~~ другую вещь
**сильное выделение** (например, полужирное начертание)
> Данный текст будет заключен в HTML-теги <blockquote></blockquote>
[Текст ссылки](http://example.com/ "Необязательный заголовок ссылки")
Где-то среди текста встречается [текст ссылки][example].

Также ссылка повторяется [пример адреса][example].

Ссылка на [второй][foo] также [Bar][] ресурсы.

[example]: http://example.com/ "Необязательный заголовок ссылки"
[foo]: http://example.net/ 'Необязательный заголовок ссылки'
[bar]: http://example.edu/ (Необязательный заголовок ссылки)

![Alt-текст](http://example.com/ "Заголовок изображения")

* элемент маркированного списка
- ещё один элемент ненумерованного списка
+ буллеты элементов могут быть разными

1. Элемент нумерованного списка
2. Элемент №2 того же списка
9. Элемент №3 списка — элементы нумеруются по порядку, цифра в начале строки не имеет значения


Пример кода внутри строки (inline) `Hello world!`
Ниже начинается многострочный блок кода

    <!doctype html>
    <html>
        <head>
            <!-- Заголовок документа -->
        </head>
        <body>
            <!-- Тело документа -->
        </body>
    </html>

Блок кода завершился




>git
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
'git help -a' и 'git help -g' перечисляют доступные подкоманды и некоторые
концептуальные руководства. См. «git help <команда>» или «git help <концепция>».
чтобы прочитать о конкретной подкоманде или концепции.
См. «git help git» для обзора системы.