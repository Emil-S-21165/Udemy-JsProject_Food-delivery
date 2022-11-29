Пет-проект - сервис по выбору стиля питания,  заказа питания и расчета калорий.

Этот проект был сделан на чистом JavaScript в рамках курса по JS на Udemy( https://www.udemy.com/course/javascript_full/ ) 

<<<<<<< HEAD
Статическая версия сайта (без отправки данных на сервер) доступна по ссылке --  https://pet-project-js-food-delivery.vercel.app/
 
=======
Проект сделан с отправкой и получением данных с сервера, однако по данной ссылке доступна только статическая версия сайта (без отправки данных на сервер) -- https://pet-project-js-food-delivery.vercel.app/
>>>>>>> cc9d42573416b1f928f0be6d763970823c578728

В данном JavaScript проекте были реализованы следующие функциональности:
- переключение табов "выбор стиля питания", а точнее переключение изображений с описанием  меню.
- запуск функции таймера для промоакций.
- создание модального окна для формы заказа, появление окна автоматически через определенное время или при прокрутки до конца страницы.
- создание шаблонов для формирования карточек "Наше меню на день" с использованием классов и c применением JSON.
- установка локального LAMP сервера, создание функции для отправки данных на сервер с использованием: промисов, async/await, JSON и FormData, 
  XMLHttpRequest, затем замена на fetch.
- написание функциональности слайдера изображений.
- функциональнсть для калькулятора по расчету рекомендуемых калорий согласно выбранным данным и критериям, 
  запоминание некоторых критериев после обновления страницы.
- разбиение проекта на модули и подключение webpack.

Для запуска проекта необходимо установить локальный сервер LAMP, MAMP, OpenServer и т.п.

команды для запуска:
$ npm install
$ json-server db.json

в другом терминале:
$ npx webpack

-----------------------------------------------------------------------------------------

Pet-project is a service for choosing food style, ordering meals and calculating calories.

This JavaScript project was made as part of a JS course on Udemy( https://www.udemy.com/course/javascript_full/ ) 

The static version of the site (without sending data to the server) is available 
<<<<<<< HEAD
 at the link --  https://pet-project-js-food-delivery.vercel.app/

=======
 at the link -- https://pet-project-js-food-delivery.vercel.app/ 
>>>>>>> cc9d42573416b1f928f0be6d763970823c578728

The following functionalities was implemented in this JS project:
- switching the "food style selection" tabs, more specifically switching the images with the menu description.
- launch a timer function for promotions.
- creating a modal window for the order form, the window also will appear automatically after a certain time or when scrolling to the end of the page.
- creation of templates to create the cards "Our menu for the day" using classes and JSON.
- setting up a local LAMP server, creating a function to send data to the server using: promise, async/await, XMLHttpRequest, 
  then changing it to fetch, JSON and FormData.
- Writing image slider functionality.
- functionality for the calculator to calculate the recommended calories according to the selected data and criteria, 
  remembering some criteria after refreshing the page.
- splitting the project into modules and connecting webpack.

To run the project you need to install a local server LAMP, MAMP, OpenServer, etc.

To start the project:
$ npm install
$ json-server db.json

in other terminal:
$ npx webpack
