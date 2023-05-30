# Туториал по основам системы контроля версий git

## Инициализация проекта
**Чтобы начать вам потребуется инициализировать локальный репозиторий команндой:**

```fix
git init
```
## Добавление нового файла на отслеживание
**Используйте следующую команду:**

```fix
git add .
```
## Текущее состояние git
**Информация от git о его текущем состоянии выводится по команде:**

```fix
git status
```
## Получение истории изменений
**Следующая комманда выводит на экран истории всех коммитов с их хеш-кодами**

```fix
git log
```

## Просмотр разницы файла и коммита
**Иногда нужно увидеть разницу между текущим файлом и закоминченным в таких случаях комманда:**

```fix
git diff
```
# Инструкция(туториал) по разметке Markdown

## Исходный код

В чистом Маркдауне блоки кода отбиваются 4 пробелами в
начале каждой строки.
Но в GitHub-Flavored Markdown (сокращенно GFM) есть
более удобный способ: ставим по три апострофа (на букве
Ё) до и после кода. Также можно указать язык исходного
кода.
```html
<nav class="nav nav-primary">
 <ul>
 <li class="tab-conversation active">
 <a href="#" data-role="post-count"
class="publisher-nav-color" data-nav="conversation">
 <span class="comment-count">0
комментариев</span>
 <span class="comment-countplaceholder">Комментарии</span>
 </a>
 </li>
 <li class="dropdown user-menu" data-role="logout">
 <a href="#" class="dropdown-toggle" datatoggle="dropdown">
    <span class="dropdown-toggle-wrapper">
 <span>
 Войти
 </span>
 </span>
 <span class="caret"></span>
 </a>
 </li>
 </ul>
</nav>
```
Самое приятное, что в коде не нужно заменять угловые
скобки `< >` и амперсанд `&` на их html-сущности.

## Таблицы

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.
First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell
Для красоты можно и по бокам линии нарисовать:
| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |
Можно управлять выравниванием столбцов при помощи
двоеточия.
| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |
Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.
Для всего остального есть обычный HTML.

## Изображения

![vasya](https://plus.unsplash.com/premium_photo-1684923610356-001513e75d62?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=987&q=80)

**Если мы хотим добавить изображения ссылки, то нужно сделать следующую конструкцию**

```
![[альтернативный текст(ссылка)]](ссылка на другую картинку - наш перевертыш)
```

[![Фото Васи и Пети - нажми и получишь бонус](https://ic.pics.livejournal.com/kalinchevse/84151318/730070/730070_original.jpg)](https://images.unsplash.com/photo-1517649763962-0c623066013b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=870&q=80)
