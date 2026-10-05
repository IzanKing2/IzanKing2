<h1 align="center">Izan Carlo Celis Afonso</h1>

<p align="center">
  <b>Full Stack Developer · AI-Native Developer</b><br/>
  Next.js / React · Supabase / PostgreSQL · Laravel / PHP · Java / Spring Boot
</p>

<p align="center">
  <img
    src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&duration=3000&pause=1000&color=00F7FF&center=true&vCenter=true&width=650&lines=Creador+de+Between+%E2%80%94+betweengame.com;Next.js+16+%7C+React+19+%7C+TypeScript+%7C+Supabase;Spec-Driven+Development+con+IA;Claude+Code+%7C+MCPs+%7C+Agent+Skills;Laravel+%7C+PHP+%7C+Java+%7C+Spring+Boot"
    alt="Typing SVG"
  />
</p>

<p align="center">
  <a href="https://betweengame.com"><img src="https://img.shields.io/badge/Between-betweengame.com-E0457B?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Between"/></a>
  <a href="https://portafolio-izan.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/izan-celis-afonso-4a4a1036b/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:izanwork2@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
</p>

---

## 👨‍💻 Sobre mí

**Técnico Superior en DAW** y desarrollador Full Stack. Trabajo como **Desarrollador Web en Servibyte S.L.** (Beca Cataliza) tras 466 horas de FP Dual en la misma empresa, y en paralelo he diseñado, construido y lanzado mi propio producto: **[Between](https://betweengame.com)**.

Me defino como **desarrollador AI-native**: no uso la IA para "generar código", la uso como parte de un proceso de ingeniería con especificaciones, decisiones documentadas, tests y revisión.

📍 Agüimes, Las Palmas, España · 🌍 Español nativo · Inglés B1

---

## ⭐ Proyecto estrella: [Between](https://betweengame.com)

<p>
  <a href="https://betweengame.com"><img src="https://img.shields.io/badge/estado-beta_cerrada_en_producci%C3%B3n-2ea44f?style=flat-square" alt="Estado"/></a>
  <img src="https://img.shields.io/badge/tests_unitarios-556-blue?style=flat-square" alt="Tests unitarios"/>
  <img src="https://img.shields.io/badge/migraciones_SQL-125-blue?style=flat-square" alt="Migraciones"/>
  <img src="https://img.shields.io/badge/ADRs-6-blue?style=flat-square" alt="ADRs"/>
</p>

**Un juego privado y persistente para parejas**, instalable como PWA: retos, misiones diarias y semanales, minijuegos en tiempo real y a distancia, partidas asíncronas, recompensas, logros y rachas. Producto completo hecho por mí de punta a punta — especificación, diseño, código, despliegue, legal y marketing — y en **beta cerrada con usuarios reales**.

**Lo más interesante a nivel técnico**

- 🔒 **Privacidad y consentimiento como reglas estructurales**, no como avisos: cada pareja es un espacio aislado con **Row Level Security** en todas las tablas, y los límites de cada usuario se aplican en el motor de selección de contenido sin revelarse nunca a la otra persona.
- 🧠 **Lógica de negocio en PostgreSQL**: funciones `security definer`, triggers y tareas `pg_cron` para misiones, cofres semanales, economía de puntos, rachas y recordatorios.
- ⚡ **Sincronización en tiempo real** entre los dos móviles con Supabase Realtime, más partidas "sin prisa" asíncronas.
- 🔔 **Notificaciones Web Push y email** mediante Edge Functions (Deno), con copy genérico en la pantalla de bloqueo y deduplicado.
- 🧩 **Motor de juego separado del contenido**: catálogo de retos por niveles de intensidad con esquema propio, sin texto hardcodeado en la lógica.
- 💳 **Planes opcionales con Stripe** (Checkout + Billing Portal) detrás de un único punto de control de acceso.
- ✅ **Calidad**: 556 tests unitarios (Vitest), 17 tests e2e (Playwright), 16 scripts de integración SQL que prueban RLS actuando como cada miembro de la pareja y como un extraño.
- ⚖️ **RGPD / LOPDGDD**: registro de tratamientos, evaluación de impacto (DPIA) y protocolo de brechas.

`Next.js 16` `React 19` `TypeScript` `Tailwind CSS 4` `shadcn/ui` `Supabase` `PostgreSQL` `RLS` `pg_cron` `Edge Functions` `Web Push` `PWA` `Stripe` `Vitest` `Playwright` `Vercel`

---

## 🤖 Desarrollo con IA

Construyo software con agentes de IA (sobre todo **Claude Code**) siguiendo un flujo de ingeniería, no de "prompt y copiar":

- 📐 **Spec-Driven Development**: cada funcionalidad nace de una especificación (Between tiene una spec de producto de 100+ secciones, specs técnicas por servicio y **ADRs** para cada decisión transversal). La IA implementa contra la spec, no contra una idea vaga.
- 🧰 **Agent Skills propias**: he escrito skills específicas del dominio que el agente carga solo cuando las necesita — reglas de consentimiento y seguridad, aislamiento de datos con RLS, sistema de diseño, checklist para nuevos tipos de notificación, comprobación de coherencia con la spec, grabación de vídeos de marketing…
- 🔌 **MCPs**: el agente trabaja conectado a Supabase (consultas de verificación en solo lectura), Vercel, el navegador (Chrome) y otras herramientas.
- 📝 **Contexto de proyecto** (`CLAUDE.md`, memoria persistente) con principios no negociables, comandos, flujo de despliegue y convenciones de migraciones.
- 🧪 **Verificación siempre**: tests, typecheck, scripts SQL contra el stack local y comprobación en el navegador antes de dar algo por terminado.

`Claude Code` `MCP` `Agent Skills` `Spec-Driven Development` `ADRs` `TDD`

---

## 💼 Experiencia

### Servibyte S.L. — Desarrollador Web (Beca Cataliza)
`Junio 2026 – Presente`

**GestiCAB V3** — refactorización de una plataforma **multi-tenant** legacy de inscripciones y control de aforo de eventos municipales hacia una arquitectura desacoplada con **DTOs y Servicios de Dominio**.

- Control de concurrencia con bloqueos pesimistas (`lockForUpdate`) y servicio de *heartbeat lock*.
- Seguridad: **CSP** con nonces dinámicos, **HSTS** y autorización **RBAC** con 20+ middlewares.
- 60 migraciones sobre **MySQL 8.0** y CI/CD con **GitHub Actions** sobre MySQL y SQLite.
- **174 tests** (unitarios, feature y smoke) con **566 aserciones** al 100 %.

`PHP` `Laravel` `Vue` `MySQL` `PHPUnit` `GitHub Actions` `Docker`

### Servibyte S.L. — Desarrollador Web en Prácticas (FP Dual)
`2025 – Junio 2026 · 466 horas`

Desarrollo Full Stack de módulos para aplicaciones en producción, optimización de código heredado e integración de asistentes de IA en el flujo de entrega.

---

## 🚀 Otros proyectos

| Proyecto | Descripción | Stack |
|---|---|---|
| 🍽️ [**SaborSemanal**](https://saborsemanal.vercel.app/) | PWA de planificación semanal de comidas: recetas, alérgenos, porciones, lista de la compra, modo offline. RPC transaccionales, RLS y tests con pgTAP. | Next.js · Supabase · PostgreSQL · pgTAP |
| 🛒 [**GeekZone E-Commerce**](https://github.com/IzanKing2/geekzone-ecommerce) | E-commerce de coleccionables con carrito, panel de administración y API REST documentada. | Laravel · MySQL · Docker · JWT · Swagger |
| 📚 [**API REST Libros y Autores**](https://github.com/IzanKing2/API-REST-de-Libros-y-Autores) | API con Spring Security + JWT, validaciones, manejo global de excepciones y tests de integración. | Java · Spring Boot · MySQL · JUnit · Mockito |

---

## 🛠️ Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,vue,angular,supabase,postgres,mysql,sqlite&perline=10" alt="Frontend y datos"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=php,laravel,java,spring,python,docker,githubactions,git,linux,vercel&perline=10" alt="Backend y DevOps"/>
</p>

<p align="center">
  <b>Testing:</b> Vitest · Playwright · Testing Library · PHPUnit · pgTAP · JUnit · Mockito
</p>

---

## 🎓 Formación

- **Técnico Superior en Desarrollo de Aplicaciones Web (DAW)** — CIFP Villa de Agüimes · `2024 – 2026`
- **Bachillerato Tecnológico** — IES Playa de Arinaga · `2020 – 2022`

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer&animation=twinkling"/>
</p>
