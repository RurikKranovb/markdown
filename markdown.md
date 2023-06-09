# Инструкция по использованию Markdown 

## Выделение текста

Что бы выделить курсивом необходимо выделить его (*) или (_). Например *вот так* или _так_. 

Что бы выделить полужирным (**) или (__). Например **вот так** или __так__.

Альтернативные способы выделения служат для совмещения в одном тексте обоих способов выделения. Например: _текст может быть выделен курсивом и при этом быть **полужирным**_.

## Списки 

Нумерованные списки просто нумеруем:
1. Первый
2. Второй
 
Не нумерованные списки выделяем (*) или (+). Вот так
* Элемент 1
* Элемент 2
+ Элемент 3

## Работа с изображениями 

Один из способов вставки изображения ссылка на картинку:

![название - описание картинки](ссылка на картинку)

Например:

![Зиверт](https://avatars.mds.yandex.net/i?id=0ea405571daaee5111e6b02217665af2eea127ed-4322260-images-thumbs&n=13)


Второй вариант ссылка на реальное изображение с указанием локального адреса.
Например:

![Мандалорец](mando.webp)


## Ссылки 

Возможно оформление ссылки в виде сноски. Когда в текст вставляется конструкция вида:

[Текст ссылки][Тег1]

 Указывающая, что именно в этом место будет располагаться ссылка, а где-нибудь ниже её описание:

[Тег1][Адрес ссылки]

Например:

I get 10 times more traffic from [Google][1] than from
[Yahoo][2] or [MSN][3].

[1]: http://google.com/        "Гугл"
[2]: http://search.yahoo.com/  "Яху"
[3]: http://search.msn.com/    "МСН"



Существует второй вариант оформления ссылок - обычная вставка в текст \[Текст ссылки](адрес "Описание")\.

Например:
[10 лучших GUI-клиентов Git для разработчиков]( https://techrocks.ru/2020/04/24/best-git-gui-for-mac-linux-windows/
)

## Таблицы ##

Создание таблиц с Markdown намного нагляднее, чем в HTML. Для выравнивания текста внутри ячеек используются знаки : в строке, отделяющей заголовок от основной таблицы.

Item      | Value | Quantity
:-------- |:-----:| -------:
Computer  | 1600  | 3
Phone     | 12    | 2
Pipe      | 1     | 1


## Цитаты
Пример второй:

> Arrrrhhhhaaaaa Vrraaaaahhhaar Rrrrraaaaaaahv (Если хочешь мира, готовся к войне).( собственно — Чубакка)

Под цитатами имеется в виду тег \<blockquote>\. Для их оформления применяется знак >. 

Например:
 > На темный путь единожды вступив,навсегда свяжешь с ним судьбу свою. (Йода) 

## Заключение

В последнее время все большую популярность приобретает Markdown - облегченный язык разметки *( wiki)*. И не удивительно. С одной стороны, для его использования не нужно изучать толстые книги и тратить кучу времени для "набивания руки" и знакомством с техническими особенностями. Это привлекает людей, далеких от IT сферы: писателей, дизайнеров и др.
Markdown (маркдаун) — облегчённый язык разметки созданный с целью написания максимально читабельного и удобного для правки текста, но пригодного для преобразования в языки для продвинутых публикаций (HTML, Rich Text и др.)

