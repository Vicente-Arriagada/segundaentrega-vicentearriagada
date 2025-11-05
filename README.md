

## 🛠️ Tecnologías Utilizadas

* **Framework:** [Astro](https://astro.build/)
* **Estilos:** [Tailwind CSS](https://tailwindcss.com/)
* **Runtime / Gestor de Paquetes:** [Bun](https://bun.sh/)
* **Gestión de Datos:** Archivos JSON locales (`.json`)
* **Despliegue:** (Optimizado para despliegue estático en plataformas como Vercel, Netlify o GitHub Pages)



### 1. Prerrequisitos

Asegúrate de tener **[Bun](https://bun.sh/)** instalado en tu sistema.

```bash
bun install
```
1. Instalar Dependencias
Usa bun para instalar todos los paquetes necesarios.

```bash
bun install
```
1. Configurar Tailwind CSS
Añade Tailwind CSS al proyecto usando el comando astro add.

```bash
    bunx astro add tailwind

```
2. Añadir global.css al Layout
Añade la importación de global.css en el head de Layout.astro.

```astro
---
import '../styles/global.css';
---
```

3. Configurar el Entorno de Desarrollo
Inicia el servidor de desarrollo con el siguiente comando:

```bash
bun run dev
```
1. Acceder al Sitio
Abre tu navegador y ve a http://localhost:4321 para ver el proyecto en acción.
<<<<<<< HEAD




📂 Estructura del Proyecto
/
├── public/                 # Imágenes estáticas, logos y fuentes
│   └── images/
├── src/
│   ├── components/         # Componentes reutilizables (.astro)
│   │   ├── Header.astro
│   │   ├── Footer.astro
│   │   ├── ProductCard.astro
│   │   ├── NewsCard.astro
│   │   └── CustomCarousel.astro
│   ├── data/                 # Datos de la aplicación
│   │   ├── telefonos.json
│   │   ├── hardware.json
│   │   └── blogPosts.json
│   ├── layouts/              # Plantilla principal
│   │   └── Layout.astro
│   └── pages/                # Todas las páginas y rutas del sitio
│       ├── telefonos/
│       │   └── [id].astro    # Plantilla de detalle de teléfono
│       ├── hardware/
│       │   └── [id].astro    # Plantilla de detalle de hardware
│       ├── perifericos/
│       │   └── [id].astro    # Plantilla de detalle de periférico
│       ├── notebooks/
│       │   └── [id].astro    # Plantilla de detalle de notebook
│       ├── blogs/
│       ├── index.astro       # Página de inicio
│       ├── blog.astro        # Grilla de todos los posts
│       └── nosotros.astro    # Página "Sobre Nosotros"
└── package.json            # Dependencias del proyecto
=======
>>>>>>> a0f3a4105e393936e6f058918c94e7374411aeed
