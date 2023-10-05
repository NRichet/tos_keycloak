# Configurer Keycloak et définir une audience

Au cours du projet Digital Jukebox, vous devez effectuer la configuration de l'audience, c'est-à-dire spécifier le nom de votre application de manière à ce qu'il soit inclus dans le jeton jwt et puisse être vérifié lorsqu'une requête est faite à votre backend.

# Configuration du Keycloak

1. Créer un nouveau Realm
![1](https://github.com/NRichet/tos_keycloak/assets/87064243/b0a36e53-0c82-45c3-9f3f-b5348dd9f850)

2. Spécifier le nom souhaité et cliquer sur Create
![2](https://github.com/NRichet/tos_keycloak/assets/87064243/ebda9ba8-90d7-4f6d-a16e-6b87e9b6bff4)

3. Aller dans l'onglet Clients puis cliquer sur Create client
![3](https://github.com/NRichet/tos_keycloak/assets/87064243/4f701da1-c24a-4d9b-8f5c-97a93cfdd811)

4. Spécifier le client id puis cliquer sur Next
![4](https://github.com/NRichet/tos_keycloak/assets/87064243/f9c64c5e-ddb3-4215-bbb9-85e58e3733eb)

5. Activer Client authentication puis cliquer sur Next
![5](https://github.com/NRichet/tos_keycloak/assets/87064243/d142cf5e-42e3-4a56-88fb-2a5070a09a2f)

6. Spécifier les url de votre front pour la redirection puis cliquer sur Next
![6](https://github.com/NRichet/tos_keycloak/assets/87064243/a349b927-5ccc-48af-8f91-f37478aa0b4e)

7. Aller dans l'onglet Client scopes puis cliquer sur Create client scope 
![7](https://github.com/NRichet/tos_keycloak/assets/87064243/2352fa32-6648-4440-a7ab-87e220fe163d)

8. Spécifier le nom, en l'occurence audience, de type Default puis décocher à la fois Display on consent screen et include in token scope et enfin cliquer sur save.
![8](https://github.com/NRichet/tos_keycloak/assets/87064243/b075b4c2-c5ee-415a-85ac-f41fe21a6c1f)

9. Aller dans l'onglet Mappers puis cliquer sur Configure a new mapper
![9](https://github.com/NRichet/tos_keycloak/assets/87064243/c50ba154-8a68-41ff-a47a-0737f9dcfb50)

10. Ajouter Audience
![10](https://github.com/NRichet/tos_keycloak/assets/87064243/dc7256c7-17cf-4cfb-a5e0-910387248736)

11. Renseigner le nom spécifié en début de tos puis cliquer sur save
![11](https://github.com/NRichet/tos_keycloak/assets/87064243/6b7b3d23-3bb8-442c-8681-6dd7ebef1751)

12. Aller dans l'onglet Clients puis cliquer sur le client spécifié en début de tos.
![12](https://github.com/NRichet/tos_keycloak/assets/87064243/545a975c-3c6b-40b9-8e9d-a7acfcdb050c)

13. Aller dans l'onglet Client scopes puis cliquer sur Add client scope.
![13](https://github.com/NRichet/tos_keycloak/assets/87064243/bb1fa136-b001-4d13-9d3d-57abc158f7f2)

14. Ajouter le scope audience avec comme paramètre Default.
![14](https://github.com/NRichet/tos_keycloak/assets/87064243/87eaffa9-0be1-42e4-adee-6dd9c4943fb8)
