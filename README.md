# Odontología Especializada Karen Padilla

Sitio web de una sola página para la Dra. Karen Padilla, especialista en Endodoncia.

## Estructura del proyecto

```
karen-padilla-web/
├── index.html          → página principal
├── assets/
│   ├── css/
│   │   └── style.css   → todos los estilos
│   └── js/
│       └── main.js     → interacciones (menú móvil, animaciones)
└── README.md
```

## Cómo subirlo a GitHub

1. **Crea un repositorio nuevo en GitHub**
   Entra a [github.com/new](https://github.com/new), ponle un nombre (por ejemplo `karen-padilla-web`) y créalo **vacío** (sin README, sin .gitignore).

2. **Abre esta carpeta en la terminal de VS Code**
   Terminal → New Terminal (asegúrate de estar dentro de la carpeta `karen-padilla-web`).

3. **Sube el código** (reemplaza `TU-USUARIO` por tu usuario de GitHub):

   ```bash
   git init
   git add .
   git commit -m "Primera versión del sitio"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/karen-padilla-web.git
   git push -u origin main
   ```

   Si es la primera vez que usas Git en esta computadora, antes de lo anterior corre:
   ```bash
   git config --global user.name "Tu Nombre"
   git config --global user.email "tu-correo@ejemplo.com"
   ```

## Cómo verlo en cualquier dispositivo (GitHub Pages)

1. En tu repositorio en GitHub, ve a **Settings** (Configuración) → **Pages** (en el menú izquierdo).
2. En **Source**, selecciona la rama **main** y la carpeta **/ (root)**.
3. Haz clic en **Save**.
4. Espera 1-2 minutos. GitHub te dará una URL como:

   ```
   https://TU-USUARIO.github.io/karen-padilla-web/
   ```

   Esa URL funciona desde cualquier celular, tablet o computadora — sin instalar nada.

## Cómo actualizar el sitio después de hacer cambios

Cada vez que edites algo (en VS Code) y quieras que se vea reflejado en la web:

```bash
git add .
git commit -m "Descripción breve del cambio"
git push
```

GitHub Pages se actualiza solo, unos minutos después de cada `push`.

## Pendientes de contenido

- Agregar teléfono, correo y horario reales en la sección de contacto (`index.html`, sección `#contacto`).
