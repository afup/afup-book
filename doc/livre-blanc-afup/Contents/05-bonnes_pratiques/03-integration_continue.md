L'intégration continue
========================================

Ces tests unitaires ne sont qu'un des aspects des bonnes pratiques qui peuvent être mises en place au sein d'une équipe de développement. Une autre bonne pratique consiste à centraliser les informations disponibles sur le suivi d'un projet au sein d'une seule et unique interface. 

Cette interface, qui offre un suivi de la couverture de code par les tests unitaires, mais aussi qui centralise les erreurs, les anomalies techniques, les avancées de code... consiste en ce qu'on appelle une Plate-forme d'Intégration Continue.

Enjeux financiers
-----------------

Mettre en place une plate-forme d'intégration continue (ou PIC) a un coût non négligeable à prendre en compte dans un projet professionnel aujourd'hui. Le premier coût consiste à son installation par un expert qualifié, sur un serveur généralement dédié à son bon fonctionnement. 

A cela s'ajoute le temps de formation des équipes qui ne sont pas forcément habituées à travailler autour d'une Intégration continue de leur code.

Par ailleurs, il faut prendre en compte le temps d'exploitation de ces informations d'Intégration Continue : une personne doit prendre le temps de les consulter, et de les interpréter, afin de réorienter l'équipe en fonction des indicateurs de suivi du projet. Toutefois, ce coût reste très modeste.

Cependant, ces investissements sont généralement rapidement rentabilisés, surtout auprès d'une équipe compétente ou à forte capacité d'apprentissage. En effet, le gain de qualité obtenu permet :

  * d'**alléger les coûts de maintenance** : toute « cassure » dans le projet est immédiatement identifiée
  * de **faciliter l'intégration de nouveaux éléments dans l'équipe** et de limiter les risques
  * d'avoir un **suivi régulier d'un projet** (on évite d'avoir un projet pour lequel tous les indicateurs passent au rouge quelques semaines avant la date de livraison)
  * de forcer l’uniformisation et le **respect de normes de développement** au sein d'une équipe, facilitant ainsi la reprise du projet par des tiers.
  * D'**éviter à un projet de régresser fonctionnellement** suite à des changements ou des évolutions (techniques ou fonctionnelles)

Enfin, l'intégration continue permet aux entreprises adeptes du « **Lean Startup** » d'avoir un développement cohérent avec leurs enjeux financiers. Un développement « **Agile** » permet de livrer des lots fonctionnels très régulièrement et rapidement, et laisse le client réorienter son projet tout au long de son développement sans mettre en péril ni son coût ni ses délais. 

Cela n'est possible justement que grâce à l'aspect qualitatif et aux indicateurs de suivi du projet : si changer une fonctionnalité « casse » le projet, le problème est immédiatement identifié et facilement corrigé. Pour synthétiser, disons que **l'intégration continue contribue à mieux gérer le fameux triangle Coût / Délai / Fonctionnalités**.

Outils et solutions
-------------------

L'intégration continue consiste donc à utiliser des outils de suivi de qualité, afin de permettre d'avoir un suivi global de l'avancée d'un projet.

Ces outils de suivi peuvent être :

  * des tests unitaires pour tester la fiabilité d'un code (phpUnit, Simpletest, Atoum...)
  * des tests d'intégration pour tester l'interface des écrans d'une application / d'un site (Selenium, Zend_Test...)
  * des tests fonctionnels pour vérifier le comportement de l'application (Zend_Test, Behat...)
  * un monitoring du respect des normes de développement (phpCodeSniffer)
  * un monitoring du respect de la qualité et de la pertinence du code (phpUnit, Cornac...)
  * et bien d'autres que nous vous invitons à découvrir.


Ces outils sont pour la plupart gratuits (ou peu onéreux) et ne nécessitent que peu de formation pour réussir à les utiliser convenablement. 

Il n'en va pas de même, comme nous l'avons vu, avec les plate-formes de centralisations de suivi de ces outils (ce que nous avons appelé Plate-forme d'Intégration Continue), qui nécessitent des compétences pointues et une expertise forte pour les installer.  
Cependant, une fois installées et configurées, le coût en maintenance est généralement très bas, voire nul, étant donnée la stabilité et la qualité des solutions logicielles proposées.

Parmi ces solutions logicielles, nous pouvons penser à :

  * PhpUnderControl, gratuit, aujourd'hui fiable et reconnu mais lourd et coûteux à mettre en place
  * Jenkins, gratuit, lui aussi fiable mais sans doute moins coûteux à installer

Il en existe d'autres, aussi il peut être pertinent pour vos projet de vous faire conseiller par des sociétés spécialisées dans la mise en place de solutions d'Intégration Continue.  
Toutefois, si parmi vos équipes il en est qui ont des compétences en administration système Unix, la prise en main de ces outils peut être relativement rapide, ce qui réduira donc vos frais de mise en place.

Toutefois, rappelons-le, ces frais de mise en place seront généralement largement rentabilisés par l'assurance qualité fournies par ces pratiques d'Intégration Continue.
