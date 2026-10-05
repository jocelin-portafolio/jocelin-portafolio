# Hola, soy Jocelin 👋

**Desarrollo web full stack e ingeniería de agentes de IA.** Construyo aplicaciones con foco en el área de la salud y la inclusión: plataformas para organizaciones que trabajan con neurodiversidad y discapacidad, y agentes con LLMs diseñados para ser seguros, medibles y observables.

🌐 **Portafolio:** [jocelin-portafolio.github.io](https://jocelin-portafolio.github.io)

### 🛠️ Stack

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-D97757?logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

## 🌱 NINTAI — AI Capability Intelligence
Startup que estoy construyendo como fundadora: una plataforma de IA que transforma capacidades humanas en nuevas rutas de aprendizaje, empleo e ingresos. Parte con mujeres que buscan reconversión laboral y escala a personas en transición, freelancers e instituciones.
- **NINTAI 2.0 (LATAM):** acceso conversacional por WhatsApp, constructor de micro-servicios con cobros locales y alianzas B2B2C con programas públicos.
- **MVP:** perfil inteligente, motor IA con RAG, generador de rutas y constructor de servicios.

`Next.js` `TypeScript` `Python` `LangChain` `Langfuse` `n8n` · [Ver propuesta completa](https://jocelin-portafolio.github.io/#nintai)

## 🚀 Proyectos destacados

### 🤖 [finanzas-agent](https://github.com/jocelin-portafolio/finanzas-agent) — Agente de IA + servidor MCP
Agente con Claude que gestiona finanzas personales en lenguaje natural a través de un servidor **Model Context Protocol** propio.
- Bucle de *tool use* con límite de pasos y **aprobación humana** obligatoria para acciones destructivas.
- **Defensa contra prompt injection** y errores de validación devueltos al modelo para que se autocorrija.
- **Evals automatizados** que verifican el estado final de la base de datos; CI separado para tests deterministas (ruff + pytest) y evals con costo.
- Trazas de **latencia, tokens y costo** por tarea.

`Python` `MCP` `Claude API` `Pydantic` `SQLite` `pytest` `GitHub Actions` `Docker`

### 🏛️ [IA para licitaciones · PlatWave](https://github.com/jocelin-portafolio/platwave-licitaciones-ia) — Experiencia profesional *(desarrollo full stack)*
Plataforma que analiza bases de licitación y evalúa ofertas técnicas y económicas con agentes de IA hasta generar un ranking global.
- Tres agentes en **LangGraph**: análisis de criterios con ramas en paralelo, preguntas y respuestas (*retrieve → generate → rewrite*) y evaluación de ofertas.
- **RAG** con una colección de ChromaDB por licitación; API en **FastAPI** con evaluaciones asíncronas sobre PostgreSQL.
- Frontend en **React** con SSO de Keycloak; trazas en **Langfuse**.

`Python` `FastAPI` `LangGraph` `LangChain` `ChromaDB` `PostgreSQL` `React` `Keycloak` · *Código propiedad de PlatWave; se publica el caso de estudio.*

### 🏥 [aped-plataforma](https://github.com/jocelin-portafolio/aped-plataforma) — Plataforma full stack para ONG
Sitio y API para una organización de personas con discapacidad.
- **API REST** con Route Handlers: citas con filtros y paginación, cálculo de **disponibilidad en tiempo real** por terapeuta.
- Talleres con **control de cupos y lista de espera automática**.
- Modelado con Mongoose, validación centralizada, contraseñas con bcrypt y **SEO con JSON-LD**.

`Next.js 15` `React 19` `MongoDB` `Mongoose` `Tailwind CSS`

### 🧩 [neurodashboard](https://github.com/jocelin-portafolio/neurodashboard) — Dashboard de seguimiento terapéutico
SPA para registrar pacientes y sesiones y visualizar su evolución.
- Estado global con **Context API + useReducer** y persistencia local.
- Capa de API aislada en un **custom hook** con estados de carga y error; consumo de API pública con Axios.
- Rutas dinámicas, modo oscuro, CSS Modules y PropTypes.

`React 19` `Vite` `React Router 7` `Axios`

### 🌿 [huellanativa](https://github.com/jocelin-portafolio/huellanativa) — SPA en JavaScript vanilla
Perfiles sensoriales, e-commerce con carrito persistente y monitor IoT simulado.
- **Renderizado 100 % seguro frente a XSS**: sin `innerHTML`, solo `createElement` / `textContent`.
- Validación con expresiones regulares, búsqueda y filtrado en tiempo real, notificaciones toast.

`JavaScript ES6+` `DOM API` `localStorage` · [Demo](https://jocelin-portafolio.github.io/huellanativa/)

### 🐴 [terapia_proyecto](https://github.com/jocelin-portafolio/terapia_proyecto) — Sitio institucional
Sitio responsive para una fundación de terapias en la naturaleza: donaciones, alianzas RSE, scroll spy y validación de formularios en tiempo real.

`HTML5` `CSS3` `Bootstrap 5` `JavaScript` · [Demo](https://jocelin-portafolio.github.io/terapia_proyecto/)

### 🗄️ [proyecto_bd](https://github.com/alexispferrada-wq/proyecto_bd) — Gestión de productos en Django *(proyecto en equipo)*
CRUD con autenticación sobre base de datos relacional, desarrollado junto a [Alex Ferrada](https://github.com/alexispferrada-wq).
- Patrón MVT con ORM y migraciones; login y registro con hash PBKDF2, CSRF y `@login_required`.
- Doble entorno: Docker Compose (Django + MySQL 8 + phpMyAdmin) o local con SQLite.

`Python` `Django 5` `MySQL` `Docker`

## 📌 Enfoque de trabajo

- **Seguridad desde el diseño:** validación en cliente y servidor, prevención de XSS y de prompt injection.
- **Código mantenible:** separación por capas, componentes reutilizables y principio DRY.
- **Calidad medible:** tests, evals, linters y CI.
- **Accesibilidad y SEO** como parte de la definición de terminado.
