#Conseitos basicos de Java Script


# Exemplos do que o JavaScript pode fazer.

## JavaScript pode alterar o conteúdo HTML

 - Ele aceita aspas simples ou duplas

 <blockquote>
 	document.getElementById("demo").innerHTML = "Hello JavaScript";
 </blockquote>

 - Com o "document.getElementById("demo")" ele encontra o elemento HTML com o ID "demo"!

 - Com o ".innerHTML" ele altera o conteúdo!

## JavaScript pode alterar valores de atributos de HTML

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

## JavaScript pode alterar estilos HTML (CSS)


 <blockquote>
 	document.getElementById("demo").style.fontSize = "35px";
 </blockquote>

## JavaScript pode ocultar elementos HTML (CSS)


 <blockquote>
 	document.getElementById("demo").style.display = "none";
 </blockquote>

## JavaScript pode mostrar elementos HTML (CSS)

 <blockquote>
 	document.getElementById("demo").style.display = "block";
 </blockquote>

