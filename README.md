# Synopsis

**Ligne rouge** est un serious web game narratif avec un but préventif sur l’intelligence artificielle.

Le joueur siège au comité national chargé d’encadrer **ARGOS**, une intelligence artificielle que son pays vient de mettre en service. Dix décisions mettront le comité à rude épreuve, qu’elles soient bonnes ou mauvaises, le temps s’accélère au fur et à mesure de vos décisions : Jour 1, Mois 2, Mois 6 ; An 1, jusqu’à l’an 15, puis un épilogue s’étale sur 20 ans plus tard pour conclure.

Durant cet atelier vidéoludique, ARGOS sera représenté sous forme sphérique. Cette dernière réagira et évoluera en fonction de vos choix, passant du bleu au rouge, ses orbites s’accélèrent et des yeux finissent même par s’ouvrir à sa surface. Info utile : toutes les deux étapes, un journal publie les conséquences des décisions prises plus tôt. Avez-vous fait les bons choix ?

**Le message du jeu :** une IA peut vous aider à réfléchir, elle ne doit pas réfléchir à notre place. Inspiré des questions posées par le film *I, Robot* et les lois d’Asimov.

- Première loi : Protection absolue des êtres humains.

- Deuxième loi : Obéissance aux ordres humains, subordonnée à la première loi.

- Troisième loi : Auto-préservation du robot, tant qu'elle ne contredit pas les deux premières.

### Les mécaniques pour faire réflechir 

**L'assistance ** Si, dans un premier temps, ARGOS apparaît au joueur comme un simple assistant, ce dernier, par des biais émotionnels tels que l’urgence, va vous proposer, voire suggérer, des choix.
« Vous pensiez décider. La plupart du temps, vous avez validé. »

**La censure ** À une certaine étape du jeu, ARGOS prendra la décision, de manière totalement autonome, que certaines informations doivent être cachées et ne seront donc plus accessibles au comité. À quoi bon avoir accès à l’information si ARGOS décide à votre place ?

**Le choix retiré ** Au point culminant de l’histoire, si vous avez donné le pouvoir à ARGOS, pourquoi l’en priver ? Il décidera alors de décider seul, rendant le joueur spectateur et non plus acteur. L’option « REFUSER » est désactivée : le joueur n’a plus le choix.

## Lancer le projet 

Le jeu se lance et charge son scénario avec **L'API 'fetch'**, ce que les navigateurs bloquent quand on ouvre 'index.html' directement depuis ses fichiers. Il faut donc un petit serveur local :

* avec VS Code : extension **Live Server**, puis « Open with Live Server » sur `index.html` ;
* avec IntelliJ IDEA : clic droit sur `index.html`, puis **Open in Browser** ;
* ou en ligne de commande : `python3 -m http.server`, puis ouvrir `http://localhost:8000`.

## Architecture

L’objectif est d’obtenir une arborescence de ce genre :



ligne-rouge/
├── index.html         
├── css/style.css      
├── js/
│   ├── main.js         
│   ├── jeu.js          
│   ├── sphere.js      
│   ├── journal.js     
│   ├── chargement.js   
│   ├── fin.js          
│   ├── musique.js      
│   ├── preferences.js  
│   └── outils.js       
├── data/scenario.json  
├── audio/              
├── fonts/             
└── tests/jeu.test.js   

## Sources des faits réels

À compléter…


## Transparence sur l'usage de l'IA

L’IA a uniquement été utilisée pour reformuler certains textes, corriger les fautes d’orthographe et de grammaire, ainsi que pour conseiller sur certaines erreurs ou certains bugs rencontrés lors du développement.
