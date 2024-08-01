# 📁 Proyecto de Estructura de Carpetas y Archivos

Este repositorio contiene scripts para crear una estructura de carpetas y archivos básica para un proyecto frontend. Los scripts están disponibles tanto para sistemas Unix (bash) como para Windows (PowerShell).

## 🛠️ Instrucciones

### 🐧 IOS - Unix (bash)

1. Asegúrate de tener permisos de ejecución en el archivo `create_structure.sh`. Puedes otorgar permisos con el siguiente comando:

    ```bash
    chmod +x create_structure.sh
    ```

2. Ejecuta el script:

    ```bash
    ./create_structure.sh
    ```

### 🖥️ Windows (PowerShell)

1. Abre PowerShell con permisos de administrador.
2. Navega al directorio donde se encuentra el archivo `create_structure.ps1`.
3. Ejecuta el script:

    ```powershell
    .\create_structure.ps1
    ```

## 🗂️ Estructura de Carpetas y Archivos

La estructura creada será la siguiente:



assets/
├── css/
│ └── main.css
├── img/
├── js/
│ └── main.js
└── sass/
├── abstracts/
│ ├── _variables.scss
│ └── _mixins.scss
├── base/
│ ├── _reset.scss
│ └── _typography.scss
├── components/
│ ├── _buttons.scss
│ └── _forms.scss
├── layout/
│ ├── _header.scss
│ └── _footer.scss
├── pages/
│ ├── _home.scss
│ ├── _register.scss
│ └── _postDetail.scss
├── themes/
│ └── _theme.scss
└── vendors/
└── _bootstrap.scss
index.html

