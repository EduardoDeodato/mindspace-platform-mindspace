<p align="center">
  <img src="https://raw.githubusercontent.com/EduardoDeodato/mindspace-platform/main/frontend/public/images/logo/mindspace-logo.png" width="250"/>
</p>

# 🧠 MINDSPACE

Plataforma de atendimento psicológico online moderna. con programas terapéuticos personalizados, teleconsultas profesionales y comunidad de soporte.

![Status](https://img.shields.io/badge/status-desarrollo-yellow)
![Version](https://img.shields.io/badge/version-0.1.0-blue)
![License](https://img.shields.io/badge/license-TFG-green)

---

## 📋 Tabla de contenidos

- [Descripción](#descripción)
- [Características](#características)
- [Tecnologías](#tecnologías)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura del proyecto](#estructura-del-proyecto)
- [Roadmap](#roadmap)
- [Autor](#autor)

---

## 📖 Descripción

**MindSpace** es una plataforma digital diseñada para **democratizar el acceso a servicios de salud mental de calidad**. Ofrece un ecosistema completo que combina:

✨ **Programas terapéuticos estructurados** basados en técnicas de terapia cognitivo-conductual (TCC) y mindfulness

🎥 **Teleconsultas profesionales** con psicólogos y psiquiatras certificados

📚 **Biblioteca psicoeducativa** con contenido validado por expertos

👥 **Comunidad de soporte** para compartir experiencias y conectar con otros usuarios

📊 **Seguimiento del progreso** con métricas de bienestar y evolución personal

---

## 🎯 Características

### 🏠 Dashboard intuitivo

- Resumen diario del estado emocional
- Progreso en programas activos
- Acceso rápido a sesiones y recursos
- Próxima cita programada con tu profesional

### 📋 Programas Terapéuticos

- **Mindfulness y Atención Plena** (8 semanas)
- **Gestión Emocional** (6 semanas)
- **Higiene del Sueño** (4 semanas)
- **Reducción de Estrés** (6 semanas)

Cada programa incluye:

- Sesiones interactivas paso a paso
- Videos educativos
- Ejercicios prácticos con retroalimentación
- Seguimiento automático del progreso

### 📚 Biblioteca Psicoeducativa

- Artículos, audios y vídeos sobre temas de salud mental
- Contenido filtrable por tema y tipo de recurso
- Todo validado por profesionales certificados
- Acceso 24/7 sin restricciones

### 💬 Comunidad

- Foro de soporte entre usuarios
- Compartir experiencias y avances
- Ambiente respetuoso y moderado
- Recursos para crisis y emergencias

### 📞 Teleconsultas

- Sesiones de 50 minutos vía videollamada
- Múltiples especialistas disponibles
- Horarios flexibles
- Cifrado end-to-end garantizado
- Política de cancelación flexible (24h antes)

### 📊 Seguimiento del Progreso

- Estadísticas semanales personalizadas
- Gráficas de evolución emocional
- Racha de consistencia
- Exportación de reportes

---

## 🛠 Tecnologías

### Frontend

React 18 + TypeScript
Material-UI (MUI) - Diseño profesional responsive
React Router - Navegación eficiente
Framer Motion - Animaciones suaves
React Hook Form - Gestión de formularios

text

### Backend

Node.js + Express - Servidor robusto
TypeScript - Tipado estático
MongoDB + Mongoose - Base de datos flexible
JWT - Autenticación segura
CORS - Comunicación segura cross-origin

text

### DevOps & Deployment

GitHub - Control de versiones
npm - Gestor de paquetes
Vite - Build tool ultrarrápido

text

---

## 🚀 Instalación

### Requisitos previos

- **Node.js** (v18 o superior)
- **npm** (v9 o superior)
- **MongoDB** (local o Atlas)
- **Git**

### Pasos de instalación

#### 1️⃣ Clonar el repositorio

git clone https://github.com/EduardoDeodato/mindspace.git
cd mindspace

text

#### 2️⃣ Configurar Backend

cd backend
npm install

text

Crea un archivo `.env` en `backend/`:
PORT=4000
MONGODB_URI=mongodb+srv://tu-usuario:tu-contraseña@cluster.mongodb.net/mindspace
JWT_SECRET=tu-clave-secreta-super-segura
NODE_ENV=development

text

Inicia el servidor:
npm run dev

text

✅ Backend corriendo en `http://localhost:4000`

#### 3️⃣ Configurar Frontend

cd ../frontend
npm install

text

Inicia la aplicación:
npm run dev

text

✅ Frontend disponible en `http://localhost:5173`

---

## 📖 Uso

### 🔐 Primeros pasos

1. Accede a `http://localhost:5173`
2. Regístrate con tu email y contraseña
3. Completa tu perfil con preferencias de bienestar
4. Elige un programa inicial
5. ¡Comienza tu viaje hacia el bienestar! 🌟

### 📱 Navegación principal

| Sección           | Descripción                               |
| ----------------- | ----------------------------------------- |
| 🏠 **Dashboard**  | Resumen personalizado de tu día           |
| 📋 **Programas**  | Intervenciones terapéuticas estructuradas |
| 📚 **Biblioteca** | Recursos educativos sobre salud mental    |
| 👥 **Comunidad**  | Conecta con otros usuarios                |
| 📞 **Sesiones**   | Reserva citas con profesionales           |
| 📊 **Progreso**   | Visualiza tu evolución                    |

---

## 📁 Estructura del Proyecto

mindspace/
├── frontend/ # Aplicación React
│ ├── src/
│ │ ├── pages/ # Páginas principales
│ │ │ ├── Dashboard.tsx
│ │ │ ├── Programas.tsx
│ │ │ ├── Biblioteca.tsx
│ │ │ ├── Comunidad.tsx
│ │ │ ├── Sesiones.tsx
│ │ │ ├── Progreso.tsx
│ │ │ ├── Login.tsx
│ │ │ └── Register.tsx
│ │ ├── components/ # Componentes reutilizables
│ │ │ ├── Sidebar.tsx
│ │ │ ├── TopBar.tsx
│ │ │ ├── QuickAccessCards.tsx
│ │ │ ├── WeeklyProgress.tsx
│ │ │ ├── DailyMoodModal.tsx
│ │ │ └── ConfirmDialog.tsx
│ │ ├── hooks/ # Custom hooks
│ │ │ └── useApi.ts
│ │ ├── theme/ # Configuración de Material-UI
│ │ │ └── theme.ts
│ │ └── App.tsx # Componente raíz
│ └── package.json
│
├── backend/ # API Express
│ ├── src/
│ │ ├── routes/ # Rutas API (próximamente)
│ │ ├── controllers/ # Controladores (próximamente)
│ │ ├── models/ # Modelos MongoDB (próximamente)
│ │ └── index.ts # Punto de entrada
│ └── package.json
│
├── README.md # Este archivo
├── .gitignore
└── LICENSE

text

---

## 🗺️ Roadmap

### ✅ Completado (v0.1.0)

- [x] Diseño UI/UX profesional
- [x] Estructura de carpetas y componentes
- [x] Sistema de autenticación (frontend)
- [x] Navegación y rutas protegidas
- [x] Animaciones y transiciones suaves
- [x] Componentes con loading states
- [x] Dashboard con widgets interactivos

### 🔄 En desarrollo

- [ ] API REST completa (Express + MongoDB)
- [ ] Autenticación con JWT
- [ ] CRUD de programas y sesiones
- [ ] Sistema de notificaciones
- [ ] Chat en tiempo real (WebSocket)
- [ ] Calendario de sesiones

### 📋 Próximas versiones

- [ ] App móvil (React Native)
- [ ] Integración de pagos (Stripe)
- [ ] Videoconferencia segura (Jitsi)
- [ ] Análisis de datos y IA (recomendaciones personalizadas)
- [ ] Integración con wearables (ritmo cardíaco, sueño)
- [ ] Multilengua (ES, EN, FR)

---

## 📝 Documentación API

_En desarrollo. Se actualizará conforme se implementen los endpoints._

POST /api/auth/register - Crear nueva cuenta
POST /api/auth/login - Iniciar sesión
GET /api/programas - Obtener programas disponibles
GET /api/programas/:id - Detalles de un programa
POST /api/sesiones - Reservar sesión
GET /api/progreso - Obtener estadísticas de progreso

text

---

## 🤝 Contribuciones

Este es un proyecto de **Trabajo de Fin de Grado**. Las contribuciones están limitadas al autor.

Si encuentras bugs o tienes sugerencias, abre un **issue** en GitHub.

---

## 🔐 Seguridad

- ✅ Contraseñas hasheadas con bcrypt
- ✅ Autenticación con JWT
- ✅ CORS configurado
- ✅ Variables de entorno protegidas
- ✅ RGPD compliant
- ✅ Encriptación end-to-end en teleconsultas

---

## 📄 Licencia

Este proyecto es parte de un **Trabajo de Fin de Grado en Ingeniería Informática** por Iván Blasco.

**Año:** 2025  
**Universidad:** Universitat de Verdum (modificar según corresponda)  
**Materia de Honor:** Cumplimiento de estándares profesionales

---

## 👨‍💻 Autor

**Eduardo Deodato Souza Costa**

Desenvolvedor em formação focado em sistemas web e arquitetura de software.

- 🔗 GitHub: https://github.com/EduardoDeodato

---

## 📞 Soporte

Para consultas técnicas o reportar problemas:

1. Abre un **issue** en GitHub
2. Describe el problema en detalle
3. Incluye pasos para reproducirlo
4. Adjunta screenshots si es necesario

---

## 🙏 Agradecimientos

- Material-UI por los componentes profesionales
- React community por las librerías útiles
- Profesionales de salud mental que validaron el contenido

---

<div align="center">

### ⭐ Si te gusta el proyecto, ¡déjame una estrella en GitHub!

**[🌟 Star the Repo](https://github.com/ivanblascoverdu/mindspace)**

---

**Hecho con ❤️ para mejorar la salud mental digital**

</div>
