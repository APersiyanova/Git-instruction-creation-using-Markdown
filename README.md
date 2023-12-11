# Instraction of using Git, created with markup language **Markdown**
<!---Для написания этой инструкции использованы:--->
<!---Материалы лекции gb.ru--->
<!---Материалы семинара gb.ru преподаватлель Хамматшин Алмас--->
Литература: <br>
![Git для профессионального промграммиста С.Чакон, Б.Штрауб](Image_ChakonStraubGIT.JPG) <br>
> Git - это контентно-адресуемая файловая система, на которую наложен пользовательский интерфейс от VCS

Полезные ссылки:<br>
[Установка VS Code](https://code.visualstudio.com/downloads) <br>
[Установка Git](https://git-scm.com/downloads) <br>
## Настройка окружения
* git version *-отобразить версию git*
* git --global user.name
## Инициирование репозитория
* git init *- инициировать локальный репозиторий*
## Добавление изменений
* *внести необходимые изменения файла*
* Ctrl + S *- сохранить изменения*
* git add . *- добавить файлы в индекс*
* git rm --cached 'file name' *- to unstage*
* git commit -m 'Комментарий' *- зафиксировать изменения*
* git commit -amend 'Новый комментарий' *- повторно зафиксировать изменения при необходимости внесения изменений в ранее данный комментарий*
## Переключение между фиксациями изменений (коммитами)
* git log *- отследить изменения*
* git checkout 'достаточно первых 4 символов коммита' *- вернуться к одному из непоследних коммитов*
* git checkout main (или master) *- восстановить последний коммит*
* git diff *- отобразить разницу между зафиксированным файлом staged changes и сохраненным файлом unstaged changes*
## Связь локального репозитория с удаленным
* git push -u *- Первоначальная связь локального репозитория с удаленным*
* git push *- Связь локального репозитория с удаленным*