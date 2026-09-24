# 🚀 Academia La Rompemos — Plataforma Web Oficial

<p align="center">
  <img src="https://larompemos.com/wp-content/uploads/2026/05/Diseno-sin-titulo-19.png" alt="La Rompemos Logo" width="180">
</p>

<p align="center">
  <strong>Plataforma integral de aprendizaje y ventas: Creación de sitios web con Inteligencia Artificial.</strong><br>
  Diseñada para el subdominio <code>academia.larompemos.com</code>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Diseño-Dark_Luxury-D4AF37?style=for-the-badge" alt="Dark Luxury">
  <img src="https://img.shields.io/badge/Licencia-MIT-green?style=for-the-badge" alt="MIT License">
</p>

---

## 🌟 Características Principales

### 🖥️ Landing Page de Alta Conversión (`index.html`)
- **Estética Dark Luxury:** Fondo negro mate, acentos dorados metálicos, tipografía de impacto y detalles clave en verde esmeralda.
- **Cintas en Bucle Infinito (*Infinite Marquee Ribbons*):** Tickers animados continuos en CSS que comunican la propuesta de valor sin interrupciones.
- **Hero Interactivo:** Reproductor de video integrado con botón de activación de sonido y placeholder persuasivo.
- **Módulo «Qué Aprenderás» estilo Bento Grid:** Diseño moderno con números de fondo en marca de agua (01, 02, 03...), tarjetas de vidrio esmerilado y cero aspecto de IA genérica.
- **Sección «¿Quieres crear webs así?»:** Grid con recuadros listos para incrustar videos demostrativos de Landing Pages, E-commerce y Webs Corporativas.
- **Selector Multidivisa en Vivo:** Convierte en tiempo real los precios entre **USD, CLP, MXN, COP, PEN, EUR, ARS y BRL**.
- **Planes de Precios:**
  - Plan Inicial Web: **$50 USD**
  - Plan Maestro Web IA: **$89 USD** (Tarjeta entera dorada `full-gold-card` con botón negro de alto contraste)
  - Plan Vitalicio Agencia Pro: **$140 USD**
- **Acordeón FAQ Desplegable:** Preguntas y respuestas frecuentes con animaciones suaves.
- **Acceso Privado:** Modal de inicio de sesión limpio y seguro.

### 🛡️ Panel de Control & Aula Virtual (`admin.html`)
- **Editor Visual de Landing Page:** Modifica directamente desde el panel la URL del video del hero, los textos, el rango de facturación, los precios de los planes, las demos y los colores de la marca sin editar código.
- **Banco de Prompts en Tarjetas:** Biblioteca organizada (Webs, Flyers y Ventas) con botón de **«Copiar Prompt» en 1 clic**, previsualizaciones de imágenes y videos.
- **Gestión de Alumnos:** Monitor en tiempo real de estudiantes registrados, buscador y alta manual con plan asignado.
- **Aula Virtual:** Reproductor de lecciones en video y temario estructurado por módulos.

---

## 📂 Estructura del Repositorio

```text
├── .gitattributes          # Normalización de saltos de línea y codificación
├── .gitignore              # Exclusión de archivos innecesarios
├── LICENSE                 # Licencia de código abierto MIT
├── README.md               # Documentación general del proyecto
├── index.html              # Landing Page de ventas
├── admin.html              # Panel de administración y aula virtual
├── css/
│   ├── styles.css          # Estilos oficiales Dark Luxury y Bento Grid
│   └── admin.css           # Estilos del panel de control y tarjetas
└── js/
    ├── store.js            # Motor central de datos, persistencia y autenticación
    ├── currency.js         # Conversor multidivisa en tiempo real
    ├── main.js             # Lógica e interactividad de la Landing Page
    └── admin.js            # Lógica del panel y editor de la Landing Page
```

---

## 🚀 Cómo Subir este Proyecto a GitHub

Puedes subirlo siguiendo cualquiera de estos 2 métodos sencillos:

### Opción A: Usando la Terminal (Git CLI)

1. Abre tu terminal o PowerShell en esta carpeta (`c:\Users\Fernando\Desktop\web de academia`).
2. Ejecuta los siguientes comandos:
   ```bash
   git init
   git add .
   git commit -m "feat: lanzamiento de plataforma Academia La Rompemos"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git
   git push -u origin main
   ```

### Opción B: Desde GitHub Web (Sin instalar nada)

1. Ingresa a [github.com](https://github.com) y crea un nuevo repositorio (por ejemplo: `web-academia-larompemos`).
2. Haz clic en **"uploading an existing file"** (subir archivos existentes).
3. Arrastra todos los archivos y carpetas de este proyecto hacia la ventana del navegador.
4. Escribe un mensaje de commit como `Versión inicial de la plataforma` y haz clic en **Commit changes**.

---

## 🌐 Publicación Gratis en GitHub Pages (Opcional)

Si deseas tener una vista previa online inmediata desde GitHub:
1. En tu repositorio de GitHub, ve a **Settings** > **Pages**.
2. En la sección **Branch**, selecciona `main` y la carpeta `/ (root)`.
3. Haz clic en **Save**. En un par de minutos tendrás tu enlace web activo (ejemplo: `https://tu-usuario.github.io/web-academia-larompemos/`).

---

## 🏢 Despliegue en Subdominio `academia.larompemos.com`

1. En tu panel de hosting (cPanel/Hostinger/Vercel/etc.), crea el subdominio **`academia`**.
2. Sube todos los archivos a la carpeta raíz de ese subdominio (normalmente `public_html/academia`).
3. ¡Listo! Al ingresar a `https://academia.larompemos.com` estará funcionando inmediatamente.
