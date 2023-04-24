# NodeJS Notes 

## Modules

`module.exports` is used for exporting modules

### Example

``` 
const vehicle = {
    brand:"Honda",
    name:"Dio"
}  

module.exports = vehicle
```
These modules can be imported into other files with following method 

```
const vehicle = require("")
```
- Above syntax is called common JS 
- import syntax is called ES6