# Ejercicios-JavaScript-1
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
	<title></title>
</head>
<body>


<script type="text/javascript">
	

	  var selec=prompt('Ingrese un valor entre 1 y 10','');
  selec=parseInt(selec);    
  var num=parseInt(Math.random()*10)+1;
  if (num==selec)
    document.write('Ganó el número que se sorteó es el '+ num);
  else
    document.write('Lo siento se sorteó el valor '+num+' y usted eligió el '+selec);  


</script>
</body>
</html>
