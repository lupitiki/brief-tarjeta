# Brief de Diseño - Tarjeta de Presentación

Este proyecto contiene un formulario web interactivo diseñado con una estética "Tech/Glassmorphism" para recopilar información de clientes sobre el diseño de su tarjeta de presentación.

## 🚀 Cómo usar

1. **Abrir localmente**:
   - Haz doble clic en el archivo `index.html` para verlo en tu navegador.

2. **Subir a GitHub**:
   - Puedes subir esta carpeta completa a un repositorio de GitHub.
   - Para que tus clientes puedan ver el formulario online, activa **GitHub Pages** en la configuración del repositorio (Settings > Pages > Branch: main > Save).
   - Te dará un link público (ej. `tousuario.github.io/brief-tarjeta`).

## 🛠 Personalización

- **Colores/Estilos**: Edita el archivo `styles.css` para cambiar la paleta de colores (variables `--primary`, `--secondary`).
- **Preguntas**: Edita el archivo `index.html` para modificar o agregar preguntas.
- **Recibir Respuestas**:
   - Actualmente el formulario es estático (frontend).
   - Para recibir los correos, puedes usar un servicio gratuito como [Formspree](https://formspree.io/).
   - Regístrate en Formspree, crea un formulario y reemplaza la etiqueta `<form action="#">` por `<form action="https://formspree.io/f/tu-codigo">` en el archivo `index.html`.

## 📂 Estructura

- `index.html`: Estructura del formulario.
- `styles.css`: Estilos visuales (Glassmorphism, Neon).
- `bg.png`: Imagen de fondo (copiada del proyecto anterior).
