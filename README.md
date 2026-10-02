# 📊 Distribuciones de Frecuencias — Conceptos

Proyecto académico interactivo sobre **distribuciones de frecuencias**, desarrollado con **R, RStudio y Quarto** y presentado como una página web HTML.

El proyecto organiza conceptos fundamentales de estadística descriptiva, ejemplos, tablas y código de R dentro de una interfaz web diseñada para facilitar la lectura y el aprendizaje.

---

## 👤 Autor

**David Santiago Cortes Mejia**

**Afiliación:** Universidad del Tolima  
**Fecha de publicación:** 19 de septiembre de 2026

---

## 🌐 Ver el proyecto en línea

Una vez publicado mediante GitHub Pages, el proyecto podrá compartirse con un enlace de este tipo:

```text
https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/
```

> El enlace definitivo será generado por GitHub después de activar **GitHub Pages**.

---

## ✨ Características

- 📚 Contenido educativo sobre distribuciones de frecuencias.
- 📊 Explicación de conceptos estadísticos fundamentales.
- 💻 Ejemplos y código desarrollado en R.
- 🧮 Trabajo con frecuencias absolutas, relativas y acumuladas.
- 📑 Tablas y resultados integrados en la página.
- 🎨 Diseño académico personalizado mediante CSS.
- 🧭 Tabla de contenidos lateral para navegar por el documento.
- 📱 Diseño adaptable a diferentes tamaños de pantalla.
- 🔢 Secciones numeradas automáticamente.
- 👨‍💻 Bloques de código con opción **“Mostrar código”**.
- ⚡ Página HTML lista para publicarse como sitio web estático.

---

## 🗂️ Estructura del proyecto

```text
Lili-main/
│
├── index.html
├── index.qmd
├── styles.css
├── Logo_ut.png
├── Lili.Rproj
├── .gitignore
│
├── index_files/
│   └── libs/
│       ├── bootstrap/
│       ├── clipboard/
│       ├── quarto-html/
│       └── figure-html/
│
└── .github/
    └── workflows/
        ├── publish.yml
        └── deploy-gh-pages.yml
```

### Archivos principales

| Archivo | Función |
|---|---|
| `index.html` | Página web final que puede ser servida directamente por GitHub Pages. |
| `index.qmd` | Documento fuente de Quarto con el contenido y código R. |
| `styles.css` | Diseño visual y estilos personalizados. |
| `Logo_ut.png` | Imagen utilizada en la presentación del proyecto. |
| `Lili.Rproj` | Proyecto de RStudio. |
| `index_files/` | Recursos generados y utilizados por la página HTML. |
| `.github/workflows/` | Configuraciones de automatización relacionadas con GitHub Actions. |

---

# 🚀 Cómo subir el proyecto a GitHub

## 1. Crear el repositorio

Entra en GitHub y crea un repositorio nuevo.

Puedes utilizar, por ejemplo:

```text
distribuciones-de-frecuencias
```

También puedes utilizar otro nombre que prefieras.

Se recomienda crear el repositorio **sin README, sin .gitignore y sin licencia**, porque este proyecto ya contiene esos archivos cuando corresponda.

---

## 2. Subir los archivos

Después de crear el repositorio:

1. Abre el repositorio.
2. Selecciona **Add file → Upload files**.
3. Sube el contenido de esta carpeta.
4. Verifica especialmente que `index.html` quede en la raíz del repositorio.
5. Escribe un mensaje como:

```text
Publicación inicial del proyecto
```

6. Pulsa **Commit changes**.

La estructura principal debería verse así:

```text
tu-repositorio/
├── index.html
├── index.qmd
├── styles.css
├── Logo_ut.png
├── index_files/
└── README.md
```

---

# 🌍 Cómo obtener un enlace público con GitHub Pages

Una vez que los archivos estén en GitHub:

1. Entra al repositorio.
2. Ve a **Settings**.
3. En el menú lateral busca **Pages**.
4. En **Build and deployment**, selecciona:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main`
   - **Folder:** `/(root)`
5. Guarda la configuración.

GitHub comenzará a publicar el sitio.

Después de unos momentos, GitHub mostrará la dirección pública del proyecto.

Normalmente tendrá esta estructura:

```text
https://TU-USUARIO.github.io/TU-REPOSITORIO/
```

Por ejemplo:

```text
https://david-santiago.github.io/distribuciones-de-frecuencias/
```

> El ejemplo anterior es únicamente ilustrativo. Debes utilizar tu nombre de usuario y el nombre real de tu repositorio.

---

# 💻 Ejecutar el proyecto localmente

Como el proyecto ya incluye `index.html`, puedes abrirlo directamente desde tu computador:

1. Abre la carpeta del proyecto.
2. Haz doble clic en `index.html`.
3. El navegador mostrará la página.

Para trabajar sobre el documento fuente mediante **Quarto y RStudio**, abre:

```text
Lili.Rproj
```

y posteriormente:

```text
index.qmd
```

---

# 🧪 Requisitos para editar y volver a generar el proyecto

Si deseas modificar el documento fuente, se recomienda disponer de:

- **R**
- **RStudio / Posit**
- **Quarto**

El documento utiliza paquetes de R como:

```r
tidyverse
kableExtra
psych
readxl
```

Estos paquetes se gestionan desde el propio código del proyecto.

---

# 🔄 Actualizar el sitio

Si modificas `index.html` directamente:

```text
Modificar → Guardar → Subir a GitHub → GitHub Pages se actualiza
```

Si modificas `index.qmd`:

```text
Modificar index.qmd
        ↓
Renderizar con Quarto
        ↓
Se genera index.html
        ↓
Subir los cambios a GitHub
        ↓
GitHub Pages publica la nueva versión
```

---

# 📖 Contenido académico

El proyecto aborda, entre otros, los siguientes conceptos:

- Población.
- Muestra.
- Individuo o unidad estadística.
- Variable estadística.
- Variables cualitativas.
- Variables cuantitativas.
- Variables discretas.
- Variables continuas.
- Distribuciones de frecuencias.
- Frecuencia absoluta.
- Frecuencia relativa.
- Frecuencia absoluta acumulada.
- Frecuencia relativa acumulada.
- Organización y análisis de datos mediante R.

---

# 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| **R** | Análisis y procesamiento estadístico. |
| **RStudio / Posit** | Desarrollo del proyecto. |
| **Quarto** | Generación del documento HTML. |
| **HTML5** | Estructura de la página web. |
| **CSS3** | Diseño y presentación visual. |
| **Bootstrap** | Componentes y recursos visuales integrados por Quarto. |
| **KaTeX** | Representación de expresiones matemáticas. |
| **GitHub Pages** | Publicación gratuita del sitio web. |
| **GitHub Actions** | Automatización incluida en la configuración del proyecto. |

---

# 📄 Licencia

Este repositorio corresponde a un proyecto académico.

Si deseas permitir reutilización, modificación o distribución del código y contenido, puedes añadir posteriormente una licencia como **MIT**, **Apache-2.0** o una licencia académica que corresponda a tus necesidades.

---

## 🎓 Proyecto académico

**Distribuciones de Frecuencias — Conceptos**

**David Santiago Cortes Mejia**  
**Universidad del Tolima**  
**2026**
