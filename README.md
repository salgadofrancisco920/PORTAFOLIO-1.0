# Francisco.dev - Portafolio Personal

Portafolio web personal desarrollado durante mi formacion como desarrollador de software en **Riwi** (Medellin, Colombia). Este repositorio documenta la construccion progresiva del proyecto: desde la estructura semantica pura en **HTML5** hasta la incorporacion incremental de estilos con **Tailwind CSS**.

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
   * Estilizado de la barra de navegacion fija (`header`) con efecto desenfoque (`backdrop-blur`), enlaces de navegacion responsivos y boton principal con brillo azul.

6. **Diseno de la seccion Hero / Presentacion (Fase visual 2):**
   * Organizacion en dos columnas responsivas (`grid md:grid-cols-2`) con separacion estructural respecto al resto del contenido.
   * Estilizado del distintivo de estado en Riwi, titulo principal con degradado azul, botones de accion (`Ver proyectos` y `Conocer mas`) y enlaces rapidos a GitHub y correo.
   * Incorporacion de tarjeta contenedora limpia (`blue-card` y `blue-border`) para la fotografia de perfil y lema personal.

---

## Estructura de archivos

```text
portafolio/
├── img/
│   ├── Fotodelballer.jpeg
│   ├── ruedarueda.png
│   └── sismo.png
├── index.html
└── README.md