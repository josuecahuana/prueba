|![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.001.png)|**UNIVERSIDAD NACIONAL DE SAN AGUSTIN FACULTAD DE INGENIERÍA DE PRODUCCIÓN Y SERVICIOS ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMA**|![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.002.png)|
| - | :-: | - |
|**Formato:** Guía de Práctica de Laboratorio / Talleres / Centros de Simulación|
|**Aprobación:  2022/03/01**|**Código: GUIA-PRLE-001**|**Página:** 1|
**INFORME DE LABORATORIO (formato estudiante)**



|**INFORMACIÓN BÁSICA**|
| - |
|**ASIGNATURA:**|Laboratorio Estructura de datos y algoritmos|
|**TÍTULO DE LA PRÁCTICA:**|*Java Tutorial/Methods*|
|**NÚMERO DE PRÁCTICA:**|*2*|**AÑO LECTIVO:**|*2022 A*|**NRO. SEMESTRE:**|*III*|
|**FECHA DE PRESENTACIÓN**|*10/05/2022*|**HORA DE PRESENTACIÓN**||
|<p>**INTEGRANTE (s):**</p><p>- César Alejandro Garay Bedregal</p><p>- Jean Carlo Leonel Chua Aguilar</p><p>- Josué Mathías Miguel Cahuana Aguilar</p><p>- Willy Alexander Huisa Perez</p><p>- Luis Edgar Arocutipa Gutierrez</p>|**NOTA:**||
|<p>**DOCENTE(s):**</p><p>*Richart Smith Escobedo Quispe - rescobedoq@unsa.edu.pe*</p>|


|**SOLUCIÓN Y RESULTADOS**|
| - |
|<p>I. **SOLUCIÓN DE EJERCICIOS/PROBLEMAS**</p><p>- Invertir un matriz de enteros (2 pts)</p><p>Para este método, lo primero que haremos será crear un array (Ain) en el cual se almacenarán los datos que vayamos a invertir. Después, en un ciclo "for" inicializamos dos contadores (i=0, j=A.length-1), de este modo mientras que "i" vaya aumentado de valor, "j" irá disminuyendo el suyo.</p><p>A medida que vayamos recorriendo el array, se irán asignando los valores de Ain (Ain[ i ] = A[ j ]) y cuando se termine el ciclo se retornará el array invertido (Ain).</p><p>![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.003.png)</p>|

|![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.001.png)|**UNIVERSIDAD NACIONAL DE SAN AGUSTIN FACULTAD DE INGENIERÍA DE PRODUCCIÓN Y SERVICIOS ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMA**|![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.002.png)|
| - | :-: | - |
|**Formato:** Guía de Práctica de Laboratorio / Talleres / Centros de Simulación|
|**Aprobación:  2022/03/01**|**Código: GUIA-PRLE-001**|**Página:** 2|
- Rotación a la Izquierda (3 pts)![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.004.png)

Para realizar este ejercicio se uso System.arraycopy para copiar los contenidos del array original al nuevo de forma más rápida, primero se copian los elementos que se moverán a la derecha, y luego los elementos que irán a la izquierda. Luego se devuelve el nuevo array con los elementos rotados a la izquierda

![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.005.png)

- Triángulo recursivo (4 pts)

El código de este ejercicio funciona gracias a este método, el cual nos pide el tamaño de la base anteriormente determinada. Para posteriormente declarar una variable int con valor 1. Y así empezar a dibujar el triángulo gracias al bucle for. El cual escribe “\*” hasta que sea mayor que la variable declarada inicialmente. Y de ahí aumentar el valor de esta hasta que esta sea mayor que la base y ahí se rompa el bucle.

![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.006.png)

- Lista (11 pts)

-Implementa una Lista usando POO con tipos genéricos siguiendo los estándares de Java. (Los métodos para una lista). <https://docs.oracle.com/javase/7/docs/api/java/util/List.html>

-Puede ignorar los siguientes métodos:

- hashCode()
- iterator()
- listIterator()
- listIterator(int index)
- retainAll(Collection<?> c)
- toArray()
- toArray(T[] a)

