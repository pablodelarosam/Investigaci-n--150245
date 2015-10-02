# Investigaci-n--150245

Pablo de la Rosa Michicol -150245

Variables estáticas 
Son propias únicamente de la clase y no de los objetos que pueden crearse de la misma, por lo tanto, sus valores son compartidos por todos los objetos de la clase. Van precedidas del modificador static. 
Para invocar a una variable estática no se necesita crear un objeto de la clase en la que se define: 
* Si se invoca desde la clase en la que se encuentra definido, basta con escribir su nombre. 
* Si se le invoca desde una clase distinta, debe anteponerse a su nombre, el de la clase en la que se encuentra seguido del operador punto (.) <NombreClase>.variableEstatica 
Suelen emplearse para definir constantes comunes a todos los objetos de la clase. 


Ciclo de vida de las variables 


* Variables de instancia (u objeto): 
o Se crean cuando se crea el objeto que las contiene. 
o Se inicializan por defecto si no se hace de modo explícito: 
* 0 para números, "false" para booleano, "null" para objetos. 
o Se destruyen cuando el recolector de basura de Java no encuentra referencias activas para el objeto. 
* Variables estáticas : 

o Se crean cuando la clase se usa por primera vez. 
o Se inicializan por defecto si no se hace de modo explícito: 
* 0 para números, "false" para booleano, "null" para objetos 
o Suelen existir para el resto del programa (salvo que no esté cargado). 
* Variables locales (o de bloque): 
o Creadas en la sentencia en la que están definidas. 
o No se inicializan por defecto. Contienen datos imprevisibles. 
o Se destruyen al salir del bloque (en la llave final).

Variables de clase:

*Su ciclo de vida solo corresponde cuando la variable es llamada.
 
Memoria dinámica 

Es memoria que se reserva en tiempo de ejecución. Su principal ventaja frente a la estática, es que su tamaño puede variar durante la ejecución del programa. (En C, el programador es encargado de liberar esta memoria cuando no la utilice más). El uso de memoria dinámica es necesario cuando a priori no conocemos el número de datos/elementos a tratar. 
Pablo de la Rosa Michicol -150245

Clase 

En informática, una clase es una plantilla para la creación de objetos de datos según un modelo predefinido. Las clases se utilizan para representar entidades o conceptos, como los sustantivos en el lenguaje. Cada clase es un modelo que define un conjunto de variables -el estado, y métodos apropiados para operar con dichos datos -el comportamiento. Cada objeto creado a partir de la clase se denomina instancia de la clase. 

Objeto 

La programación orientada a objetos consiste en ordenar datos en conjuntos modulares de elementos de información del mundo real (denominado un dominio). Estos elementos de datos se llaman objetos. Estos datos se agrupan de acuerdo a las características principales del mundo real de estos elementos (tamaño, color, etc.). 
Instanciación 
En el paradigma de la orientación a objetos, una instancia se refiere a una realización específica de una clase o prototipo determinados. En general, cuando se ejecuta un programa en un computador, se dice que éste se instancia. En lenguajes que crean objetos a partir de clases, un objeto es una instancia de una clase. Esto es, un miembro de una clase que tiene atributos en lugar de variables. En un contexto del mundo real, podríamos pensar en "Perro" como una clase y en un perro concreto es una instancia de esta clase. 

Herencia 

La herencia es, después de la agregación o composición, el mecanismo más utilizado para alcanzar algunos de los objetivos más preciados en el desarrollo de software como lo son la reutilización y la extensibilidad. A través de ella los 
diseñadores pueden crear nuevas clases partiendo de una clase o de una jerarquía de clases preexistente (ya comprobadas y verificadas) evitando con ello el rediseño, la modificación y verificación de la parte ya implementada. La herencia facilita la creación de objetos a partir de otros ya existentes e implica que una subclase obtiene todo el comportamiento (métodos) y eventualmente los atributos (variables) de su superclase. 

Sobrecarga 

La sobrecarga se refiere a la posibilidad de tener dos o más funciones con el mismo nombre pero funcionalidad diferente. Es decir, dos o más funciones con el mismo nombre realizan acciones diferentes. El compilador usará una u otra dependiendo de los parámetros usados. A esto se llama también sobrecarga de funciones.




Referencias

http://estructuradedatosfitec.wikispaces.com/file/view/3_4+Var+Instancia+y+Clase.pdf

http://www.aprenderaprogramar.com/index.php?option=com_content&view=article&id=639:static-final-en-java-palabras-clave-variables-de-clase-o-campos-estaticos-y-constantes-ejemplos-cu00673b&catid=68:curso-aprender-programacion-java-desde-cero&Itemid=188

http://uqbar-wiki.org/index.php?title=Variables_y_métodos_de_clase
