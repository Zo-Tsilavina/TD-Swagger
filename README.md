# Student AND teachers API Documentation

Voici le lien du Swagger.io: **https://petstore.swagger.io/?url=https://raw.githubusercontent.com/Zo-Tsilavina/TD-Swagger/main/TD.yaml**

Cette documentation décrit l'API des étudiants, qui permet de gérer les informations des étudiants.

## Spécifications de l'API

- Version OpenAPI : 3.0.0
- Titre : Student API
- Version : 1.0.0

## Serveur

L'API est accessible à l'adresse : **http://STD22083.com**

## Endpoints

### GET /students

Récupère les informations des étudiants.

- Réponse en cas de succès (code 200) :

  ```json
  {
    "id": "STD22083",
    "name": "Zo Tsilavina",
    "age": 18
  }