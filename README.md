# Description du projet 
Vous trouverez ci-joint deux fichiers Json, exportés depuis Omeka-s afin de service de template.
  > le champ discography servira de collection à contenir des albums, et faire ainsi le lien entre la ressource template Artist et la ressource template Album

### Un fichier Json Artist contenant les informations suivantes:
1. firstName
2. familyName
3. birthday
4. Description
5. activity
6. image
7. genre
8. Date Available
9. discography
10. instrument
11. biography
12. download
13. group
15. producer
16. wikipedia

### Un fichier Json Album contenant les informations suivantes:
1. Title
2. Description
3. duration
4. Date Available
5. producer
6. label
7. image
8. download
9. track
10. track number

## Lien API artiste
  > http://localhost:8888/omeka/api/items/9
ceci est le lien vers l'item de l'artiste renaud dedans on peut trouver les informations classiques et la collection discographie contenant ses albums.
### Lien API album "Amoureux de Paname" de renaud
  > http://localhost:8888/omeka/api/items/14

### Lien API album "laisse béton" de renaud
  > http://localhost:8888/omeka/api/items/15
