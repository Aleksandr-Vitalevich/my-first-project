# ___Глобальные настройки для локального репозитория___
---

## ___Команды___
---

> Для подписи регистрируем наше имя командой `git config --global user.name "name surname"`<br>
> Для электронной почты команда `git config --global user.email "email"`<br>
> Для проверки настроек команда `git config --global --list`<br>
> Общая команда. Для избегания строк в неправильной кодировке `git config --global core.quotepath off`<br>
> Для правильной настройки строк <br>
- macOS и Linux команды
	- `git config --global core.autocrlf input`
	- `git config --global core.safecrlf warn`
- Windows команды
	- `git config --global core.autocrlf true`
	- `git config --global core.safecrlf warn`

> Настройка основной ветки команда `git config --global init.defaultBranch main`

## ___Справка GIT___
---

> Подробная подсказка по git `git help -g`<br>
> Подсказка по команде `git help команда`<br>
> Для выхода из режима подсказки `Escape -> :wq -> Enter`<br> 

### ___Информация по изменениям___
---
|Дата|Изменения|
|:-:|:-:|
|13.05.2026|Создал первый список команд|
|13.05.2026|Добавили справку|
