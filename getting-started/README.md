## Caso de uso #1

**Instrucción:**

Desarrollar un proyecto web full stack, utilizando solamente, para el frontend **HTML, CSS3, JavaScript (NO frameworks),** para el backend y contenedores **PHP y Docker**, finalmente PostgreSQL para la base de datos. La aplicación debe permitir gestionar información de variedades de café colombiano. El sistema debe aplicar un CRUD completo para la parte de los Admins que permita (crear, leer, actualizar y eliminar) para los distintos tipos de café almacenados en la base de datos. También debe implementar tarjetas dinámicas en el frontend que muestren la información de cada variedad y una interfaz completamente responsiva utilizando diseño web adaptable. El sistema debe estar organizado bajo arquitectura por capas:

**modelo–controlador–vista**, manejo seguro de formularios y conexión PDO en PHP.

Contexto: Soy una desarrolladora junior construyendo una aplicación para una empresa cafetera que quiere un sitio web informativo, rápido, seguro y fácil de navegar, destinado a usuarios que desean aprender sobre las variedades de café colombiano. La empresa desea en mantener un estilo visual que gire en torno al café (tonos marrones, dorados, crema, pasteles) y una interfaz clara. El proyecto servirá a la empresa como catálogo digital y también me servirá a mí como práctica profesional de desarrollo full stack.

Datos de entrada: 

- Nombre del tipo de café
- Región de origen
- Condiciones de cultivo
- Beneficios para la salud
- Imagen que represente al café

Los admins con el CRUD, podrán crear, leer, actualizar y eliminar los cafés almcenados

Indicador de salida:

Un sitio web funcional que cumpla con los siguientes criterios:

- **Base de datos PostgreSQL:** tablas creadas correctamente, llaves primarias, tipos adecuados y datos persistentes.
- **Backend en PHP con PDO:** API CRUD funcional y segura.
- **Frontend HTML, CSS, JS:** tarjetas generadas dinámicamente desde la BD, diseño responsivo, paleta de colores de café.
- **Flujo completo de interacción:** registrar → guardar → visualizar → editar → actualizar/eliminar.

## Caso de uso #1 ( otro prompt)

INSTRUCCIÓN: Analizar la interfaz de usuario actual del proyecto web “Café Colombiano” y generar una propuesta completa de mejoras visuales y de experiencia de usuario **sin alterar la estructura ya existente (HTML, JavaScript y CSS puro)**. Las recomendaciones deberán estar enfocadas únicamente en optimizar la presentación visual, interacción, navegación y legibilidad, comenzando específicamente por la vista de “cafe”. Además de identificar problemas, detallar soluciones aplicables y justificarlas con fundamentos UI/UX modernos.

**Contexto:**

Soy una desarrolladora junior que necesita mejorar la presentación del sitio para hacerlo más atractivo e intuitivo.
El cliente no desea cambios en la arquitectura ni migración a frameworks; sin embargo, quiere un diseño más estilizado, cálido y profesional con una temática **vintage**, inspirado en cafés tradicionales de Colombia. La marca solicita mantener predominantemente tonos **café, beige, crema y acentos en dorado**, con una prioridad xen la **experiencia visual del usuario, claridad lectora y fluidez de navegación**. También desea mantener tiempos de carga rápidos y animaciones suaves, sin saturar la vista ni dificultar el acceso a la información.

Se toma como referencia todo lo siguiente:

- Capturas de pantalla actuales de la vista “cafe
- Distribución actual de tarjetas de productos, imágenes, encabezados y bloques de texto
- Paleta cromática, tipografías y estilos actuales
- Diseño responsivo aplicado a desktop, tablet y móvil
- Feedback recibido por el cliente:
    
    — “No se siente lo suficientemente vintage”
    
    — “Los textos se ven muy simples y poco llamativos”
    
    — “Las imágenes no destacan como debería hacerlo el producto”
    
    — “La navegación funciona bien, pero visualmente no impacta”
    
- Restricciones: no agregar nuevas librerías y no integrar frameworks externos

**Indicador de salida:**

Un plan de mejoras de UI/UX con lista priorizada de cambios visuales, propuestas de animaciones ligeras para una mejor vista y demás ajustes de diseño, que incluya:

