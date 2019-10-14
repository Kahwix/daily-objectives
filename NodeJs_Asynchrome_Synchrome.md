NODE JS
• Comprendre ce qu'est Node.jsNodejs est environnement d’execution JavaScript côté serveur, contrairement à ce qu'on a l'habitude de voir avec le javascript côté client.
Node.js n'est pas un framework.
Node.js est un environnement
L'avantage d'utiliser Nodejs est que javascript permet l'exécution de tâches  EN TEMPS REEL (RTA real time application)
asynchrones (ce qui veut dire qui n’attends pas que la tâche soit terminée et commence déjà à travailler une autre) ce qui peut être pratique dans certaines situations.
C’est de plus en plus souvent necessaire avec le web moderne (html5/css3/ javascript)Nodejs permet de créer des applications « serveur » facilement grâce à des applications tierces qu'il prend en charge via un logiciel similaire à un gestionnaire de paquets (NPM).
Il se distingue des autres plateformes gràce à une approche non bloquante  (synchrome) permettant d'effectuer des entrées/sorties (I/O) de manière asynchrone.
Par exemple: Un serveur de Chat , Un système d'upload très rapide...
et de façon générale n'importe quelle application qui doit répondre à de nombreuses requêtes rapidement et efficacement, en temps réelIl transforme le code JavaScript très rapidement en code machine et l'optimise même grâce à des procédés complexes
Retenez juste qu'il permet de rendre l'exécution de code JavaScript ultrarapide
• Préparation de l'environnement de développement backend (installations, mises à jour)
- pour installer: les paquets nodejs npm. sudo apt-get update sudo apt-get install nodejs npm
- mises à jour:
• Comprendre la différence entre le développement synchrone et asynchrone
asynchrome
le code/programme n’attend pas et commence déjà à passer à une autre tâche(ou requetes)exemple:
Le programme n'exécute plus les lignes dans l'ordre où elles sont écrites. Il fait ceci :
  1. Le programme lance le téléchargement d'un fichier sur Internet
  2. Le programme fait d'autres choses (le programme suit son cours)
  3. Dès que le téléchargement est terminé, le programme effectue les actions qu'on lui avait demandées : il affiche le fichiersynchrome:
l’inverse donc (execution de taches étapes par étapes)Les actions sont effectuées dans l'ordre. Il faut lire les lignes de haut en bas :
  1. Le programme va télécharger un fichier sur Internet
  2. Le programme affiche le fichier à l'utilisateur
  3. Puis ensuite le programme peut faire d'autres choses (effectuer d'autres actions)