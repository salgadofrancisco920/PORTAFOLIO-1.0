# Francisco.dev - Portafolio Personal

Portafolio web personal desarrollado durante mi formacion como desarrollador de software en **Riwi** (Medellin, Colombia). Este repositorio documenta la construccion progresiva del proyecto: desde la estructura semantica pura en **HTML5** hasta la incorporacion incremental de estilos con **Tailwind CSS**, respaldo CSS interno e interactividad con **JavaScript**.

---

## Avances realizados

1. **Estructura semantica en HTML5:**
   * Creacion de `index.html` con etiquetas nativas (`header`, `nav`, `main`, `section`, `article`, `footer`).
   * Navegacion interna por anclas (`#inicio`, `#sobre-mi`, `#habilidades`, `#proyectos`, `#contacto`).

2. **Contenido e identidad:**
   * Integracion de informacion personal, perfil como coder en Riwi y enlaces a GitHub y correo (`salgadofrancisco920@gmail.com`).
   * Vinculacion de imagen de perfil (`img/Fotodelballer.jpeg`).

3. **Seccion de habilidades y proyectos:**
   * Listado de tecnologias base: HTML5, CSS3, Tailwind, JavaScript, Git y GitHub, y Linux.
   * Tarjetas de proyectos reales con enlaces a sus demos y repositorios: **Rueda Libre** (`img/ruedarueda.png`) y **SismoTwin** (`img/sismo.png`).

4. **Formulario de contacto:**
   * Conexion con **Formspree** (`https://formspree.io/f/xdegkpnl`).
   * Campos incluidos: nombre completo, correo electronico, telefono/WhatsApp, empresa o proyecto, selector de motivo de contacto y mensaje.

5. **Configuracion de Tailwind CSS y barra de navegacion (Fase visual 1):**
   * Integracion de Tailwind CSS mediante CDN y configuracion de la tipografia **Inter**.
   * Definicion de la paleta de colores oscura con tonos azules (`#050811` para el fondo principal, `#0A1124` para tarjetas y degradados en azul cielo, azul rey y azul marino).
   * Estilizado de la barra de navegacion fija (`header`) con enlaces responsivos y boton principal.

6. **Diseno de la seccion Hero / Presentacion (Fase visual 2):**
   * Organizacion en dos columnas responsivas (`hero-grid`) con separacion estructural respecto al resto del contenido.
   * Estilizado del distintivo de estado en Riwi, titulo principal con degradado azul, botones de accion (`Ver proyectos` y `Conocer mas`) y enlaces rapidos a GitHub y correo.
   * Incorporacion de tarjeta contenedora limpia (`inner-card`) para la fotografia de perfil y lema personal.

7. **Diseno de las secciones Sobre mi y Habilidades (Fase visual 3):**
   * Estructuracion de `#sobre-mi` en dos columnas (`about-grid`), combinando la biografia personal a la izquierda con tarjetas informativas de formacion actual en Riwi (2026) y mentalidad de desarrollo a la derecha.
   * Organizacion de `#habilidades` mediante una cuadricula responsiva (`skills-grid`) con tarjetas limpias para cada tecnologia y efecto de resaltado en el borde al pasar el cursor.

8. **Diseno de la seccion Proyectos (Fase visual 4):**
   * Estructuracion de `#proyectos` en dos columnas lado a lado (`projects-grid`) con tarjetas alineadas (`inner-card`).
   * Ajuste de vistas previas con dimensiones compactas (`project-thumb`), etiquetas de tecnologias utilizadas y botones de accion (`Ver proyecto` y `Codigo GitHub`).
   * Actualizacion de enlaces del proyecto **Rueda Libre** hacia el repositorio `Rueda-Libre`.

9. **Diseno de Contacto, Footer e interactividad en JavaScript (Fase visual 5):**
   * Estilizado del contenedor y campos del formulario en `#contacto` con bordes y enfoque en tonos azules, ademas de boton rapido para copiar correo.
   * Diseno del pie de pagina (`footer`) con derechos de autor y lema personal.
   * Implementacion de JavaScript para copiar el correo al portapapeles con confirmacion visual y envio asincrono del formulario mediante `fetch` hacia **Formspree**.

10. **Organizacion de contenedores, contraste de texto blanco y respaldo CSS (Fase visual 6):**
    * Cambio general de tipografia a color blanco (`#ffffff` y `text-slate-200`) para asegurar contraste total sobre el fondo oscuro en todas las secciones y campos de formulario.
    * Encapsulamiento de cada seccion (`#inicio`, `#sobre-mi`, `#habilidades`, `#proyectos`, `#contacto`) dentro de recuadros independientes (`section-box`) con borde azul.
    * Reduccion y estandarizacion del tamano de la fotografia de perfil (`220px x 220px`) y de las vistas previas de proyectos (`145px` de alto) alineados uno al lado del otro.
    * Incorporacion de reglas CSS nativas internas en `<style>` para garantizar la cuadricula y organizacion visual sin depender exclusivamente de la carga externa del CDN.

11. **Refinamiento de botones, pildoras de correo y campos de formulario (Fase visual 7):**
    * Estandarizacion de botones principales (`glow-button`) y secundarios (`outline-button`) con relleno interno, bordes redondeados y separacion uniforme (`hero-actions` y `project-actions`).
    * Diseno personalizado en forma de pildora oscura (`email-pill`) para los botones de copia de correo (`salgadofrancisco920@gmail.com`), eliminando estilos nativos por defecto del navegador.
    * Estructuracion de los controles del formulario (`form-control`, `form-row` y `form-group`) con fondo oscuro (`#050811`), bordes azules y alineacion responsiva en dos columnas.
    ----

 
 **Roma caera pero no caeremos con Roma.**