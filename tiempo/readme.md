#TIEMPO
**Se le agrega dentro del clousure marcado en negrito un parametro (num2) para que funcione el ejercicio return..

SE CREA UN EVENTO al cual se le agrega un html con los botones debidamente identificados 
 
window.addEventListener("load", function() {
    var boton = document.getElementById("calcular");
    boton.addEventListener("click", function() {
        var segundos = parseInt(document.getElementById("segundos").value);
        var numero = parseInt(document.getElementById("numero").value);

       var resultado = document.getElementById("resultado");

        setInterval(function(){ 
            resultado.innerHTML = numero ++; 
        },segundos * 1000);
        }); 
});