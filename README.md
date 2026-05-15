# TNE App

Repositorio orquestador del sistema de autenticación TNE.
Levanta los 3 servicios (base de datos, backend y frontend) con un solo comando.

## Repositorios
- [tne-database](https://github.com/1rv1nn/tne-database.git)
- [tne-backend](https://github.com/1rv1nn/tne-backend.git)
- [tne-frontend](https://github.com/1rv1nn/tne-frontend.git)

## Requisitos
- Docker Desktop instalado y corriendo
- Git

## Instalación

1. Clona este repositorio:
git clone https://github.com/1rv1nn/tne-app.git
cd tne-app

1. Clona los servicios dentro de esta carpeta:
git clone https://github.com/1rv1nn/tne-backend.git
git clone https://github.com/1rv1nn/tne-frontend.git

1. Copia las variables de entorno:
copy .env.example .env

1. Levanta todo:
docker compose up -d

## URLs
| Servicio | URL |
|----------|-----|
| Frontend | http://localhost:9000 |
| Backend  | http://localhost:3000 |

## Usuario de prueba
| Campo    | Valor          |
|----------|----------------|
| Email    | admin@tne.com  |
| Password | password       |
| Rol      | admin          |

## Detener los servicios
docker compose down


## SS