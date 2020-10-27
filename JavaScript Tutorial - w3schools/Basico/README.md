# CONCEITOS BÁSICOS DE JAVA SCRIPT


# Exemplos do que o JavaScript pode fazer.

### JavaScript pode alterar o conteúdo HTML

 - Ele aceita aspas simples ou duplas

 <blockquote>
 	document.getElementById("demo").innerHTML = "Hello JavaScript";
 </blockquote>

 - Com o "document.getElementById("demo")" ele encontra o elemento HTML com o ID "demo"!

 - Com o ".innerHTML" ele altera o conteúdo!

### JavaScript pode alterar valores de atributos de HTML

 - Trocando o valor do atributo src!

 <blockquote>

 	< !DOCTYPE html>

	< html>
	< head>
		< title>Exemplo lampada</ title>
	< /head>
	< body>



	< button onclick="document.getElementById('myImage').src='pic_bulbon.gif'">Turn on the light</ button>

	< img id="myImage" src="pic_bulboff.gif" style="width:100px">

	< button onclick="document.getElementById('myImage').src='pic_bulboff.gif'">
	Turn off the light
	< /button>


	< /body>
	< /html>

 </blockquote>

### JavaScript pode alterar estilos HTML (CSS)


 <blockquote>
 	document.getElementById("demo").style.fontSize = "35px";
 </blockquote>

### JavaScript pode ocultar elementos HTML (CSS)


 <blockquote>
 	document.getElementById("demo").style.display = "none";
 </blockquote>

### JavaScript pode mostrar elementos HTML (CSS)

 <blockquote>
 	document.getElementById("demo").style.display = "block";
 </blockquote>

# JavaScript para onde

### A tag <script>

 - Em HTML, o código JavaScript é inserido entre as tags <script>e </script>.

 - Um JavaScript functioné um bloco de código JavaScript que pode ser executado quando "chamado".

 - Por exemplo, uma função pode ser chamada quando ocorre um evento , como quando o usuário clica em um botão.

 - Os scripts podem ser colocados na <body>, ou na <head>seção de uma página HTML, ou em ambas.

 <blockquote>

 	< !DOCTYPE html>

	< html>

	< head>

	< script>

	function myFunction() {
	  document.getElementById("demo").innerHTML = "Paragraph changed.";
	}

	< /script>

	< /head>

	< body>

	< h1>A Web Page</ h1>

	< p id="demo">A Paragraph</ p>

	< button type="button" onclick="myFunction()">Try it</ button>

	< /body>

	< /html>

 </blockquote>

 - Os scripts também podem ser colocados em arquivos externos!

 <blockquote>
 	<script src="myScript.js"></script>
 </blockquote>

 - Vantagens do JavaScript externo

	- Ele separa HTML e código
	- Torna HTML e JavaScript mais fáceis de ler e manter
	- Arquivos JavaScript em cache podem acelerar o carregamento da página

# Saída JavaScript

### Possibilidades de exibição de JavaScript


 - JavaScript pode "exibir" dados de maneiras diferentes:

 	- Escrevendo em um elemento HTML, usando innerHTML.

 <blockquote>


	< script>

	document.getElementById("demo").innerHTML = 5 + 6;

	< /script>


 </blockquote>

   - Escrevendo na saída HTML usando document.write().

   - Escrevendo em uma caixa de alerta, usando window.alert().
	
   - Escrevendo no console do navegador, usando console.log().



 - Impressão JavaScript

 <blockquote>

 	< button onclick="window.print()">Print this page</ button>

 </blockquote>

# Declarações JavaScript

  - Declaração de variaveis e palavras chaves!

  <blockquote>
	var x, y, z;    // Statement 1
	x = 5;          // Statement 2
	y = 6;          // Statement 3
	z = x + y;      // Statement 4
  </blockquote>

# JavaScript Syntax

### Link para os syntax, nada novo para mim !

  - https://www.w3schools.com/js/js_syntax.asp

  - JavaScript diferencia maiúsculas de minúsculas

  - As variáveis lastNamee lastname, são duas variáveis ​​diferentes

# JavaScript Comments

# JavaScript Variables

### Usando let e const (2015)

	- A versão 2015 do JavaScript (ES6 - ECMAScript 2015) permite o uso da const palavra-chave para definir uma variável que não pode ser reatribuída, e a letpalavra-chave para definir uma variável com escopo restrito.


# JavaScript Operators

### Operadores aritméticos JavaScript

 - Nada de novo : https://www.w3schools.com/js/js_operators.asp

 - ** : Exponentiation(ES2016)

 - typeof : Retorna o tipo de uma variável

 - instanceof : Retorna verdadeiro se um objeto é uma instância de um tipo de objeto

# Aritmética JavaScript

### Operador precedente

 - Como na matemática escolar tradicional, a multiplicação é feita primeiro.

 - Multiplicação ( *) e divisão ( /) têm precedência mais alta do que adição ( +) e subtração ( -).


# Atribuição de JavaScript

 - https://www.w3schools.com/js/js_assignment.asp

# JavaScript Data Types

### Data Types

 - https://www.w3schools.com/js/js_datatypes.asp

 - Infelizmente, em JavaScript, o tipo de dados de nullé um objeto.

 - undefinede nullsão iguais em valor, mas diferentes em tipo:

 <blockquote>

	typeof undefined           // undefined
	typeof null                // object

	null === undefined         // false
	null == undefined          // true

 </blockquote>

 <blockquote>

	typeof {name:'John', age:34} // Returns "object"
	typeof [1,2,3,4]             // Returns "object" (not "array", see note below)
	typeof null                  // Returns "object"
	typeof function myFunc(){}   // Returns "function"

 </blockquote>

# Funções JavaScript

### Funções

 - O operador () invoca a função

  - Usando o exemplo acima, toCelsiusrefere-se ao objeto de função e toCelsius()refere-se ao resultado da função.

  - Acessar uma função sem () retornará o objeto de função em vez do resultado da função.

 - Variáveis ​​Locais

  - Variáveis ​​declaradas em uma função JavaScript tornam-se LOCAL para a função.

  - Variáveis ​​locais só podem ser acessadas de dentro da função.

<blockquote>

</blockquote>

# JavaScript Objects

### Objects

 - Você pode acessar as propriedades do objeto de duas maneiras:

  - objectName.propertyName

  - objectName["propertyName"]

 - Um método é uma função armazenada como uma propriedade.

 <blockquote>

	var person = {

	  firstName: "John",
	  lastName : "Doe",
	  id       : 5566,
	  fullName : function() {
	    return this.firstName + " " + this.lastName;

	  }

	};

 </blockquote>


 - Em uma definição de função, thisrefere-se ao "proprietário" da função.


 - Tem valores diferentes dependendo de onde é usado:

   - Em um método, this refere-se ao objeto proprietário .

   - Sozinho, this refere-se ao objeto global .

   - Em uma função, this refere-se ao objeto global .

   - Em uma função, no modo estrito, this é undefined.
     
   - Os métodos gostam call()e apply()podem referir this- se a qualquer objeto .

   - Em manipuladores de eventos HTML, thisrefere-se ao elemento HTML que recebeu o evento:

   <blockquote>

 	 < button onclick="this.style.display='none'">

	   Click to Remove Me!

	 < /button>

   </blockquote>