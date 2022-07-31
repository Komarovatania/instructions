## Изображения и видео

    Синтаксис Markdown для работы с картинками очень похожий. Разница в восклицательном знаке перед первыми квадратными скобками. Ссылке на картинку тоже можно присвоить определенный ID.

*необходимо использовать следующий синтаксис - ставим восклицательный знак, потом в квадратных скобках указываем текст, а в круглых - адрес файла с картинкой. Адрес относительный или абсолютный*. 

> ![image text](ссылка на изображение)  
 *ссылка на изображение точно такое же название, как и сохранено в вашу папку с репозиторием; ссылка на изображение в интернете;*

 ![Татьяна](image.jpg)

**Чтобы добавить изображение с использованием ссылок из интернета:** 

![image alt text](ссылка на изображение)

*Примеры:*
>![image alt text](https://miro.medium.com/max/1400/1*bvMUGHtl8oJP5rZPV7X8eg.png)

>![image alt text](https://i.redd.it/pq4h8ffhymo51.jpg)

>![image alt text](https://i.redd.it/icdv9tg5eyt61.jpg)

## Интересные команды, которые есть в GIT

> [-v | --version]  
> [-h | --help]  
> [-C <path>]  
> [-c <name>=<value>]  
> [--exec-path[=<path>]]  
> [--html-path]  
> [--man-path]  
> [--info-path]  
> [-p | --paginate | -P | --no-pager]  
> [--no-replace-objects]  
> [--bare]  
> [--git-dir=<path>]  
> [--work-tree=<path>]  
> [--namespace=<name>]  
> [--super-prefix=<path>]  
> [--config-env=<name>=<envvar>]
> <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)

Clone a repository into a new directory
> git clone

Create an empty Git repository or reinitialize an existing one
> git init

work on the current change (see also: git help everyday)

Add file contents to the index
> git add

Move or rename a file, a directory, or a symlink
> git mv

Restore working tree files
> git restore

Remove files from the working tree and from the index
> git rm

examine the history and state (see also: git help revisions)

Use binary search to find the commit that introduced a bug
> git bisect

Show changes between commits, commit and working tree, etc
> git diff

Print lines matching a pattern
> git grep

Show commit logs
> git log

Show various types of objects
> git show

Show the working tree status
> git status

grow, mark and tweak your common history

List, create, or delete branches
> git branch

Record changes to the repository
> git commit

Join two or more development histories together
> git merge

Reapply commits on top of another base tip
> git rebase

Reset current HEAD to the specified state
> git reset

Switch branches
> switch

Create, list, delete or verify a tag object signed with GPG
> tag

collaborate (see also: git help workflows)

Download objects and refs from another repository
> git fetch

Fetch from and integrate with another repository or a local branch
> git pull

Update remote refs along with associated objects
> push

'git help -a' and 'git help -g' list available subcommands and some

concept guides. See 'git help <command>' or 'git help <concept>'  
to read about a specific subcommand or concept.  

See 'git help git' for an overview of the system.