1. Lista priorizada de cambios de diseño (de mayor impacto a menor)
2. Propuestas de ajustes en color, tipografía y jerarquía visual
3. Recomendaciones de animaciones suaves (CSS puro)
4. Sugerencias para accesibilidad (contraste, tamaño de fuente, espaciado, botones)
5. Mockup conceptual descriptivo en texto (cómo debería verse después la vista)
6. Justificación de cada cambio con principios UI/UX profesionales

## Caso de uso #2

Instrucción: Crear un juego web interactivo usando **HTML, CSS y JavaScript** que simule una carrera de buses en una pista horizontal. El usuario debe poder seleccionar uno de los buses para la carrera, iniciar la carrera presionando un botón y observar la animación hasta que uno de los buses cruce la meta. La velocidad de cada bus será aleatoria, al finalizar, debe mostrarse un mensaje visual claro con el ganador y ofrecer un botón para reiniciar la carrera. El diseño debe ser bastante atractivo para un público infantil, incluyendo colores brillantes, tipografías entendibles y animaciones suaves.

Contexto: Soy una estudiante de un bootcamp de desarrollo que está practicando manipulación del DOM, animaciones con JavaScript, manejo de eventos de usuario y programación basada en lógica. Quiero aprender a construir un juego llamativo y funcional sin frameworks. Deseo implementar una arquitectura limpia para facilitar futuras mejoras como sonidos, niveles de dificultad y animaciones extra.

Datos de entrada: 
"buses": [
{ "id": 1, "nombre": "Bus Amarillo", "color": "#f4d03f", "velocidadBase": 4 },
{ "id": 2, "nombre": "Bus Azul", "color": "#2980b9", "velocidadBase": 5 },
{ "id": 3, "nombre": "Bus Rojo", "color": "#c0392b", "velocidadBase": 6 }
],
"pista": {
"longitudPx": 900
}
}

Indicador de salida: 

Un juego web totalmente funcional que cumpla con lo siguiente:

- Interfaz visualmente atractiva, con pista y buses posicionados al inicio de la pista.
- Selector de bus inicial para que el usuario elija el bus participante.
- Botón de inicio de carrera fluida mediante JavaScript.
- Mensaje claro y correcto del ganador.
- Botón de reiniciar para volver a ejecutar una carrera.
- Diseño colorido y atractivo para niños.

## Caso de uso #3

Instrucción: Construir una página web que funcione como una **librería visual** usando **HTML, JavaScript y TailwindCSS**. La interfaz debe mostrar una colección de libros a través de tarjetas, cada tarjeta debe presentar información del libro (portada, título, autor, año, sinopsis breve, calificación y categoría). La página debe incluir un buscador (por título), filtros por autor, categoría y rango de calificación, y la posibilidad de ordenar (por fecha o calificación). Al hacer clic en una tarjeta se debe abrir un detalle expandido del libro con un Modal de JavaScript con la descripción completa y enlaces opcionales. El diseño debe ser responsivo y estético usando TailwindCSS.

Contexto: Quiero crear una plataforma atractiva para lectores y estudiantes, practicando consumo de datos de APIs externas, filtrado funcional, organización visual en tarjetas y diseño estilo vintage (para dar más ambiente de libreria) con TailwindCSS. El objetivo es facilitar la consulta rápida sin recargar la página, manteniendo una experiencia de navegación fluida.

Datos de entrada: (ejm de la API que se podría usar o JSON)

{
"books": [
{
"id": "BK001",
"title": "El silencio de la biblioteca",
"author": "María Gómez",
"year": 2019,
"shortDescription": "Novela sobre la memoria y los libros olvidados.",
"fullDescription": "Una historia profunda que explora cómo los libros conectan generaciones...",
"coverUrl": "https://cdn.ejemplo.com/covers/bk001.jpg",
"rating": 4.6,
"category": "Ficción",
"pages": 320,
"publisher": "Editorial Andina",
"isbn": "978-1-23456-789-7"
},
{
"id": "BK002",
"title": "Guía práctica de jardinería",
"author": "Carlos Ruiz",
"year": 2021,
"shortDescription": "Consejos para cultivar plantas en espacios pequeños.",
"fullDescription": "Manual paso a paso para crear y mantener una huerta urbana en balcones...",
"coverUrl": "https://cdn.ejemplo.com/covers/bk002.jpg",
"rating": 4.2,
"category": "No Ficción",
"pages": 180,
"publisher": "Verde Editores",
"isbn": "978-1-98765-432-1"
}
],
"filtersAvailable": {
"categories": ["Ficción", "No Ficción", "Infantil", "Ciencia", "Historia"],
"minRating": 0,
"maxRating": 5
},
"pagination": {
"itemsPerPage": 8
}
}

