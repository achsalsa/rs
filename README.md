## Lien API artiste
  > http://localhost:8888/omeka/api/items/9
ceci est le lien vers l'item de l'artiste renaud dedans on peut trouver les informations classiques et la collection discographie contenant ses albums.
### Lien API: album "Amoureux de Paname" de renaud
  > http://localhost:8888/omeka/api/items/14

### Lien API: album "laisse béton" de renaud
  > http://localhost:8888/omeka/api/items/15

### Lien API: Tous les items y compris les vins, et les evenements musicaux
  > http://localhost:8888/omeka/api/items
 
# Description du projet 
Vous trouverez ci-joint deux fichiers Json, exportés depuis Omeka-s afin de service de template.
  > le champ discography servira de collection à contenir des albums, et faire ainsi le lien entre la ressource template Artist et la ressource template Album

### Un fichier Json Artist contenant les informations suivantes:
1. Title (nom de production de l'artiste)
2. firstName
3. familyName
4. birthday
5. Description
6. activity
7. image
8. genre
9. Date Available
10. discography
11. instrument
12. biography
13. download
14. group
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

