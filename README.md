# Product Microservice

## Dev

1. Clonar el repositorio
2. Instalar dependencias
3. Crear un archivo `.env` basado n el archivo `.env.example`
4. Ejecutra migración de prisma `npx prisma migrate dev`
5. Levantar el servidor de NATS con `docker run -d --name nats-main -p 4222:4222 -p 8222:8222 nats`
6. Ejecutar el proyecto `npm run dev`
