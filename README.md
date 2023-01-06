# Ce projet est le projet_4 de ma formation intégrateur web avec Open classroom

1- On creer un dossier pour le projet et dans le terminal on lance : npm init .

2- On installe Sass en global ou juste pour ce projet en ajoutant ou enlevant le flag -g à la commande npm install -g sass .

3- Dans le fichier package.json on peut supprimer la ligne concernant les tests :

4- Toujours dans le package.json on rajoute la ligne : "sass": "sass --watch ./sass/main.scss:./public/css/style.css" ,le premier fichier étant le fichier sass et le second etant le fichier final en css, une fois cette ligne rajouter on va pouvoir executer la commande sass : npm run sass qui va lancer sass dans notre projet.

5- On créer l'architecture de dossier 7:1.

6- Les fichiers html des pages des restaurants seront stockés dans le dossier restaurants.

7- Les images seront stockés dans le dossier img du dossier public.
