# BootCamp 20 Project 

Trello: https://trello.com/invite/b/tX3MOe8j/487d891e3fc60e47db9b60a7c2cbbd4b/my-adv

РАБОТА З “GIT” GitHub:
1) Клонируете себе dev : 
	git clone https://ccылка_на_репозиторий
2) Переходите в ветку dev. Забираете последние изменения в ветке dev. Потом создаете свою ветку находясь в ветке dev, с названием своей задачи:
	git checkout dev
	git pull origin dev
	git checkout -b name_your_branch
3) Работаете только в своей ветке, все изменения пушите ТОЛЬКО в нее: 
	git add .
	git commit -m “init name_your_branch”
	git push origin name_your_branch
4) Когда полностью завершили работу в своей ветке и хотите добавить эти изменения в общий проект:
	4.1) Переходите в ветку dev (и пулите все изменения которые внесли другие):
	git checkout dev
	git pull origin dev
	4.2) Переходим в свою ветку: 
	git checkout name_your_branch
5) Мерджите dev в свою ветку, разрешаешь конфликты которых то и быть не должно на самом деле:
	git merge dev
	Если есть конфликты, открываем свой редактор кода и решаем возникшие конфликты (при сложностях обращаемся к team lead’у).
	git add .
	git commit -m “пишем название конкретной задачи которую сделали(на английском)”
6) Пушите свою ветку на удаленку:
	git push origin name_your_branch
7) Создаете pull request на слитие с dev там на гитхабе:



8) КАЖДЫЙ КАЖДЫЙ РАЗ !!!  при изменениях, которые хотите сделать в общем проекте, повторяете порядок действий с пункта 2 по 7.
