# Proyecto: _Nombre del Proyecto_

[![React](https://img.shields.io/badge/React-18-61DAFB)]() [![Next.js](https://img.shields.io/badge/Next.js-12%2B-black)]() [![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3-06B6D4)]() [![.NET](https://img.shields.io/badge/.NET%20Core-3.1%2F6-512BD4)]() [![Python](https://img.shields.io/badge/Python-FastAPI-3776AB)]() [![DB](https://img.shields.io/badge/DB-PostgreSQL%20%7C%20SQL%20Server-336791)]() [![AWS](https://img.shields.io/badge/AWS-EC2%20%7C%20S3-FF9900)]() [![CI](https://img.shields.io/badge/CI-GitHub%20Actions-2088FF)]()

> Breve descripción en 2–3 líneas: ¿qué problema resuelve, para quién y por qué es útil?  
> Opcional: una línea en inglés para reclutadores: _Short English summary of what this app does._

---

## 🧭 Tabla de contenidos
- [Arquitectura](#-arquitectura)
- [Características](#-características)
- [Stack](#-stack)
- [Requisitos](#-requisitos)
- [Configuración rápida](#-configuración-rápida)
- [Variables de entorno](#-variables-de-entorno)
- [Estructura del proyecto](#-estructura-del-proyecto)
- [Comandos útiles](#-comandos-útiles)
- [API de ejemplo](#-api-de-ejemplo)
- [Migraciones y datos](#-migraciones-y-datos)
- [Testing](#-testing)
- [CI/CD](#-cicd)
- [Roadmap](#-roadmap)
- [Contribución](#-contribución)
- [Licencia](#-licencia)
- [Autor](#-autor)

---

## 🏗️ Arquitectura
```text
apps/
  web/            -> Next.js (UI, SSR/ISR)
api/
  dotnet/         -> .NET Core 3.1/6 Web API
  fastapi/        -> FastAPI (servicios auxiliares)
db/
  migrations/     -> EF Core / Alembic
infra/
  docker/         -> Docker & docker-compose
  aws/            -> IaC / scripts de despliegue
