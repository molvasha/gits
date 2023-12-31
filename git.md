# Знакомство с Git

# Краткая инструкция #

* ## git init

Инициализация: указываем папку, в которой
git начнёт отслеживать изменения.
В папке создаётся скрытая папка .git

* ##  git status

Показывает текущее состояние гита, есть  
ли изменения, которые нужно закоммитить
(сохранить). 

*Чтобы вызвать ранее введённую команду,
пользуемся стрелками на клавиатуре.
Перебираем недавно введённые команды
нажатием стрелки «вверх».*

* ## git add

добавляет содержимое рабочего каталога  
в индекс (staging area) для последующего коммита. Эта команда дается после добавления
файлов. Писать название целиком не обязательно: терминал дозаполнит данные автоматически.

![это картинка](pic1.png)

* ##  git commit

зафиксировать или сохранить

__Для добавления сообщения нужно жно добавить комманду *-m "текст сообщения"*__

* ## git log

Журнал изменений

* ## git checkout
1. Переключение между версиями. 
2. Для работы нужно указать не только
интересующий вас коммит, но и вернуться  
в тот, где работаем, при помощи команды  
git checkout master.
> 3. Переключение между ветками.

Пример: https://gist.github.com/YordanGeorgiev/90c84066f8b4d80244b35af8112574de 

* ##  git diff

Показывает разницу между текущим файлом
и сохранённым

* ## git branch
Создать ветку можно командой git branch <название ветки>.
Делать это надо в папке с репозиторием
