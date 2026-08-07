# Flujo Navegadores en Red — Necesidad vigente y alternativas de resolución

Diagrama interactivo de un solo archivo (`index.html`), sin dependencias externas. Cada hito se despliega al hacer clic para mostrar su detalle.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo (o usa uno existente) y sube `index.html` a la raíz.
2. Ve a **Settings → Pages**.
3. En "Source" selecciona la rama (`main`) y carpeta `/ (root)`.
4. Guarda. En 1-2 minutos queda disponible en:
   `https://<tu-usuario>.github.io/<nombre-repo>/`

## Editar contenido

Todo el contenido de los hitos vive en el bloque `<script>` al final del archivo, en los arreglos `laneA`, `laneB` y `branches`. Cada objeto tiene:

- `t`: título del hito
- `s`: subtítulo corto
- `d`: detalle que se despliega (admite HTML simple: `<ul>`, `<strong>`, `<br>`)

No requiere build, servidor ni librerías — es HTML/CSS/JS plano.
