# Ejercicios-JavaScript-1
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<title>Contador de Dias Hasta Navidad</title>
</head>
<body>

<script languague="javascript">

//Fechas inicial y final

var Hoy=new Date()

var Nav=new Date(Hoy.getFullYear(), 11, 25)

var mseg_dia=1000*60*60*24

var dias

if (Hoy.getMonth()==11 && Hoy.getDate()>25)
Nav.setFullYear(Nav.getFullYear()+1)

dias = Math.ceil((Nav.getTime()-Hoy.getTime())/(mseg_dia))

document.write("Quedan "+dias+" dias hasta Navidad")


 </script>

</body>
</html>