|![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.001.png)|**UNIVERSIDAD NACIONAL DE SAN AGUSTIN FACULTAD DE INGENIERÍA DE PRODUCCIÓN Y SERVICIOS ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMA**|![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.002.png)|
| - | :-: | - |
|**Formato:** Guía de Práctica de Laboratorio / Talleres / Centros de Simulación|
|**Aprobación:  2022/03/01**|**Código: GUIA-PRLE-001**|**Página:** 3|
El código se compone de dos clases principales, la primera se trata de una clase genérica básica, con la que se hicieron las listas, la otra clase principal hace uso de todas y cada uno de los métodos de una lista de objetos genéricos, a excepción de los que el ejercicio sugiere ignorar, para esto se instancian distintos objetos genéricos que se guardan en una lista en posiciones diferentes, y se crea otra lista que servirá para comprobar el uso de métodos como equals o isEmpty, los resultados se muestran en consola.![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.007.png)

![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.008.jpeg)![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.009.png)

(i) Implemente una clase Node donde T es un tipo genérico, esta clase debe contener al menos dos propiedades. ![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.010.jpeg)[https://docs.oracle.com/javase/tutorial/java/generics/types.html ](https://docs.oracle.com/javase/tutorial/java/generics/types.html)T data: la información almacenada en el nodo

Node<T> nextNode: una referencia al siguiente nodo

(ii) Implementar una clase List esta clase debe contener al menos esta propiedad

Node<T> root: la referencia sobre el nodo inicial

|![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.001.png)|**UNIVERSIDAD NACIONAL DE SAN AGUSTIN FACULTAD DE INGENIERÍA DE PRODUCCIÓN Y SERVICIOS ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMA**|![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.002.png)|
| - | :-: | - |
|**Formato:** Guía de Práctica de Laboratorio / Talleres / Centros de Simulación|
|**Aprobación:  2022/03/01**|**Código: GUIA-PRLE-001**|**Página:** 4|


|<p>![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.011.png)</p><p>Esto es lo fundamental de este ejercicio, porque al añadir estas creando un nuevo nodo y aplicando</p><p>las referencias a los objetos que hacen que este problema pueda resolverse, nótese que se establece una cabecera que indicará que el resto de nodos sean la “cola”.</p>|
| - |
|<p>II. **SOLUCIÓN DEL CUESTIONARIO**</p><p>- **¿Qué diferencia hay entre un List y un ArrayList en Java?**</p><p>La principal diferencia que existe entre un List y un ArrayList es que el primero es una interfaz y que el segundo es una clase respectivamente. A parte de ello se diferencian en que en List no se pueden crear instancias, mientras que en el ArrayList si se puede.</p><p>- **¿Qué beneficios y oportunidades ofrecen las clases genéricas en Java?**</p><p>El principal beneficio de las clases genéricas es que no hay transferencia forzada de tipos, esto trae como consecuencia la mejora en la eficiencia y en poder evitar errores que traería la transferencia forzada.</p>|
|<p>III. **CONCLUSIONES**</p><p>- Este trabajo fue repartido a cada uno de los integrantes con el fin de que cada uno pueda realizar los ejercicios en su respectiva rama, para así después hacer el merge a la rama main.</p><p>- En este trabajo pudimos aplicar nuestros conocimientos acerca  de bucles, Arrays, listas enlazadas, recursión, datos abstractos y clases genéricas, además de esta forma pudímos buscar información necesaria para poder realizar los ejercicios propuestos en este laboratorio.</p>|

|![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.001.png)|**UNIVERSIDAD NACIONAL DE SAN AGUSTIN FACULTAD DE INGENIERÍA DE PRODUCCIÓN Y SERVICIOS ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMA**|![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.002.png)|
| - | :-: | - |
|**Formato:** Guía de Práctica de Laboratorio / Talleres / Centros de Simulación|
|**Aprobación:  2022/03/01**|**Código: GUIA-PRLE-001**|**Página:** 5|
![](Aspose.Words.71d3ec1a-8c6f-4227-a454-c5826f1a704e.012.png)



|**RETROALIMENTACIÓN GENERAL**|
| - |
||


|**REFERENCIAS Y BIBLIOGRAFÍA**|
| - |
|<p><https://www.w3schools.com/java/></p><p>● *● ● ● ●*</p><p><https://docs.oracle.com/javase/7/docs/api/java/util/List.html></p><p><https://docs.oracle.com/javase/tutorial/java/generics/types.html></p><p>[*https://www.arquitecturajava.com/list-vs-arraylist-que-es-mejor/*](https://www.arquitecturajava.com/list-vs-arraylist-que-es-mejor/)</p><p>*http://puntocomnoesunlenguaje.blogspot.com/2012/12/arraylist-en-java.html*</p>|

