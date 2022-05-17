| ![](RackMultipart20220517-1-jvmd7l_html_830890c661adbdb4.png) | **UNIVERSIDAD NACIONAL DE SAN AGUSTIN**** FACULTAD DE INGENIERÍA DE PRODUCCIÓN Y SERVICIOS ****ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMA** | ![](RackMultipart20220517-1-jvmd7l_html_9f4bcb0a52655a9c.png) |
| --- | --- | --- |
| **Formato:** Guía de Práctica de Laboratorio / Talleres / Centros de Simulación |
| **Aprobación: 2022/03/01** | **Código: GUIA-PRLE-001** | **Página:** 0 |

**INFORME DE LABORATORIO**

**(formato estudiante)**

| **INFORMACIÓN BÁSICA** |
| --- |
| **ASIGNATURA:** | Laboratorio Estructura de datos y algoritmos |
| **TÍTULO DE LA PRÁCTICA:** | _Java Tutorial/Methods_ |
| **NÚMERO DE PRÁCTICA:** | _2_ | **AÑO LECTIVO:** | _2022 A_ | **NRO. SEMESTRE:** | _III_ |
| **FECHA DE PRESENTACIÓN** | _10/05/2022_ | **HORA DE PRESENTACIÓN** |
 |
| **INTEGRANTE (s):**
- César Alejandro Garay Bedregal
- Jean Carlo Leonel Chua Aguilar
- Josué Mathías Miguel Cahuana Aguilar
- Willy Alexander Huisa Perez
- Luis Edgar Arocutipa Gutierrez

 | **NOTA:** |
 |
| **DOCENTE(s):**_Richart Smith Escobedo Quispe - rescobedoq@unsa.edu.pe_
 |

| **SOLUCIÓN Y RESULTADOS** |
| --- |
|
1. **SOLUCIÓN DE EJERCICIOS/PROBLEMAS**

- Invertir un matriz de enteros (2 pts)
 Para este método, lo primero que haremos será crear un array (Ain) en el cual se almacenarán los datos que vayamos a invertir. Después, en un ciclo &quot;for&quot; inicializamos dos contadores (i=0, j=A.length-1), de este modo mientras que &quot;i&quot; vaya aumentado de valor, &quot;j&quot; irá disminuyendo el suyo. A medida que vayamos recorriendo el array, se irán asignando los valores de Ain (Ain[i] = A[j]) y cuando se termine el ciclo se retornará el array invertido (Ain).

 ![](RackMultipart20220517-1-jvmd7l_html_80776164b37d223e.png)


- Rotación a la Izquierda (3 pts)


 Para realizar este ejercicio se uso System.arraycopy para copiar los contenidos del array original al nuevo de forma más rápida, primero se copian los elementos que se moverán a la derecha, y luego los elementos que irán a la izquierda. Luego se devuelve el nuevo array con los elementos rotados a la izquierda ![](RackMultipart20220517-1-jvmd7l_html_1d011083431dba06.png)










- Triángulo recursivo (4 pts)


 El código de este ejercicio funciona gracias a este método, el cual nos pide el tamaño de la base anteriormente determinada. Para posteriormente declarar una variable int con valor 1. Y así empezar a dibujar el triángulo gracias al bucle for. El cual escribe &quot;\*&quot; hasta que sea mayor que la variable declarada inicialmente. Y de ahí aumentar el valor de esta hasta que esta sea mayor que la base y ahí se rompa el bucle.

 ![](RackMultipart20220517-1-jvmd7l_html_e7102d91fb71ecb8.png)


- Lista (11 pts)
 -Implementa una Lista usando POO con tipos genéricos siguiendo los estándares de Java. (Los métodos para una lista).[https://docs.oracle.com/javase/7/docs/api/java/util/List.html](https://docs.oracle.com/javase/7/docs/api/java/util/List.html) -Puede ignorar los siguientes métodos:

  - hashCode()
  - iterator()
  - listIterator()
  - listIterator(int index)
  - retainAll(Collection\&lt;?\&gt; c)
  - toArray()
  - toArray(T[] a)


 El código se compone de dos clases principales, la primera se trata de una clase genérica básica, con la que se hicieron las listas, la otra clase principal hace uso de todas y cada uno de los métodos de una lista de objetos genéricos, a excepción de los que el ejercicio sugiere ignorar, para esto se instancian distintos objetos genéricos que se guardan en una lista en posiciones diferentes, y se crea otra lista que servirá para comprobar el uso de métodos como equals o isEmpty, los resultados se muestran en consola.

 ![](RackMultipart20220517-1-jvmd7l_html_88f614cb8b528ccb.png) ![](RackMultipart20220517-1-jvmd7l_html_201c5e8bf740bbf6.png) ![](RackMultipart20220517-1-jvmd7l_html_201c5e8bf740bbf6.png)















 (i) Implemente una clase Node donde T es un tipo genérico, esta clase debe contener al menos dos propiedades.[https://docs.oracle.com/javase/tutorial/java/generics/types.html](https://docs.oracle.com/javase/tutorial/java/generics/types.html) T data: la información almacenada en el nodo Node\&lt;T\&gt; nextNode: una referencia al siguiente nodo (ii) Implementar una clase List esta clase debe contener al menos esta propiedad Node\&lt;T\&gt; root: la referencia sobre el nodo inicial

 ![](RackMultipart20220517-1-jvmd7l_html_dcc455159ba7ddc3.png)

















Esto es lo fundamental de este ejercicio, porque al añadir estas creando un nuevo nodo y aplicando las referencias a los objetos que hacen que este problema pueda resolverse, nótese que se establece una cabecera que indicará que el resto de nodos sean la &quot;cola&quot;.


 |
|
1. **SOLUCIÓN DEL CUESTIONARIO**

- **¿Qué diferencia hay entre un List y un ArrayList en Java?**
 La principal diferencia que existe entre un List y un ArrayList es que el primero es una interfaz y que el segundo es una clase respectivamente. A parte de ello se diferencian en que en List no se pueden crear instancias, mientras que en el ArrayList si se puede.
- **¿Qué beneficios y oportunidades ofrecen las clases genéricas en Java?**
 El principal beneficio de las clases genéricas es que no hay transferencia forzada de tipos, esto trae como consecuencia la mejora en la eficiencia y en poder evitar errores que traería la transferencia forzada.
 |
|
1. **CONCLUSIONES**

- Este trabajo fue repartido a cada uno de los integrantes con el fin de que cada uno pueda realizar los ejercicios en su respectiva rama, para así después hacer el merge a la rama main.
- En este trabajo pudimos aplicar nuestros conocimientos acerca de bucles, Arrays, listas enlazadas, recursión, datos abstractos y clases genéricas, además de esta forma pudímos buscar información necesaria para poder realizar los ejercicios propuestos en este laboratorio.



 |

| **RETROALIMENTACIÓN GENERAL** |
| --- |
|
 |

| **REFERENCIAS Y BIBLIOGRAFÍA** |
| --- |
|
- [https://www.w3schools.com/java/](https://www.w3schools.com/java/)
- [https://docs.oracle.com/javase/7/docs/api/java/util/List.html](https://docs.oracle.com/javase/7/docs/api/java/util/List.html)
- [https://docs.oracle.com/javase/tutorial/java/generics/types.html](https://docs.oracle.com/javase/tutorial/java/generics/types.html)
- [_https://www.arquitecturajava.com/list-vs-arraylist-que-es-mejor/_](https://www.arquitecturajava.com/list-vs-arraylist-que-es-mejor/)
- _http://puntocomnoesunlenguaje.blogspot.com/2012/12/arraylist-en-java.html_
 |
