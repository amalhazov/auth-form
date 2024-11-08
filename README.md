## Задание:
Реализовать поле для ввода логина и кнопку "Отправить". При нажатии на нее идет запрос на сервер, на это время кнопка будет заблокирована. При успешном логине (admin) мы выведем имя пользователя ниже, в противном случае покажем ошибку на 5 секунд. Повторная отправка логина возможно только через 1 минуту, нужно добавить таймер, ведущий отсчет перед повторной отправкой логина.

## Комментарий по реализации:
1. Создал на Angular 17, но без использования standalone, условных конструкций, сигналов
2. Fake API реализовал через интерцептор
3. Не использовал сторонние библиотеки, в шаблоне все на HTML/SCSS, Angular + RxJS
4. Осознанно не прикручивал Husky, Linter, Prettier

# AuthFormTask

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.3.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Favicon
image: Flaticon.com
