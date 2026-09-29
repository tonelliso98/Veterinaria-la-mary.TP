# Veterinaria La Mary — Trabajo Final Integrador

**Materia:** Introducción al Desarrollo Web (2do Cuatrimestre 2026)
**Carrera:** Tecnicatura Universitaria en Desarrollo Web
**Institución:** Facultad de Ciencias de la Administración — Universidad Nacional de Entre Ríos (UNER)
**Comisión / Grupo:** IDW Grupo 19

## Integrantes del Grupo

- Francisconi, Gonzalo
- Moreno Abuslaiman, Jorge
- Serrano, Valentin
- Tonelli, Sofia Macarena

## Descripción del Proyecto

Aplicación web para la clínica **"Veterinaria La Mary"**, un establecimiento dedicado a la atención médica de animales de compañía en Paraná, Entre Ríos.

## Alcance de la 2da Entrega (Rol Visitante + RWD + Bootstrap 5)

Sobre la base de HTML5 semántico entregada en la 1ra etapa, esta entrega incorpora:

- **Bootstrap 5** (vía CDN), combinado con la hoja de estilos propia del proyecto.
- **Diseño responsivo (RWD)** con más de tres puntos de quiebre (sistema `row-cols-*` de Bootstrap, `navbar-expand-lg`, y media queries propias en 860px y 640px).
- **Catálogo de profesionales** en la portada, armado con el sistema de grillas de Bootstrap: cada tarjeta incluye foto, nombre, especialidad y valor de consulta.
- **Barra de navegación responsiva**, con menú colapsable tipo "hamburguesa" en dispositivos móviles, y acceso a las tres páginas del sitio.
- **Componentes de Bootstrap**: cards, modals (perfil de cada profesional y confirmación de envío del formulario), formularios con validación, alerts y tablas.
- **Modo oscuro** (opcional), con preferencia guardada en `localStorage`.

Páginas del sitio:

- `index.html` — Portada, con listado de profesionales
- `institucional.html` — Información institucional, valores y horarios
- `contacto.html` — Datos de contacto y formulario de consulta

## Estructura de Carpetas

```
veterinaria-la-mary/
├── index.html
├── institucional.html
├── contacto.html
├── package.json
├── README.md
├── assets/
│   ├── images/       # Logo institucional (svg/png)
│   └── fonts/         # Tipografía Roboto local
├── css/
│   └── style.css      # Estilos propios + integración con variables de Bootstrap
└── js/
    └── main.js         # Modo oscuro (localStorage) + validación del formulario
```

## Cómo correr el proyecto

1. Instalar dependencias:
   ```
   npm install
   ```
2. Levantar el servidor de desarrollo con Vite:
   ```
   npx vite
   ```
3. Abrir en el navegador la URL que indique la terminal (por defecto `http://localhost:5173`).

## Próximas etapas

- **3ra entrega (final):** interfaces de administrador, JavaScript avanzado, persistencia con LocalStorage para Mascotas/Veterinarios/Turnos/Historia Clínica, consumo de API REST externa con fetch, y video de exposición grupal.
