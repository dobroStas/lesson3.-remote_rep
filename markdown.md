# Инструкция по работе с удаленным репозиторием

---
<u>_git push_</u> - добавить в gitHub новые езменения в документе.

<u>_git clone url_name_</u> - скачать репощиторий

<u>_git remote name_rem_rep_</u> - связываем удаленный репозиторий с локальным

<u>_git btanch -M branch_name_</u> - укзываем/переименовываем имя основной ветки

<u>_git pull_</u> - подтягиваем с основной ветки

>>>Fork

>>>git clone

>>>git branch Branch_name

>>>git push

>>>pull recuest





## Работа с изображением

Чтобы вставить изображение в текст достаточно написать следующее:
![Текст](images.jpg)

Картинка без `alt` текста

![](conflict.webp)

Картинка с альтом и тайтлом:

![Alt text](images2.jpg "Можно задать title")

Запомнить просто: синтаксис как у ссылок, только перед открывающей квадратной скобкой ставится восклицательный знак.

Картинки «сноски»:

![Картинка][image1]
![Картинка][image2]
![Картинка][image3]

[image1]: images3.jpg
[image2]: images4.jpg
[image3]: images5.jpg

Картинки-ссылки:

[![Alt text](images1.jpg)](http://example.com/)

[image1]: images3.jpg
[image2]: images4.jpg
[image3]: images5.jpg


### Заголовок третьего уровня ###

###### Заголовок 6 уровня ######

## Выделения текста

==================

Чтобы выделить текст курсивом необходимо обрамить его звездочками (*) или знаком нижнего подчеркивания(_). Например *вот так* или _вот так_

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками(**) или двойным знаком нижнего подчеркивания (__). Например **вот так** или __вот так__

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например _текст может быть выделен курсивом и при этом может быть **полужирным** 

***Косой жирный***

Полу___провод___ник


~~ Зачеркивание ~~

` блок кода `

Для вставки кода внутри предложений нужно заключать этот код в апострофы (на букве Ё). Пример: `<html class="ie no-js">`.

Если апостроф 
код надо обрамить 
двойными апострофами: 
``There is a literal backtick (`) here.``

=================

## Списки

===================

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой(*) или знаком (+) или згаком (-). Например:
* Элемент 1
- Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать. Например:
1. Элемент 1

>>>>>>>>>Цитата

2. Элемент 2

>>>>>>>>>Цитата

3. Элемент 3

>>>>>>>>>Цитата




===================

## Ссылки

=============

[Переход на страницу](http://exampl.com/ "Отображается при наведении. Необязательная")

а тут присваевается Id. Пока не понял зачем))

[Example][]

А вот [пример][1] [нескольких][2] [ссылок][id] с разметкой как у сносок. Прокатит и [короткая запись][] без указания id.

[1]: http://example.com/ "Optional Title Here"
[2]: http://example.com/some
[id]: http://example.com/links (Optional Title Here)
[короткая запись]: http://example.com/short

___теперь понял)))___


**И вот еще ```** 

```html
<nav class="nav nav-primary">
  <ul>
    <li class="tab-conversation active">
      <a href="#" data-role="post-count" class="publisher-nav-color" data-nav="conversation">
        <span class="comment-count">0 комментариев</span>
        <span class="comment-count-placeholder">Комментарии</span>
      </a>
    </li>
    <li class="dropdown user-menu" data-role="logout">
      <a href="#" class="dropdown-toggle" data-toggle="dropdown">
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

=======================

## Блоки ввода

==============


_первая часть текста_

---

_вторая часть текста_

__или (***)__ 


====================

## Цитаты

=============

>Это пример цитат,

>в которой перед каждой строкой

>ставится угловая скобка.

>Это пример цитаты,
в котрой угловая скобка ставится только перед началом нового параграфа

>Второй параграф.

### Вложение цитаты в цитату:

>Первый уровень цитирования
>
>>Второйуровень цитирования
>>
>>>Третий уровень цитирования
>
>Первый уровень цитирования

_max = 15-й_

================

## Команды

===============

**Задаем имя пользователя и имейл**

**git config --global user.name "your name"** - make a record in config of your name.

**git config --global user.emale "your email"** - make a record in config of your email.

__git add .\git_commit.md = git add .__ - track all files.

**git add file_name** - track a file name.

**git commit -m "Massege"** - fix changes in our project.

1. Добавляем файл
2. Делаем изменения
3. Трекаем файл
4. Делаем комит

**git commit -am "your_commit = git commit -m "your_commit" + git add .** - let us avoid using "git add" again.

__git revert "4 simbol of commit"__ - откатить на предыдущий commit.

__git chekout "4 simbol of commit"__ - checkout yor commit

**cls = clear** - очистить терминал.

**:wq** - consol of commit(or wQ)

**git diff** - show the differences between actual state and last commit.

======

**Существует 2 состояния:**
1. modified file - *git add, git commit -am*
2. untrucked file - *git add*


## Заключение

