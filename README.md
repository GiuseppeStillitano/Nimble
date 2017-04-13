# Nimble
Nimble, a new HTML and CSS framework, created for responsive and mobile first web designs.

##About
Nimble is a new HTML5 and CSS3 framework created in order to facilitate the development of the front-end section of responsive and mobile-first web designs. 
* **LESS** - the fastest way to develop and the easiest to handle; it provides variables in order to control Nimble styles (color, typography, grid system, buttons, forms, icons).
* **Smart** - file HTML5, an excellent starting point for the development of a web project, ready for your Mark-up
* **Fast** - just download the package to save time in writing the common code
* **FlexBox** - a library callable from ```.flex```

##Installation
Download the package. Let’s start your project.

##Usage 
Nimble controls the general style: 
* Color
*	Typography
*	Grid system
*	Buttons
*	Forms
*	Icons

###Color
```
@primary-color: #27262c;
@secondary-color: #ea5456;
@third-color: #01D6A2;

@link-color: @primary-color;


@success-color: #3adb76;
@warning-color: #ffae00 + 40%;
@danger-color: red + 70%;

@white-color: #fff;
@grey-color: #ccc;
@grey-light-color: #efefef;
@grey-dark-color: #1a1a1a;
```
###Typhography
**Import of Local**
```
@font-face {
font-family: "Roboto";
src: 
	url(/font/roboto/Roboto-Regular.eot);
	font-weight: 400;
} 
```
**Import of Url**
```
@import url('https://fonts.googleapis.com/css?family=Playfair+Display:400,700,900');
```
**Variable**
```
@font-family-sans-serif: "helvetica", sans-serif;
@font-family-serif: 'Playfair Display', serif;
@font-family-monospace: 'Cutive Mono', monospace;

@font-size-h1: (@font-size-p * 2);
@font-size-h2: (@font-size-h1 - 3%);
@font-size-h3: (@font-size-h2 - 3%);
@font-size-h4: (@font-size-h3 - 3%);
@font-size-h5: (@font-size-h4 - 3%);
@font-size-h6: (@font-size-h5 - 3%);
@font-size-p: 13px;

@title-color: @primary-color;
```
###Grid System
```
@number-column: 12;

@grid-gutter-width: 20px;

@grid-float-breakpoint: 767px;

@row-md: 960px;
@row-xl: 1001px;
@row-xs: 767px;

@container-desktop: 1440px;
@container-tablet: 768px;
@container-phone: 320px;

@breakpoint-container-desktop: (@container-desktop - 1);
@breakpoint-container-tablet: (@container-tablet - 1);
@breakpoint-container-phone: (@container-phone - 1);
```
###Buttons
```
@btn-color-primary: @primary-color;
@btn-color-secondary: @secondary-color;

@btn-color-success: success-color;
@btn-color-warning: warning-color;
@btn-color-danger: dange-color;

@btn-radius: 2px;

@btn-text-color: @white-color;

@btn-radius-hover: 2px - 60%;
```
###Forms
```
@forms-background: @grey-light-color;
@forms-color: @primary-color;
@forms-border: 1px solid @grey-color;
@fomrs-height: 30px;
@forms-radius: @btn-radius;

@forms-background-active: @white-color;
@forms-border-active: @forms-border;
```
###Icons
```
@icon-color: @primary-color;
@icon-color-hover: @primary-color + 30%;
@icon-color-active: @primary-color + 60%;
```
