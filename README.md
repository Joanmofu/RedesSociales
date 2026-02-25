# RedesSociales

Este proyecto es una interfaz web sencilla y elegante que muestra un panel de botones para diferentes redes sociales (Facebook, Instagram, GitHub y YouTube). Destaca por el uso de animaciones y efectos interactivos (hover) desarrollados puramente con CSS.

## 🚀 Características

* **Botones Interactivos:** Al pasar el ratón sobre cada icono (efecto *hover*), el fondo del botón cambia a negro, el icono se vuelve blanco y aparece un mensaje emergente (tooltip) con el nombre de la red social correspondiente.
* **Múltiples Estilos:** El proyecto incluye dos hojas de estilos diferentes para demostrar distintas técnicas de maquetación:
  * `estilo2.css` (Activo por defecto): Utiliza **CSS Grid** (`grid-template-columns`), muestra iconos de gran tamaño y aplica los colores corporativos originales a cada red social (como el gradiente característico de Instagram).
  * `style.css` (Alternativo): Utiliza **Flexbox**, sombras (`box-shadow`) y un diseño más compacto.
* **Iconografía Vectorial:** Utiliza la librería Font Awesome para renderizar iconos escalables y ligeros.

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica del contenedor y los enlaces.
* **CSS3:** Maquetación (Flexbox y Grid), gradientes (`linear-gradient`), transiciones y posicionamiento absoluto/relativo para los tooltips emergentes.
* **Font Awesome (v6.0.0-beta3):** Librería externa de iconos.

## 📂 Estructura del Proyecto

```text
redessociales/
│
├── css/
│   ├── estilo2.css      # Hoja de estilos principal (Diseño con Grid e iconos grandes)
│   └── style.css        # Hoja de estilos secundaria (Diseño con Flexbox y sombras)
├── index.html           # Estructura principal
├── LICENSE              # Licencia MIT del proyecto
└── README.md            # Documentación del proyecto
