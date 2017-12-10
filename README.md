## Welcome to Json-Example
JSON (JavaScript Object Notation) is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate.

## Comments
---
Single line comments start with `//json`. For multi-line commands `/* json */` or `<!-- json -->` 

## Json Syntax
---
### Json data types:
* a string
* a number
* an object (JSON object)
* an array
* a boolean
* null

### Json number types:
* Integer
* Fraction
* Exponent

### Json Objects:
```js
{
"developer":{ "name":"Rafi", "age":20, "city":"Barisal" }
}
```
### Json Array:
```js
{
"developer":[ "Rafi", "Dhaka", "Bangladesh" ]
}
```
### Json Strings:
```js
{ "name":"Rafi" }
```
### Json Numbers:
```js
{ "year": 2017 }
```
### Json Booleans:
```js
{ "name": true }
```
### Json Null:
```js
{ "name": null }
```
### Example showing array containing multiple objects:
```js
{
   "devlopers": [
      { "name":"nahid" , "skill":"laravel" },
      { "name":"rid" , "skill":"php" },
      { "name":"rafi" , "skill":"html" }
   ]
}
```
## Json Objects
---
### Json Object Syntax:
```js
{ "name":"rafi", "age":10, "class":null, "year": true }
```
### Json Accessing Object Values:
```js
obj = { "name":"rafi", "age":10, "class":null, "year": true };
myobj= obj.name;
```
or
```js
obj = { "name":"rafi", "age":10, "class":null, "year": true };
myobj= obj["name"];
```
