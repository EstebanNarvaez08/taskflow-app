
# Documentación del componente Login

Este repositorio contiene un ejemplo simple de interfaz de login para pruebas y diseño.

Archivos relevantes:
- `login.html` - Marcado HTML del formulario de inicio de sesión (con comentarios y buenas prácticas de accesibilidad).
- `style.css` - Estilos modernos y responsive para el proyecto.
- `login-panel-extra.html` / `login-panel-extra.css` - Panel adicional creado para probar conflictos git.

Cómo probar localmente:
1. Abrir `login.html` en un navegador (doble clic o `http-server`).
2. Verificar el enfoque de teclado en los campos y el comportamiento responsive reduciendo el ancho de la ventana.

Notas para producción:
- Reemplazar `form action="#"` por la ruta real del backend.
- Implementar protección CSRF y validación del lado servidor.
- Extraer variables de color y tipografías a un sistema de variables (SCSS o CSS custom properties) si el proyecto crece.

