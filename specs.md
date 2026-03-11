# Library of America – Homepage Redesign

## Design Justification (Deliverable 2)

Este documento describe las decisiones de diseño tomadas para el rediseño de la página principal de **Library of America**.

El objetivo del rediseño es crear una homepage **moderna, intuitiva y culturalmente rica**, que facilite la exploración del canon literario estadounidense mientras mantiene una experiencia usable y accesible.

El rediseño se basa en:

- Planeación estratégica del contenido
- Diseño basado en **cards**
- Arquitectura narrativa de la página
- Uso del framework **UIKit**
- Mejora de engagement y conversión

## Toda la página debe estar en inglés

# Estrategia General de Rediseño

La página original funciona como un **portal editorial tradicional**, donde múltiples tipos de contenido compiten por atención sin una jerarquía clara.

El rediseño reorganiza la homepage como una **experiencia narrativa cultural**, guiando al usuario a través de un flujo claro:

Hero → Exploración cultural → Autores → Libros → Participación.

Principios clave del rediseño:

- Jerarquía visual clara
- Sistema consistente de tarjetas
- Navegación orientada al descubrimiento
- Refuerzo de la misión cultural de la organización
- Componentes reutilizables con UIKit
- Diseño completamente responsivo

---

# Sección 1 – Hero Cultural

## Cambio realizado

Se introduce una sección **Hero** en la parte superior de la página con:

- Imagen cultural destacada
- Mensaje sobre la misión de la organización
- Dos llamadas a la acción principales:
  - Explorar libros
  - Descubrir escritores

## Problema detectado

La homepage actual **no tiene una sección hero**, por lo que los usuarios llegan directamente a una grilla de contenido editorial sin contexto.

Esto provoca:

- Falta de orientación para nuevos usuarios
- Baja claridad sobre la misión del sitio
- Falta de una acción principal

## Meta que apoya

- Comunicar claramente la misión cultural
- Orientar al usuario desde el primer momento
- Aumentar exploración del catálogo

## Componentes UIKit utilizados

- `uk-section`
- `uk-container`
- `uk-grid`
- `uk-cover`
- `uk-button`

Estos componentes permiten crear un **hero responsive con imagen adaptable**, alineación tipográfica consistente y llamadas a la acción claras.

---

# Sección 2 – Exploración Cultural

## Cambio realizado

La sección de noticias se transforma en **Explore the Canon**, una galería editorial que presenta contenido cultural destacado:

- ensayos
- artículos
- historias literarias
- eventos

El contenido se muestra mediante **cards editoriales grandes con imagen y resumen**.

## Problema detectado

En el sitio actual:

- el contenido aparece en una grilla con jerarquía débil
- no existe una narrativa editorial clara
- las tarjetas tienen tamaños inconsistentes

## Meta que apoya

- Fomentar la exploración cultural
- Aumentar el tiempo de permanencia en el sitio
- Posicionar el portal como referente literario

## Componentes UIKit utilizados

- `uk-card`
- `uk-card-media-top`
- `uk-card-body`
- `uk-grid`
- `uk-grid-match`

El sistema de tarjetas de UIKit permite crear **contenidos visualmente consistentes y fáciles de explorar**.

---

# Sección 3 – Autores Destacados

## Cambio realizado

Se introduce una sección **Featured Writers** donde los autores se presentan como tarjetas visuales.

Cada tarjeta incluye:

- Retrato del autor
- Nombre
- Enlace al perfil del autor o colección

## Problema detectado

En la página actual:

- los autores aparecen en una sección visualmente débil
- no existe un patrón claro para explorarlos
- el "Writer of the Week" compite con el resto del contenido

## Meta que apoya

- Facilitar descubrimiento de autores
- Destacar el canon literario estadounidense
- Fortalecer el posicionamiento cultural del sitio

## Componentes UIKit utilizados

- `uk-card`
- `uk-card-media-top`
- `uk-grid`
- `uk-grid-small`
- `uk-hover`

Estos componentes permiten crear **tarjetas uniformes con microinteracciones**, mejorando la exploración.

---

# Sección 4 – Libros Destacados

## Cambio realizado

La sección de libros se rediseña como **Recommended Books**, mostrando portadas en una grilla de tarjetas uniformes.

Cada tarjeta incluye:

- Portada del libro
- Título
- Autor
- Enlace para explorar el libro

## Problema detectado

En el sitio actual:

- las portadas se presentan en una fila editorial poco interactiva
- no existe una estructura clara para explorar el catálogo

## Meta que apoya

- Promover el catálogo editorial
- Aumentar clics hacia páginas de libros
- Reforzar la identidad editorial de la organización

## Componentes UIKit utilizados

- `uk-card`
- `uk-card-media-top`
- `uk-grid`
- `uk-child-width-1-5@m`
- `uk-button-text`

UIKit facilita la construcción de **rejillas responsivas de libros**, manteniendo proporciones correctas de portada.

---

# Sección 5 – Participar y Apoyar la Misión

## Cambio realizado

La sección final se rediseña como un bloque de **engagement**, con tres tarjetas principales:

- Suscribirse al newsletter
- Explorar el catálogo
- Apoyar la misión mediante donación

## Problema detectado

En el sitio actual:

- la suscripción aparece muy tarde en la página
- no existe una narrativa clara que conecte la misión con la acción del usuario

## Meta que apoya

- Incrementar suscripciones
- Incentivar donaciones
- Fortalecer la comunidad de lectores

## Componentes UIKit utilizados

- `uk-card`
- `uk-card-primary`
- `uk-grid`
- `uk-form`
- `uk-button-primary`

Estos componentes permiten crear **llamados a la acción visibles, accesibles y consistentes con el diseño del sitio**.

---

# Resultado esperado del rediseño

El rediseño transforma la homepage en una experiencia que combina:

- Exploración cultural
- Descubrimiento literario
- Narrativa editorial
- Participación comunitaria

Gracias al uso de **UIKit y un sistema consistente de cards**, la nueva página será:

- moderna
- modular
- accesible
- completamente responsiva
- escalable para futuras expansiones del contenido.
