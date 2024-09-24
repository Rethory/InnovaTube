#  InnovaTube - Plataforma de Videos Integrada con YouTube

## Descripción del Proyecto

Este proyecto comenzó utilizando **Angular**, pero debido a restricciones de tiempo, se decidió migrar a **React**. El plan de trabajo se dividió en dos áreas principales: **Frontend** y **Backend**, integrando diversas tecnologías para ofrecer una plataforma robusta y eficiente.

---

## Tecnologías Utilizadas

### Frontend:
- **React.js**
- **Redux** para la gestión de estado
- **React icons** para el diseño y componentes visuales

### Backend:
-  **FireBase** como base de datos

### API y Servicios:
- **YouTube API v3** para la integración de videos
- **Autenticación** con Google

### Hosting:
- **GitHub** para el despliegue y hosting del proyecto

---

## Funcionalidades Principales

### Búsqueda de Videos
Integración con la **YouTube API** que permite traer y buscar videos directamente desde YouTube.

### Suscripciones
Los usuarios pueden suscribirse a canales, y las suscripciones se guardan en la base de datos bajo el perfil de cada usuario. Esto permite mostrar una **sección personalizada de canales suscritos**.

### Me Gusta
Los usuarios pueden marcar videos como favoritos. Estos "Me gusta" se almacenan en la base de datos y se muestran en una **sección de videos favoritos** bajo el perfil de cada usuario.

---

## Cómo Ejecutar el Proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Rethory/InnovaTube.git

2. Instala las dependencias:
   ```bash
   npm install

1. Ejecuta el proyecto localmente:
   ```bash
   npm start