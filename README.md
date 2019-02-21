# chat_bolado



Como a comunidade Node.js garante que novos recursos da especificação JavaScript ECMA-262 sejam trazidos para os desenvolvedores do Node.js de maneira oportuna.

Você pode dar uma olhada nas classes JavaScript . Link MDN para classes JS Nas classes JavaScript do ECMAScript 6, este método fornece uma maneira mais fácil de modelar conceitos OOP em Javascript.

Nota : As classes JS funcionarão apenas no modo estrito .

Abaixo está um esqueleto de classe, herança escrita em Node.js (Used Node.js Version v5.0.0 )

Declarações de classe:

'use strict'; 
class Animal{

 constructor(name){
    this.name = name ;
 }

 print(){
    console.log('Name is :'+ this.name);
 }
}

var a1 = new Animal('Dog');
Herança:

'use strict';
class Base{

 constructor(){
 }
 // methods definitions go here
}

class Child extends Base{
 // methods definitions go here
 print(){ 
 }
}

var childObj = new Child();
