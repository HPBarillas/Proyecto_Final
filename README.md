# Proyecto final

# Programa de cotizaciones Empresa de seguros TK-U - Explicacion -

El siguiente programa se encarga de realizar cotizaciones de forma rapida y sencilla para que el usuario no lo tenga que hacer manual.

Tener en cuenta los siguientes aspectos:
1. Se necesita ingresar el nombre del asegurado y su edad.
2. Se necesita saber si el asegurado esta casado.
3. Si esta casado, se necesita la edad de su conyuge.
4. La cantidad de hijos, esta puede ser 0 si no se posee.
5. La cantidad de propiedades que posee el asegurado, puede ser o si no posee.
6. El salario mensual que tiene el asegurado.

# Partes a considerar

El programa calcula con el valor base de 2000 y sobre ese valor base se agregarn los recargos de la siguiente manera:

## Edad : Se calcula tanto la edad del asegurado como conyuge si es que esta casado.
1. Si esta en el rango de 18 a 24 años se recarga el 10% al valor base.
2. Si esta en el rango de 15 a 49 años se recarga el 20% al valor base.
3. Si esta en el rango de 50 años en adelante se recarga el 30% al valor base.

## Hijos : Solo se calcula la cantidad de hijos, ya que puede estar casado o no.
1. Se recarga el 20% al valor base por cada hijo que se agrege.

## Propiedades : Se realiza un recargo por cada propiedad que se posea.
1. Se recarga el 35% al valor base por cada propiedad que se agrege.

## Salario : Se realiza un recargo por el salario que recibe el asegurado.
1. Se recarga el 5% del salario que recibe el asegurado.

Todos estos recargos son sumados al Valor base para obtener el total.

# Mejoras

## Implementadas 

El programa lleva un conteo de las cotizaciones que va realizando para poder ver cuantas cotizaciones relizo el usuario por cada sesion. 

Se debe de escribir "Continuar" para mantener la sesion activa, si se desea terminar la sesion se debe escribir "Salir".

## Deseables

Que el programa pueda guardar en un archivo de texto todas las cotizaciones por sesion para tener una bitacora completa.