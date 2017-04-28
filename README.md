# MyGfi

Pour réaliser notre Webapp, nous avons décidé d'utiliser la technologie Nodejs qui nous semblait la plus appropriée.
Cette technologie permet d'executer du Javascript coté serveur avec une rapidité considérable. Cela permet également d'unifier les langages dans l'application étant donné que le Javascript represente l'intégralité du coté client.


### Moteur de template

Pour une efficience accru, nous avons utilisé le moteur de template Jade, ce moteur offre une nouvelle façon d'écrire un marquage, avec un certain nombre d'avantages par rapport au HTML.

### Framework Express

Nous avons utilisé le Framework Express qui apporte une couche de fonctionnalités robuste pour les applications mobiles sans masquer celles de Nodejs, l'avantage de cette infrastructure est qu'elle se veux minimaliste et flexible.

### Mongodb

Nous avons décidé d'utiliser une base de données NoSql pour la légerété, pour cela nous avons choisi Mongodb qui nous parait le plus approprié car elle fourni un format JSON qui convient parfaitement au javascript.

### Installation

A l'aide du gestionnaire de paquet npm, nous avaons généré un package.json qui permet d'installer automatiquement toute les dépendances du projet en appelant la commande :

```
npm install
```

Le package.json contient également la commande de démarrage de l'application, il suffit de se placer à la racine de l'application et d'executer la commande suivante pour demarrer l'application :

```
npm start
```



