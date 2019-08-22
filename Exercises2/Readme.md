Ejercicio 2
A usted se le ha encargado con hacer la implementación de un generador de ejercicios de
suma para ser utilizado en la creación de tareas de matemáticas para alumnos de 4to grado de
primaria. Un ejercicio típico de suma se muestra en la imagen a continuación y consiste en tres
partes:
1. Instruction: el mandato que el usuario lee
2. Problem: los números a sumar en el ejercicio
3. Options: las opciones que se presentan al usuario para que éste elija la respuesta
correcta
Escriba un programa en JavaScript, C#, C++ o Python (elija uno de su preferencia) para
generar un ejercicio de suma donde el output de dicho programa debe ser un JSON como se
muestra a continuación.
{
"instruction": "Selecciona el resultado de la siguiente suma.",
"problem": [
"13,064",
"66,318"
],
"options": [
"79,382",
"53,459",
"12,193",
"96,408"
],
"result": 0
}
