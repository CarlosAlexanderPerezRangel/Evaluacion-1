# Evaluacion-1
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Hola</title>
</head>
<body>
<script>
let opcion = 0, operando_uno, operando_dos, operando_tres
while(opcion !=8){
	alert("Menu De Operaciones")
	opcion = prompt('Introduzca  que operacion se ralizara:'+'1: Suma / 2: Resta / 3: Multiplicacion / 4: Division / 5: Raiz Cuadrada / 6: Formula General / 7: Binomio Cuadrado Perfecto /8: Salir','')
	switch(parseInt(opcion)){
		case 1:  alert("Suma")
		operando_uno = prompt('Primer Operando:','')
		operando_dos = prompt('Segundo Operando:','')
		alert("Resultado:"+(parseInt(operando_uno) + parseInt(operando_dos)))
	break;
	case 2:  alert("Resta")
		operando_uno = prompt('Primer Operando:','')
		operando_dos = prompt('Segundo Operando:','')
		alert("Resultado:"+(parseInt(operando_uno) - parseInt(operando_dos)))
	break;
case 3:  alert("Muliplicacion")
		operando_uno = prompt('Primer Operando:','')
		operando_dos = prompt('Segundo Operando:','')
		alert("Resultado:"+(parseInt(operando_uno) * parseInt(operando_dos)))
	break;
case 4:  alert("Division")
		operando_uno = prompt('Primer Operando:','')
		operando_dos = prompt('Segundo Operando:','')
		alert("Resultado:"+(parseInt(operando_uno) / parseInt(operando_dos)))
	break;
case 5:  alert("Raiz Cuadrada")
		const numero = 25;
                const raizCuadrada = Math.sqrt(numero);
               alert("resultado" +raizCuadrada); //5
	break;
case 6:  alert("Formula General")
		var a = parseInt(prompt("Variable a"));
        var b = parseInt(prompt("Variable b"));
        var c = parseInt(prompt("Variable c"));
		
		function x1 (a, b, c){
			return (((-1)*b)-(Math.sqrt(Math.pow(b,2)) - (4*a*c)))/(2*a);
		}
        var resultado_x1 = x1 (a,b,c);
        alert("x1 =" + resultado_x1)
		function x2 (a, b, c){
			return (((-1)*b)-(Math.sqrt(Math.pow(b,2)) - (4*a*c)))/(2*a);
		}
        var resultado_x2 = x1 (a,b,c);
        alert("x2 =" + resultado_x2)
		
	    
	
     alert("solucion 1:" + solu1);
     alert("solucion 2:" + solu2);
break;
case 7:  alert("Binomio Cuadrado Perfecto")
        var a = parseInt(prompt("Variable a"));
        var b = parseInt(prompt("Variable b"));
        
        function yei(a,b){
        	return a^2 * b^2;
        }
     var result = yei (a,b)
     alert("bin =" + result);
    
	break;
case 8: alert("Gracias por usar el programa, nos vamos")
break;
default:alert("Por Favor Ingrese Una Opcion Valida.")
	}
}
</script>


</body>
</html>
