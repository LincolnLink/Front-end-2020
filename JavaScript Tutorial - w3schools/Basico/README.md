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

## Declarações JavaScript

<blockquote>
</blockquote>
