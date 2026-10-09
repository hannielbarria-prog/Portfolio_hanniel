# Portafolio personal — Haniel Barría

Portafolio web estático creado con **HTML, CSS y JavaScript**. Está organizado para practicar desarrollo web y publicar el proyecto mediante GitHub Pages.

## Estructura del proyecto

```text
portfolio-haniel/
├── index.html          # Estructura y contenido del sitio
├── css/
│   └── style.css       # Estilos, componentes y diseño responsive
├── js/
│   └── script.js       # Menú, animaciones y validación
├── img/                # Carpeta para imágenes del proyecto
├── .gitignore          # Archivos que Git debe ignorar
├── LICENSE             # Licencia del proyecto
└── README.md           # Documentación
```

## Funcionalidades

- HTML semántico y atributos básicos de accesibilidad.
- Diseño adaptable a teléfonos, tabletas y computadoras.
- Menú móvil que se puede abrir, cerrar con Escape y cerrar al navegar.
- Barras de habilidades animadas al llegar a esa sección.
- Formulario con validación de nombre, correo y mensaje.
- Año del pie de página actualizado automáticamente.
- CSS organizado por secciones y variables reutilizables.
- JavaScript separado en funciones pequeñas y con comprobaciones para evitar errores.

> **Importante:** el formulario solamente valida los datos en el navegador. No envía correos ni guarda mensajes en una base de datos.

## Cómo probarlo

1. Descarga y extrae el archivo ZIP.
2. Abre `index.html` en un navegador.
3. Prueba el menú, desplázate hasta habilidades y envía el formulario con datos correctos e incorrectos.

## Cómo publicarlo gratis con GitHub Pages

1. Inicia sesión en GitHub y crea un repositorio nuevo. Puedes llamarlo `portfolio-haniel`.
2. Si el repositorio es solo para practicar, puedes marcarlo como **Public** para que otras personas puedan ver el código.
3. Sube el contenido de esta carpeta al repositorio. Asegúrate de que `index.html` quede en la raíz del repositorio, no dentro de otra carpeta adicional.
4. En el repositorio, entra en **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**.
6. Elige la rama `main` y la carpeta `/ (root)`, y guarda.
7. Espera unos minutos y vuelve a la sección **Pages** para abrir el enlace que GitHub genere.

## Para practicar buenas costumbres

- Usa nombres de clases que expliquen su propósito.
- Mantén HTML, CSS y JavaScript en archivos separados.
- Escribe comentarios para explicar bloques importantes, no cada línea.
- Revisa los cambios antes de confirmarlos.
- Haz cambios pequeños y comprueba que la página siga funcionando.
- No subas contraseñas, tokens, datos privados ni credenciales al repositorio.

## Tecnologías

- HTML5
- CSS3 (Grid, Flexbox, variables y media queries)
- JavaScript moderno (ES6+)
- Git y GitHub Pages
