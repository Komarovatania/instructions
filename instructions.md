# Инструкция по работе с Git в Visual Studio Code

## Основные функции GIT:

1. Чтобы посмотреть команды Git
> git

2. Чтобы посмотреть какую версию Git вы используете:
> git version

3. При первом использовании Git необходимо представиться в терминале:
> git config --global user.name "Your name"  
> git config --global user.email <почта@example.com>

4. Чтобы создать пустой репозиторий в Git:
> git init  

5. Чтобы получить информацию от git о его текущем состоянии:
> git status  

6. Чтобы добавить файлы к коммиту:
> git add filename  
> git add .

7. Чтобы создать коммит:
> git commit -m “message”

8. Чтобы создать сам коммит и добавить к нему файл или файлы:
> git commit -a -m "message"

9. Чтобы вывести на экран истории всех коммитов с их хеш-кодами:
> git log
