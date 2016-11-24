Приведен блок кода из текущего проекта.

В котором, находится верстка блока Слайдер и страницы, на котором он отображен.
В полноценном проекте для сборки использовался Webpack, код написан с использованием препроцессоров Jade(ныне Pug), Stylus, 
для трансляции ES6 в ES5 используется модуль Babel.

В папке block.slider:
- block.slider.controller.js - отвечает за логику слайдера, перехватывает и обрабатывает события скролла;
- block.slider.directive.js - формируется директива принимающая параметры;
- block.slider.jade - верстка с Jade;
- block.slider.styl - стили с Stylus;
- index.js точка входа. Подключение необходимых модулей и инициализация;

В папке main:
- main.controller.js - запрос к бэкенду на получение необходимых данных;
- main.jade - использование директивы из блока;
- main.route.js - роутинг, для отображения страницы при вызове текущего состояния.
