# Documentación funciones Entrega 4

## Contexto

El proposito del ejercicio de la entrega 4 era optimizar el codigo de la entrega 3 y mostrar las 31 funcionalidades desarrolladas previamente ahora en la página web manipulando el DOM. 

De igual manera se pedía añadir estilos, con un framework propio, y una web semantica al ejercicio

## HTML

Se diseñó una web semantica con una lista ordenada en un aside al lado izquierdo de la pantalla, la cual contiene las 31 funcionalidades requeridas inicialmente en el software desarrollado para el ejercicio 3. En la parte derecha, se tienen tres secciones que mostraran al usuario, la funcion sobre la que se está consultando información, los parámetros, en caso de que los requiera, y el resultado de la consulta

Estas secciones son manipuladas por el DOM, desde JavaScript, para mostrar la información solicitada, sobreescribir los valores de los parrafos ya definidos y ocultar o mostrar las secciones y las listas para escoger los parámetros, según lo requiera la función

## DOM

Se creó una función principal llamada 
> seleccionarFuncion()

La cual se encarga de invocar la función en javascript correspondiente a la solicitada desde HTML por el usuario, por medio de un switch. Luego de hacer la consulta, asigna el resultado al innerText de un parrafo previamente definido en HTML

Adicionalmente, se tiene una función llamada
>consultarParametros

La cual se encarga de volver a realizar la consulta cuando el usuario hace click en el boton de consultar, luego de haber modificado los parámetros en las listas predefinidas
