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
you have to call api auth login endpoint first get the token then you can call that translations api(If not excuting Test)
** if you want to run the translationControllerTest and translationserviceTest you need to disabled security as i do this in project.
