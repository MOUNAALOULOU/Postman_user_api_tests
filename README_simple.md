# Postman API Testing - User Collection

Ce projet contient une collection Postman complète pour tester l'API FakeREST (`fakerestapi.azurewebsites.net`).

## Objectif

Automatiser les tests des endpoints utilisateurs (`/Users`) de l'API FakeREST avec les opérations suivantes :
- GET : récupérer un utilisateur
- POST : créer un utilisateur avec ID dynamique
- PUT : mettre à jour un utilisateur existant
- DELETE : supprimer un utilisateur

## Contenu

### Fichiers inclus :
- `UserCollection.postman_collection.json` : collection Postman avec requêtes et scripts de test
- `FakeAPI_Users.postman_environment.json` : environnement avec variables dynamiques

### Variables utilisées :
- `baseUrl` : URL de base de l'API
- `randomUserId` : ID aléatoire généré avant chaque POST
- `createdUserId` : ID sauvegardé pour GET et DELETE après création

## Comment utiliser cette collection ?

### Étape 1 : Importer les fichiers dans Postman
1. Ouvrir Postman
2. Cliquer sur **Import**
3. Sélectionner `UserCollection.postman_collection.json`
4. Répéter l’opération pour `FakeAPI_Users.postman_environment.json`

### Étape 2 : Activer l’environnement
- En haut à droite, choisir l’environnement **FakeAPI_Users**

### Étape 3 : Lancer les tests automatisés
1. Cliquer sur la collection `UserCollection`
2. Cliquer sur **Run Collection**
3. Définir `Delay` sur `500 ms` (facultatif mais conseillé)
4. Lancer l’exécution et observer les résultats des tests

---

*Généré pour Mouna, le 21/05/2025*