Indicador de salida: 

Una página web completamente funcional que incluya:

- Catálogo visual en forma de tarjetas responsivas.
- Filtros funcionales, divididos por categoría, autor y calificación.
- Buscador por título con sugerencias inmediatas.
- Ordenamiento por fecha o calificación.
- Paginación ligera sin recargar la página.
- Modal de JavaScript con contenido extendido.
- Diseño optimizado con TailwindCSS.

## Caso de uso #4

Introducción: 
Crear una página web full stack para una empresa de videojuegos Colombiana, con frontend en **HTML, JavaScript y TailwindCSS**, backend en **Node.js**, y base de datos **MySQL**. Debe permitir registrar, editar, eliminar y visualizar personajes y niveles del videojuego. La interfaz usará tarjetas dinámicas para mostrar información y debe cargar rápido, ser responsiva y mantener una estética gamer llamativa.

Contexto: 

Soy una desarrolladora junior que debe entregar una solución completa, cuidando el rendimiento, la seguridad, el orden y la mantenibilidad. La idea es sentar bases profesionales para que el proyecto crezca en el futuro e incluya módulos como mecánicas, logros o tienda virtual.

Datos de entrada:

{
"character": {
"name": "",
"role": "",
"abilities": "",
"levelRequired": "",
"image": ""
},
"level": {
"levelNumber": "",
"mapName": "",
"difficulty": "",
"rewards": ""
}
}

Indicador de salida: 

Sitio full stack funcional con:

- CRUD de personajes.
- CRUD de niveles.
- Base de datos MySQL normalizada.
- Backend en Node.js con controladores, rutas y servicios.
- Interfaz con TailwindCSS y tarjetas dinámicas.
- Rendimiento rápido sin recargas innecesarias.

## Caso de uso #5

## 

Introducción: A partir del proyecto de la plataforma web para videojuego, analizar su arquitectura (frontend HTML + JavaScript + TailwindCSS, backend Node.js, base de datos MySQL), y proponer nuevas propuestas de mejora en la estructura, también sugiere módulos adicionales, patrones de diseño y optimizaciones de rendimiento para la carga de tarjetas de personajes y niveles.

Contexto:

Soy una desarrolladora junior y necesito validar o confirmar si la forma en la que estoy estructurando el sistema es la adecuada. Quiero recomendaciones claras, profesionales y fundamentadas para asegurar que la arquitectura del software sea escalable, organizada y preparada para un crecimiento futuro.

Datos de entrada.

- Estructura actual del proyecto (módulos, carpetas, rutas, controladores, servicios)
- Número aproximado de personajes y niveles
- Flujo de CRUD actual
- Descripción de cómo se están consumiendo los datos en el frontend

Indicador de salida:

Un documento detallado con:

- Recomendaciones de arquitectura para frontend, backend y base de datos.
- Patrones sugeridos (como caching).
- Ideas de módulos futuros que se deberían planear.
- Ajustes para mejorar rendimiento y orden del proyecto.

## Caso de uso #6

**Instrucción:**

Analizar el rendimiento de una aplicación frontend e identificar mejoras para carga inicial, procesamiento del DOM, lazy loading, compresión de assets y caching, sin necesidad de reescribir el proyecto desde cero.

**Contexto:**

Soy desarrolladora full stack y debo optimizar el rendimiento de un sitio web que presenta retrasos perceptibles por parte de los usuarios. El enfoque debe ser la optimización progresiva, manteniendo tecnologías actuales y reduciendo el peso de los recursos, el trabajo del navegador y los tiempos de renderizado.

**Datos de entrada (Input Data):**

- Peso total de todos los assets (JS, CSS, imágenes, videos)
- Número de componentes que se renderizan inicialmente
- Implementación actual de lazy loading o caching
- Limitaciones referentes a los navegadores objetivo
- Reporte de errores

**Indicador de salida:**

Un informe priorizado con recomendaciones de optimización por impacto, detallando cuáles afectan CSS, JS, imágenes, renderizado o arquitectura visual, con estimación de mejora en milisegundos/porcentajes, sugerencia de herramientas o librerías adicionales, y hoja de ruta progresiva para su implementación.