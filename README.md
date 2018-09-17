# Angular bootstrap date & time picker

Native AngularJS datetime picker directive styled by Twitter Bootstrap 4

[![MIT License][license-image]][license-url]
[![Build Status](https://travis-ci.org/UIPlatform/angularjs-bootstrap4-datetimepicker.svg?branch=bootstrap4)](https://travis-ci.org/UIPlatform/angularjs-bootstrap4-datetimepicker)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)
[![JavaScript Style Guide](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

Forked from [dalelotts/angularjs-bootstrap-datetimepicker](https://github.com/dalelotts/angularjs-bootstrap-datetimepicker)

updated to use bootstrap 4 instead of bootstrap 3

## Install 
```
npm i @ui-platform/angularjs-bootstrap4-datetimepicker
```

## Usage
Add the css:

```html
<link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.css"> <!-- "bootstrap": "^4.1.3"-->
<link rel="stylesheet" href="node_modules/@fortawesome/fontawesome-free/css/all.css"> <!-- "@fortawesome/fontawesome-free": "^5.3.1"-->
<link rel="stylesheet" href="node_modules/@ui-platform/angularjs-bootstrap4-datetimepicker/dist/datetimepicker.css"/>
```

Load the script files in your application:
```html
<script type="text/javascript" src="node_modules/moment/moment.js"></script> <!-- "moment": "^2.x" -->
<script type="text/javascript" src="node_modules/angular/angular.js"></script> <!-- "angular": "^1.x"-->
<script type="text/javascript" src="node_modules/@ui-platform/angularjs-bootstrap4-datetimepicker/dist/datetimepicker.js"></script>
<script type="text/javascript" src="node_modules/angular-date-time-input/src/dateTimeInput.js"></script> <!-- "angular-date-time-input": "^1.2.1" -->
```

Add the date module as a dependency to your application module:

```html
var myAppModule = angular.module('MyApp', ['ui.bootstrap.datetimepicker'])
```

Apply the directive to your form elements:

```html
<datetimepicker data-ng-model="data.date"></datetimepicker>
```