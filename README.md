# 🌐 Translation Management API (Spring Boot)

## 🚀 Features
- Manage translations by locale and context
- Search, export, and create translations via REST API
- JWT-based authentication
- 100K+ records seeding
- Swagger UI documentation
- Dockerized setup
- Response times: <200ms (CRUD), <500ms (Export)

## 🛠 Setup

```bash
git clone https://github.com/translation/translation.git
cd translation
./mvnw clean package
docker-compose up --build

* note :-
need to install postgres db and username and password is postgres as mentioned in application.properties
