# ¿Qué es Lint?
Pertence a las herramientas de análisis estático. Analisa nuestro código en busca de errores, pudiendo darte sugerencias para arreglarlo y la posibilidad de arreglarlos en automático.

# ¿Qué es ESLint?
Está enfocado en el proceso de "lintig" para javascript.Limpia nuestro código, tanto en el servidor (node.js) como en el navegador.

Mediante un sistema de reglas, permite definir que está permitido y que no dentro de nuestro código.

Sirve para:
-Mostrarte errores de sintaxis.
-Mostrarte errores cuando no se siguen buenas prácticas.
-Proveer sugerencias para mejorar tu código.
-Mantener un estilo consistente en tu código o reforzar reglas internas de tu propio equipo.

Está compuesto de 3 partes:
Parser:El parseador se encarga de convertir tu código, que es escrito para ser leído por un ser humano, a una representación o abstracción que permite que el computador pueda entender tu código.
Las reglas:Una regla es una colección de cierta lógica (función) que permite identificar un potencial problema en el código.
El resultado:Aquí es donde se define cómo se muestran los reportes de las reglas que se "infringieron". Por defecto se muestran en la consola, pero pueden ser visto también en el editor de texto favorito.

# ¿Qué es Prettier?
Su función es darle formato automaticamente a nuestro código. Tiene soporte para la sintaxis de la mayoría de lenguajes. Nos permite también personalizar nuestras reglas o usar las que vienen por defecto.

Dar formato a nuestro código nos permite trabajar mejor tanto en equipo como en proyectos personales, al tener un código limpio y ordenado es más fácil de comprender su estructura.

Su integración está disponible para los editores de texto e IDEs mas populares.

# ¿Qué es Editorconfig?
Nos sirve para darle formato a nuestro código mientras estamos escribiendo, a diferencia de prettier que nos da formato al guardar nuestros archivos.

Podemos usar editorconfig para definir la indentación, el salto de línea, el formato de caracteres que vamos a usar en nuestro proyecto.
Podemos seleccionar que  propiedades y valores deseamos configurar.