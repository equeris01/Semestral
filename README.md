# Semestral
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
<title>Tiendita</title> 
</head>
<body>
	<style type="text/css">
* { margin: auto; padding: 0; text-align: center }
#cabecera { font: times new roman 1.3em verdana; background-color: #731749; }
h1 { text-align: center ; padding: 0.5em }
#menu { float: left; width: 25%; background-color: #FFFFFF; }
#menu img { width: 35%; margin: 5%; cursor: pointer; }
#principal { float: left; width: 75%; }
#visor { width: 80%; margin: 1% }
#visor img { width: 100% }
</style>
<script type="text/javascript">
window.onload = function() { //tras cargar la página ...
visor1=document.getElementById("visor"); //referencia al visor
mititulo=document.getElementById("titulo"); //referencia al pie de foto
}
function mifoto(num) { //cambiar la imagen
         f="foto"+num+".jpg"; //ruta de la nueva imagen
         document.images["fotoVisor"].src=f; //cambiar imagen
         t=document.images["fotos"+num].alt; //texto de pie de foto
         mititulo.innerHTML=t; //cambiar pie de foto
         }
</script>
<div id="cabecera">
<h1><font size="60"><marquee>Venta de teléfonos online</marquee></font></h1>
</div>
<div id="menu">
<img src='foto1.jpg' alt='1. iPhone 12. Precio inicial: 809.00$' name='fotos1' onclick="mifoto(1)"/><br>
<img src='foto2.jpg' alt='2. Huawie p smart 2020. Precio inicial: 214.00$' name='fotos2' onclick="mifoto(2)" /><br>
<img src='foto3.jpg' alt='3. Samsung galaxy s20. Precio inicial: 1 400.00$' name='fotos3' onclick="mifoto(3)"/><br>
<a href="Semestral.html" target="_self">Ir a página principal</a><br>
<a href="Informacion.html" target="_sel">Ir a página de información</a><br>
<a href="https://www.apple.com/iphone/" target="_blank">Ir a la página de Apple</a><br>
<a href="https://www.huawei.com/en/?ic_medium=direct&ic_source=surlent" target="_blank">Ir a la página de Huawei</a><br>
<a href="https://www.samsung.com/latin/" target="_blank">Ir a la página de Samsung</a><br>
<a/>
</div>
<div id="principal">
<div id="visor">
   <img src='foto1.jpg' alt='1. iPhone 12. Precio inicial: 809.00$' name='fotoVisor'/>
   <div id="titulo">1. iPhone 12. Precio inicial 809.00$.</div>
   <a href="Formulario.html" target="_self">Llenar formulario</a>
   </div>
</div>
</body>
</html>
