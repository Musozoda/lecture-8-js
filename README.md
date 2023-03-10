# lecture-8-js

# **Table of Contents**
### ***01.*** *Modules*
### ***02.*** *Export*
### ***03.*** *Import*

___ 
___

picture Synchronous

 # ***Modules***
>> ![](https://magarticles.magzter.com/articles/5307/201532/586616f6f1cdd/20-NODEJS-Modules-You-Need-To-Know.jpg)

___
- JavaScript modules allow you to break up your code into separate files.

Перевод :

- Модули JavaScript позволяют разбивать код на отдельные файлы.
___
- This makes it easier to maintain a code-base.

Перевод : 

- Это упрощает ведение кодовой базы.
___
- Modules are imported from external files with the import statement.

Перевод : 

- Модули импортируются из внешних файлов с помощью инструкции import.
___
- Modules also rely on type="module" in the <script> tag.

Перевод : 

- Модули также полагаются на type="module" в <script> теге.
___

____

# ***Export***

- Modules with functions or variables can be stored in any external file.

Перевод :

- Модули с функциями или переменными могут храниться в любом внешнем файле.
___

- There are two types of exports: Named Exports and Default Exports.

Перевод :

- Существует два типа экспорта: именованный экспорт и экспорт по умолчанию.
___

> ***Named Export***

- Let us create a file named person.js, and fill it with the things we want to export.

Перевод :

- Давайте создадим файл с именем person.js, и заполним его вещами, которые мы хотим экспортировать.
___

- You can create named exports two ways. In-line individually, or all at once at the bottom.

Перевод :

- Вы можете создать именованный экспорт двумя способами. В строке по отдельности или все сразу внизу.
___

picture Asynchronous

> ***Default Export***

- Let us create another file, named message.js, and use it for demonstrating default export.

Перевод :

- Давайте создадим еще один файл с именем message.js и используем его для демонстрации экспорта по умолчанию.
___
- You can only have one default export in a file.

Перевод :

- В файле можно экспортировать только один экспорт по умолчанию.

___
___
 # ***Import***
 
 - You can import modules into a file in two ways, based on if they are named exports or default exports.
 
Перевод :

- Импортировать модули в файл можно двумя способами, в зависимости от того, называются ли они экспортом или экспортом по умолчанию.
___

- Named exports are constructed using curly braces. Default exports are not.

Перевод :

- Именованные экспорты строятся с использованием фигурных скобок. Экспорт по умолчанию — нет.
___

