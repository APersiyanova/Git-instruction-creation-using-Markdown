# Второй семинар
<!---Used seminar material Hammatshin Almas,--->
<!---Youtube video Atlassian Creating & merging branches in Git - Git Guides (2020)--->

[Pro Git book by Scott Chacon](https://git-scm.com/book/en/v2)
## Создание веток /
git branch *- создавать, просматривать, переименовывать и удалять **ветку** - другой указатель на текущий commit*<br>
git branch 'branch name' <br>
git branch -m 'new branch name'

## Выбор
git checkout -b 'branch name' *- выбрать указатель на commit*

## редактирование /<br> индексация add/ фиксация commit   

git add <br>
git commit

## To verify that we are where we think we are
git branch *- аналог git branch --list*
## Слияние веток
* Fast-Forward *-non-conflict merge: Изменение второстепенной ветки, главная без изменений*
* 'ort' strategy *-non-conflict merge*

git merge 'branch name' *- not nsessery to commit merge <br>
не обязательно фиксировать*
## Handle conflicts
Конфликты при слияниях:
* 3-Way

## Удаление ветки
git branch -d *- не позволит удалить ветку, если в ней есть неслитые изменения* <br>
git branch -D *- принудительное удаление ветки, даже если есть неслитые изменения* <br>
git branch -a *- список удаленных веток*