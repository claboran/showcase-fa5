# ShowcaseFa5

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Adding FontAwesome 5 Free

The intent is to show how to use FontAwesome Version 5 in an Angular 6 application with plain HTML ```<i>``` Tag and CSS (SASS) like: 
```html
<i class="fab fa-angular"></i>
``` 
e.g use it as drop in replacement for FontAwesome 4.x.


__SASS import is the key:__

```scss
$fa-font-path: "../node_modules/@fortawesome/fontawesome-free/webfonts";

@import "~bootstrap/scss/bootstrap";

@import "~@fortawesome/fontawesome-free/scss/fontawesome";
// You need to load the font-face
@import "~@fortawesome/fontawesome-free/scss/solid";
@import "~@fortawesome/fontawesome-free/scss/brands";
@import "~@fortawesome/fontawesome-free/scss/regular";

```
