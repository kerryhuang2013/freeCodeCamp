---
title: Input Tag
localeTitle: Входной тег
---
## вход

HTML-тег можно включить в документ HTML следующим образом:

```html

<input type="text"> 
```

Это создает область, в которой пользователь может легко вводить информацию. Затем эта информация отправляется в базовую базу данных и сохраняется или используется далее в веб-сайте или приложении.

Ввод с «type = 'text» будет создавать однострочное поле, в котором можно ввести любую информацию. Другие распространенные типы входных данных включают, но не ограничиваются: кнопка, флажок, цвет, электронная почта и пароль.

### Наиболее распространенные типы

*   `text` : однострочное текстовое поле.
    
*   `button` : кнопка без по умолчанию.
    
*   `submit` : кнопка, которая отправляет форму.
    
*   `checkbox` : флажок, позволяющий выбирать / отменять значения.
    
*   `date` : для ввода даты (год, месяц и день).
    
*   `email` : для редактирования адреса электронной почты.
    
*   `file` : Позволяет пользователю выбрать файл.
    
*   `hidden` : не отображается, но его значение отправляется на сервер.
    
*   `number` : для ввода числа.
    
*   `password` : однострочное текстовое поле, значение которого закрыто.
    
*   `radio` : переключатель, позволяющий выбрать одно значение из нескольких вариантов.
    
*   `range` : элемент управления для ввода числа.
    
*   `url` : для ввода URL-адреса.
    

Пример:

```html

<input type="button"> 
 <input type="checkbox"> 
 <input type="color"> 
 <input type="email"> 
 <input type="password"> 
```

Входы имеют множество предопределенных атрибутов.

Некоторые обычно обнаруживаемые атрибуты включают автозаполнение, проверку и замещение.

```html

<input type="text" placeholder="This is a placeholder"> 
```

В приведенном выше примере отображается область, в которую вводится ввод, с заполнителем, в котором указано «Это местозаполнитель». После нажатия кнопки ввода и нажатия клавиши заполнитель исчезает и заменяется вашим собственным входом.

```html

<input type="checkbox" checked> 
```

В этом случае появляется флажок, и по умолчанию он проверяется атрибутом «checked».

Существует много разных типов входов и связанных атрибутов, которые можно найти в ссылке, приведенной ниже.

#### Дополнительная информация:

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input

https://www.w3schools.com/tags/tag\_input.asp