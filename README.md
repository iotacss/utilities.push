# Push Utility #

The push utility is responsive for handling grid's before offset.


### Installation ###

```
npm install --save iotacss-push
```


### Dependencies ###

* [Settings.Default](https://github.com/iotacss/settings.default)
* [Settings.Column](https://github.com/iotacss/settings.column)
* [Settings.Breakpoint](https://github.com/iotacss/settings.breakpoint)


### Options ###

```
$iota-push-namespace  : 'push-' !default;
$iota-push--res       : false !default;
```


### Classes ###

```
.u-push-[column-number]/[total-columns-number]  // Example: .u-push-1/3


// Responsive Classes Syntax

.u-push-[column-number]/[total-columns-number]@[breakpoint-name]  // Example: .u-push-1/3@sm
```
