ion-profile-picture
===================

A nice little directive for a profile picture selector

![Animated demo](https://github.com/israelidanny/ion-profile-picture/raw/master/demo.gif)

#Installation

Installation should be dead simple, you can grab a copy from bower:
```bash
bower install ion-profile-picture
```

Or clone this repository.

You'll need to add `ion-profile-picture` as a dependency on your Ionic app:
```javascript
angular.module('myApp', [
  'ionic',
  'ion-profile-picture'
]);
```

That's pretty much it. Now you can use the directive like so:
`<ion-profile-picture ng-model="myPicture" />`

`$scope.myPicture` will contain the Base64 contents of the selected image file, from there you can `$watch` it, or pretty much do anything you want. You can set the image concents directly by storing them in the `ng-model` variable.
