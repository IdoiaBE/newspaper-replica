# 📰 Réplica de Portada de Periódico

Este proyecto consiste en la creación de una réplica estática de una portada de periódico utilizando HTML5 y SCSS. Es un ejercicio personal orientado a practicar maquetación con Flexbox, CSS Grid y diseño responsive.

## 📑 Tabla de Contenidos

- [📄 Descripción](#descripción)
- [🎯 Objetivos](#objetivos)
- [🛠️ Tecnologías utilizadas](#tecnologías-utilizadas)
- [📂 Estructura de carpetas](#estructura-de-carpetas)
- [💻 Instalación y uso](#instalación-y-uso)
- [📸 Capturas](#capturas)
- [🧑‍💻 Créditos](#créditos)
- [📝 Notas adicionales](#notas-adicionales)

---

## 📄 Descripción

Este proyecto simula visualmente una portada de periódico tradicional en formato digital. Incluye secciones como titulares, noticias destacadas, columnas, fecha, cabecera y otros elementos típicos. El diseño está basado en la portada del periódico El Pais el 21 de agosto del 2023.

## 🎯 Objetivos

- Practicar maquetación con **Flexbox** y **CSS Grid**.
- Consolidar conocimientos de **estructura semántica HTML5**.
- Aplicar diseño responsive con **media queries**.
- Mejorar organización del código utilizando **SCSS**.
- Explorar tipografías y estilos visuales propios de periódicos impresos.

## 🛠️ Tecnologías utilizadas

- 🧱 **HTML5** – Estructura semántica del contenido.
- 🎨 **SCSS** – Preprocesador CSS para una mejor organización y reutilización.
- 📐 **Flexbox** – Para estructuras flexibles de una sola dimensión.
- 🧮 **CSS Grid** – Para layouts de dos dimensiones.
- 📱 **Media Queries** – Diseño adaptable a distintos tamaños de pantalla.

## 📂 Estructura de carpetas

📁 docs/
│   ├── assets/            # Archivos estáticos generados (JS, CSS optimizados)
│   ├── images/            # Imágenes optimizadas al compilar
│   ├── js/
│   │   └── main.js        # JS compilado para producción
│   └── index.html         # HTML compilado final

📁 public/
│   └── images/            # Imágenes públicas

📁 src/
│   ├── js/               # Archivo principal de JavaScript
│   │    └── main.js
│   ├── partials/          # Fragmentos HTML para reutilizar con `vite-plugin-html-inject`
│   │   ├── header.html
│   │   ├── footer.html
│   │   ├── main.html
│   │
│   ├── scss/              # Estructura modular para estilos SCSS
│   │   ├── components/
│   │   ├── core/
│   │   ├── layout/
│   │   └── main.scss      # Punto de entrada SCSS
│   └── index.html         # Archivo HTML principal


## 💻 Instalación y uso

> **NOTA:** Necesitas tener instalado [Node JS](https://nodejs.org/) con una versión superior a la 14 para trabajar con este proyecto.

1. Clona este repositorio:

```bash
git clone [URL-del-repositorio]
```
2. Navega a la carpeta del proyecto:

```bash
   cd nombre-del-repositorio
```

3. Instala las dependencias locales ejecutando en la terminal el comando:

```bash
npm install
```

### Para arrancar el proyecto:

Una vez instaladas las dependencias, arranca el proyecto para poder empezar a programar. Para ello ejecuta el comando:

```bash
npm run dev
```

Este comando:

- **Abre una ventana de Chrome y muestra tu página web**, al igual que hace el plugin de VS Code Live Server (Go live).
- También **observa** todos los ficheros que hay dentro de la carpeta `src/`, para que cada vez que modifiques un fichero **refresca tu página en Chrome**.
- También **procesa los ficheros** HTML, SASS / CSS y JS. Por ejemplo:
   - Convierte los ficheros SASS en CSS.
   - Combina los diferentes ficheros de HTML y los agrupa en uno o varios ficheros HTML.

Después de ejecutar `npm run dev` ya puedes empezar a editar todos los ficheros que están dentro de la carpeta `src/`.

### Para publicar en GitHub Pages:

Genera tu página para producción ejecutando el comando:

```bash
npm run build
```

Y a continuación:

1. Sube a tu repo la carpeta `docs/` que se te acaba de generar.
1. Entra en la pestaña `settings` de tu repo.
1. Y en el apartado de GitHub Pages activa la opción **master branch /docs folder**.

Además, los comandos:

```bash
npm run push-docs
```
o

```bash
npm run deploy
```

son un atajo que genera la versión de producción y hace push de la carpeta `docs/` del tirón.

## 📸 Capturas


## 🧑‍💻 Créditos

Desarrollado por Idoia Belloso Elola.