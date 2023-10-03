# MODULE - DevOps : WIK-DPS-TP01

## I - Prérequis

Pour lancer ce projet, vous devez avoir une variable d'environnement nommée `PING_LISTEN_PORT` qui doit contenir le port sur lequel écoutera notre app.

Vous devez également avoir NodeJS (et NPM) d'installés.


## II - Installation & Dépendances

Pour commencer, récupérons l'app en utilisant la commande suivante !

```bash
git clone https://github.com/LukaGrc/WIK-DPS-TP01.git
```

Maintenant, nous devons installer les dépendances en utilisant la commande suivante :

```bash
npm i
```

## III - Lancement du projet

Pour lancer le projet, vous devez exécuter la commande suivante :

```bash
npm start
```

Vous pouvez maintenant vous rendre sur http://localhost:`le port que vous avez en variable d'environnement`/ping !