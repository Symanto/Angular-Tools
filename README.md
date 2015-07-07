# Angular-Tools
This package provides a toolset of small helper method that make your JavaScript and Angular life a bit easier.

## Intallation
###Bower
The easiest way to install the HttpService is by including the bower package to your solution
```shell
bower install symanto-angular-tools --save
```

## Usage
We provide the following helper methods for you:
### Array helper
#### getElementByName
Returns an element of a list that has the given string as .Name or .name property.
```javascript
var list = [{ Name: "Peter", Score: 15 }, { Name: "Bob", Score: 11 }, { Name: "Justus", Score: 23 }];

var element = getElementByName(list, "Bob");
if (element != -1) {
  // Found something
}
```

### JavaScript tools
#### isEmpty
Checks if a JavaScript object is (really) empty or undefined.
```javascript
var obj1 = undefined;
var obj2 = {};

var res1 = isEmpty(obj1); // = true
var res2 = isEmpty(obj2); // = true
```
