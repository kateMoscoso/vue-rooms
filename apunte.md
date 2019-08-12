¡Bienvenido al Curso Avanzado de Vue.js por Bedu!

En este curso vamos a aprender a construir interfaces de usuario profesionales sin dejar de lado la simplicidad y legibilidad de nuestro código. El proyecto es una aplicación como Airbnb para gestionar viviendas y registrar usuarios con Firebase.

En esta ocasión nos acompaña Javier Diaz Chamorro, él trabaja en CulturaColectiva como ingeniero de frontend y es experto del Bootcamp de Fullstack en Bedu.

¡Bienvenido al Curso Avanzado de Vue.js por Bedu!

En este curso vamos a aprender a construir interfaces de usuario profesionales sin dejar de lado la simplicidad y legibilidad de nuestro código. El proyecto es una aplicación como Airbnb para gestionar viviendas y registrar usuarios con Firebase.

En esta ocasión nos acompaña Javier Diaz Chamorro, él trabaja en CulturaColectiva como ingeniero de frontend y es experto del Bootcamp de Fullstack en Bedu.

s
¿Que son las Render Functions y JSX?
Las render functions son funciones que se encargan de renderizar contenido, interpretar nuestros elementos escritos en JavaScript y transformarlos a código plantilla. Estas funciones proveen mayor control de la lógica de negocio y permiten una transición o curva de aprendizaje más ligera.

Frameworks como React utilizan estas funciones gracias a JSX (una “JavaScript eXtension”) porque nos permite escribir código JavaScript similar a HTML y XML. Nosotros vamos a utilizar un plugin para implementar estas características con Vue.

Desventajas:

En ocasiones suele volverse complicado
Perdemos algunas características y directivas del framework (v-bind, v-if, v-for)
Generalmente, hay muy poca documentación


```
cd render_function
vue serve App.vue
```

**JSX** nos permite definir la estructura de nuestros componentes con una sintaxis similar a HTML con todos los beneficios de JavaScript. Recuerda que JSX es una syntax sugar para escribir componentes con createElement y resulta muy útil o familiar si estamos familiarizados con React.


##Utilizando Slots con Render Functions y JSX
Los Slots nos ayudan a crear componentes reutilizables y personalizables al mismo tiempo, nos permiten definir el contenido de nuestros componentes para evitar el trabajo de crear un nuevo archivo por cada cambio en los componentes. Son muy útiles e importantes en el mundo de Vue.js.