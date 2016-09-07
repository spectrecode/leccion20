#HOISTING
##PROBLEMA ORIGINAL
var feature = 'closures'; 
(function () {     
	if ( typeof feature === 'undefined' ){         
		var feature = 'callbacks';         
		console.log('JS coders love its ' + feature );     
	} else {         
		console.log('JS developers love its ' + feature );     
	} 
})();

**Se le agrega dentro del clousure marcado en negrito un parametro (num2) para que funcione el ejercicio return..

var feature = 'closures'; 
(function () {     
	if ( typeof feature === 'undefined' ){         
		feature = 'callbacks';         
		console.log('JS coders love its ' + feature );     
	} else {         
		console.log('JS developers love its ' + feature );     
	} 
})();

**RESULETO
se le quita el var antes del feature ="callbacks"