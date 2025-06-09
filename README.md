# Kit de inicio Astro: minimalista

```
npm create astro@latest -- --template minimal
```

> 🧑‍🚀 **Disponibilidad inmediata?** Con este framework es posible!

## 🚀 Estructura del proyecto

Dentro del proyecto Astro, verás las siguientes carpetas y archivos:

```text
/
├── public/
│   └── favicon.svg -- Icono del sitio web
├── src/
│   └── pages/
│       └── index.astro -- Página principal del proyecto
│   └── styles/
│       └── global.css -- Archivo CSS global para estilos del proyecto
└── .env -- Variables de entorno para trabajar con Cloudinary
└── .gitignore -- Archivos y carpetas a ignorar por Git
└── astro.config.mjs -- Configuración de Astro integrando frameworks y autorización de dominios
└── package.json -- Dependencias y scripts del proyecto
└── package-lock.json -- Bloqueo de dependencias
└── README.md -- Documentación del proyecto
└── tsconfig.json -- Configuración de TypeScript
```

Astro busca archivos `.astro` o `.md` en el directorio `src/pages/`. Cada página se expone como una ruta según su nombre de archivo.

No hay nada especial en `src/components/`, pero ahí es donde nos gusta colocar cualquier componente Astro/React/Vue/Svelte/Preact.

Cualquier activo estático, como imágenes, se puede colocar en el directorio 'public/'.

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

| Comando                   | Acción                                                                                          |
|:--------------------------|:------------------------------------------------------------------------------------------------|
| `npm install`             | Instala dependencias                                                                            |
| `npm run dev`             | Inicia el servidor de desarrollo local en `localhost:4321`                                      |
| `npm run build`           | Construya su sitio de producción en `./dist/`                                                   |
| `npm run preview`         | Obtenga una vista previa de su compilación localmente, antes de implementarla                   |
| `npm run astro ...`       | Ejecute comandos CLI como `astro add`, `astro check`                                            |
| `npm run astro -- --help` | Obtenga ayuda para utilizar la CLI de Astro                                                     |

## Cómo usar este proyecto

Al instalar las dependencias con `npm install`, puedes iniciar el servidor de desarrollo con 
`npm run dev`. Esto iniciará un servidor local en `http://localhost:4321` 
donde podrás ver el proyecto en acción localmente.


## 👀 ¿Quieres saber más?

No dudes en consultar [nuestra documentación](https://docs.astro.build) o visitar nuestro [servidor de Discord](https://astro.build/chat).
Estos enlaces son de referencia a la documentación oficial de Astro, donde encontrarás guías, tutoriales y una comunidad activa para resolver tus dudas.
