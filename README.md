# Hola, soy Cristian Aceituno

Desarrollador full-stack (FastAPI · React) y estudiante de 2º de DAM en el IES Hermenegildo Lanz, Granada. Construyo aplicaciones web completas para clientes reales, desde la base de datos hasta el despliegue.

**Busco prácticas (formación en empresa) entre el periodo de febrero a mayo de 2027** en Granada o Jaén, presencial o híbrido, para posterior contratación si encajo correctamente.
Las fechas o meses de comienzo o fin son orientativos, tengo total flexibilidad para adaptarme a cualquier periodo.

## Proyectos

### [RMolinaStyle](https://github.com/CristianAceRam/AplicacionWebMolina) · en producción en [rmolinastyle.com](https://rmolinastyle.com)

Reservas online para una barbería real. Los clientes reservan, cancelan y reprograman desde el móvil; el barbero gestiona agenda, servicios y horarios, y recibe los avisos por Telegram.

- Solapes de citas imposibles a nivel de base de datos: `UNIQUE` por franja, inserción en una sola transacción y `409 Conflict`.
- JWT + bcrypt, control de acceso por objeto, rate limiting, CSP y HSTS.
- RGPD: consentimiento versionado, exportación de datos, anonimización de cuentas y purga programada.
- Tests con pytest en cada endpoint, migraciones con Alembic e infraestructura declarada en `render.yaml`.

`FastAPI` `SQLAlchemy 2` `PostgreSQL` `React 19` `Vite` `Docker` `Render`

### [ClasificadorResenasConIA_n8n_LLM](https://github.com/CristianAceRam/bar-el-algoritmo) · Taller en el Congreso de IA de Granada 2026

Clasificador de reseñas que el público usó en directo: escaneaban un QR, escribían una reseña y una IA la clasificaba, la proyectaba en un panel y avisaba por Telegram de las quejas urgentes. Hice todo el desarrollo y la demo; Canal Sur nos entrevistó sobre el proyecto.

- Salida estructurada con JSON Schema y temperatura 0: la IA solo responde con categorías fijas y las reglas actúan sobre ellas.
- Modelo de respaldo y reintentos: ningún fallo de la IA llega al público.
- Protección frente a prompt injection y XSS; el túnel solo publica las rutas del formulario.

`n8n` `LLM (Groq)` `JSON Schema` `Docker` `Telegram Bot API` `JavaScript`

### [πίστη](https://github.com/CristianAceRam/AplicacionWebBarberiaYRopa) · cliente real, pendiente de despliegue

Citas de barbería y catálogo de ropa en una sola app, con panel de administración completo y frontend mobile-first.

`FastAPI` `PostgreSQL` `React` `Vite` `Cloudinary`

### [Gestor de prácticas](https://github.com/CristianAceRam/gestor-practicas-hlanz) · proyecto de grupo, IES Hermenegildo Lanz · en producción en [gestor-practicas-hlanz.vercel.app/](https://gestor-practicas-hlanz.vercel.app/)

Aplicación para gestionar las prácticas del centro, con autenticación JWT y control de acceso por roles. Me encargué del stack completo: backend, frontend y base de datos. El despliegue formaba parte del proyecto, lo hice de forma gratuita con la herramienta vercel.

`FastAPI` `MariaDB` `React`

## Stack

- **Backend:** Python, FastAPI, SQLAlchemy, Pydantic, pytest, Alembic
- **Frontend:** React, JavaScript, Vite
- **Datos:** PostgreSQL, MariaDB, SQL
- **Infra:** Docker, Nginx, Git, Render
- **En el ciclo:** Java (JDBC/ORM), Android, Odoo
- **Automatización e IA:** n8n, LLMs vía API, salida estructurada (JSON Schema)

## Cómo trabajo

Uso Claude Code y agentes de programación en mi flujo diario: especifico el proyecto en un `CLAUDE.md`, reviso cada cambio y lo cubro con tests. La IA acelera; las decisiones y la revisión son mías.

## Contacto

- Email: cristianaceitunor9@gmail.com
- LinkedIn: [linkedin.com/in/cristian-aceituno-ramirez](https://www.linkedin.com/in/cristian-aceituno-ramirez)

- Español nativo · Inglés C1 (Cambridge)
