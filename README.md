# 🚀 Backend Node.js Starter Generator

Este proyecto es una plantilla generada automáticamente para construir backends con **Node.js**, **Express**, **Socket.IO (opcional)**, **PostgreSQL** y **Prisma**, con una arquitectura escalable y modular.

---

## 🧰 Tecnologías integradas

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Socket.IO](https://socket.io/) (opcional)
- [PostgreSQL](https://www.postgresql.org/)
- [Prisma ORM](https://www.prisma.io/)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [Nodemon](https://www.npmjs.com/package/nodemon)

---

## 📁 Estructura del proyecto

```bash
src/
├── controllers/      # Lógica de negocio
├── routes/           # Rutas Express
├── sockets/          # Conexiones Socket.IO (si aplica)
├── listeners/        # Eventos del WebSocket (si aplica)
├── middlewares/      # Middlewares personalizados
├── services/         # Lógica reutilizable
├── models/           # Abstracción de datos
├── config/           # Configuración (ej. prismaClient.js)
prisma/
├── schema.prisma     # Modelo de base de datos Prisma
.env                  # Variables de entorno
