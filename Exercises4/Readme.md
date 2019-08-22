Ejercicio 4
Siguiendo el formato de los Ejercicios 3 y 4, a usted se le ha encargado con hacer la
implementación de un generador de ejercicios de escritura de números para ser utilizado en la
creación de tareas de matemáticas para alumnos de 4to grado de primaria. Un ejercicio típico
de escritura de números se muestra en la imagen a continuación y consiste en tres partes:
1. Instruction: el mandato que el usuario lee
2. Problem: el número en dígitos a ser expresado con su nombre
3. Options: las opciones que el usuario debe ir seleccionando en el orden correcto para
formar el nombre del número en Problem
Escriba un programa en JavaScript, C#, C++ o Python (elija uno de su preferencia) para
generar un ejercicio de porcentajes donde el output de dicho programa debe ser un JSON
como se muestra a continuación. Puede aprovechar librerías de proveedores externos para
completar este Ejercicio.
{
"instruction": "Escribe el número siguiente presionando los botones
en el orden correcto.",
"problem": "47,935",
"options": [
"treinta y seis",
"once mil",
"ochenta y dos",
"treinta y cinco",
"mil novecientos",
"cuarenta y siete"
],
"result": "cuarenta y siete mil novecientos treinta y cinco"
}