# ng-places-autocomplete
A fancy and simple diective for places autocomplete and quickly preview the place in a map window. Now support google places api and baidu places api.

# Demo
<a href="https://github.com/jacklma718/ng-places-autocomplete/index.html" target="_blank">
  DEMO
</a>

# Usage
Include the required libraries. <br>
This package is required jQuery please include jQuery on your project. <br>

#### Google places api:
```html
<script type="text/javascript" src="http://maps.googleapis.com/maps/api/js?libraries=places&sensor=false"></script>
```

#### Baidu places api:
```html
<script src="http://api.map.baidu.com/api?v=2.0&ak=YOUR API KEY"></script>
```

#### Declare a dependency on your angular app:
```javascript
var ngApp = angular.module('ngApp', ['ng-places-autocomplete']);
```

#### Add the directive to textbox, now enable places autocomplete with a map popup preview option:
```html
<input type="text" ng-places-autocomplete ng-model="location" map-popup>
```

#### or you can only enable the places autocmplete:
```html
<input type="text" ng-places-autocomplete ng-model="location">
```

#### Options:
map-popup &nbsp;&nbsp; - map popup preview window <br>
city &nbsp;&nbsp; - choose a specific city  &nbsp;&nbsp; # now only for baidu


# TODO:
test case
