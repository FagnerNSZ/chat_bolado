# chat_bolado

# animal.js
var method = Animal.prototype;

function Animal(age) {
    this._age = age;
}

method.getAge = function() {
    return this._age;
};

module.exports = Animal;

-----

# index.js

var Animal = require("./animal.js");
var john = new Animal(3);
console.log(john);
console.log(john._age);
   
------
# Resultado

     Animal { _age: 3 }
     3
