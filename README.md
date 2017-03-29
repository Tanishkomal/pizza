<!DOCTYPE html>

<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.1/angular.js" type="text/javascript">
</script>
<script src="
</head>
<body>
<div>
    plain text : {{ 10 + 20 }}
</div>
<div ng-app="">
   <p> Enter you Name: <input type="text" ng-model="name"></p>
   <p> Hello <span ng-bind="name"></span>!</p>
   <p><input type="checkbox" ng-model="enableDisableButton">Disable Button</p>
   <p><button ng-disabled="enableDisableButton">Click Me!</button></p>
   <p><button ng-hide="enableDisableButton">Click to hide!<button></p>
   </br>
   <p>Total Click: {{ clickCounter }}</p>
   <p><button ng-click="clickCounter = clickCounter + 1">Click Me!<button></p>
   </div>
   <button onclick="read()">Read more</button>
   <button onclick="remove()">Read less</button>
</body>
</html>
