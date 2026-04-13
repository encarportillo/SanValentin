# ❤️ San Valentín Digital - Special Gift

Este es un proyecto web interactivo desarrollado como un regalo personalizado de San Valentín. Combina animaciones CSS, manipulación del DOM con JavaScript y una estética minimalista para crear una experiencia visual y emocional única.

## 🌟 Características

* **Pantalla de Inicio Interactiva:** Un "overlay" que prepara la sorpresa y requiere la interacción del usuario para iniciar la experiencia.
* **Árbol de Corazones Procedural:** Los corazones que forman el árbol se generan y posicionan mediante algoritmos matemáticos (funciones seno y coseno) para crear una forma orgánica.
* **Contador en Tiempo Real:** Un motor de tiempo que calcula con precisión los años, días, horas, minutos y segundos transcurridos desde una fecha especial (21 de diciembre de 2013).
* **Efecto de Mecanografía (Typewriter):** Los mensajes y el contador aparecen dinámicamente, simulando una máquina de escribir.
* **Atmósfera Inmersiva:** Incluye música ambiental, animaciones de crecimiento (tronco y ramas) y una lluvia constante de pétalos de cerezo (Sakura).

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura del contenido y contenedores de animación.
* **CSS3:** * Animaciones con `@keyframes` para el crecimiento del árbol y pétalos.
    * Diseño responsivo y Flexbox para el centrado de elementos.
    * Uso de variables y pseudo-elementos (`::before`, `::after`) para crear formas de corazones sin imágenes.
* **JavaScript (Vanilla JS):**
    * Lógica para el cálculo de tiempo transcurrido.
    * Generación dinámica de elementos del DOM.
    * Control de eventos de audio y visualización.

## 📂 Estructura del Proyecto

```text
├── index.html      # Estructura principal y contenedores
├── style.css       # Estilos, animaciones y diseño visual
├── script.js      # Lógica del contador, árbol y efectos
└── photograph.mp3  # Música de fondo (Ed Sheeran - Photograph)
