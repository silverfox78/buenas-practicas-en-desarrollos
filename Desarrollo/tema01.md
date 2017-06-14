## **El Asesino que se encuentra tras tus pasos**

Un motivante en las buenas prácticas es entender este principio que ha pasado generación tras generación:

> Programa siempre como si el tipo que acabe manteniendo tu código fuera un psicópata violento que sabe dónde vives.
> 
> “Martin Golding”

Esta jocosa frase, hace referencia a que nuestra codificación debe resultar clara para quien asuma la labor de mantenerla en un futuro.
Esto aplica en todo lo que hacemos, desde la definición de los espacios de nombre a las variables que ocupamos.
 
Es usual que nuestro trabajo no sea para nosotros, así que lo ideal es antes de comenzar conocer cuales son las convenciones en la nomenclatura de los objetos que generamos, dependiendo de la madurez de la institución en la cual prestemos nuestro servicio es sí dispondrán o no esta especificación, en la situación de que no dispongan de ella, lo ideal es evitar la creatividad natural que nos puede invadir, lo mejor es acudir al consenso de la comunidad o de alguna institución representativa, por ejemplo:
 
* [Convenciones de nomenclatura Microsoft](https://msdn.microsoft.com/es-es/library/cc467490(v=vs.71).aspx)
 
* [Convenciones de nomenclatura Wikipedia](https://es.wikipedia.org/wiki/Convenci%C3%B3n_de_nombres_(programaci%C3%B3n))
 
* [Convenciones de nomenclatura Javascript](http://snowdream.github.io/javascript-style-guide/javascript-style-guide/es/naming-conventions.html)
 
* [Convenciones de nomenclatura IBM](https://www.ibm.com/support/knowledgecenter/es/SSLVQG_7.0.1/datacollection_survey_reporter_ddita/datacollection/reporter/xml/naming_conventions.html)

Lo importante de estas convenciones es evitar situaciones como la siguiente:
 
<!-- language: lang-js -->
```javascript
function a (b) { 
    var c = b + 3; 
    alert(c); 
};
```

Qué es lo no apropiado en el código que se puede apreciar, pueden responder las siguientes preguntas:
- ¿Cual es el propósito de la función?
- ¿Que tipo y propósito tiene el parámetro de la función?
- ¿Cual es la intención de la variable llamada *c* y que implica la adición del número *3*?
 
Para alguien con alguna experiencia puede tender a **SUPONER** qué es y qué hace cada elemento de esta función, pero esta acción es interpretativa, por ende, factible de un error interpretativo. La idea es que nuestro codigo sea universalmente claro, hay quienes recomiendan que la codificación se haga en un lenguaje más común, como por ejemplo el inglés, así obtenemos un código algo más cosmopolita, pero esto debe ser un acuerdo con nuestro cliente y su cultura en los desarrollos.
 
Una frase para cerrar este punto:
> Cualquier tonto puede escribir código que un ordenador entiende. Los buenos programadores escriben código que los humanos pueden entender.
> 
> "Martin Fowler"

