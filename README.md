# Hola, soy Kevin Uribe 👋

**Desarrollador Full-Stack · Colombia 🇨🇴**

Construyo plataformas SaaS de extremo a extremo: arquitectura, backend, frontend, IA aplicada y operación en producción. No solo escribo features — las despliego, las mantengo y las opero con usuarios reales.

🌐 **[Portafolio](https://kaizen1602.github.io/kevinPortafolio/)** · 💼 **[LinkedIn](https://www.linkedin.com/in/kevin-david-uribe-ocampo-aab882317/)** · 📫 kevindaviduribe@gmail.com

---

## En números

- 🚀 **6 proyectos en producción**, usados a diario por cientos de personas
- 👥 **+280 usuarios activos** entre plataformas corporativas
- 🤖 **Agente IA por WhatsApp** con 9 herramientas de tool-calling que cierra pedidos de forma autónoma
- 🏪 **527 puntos de venta** gestionados en una sola plataforma de field service

## Qué he construido

| Proyecto | Qué es | Stack principal |
|----------|--------|-----------------|
| **[Neziak](https://neziak.cloud)** | SaaS multi-tenant: chatbot de ventas con IA por WhatsApp + POS + inventario + CRM + pagos. 3 verticales sobre el mismo código, cliente productivo real | TypeScript · Fastify 5 · Prisma 6 · PostgreSQL 16 · BullMQ · Vercel AI SDK · React 18 · Docker · Traefik |
| **AppVisitas** 🔒 | Field service management: 65 usuarios, 8 roles, RBAC de 55 permisos, 2FA TOTP, GPS, firmas digitales, reportes Excel | Node 22 · Express 5 · PostgreSQL · Redis · Socket.IO · React 19 |
| **Altius** 🔒 | SaaS regulatorio (Res. 4272/2021 Colombia): digitaliza Análisis de Trabajo Seguro y Permisos de Trabajo en Alturas con generación de formatos oficiales en Excel | NestJS 10 · Next.js 15 · Prisma 6 · MinIO · Playwright |
| **SuperEdu** 🔒 | LMS corporativo: frontend Next.js sobre Chamilo headless con ~70 endpoints custom en Symfony, 213 usuarios | Next.js 14 · Symfony 6.4 · MariaDB · PostgreSQL 17 |
| **[Gambeta Tienda](https://gambetatienda.com)** · **[Taller Macramé](https://tallermacrame.com)** | E-commerce en producción; Gambeta opera integrada con Neziak | WordPress · WooCommerce |

🔒 = red interna corporativa — demo disponible en entrevista.

## Logros técnicos que me gusta contar

- 🐛 Diagnostiqué y resolví un bug de autenticación en producción que expulsaba usuarios cada ~8 min: **9 kicks/día → 0**, logins/día −70%.
- 🔐 RBAC idempotente: 55 permisos que se reconcilian solos al arranque — agregar un permiso es editar un archivo y desplegar, sin downtime.
- ⚛️ Transiciones de estado con CAS atómico (`updateMany({where:{id,status}})`) y retry-loop con jitter para numeración secuencial bajo concurrencia.
- 🖼️ Pipeline de imágenes Multer + Sharp (EXIF → auto-rotación → WebP): −70% de espacio en disco.

## Stack

**Backend:** TypeScript · Node.js · NestJS · Express · Fastify · PostgreSQL · Prisma · Redis · BullMQ
**Frontend:** React · Next.js · Tailwind · Zustand · TanStack Query
**IA:** Vercel AI SDK · OpenAI · Anthropic · tool-calling · anti-alucinación
**DevOps:** Docker · Nginx · Traefik · Linux (Debian) · GitHub Actions · PM2
**Seguridad:** JWT · TOTP 2FA · Argon2id · RBAC granular · rate limiting · audit logs
