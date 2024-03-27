Hola bienvenidos a el tema de arboles de derivación

Los árboles de derivación son estructuras gráficas utilizadas en el análisis gramatical y la teoría de lenguajes formales.
   - Un árbol de derivación es una representación visual que muestra cómo se puede derivar una cadena de símbolos a partir de las reglas de una gramática formal. Estas reglas definen cómo se construyen las cadenas válidas en un lenguaje.
   - Cada nodo en el árbol representa un símbolo (terminal o no terminal), y los arcos entre los nodos representan las reglas de producción aplicadas para derivar la cadena.
   - Los árboles de derivación son una herramienta fundamental en la teoría de compiladores y el análisis sintáctico.
 **Estructura**:
   - El árbol comienza con un único nodo raíz que representa el símbolo inicial de la gramática.
   - A medida que se aplican las reglas de producción, se agregan nodos y arcos al árbol.
   - Cada hoja del árbol representa un símbolo terminal (como una palabra en un lenguaje natural).
   - Los nodos internos representan símbolos no terminales y las reglas de producción aplicadas.
**Derivación**:
   - Para derivar una cadena, seguimos una ruta desde el nodo raíz hasta las hojas, siguiendo las reglas de producción.
   - Cada camino desde la raíz hasta una hoja representa una derivación válida de la cadena.
   - Los árboles de derivación son útiles para comprender cómo se construyen las cadenas y para verificar si una cadena pertenece al lenguaje generado por la gramática.
**Ejemplo**:
   - Supongamos que tenemos la gramática simple:
     ```
     S → A B
     A → a
     B → b
     ```
   - Si queremos derivar la cadena "ab", el árbol de derivación se vería así:
     ```
         S
        / \
       A   B
      /     \
     a       b
     ```
**Aplicaciones**:
   - Los árboles de derivación se utilizan en la construcción de compiladores para analizar la sintaxis de programas fuente.
   - También son útiles en la generación de código y en la comprensión de la estructura de las cadenas en lenguajes formales.

Bibliografías: 
(1) GRAMATICAS LIBRES DEL CONTEXTO - UNICEN. https://bing.com/search?q=arboles+de+derivacion.
(2) GRAMATICAS LIBRES DEL CONTEXTO - UNICEN. https://users.exa.unicen.edu.ar/catedras/ccomp1/Apunte5.pdf.
(3) 13 Derivación de gramáticas y ambigüedad - eafranco.com. https://docencia.eafranco.com/materiales/teoriacomputacional/13/Clase_13.pdf.
(4) Árbol de Derivación - Genially. https://view.genial.ly/6484d4c9e380930018a18593/presentation-arbol-de-derivacion.
(5) Arboles de derivación - información completa - Arboles de ... - Studocu. https://www.studocu.com/es-mx/document/instituto-tecnologico-de-saltillo/lenguajes-y-automatas-i/arboles-de-derivacion-informacion-completa/44318710.

Extras: 
Videos donde se pueden apoyar: 
* https://www.youtube.com/watch?v=RguJJoFXqfw
* https://www.bing.com/videos/riverview/relatedvideo?q=arboles+de+derivacion&mid=A40AF46630D879F7DC6EA40AF46630D879F7DC6E&FORM=VIRE
* https://www.youtube.com/watch?v=LAr9CsUAht8
* https://www.youtube.com/watch?v=qkJQpTzYPqs
El siguiente pdf me parecio interesante ya que abarca desde gramática: 
*http://ri.uaemex.mx/bitstream/handle/20.500.11799/34043/secme-16209.pdf?sequence=1
