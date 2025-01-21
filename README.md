# Principes Développemt Logiciel
Le Principes de Développement Logiciel: SOLID, DRY, KISS et plus encore

L'application de principes solides joue un rôle essentiel pour grantir la qulité, la maintenabilité et la robustesse du code. Parmi ces principes, SOLID, DRY et KISS sont particuliérement important mais d'autre princie comme YAGNI méritent également d'être appliqué pour une meilleure gestion de code.

## SOLID 
Ce sont des principes qui favorisent la conception du code robuste et évolutif.
  
  - SRP (Single Responsibility Principle): Une classe ne dévrait pas avoir qu'un seul responsabilité bien définie, pour faciliter la comprehension, la maintence et la réutilisation du code.
    
  - OCP (Open/Closed Principle): C'est à dire que le code doit ouvert à l'extesion, mais férmer à la modification. En d'autres termes, lorsqu'on doit ajouté d'autre fonctionnalité on étend le code existant plutôt que le modifier directement.
    
  - LSP (Liskov Substitution Principle): Il met en évidence l'importance de respecter les contrats lors de l'héritage des classe. Plus précisement, si nous avons une classe de base "Forme" avec sous-classes spécifiques telles que "Cercle" et "Rectangle", le principe de substitution de Liskov exige que les instances de "Cercle" et "Rectangle" puissent être utilisées partout où une instance de “Forme” est attendue, sans altérer le comportement attendu.
    
  - ISP (Interface Segregation Principle): Le principe de ségrégation des intérfaces préconise la définition d’interfaces spécifiques pour les clients. Par exemple,  dans une application de commerce électronique, nous pouvons avoir une interface distincte pour les méthodes de paiement en ligne et une autre pour les méthodes de paiement hors ligne. Ainsi, les classes qui traitent les paiements en ligne n’implémentent que les méthodes pertinentes pour les paiements en ligne, et vice versa.
    
  - DIP (Dependency Inversion Principle): Cet principe encourage l’utilisation de dépendances abstraites plutôt que de dépendre de classes concrètes. Au lieu d’une classe de haut niveau qui dépend directement d’une classe de bas niveau, nous pouvons introduire une interface abstraite entre les deux. Ainsi, la classe de haut niveau dépendra de l’interface plutôt que de la classe concrète, permettant ainsi des substitutions plus faciles.
    

## DRY (Don't Repeate Yourself)
  Favorisent l’élimination de la duplication de code inutile dans un projet de développement logiciel. Selon ce principe, chaque morceau de connaissance ou de logique devrait avoir une seule représentation canonique au sein du système. L'application de cet principe consistent l'élimination du code dupliqué, regroupement par fonctionnalité et la réutilisation du code.

## KISS (Keep It Simple, Stupid)
 Il met l’accent sur la simplicité dans la conception et l’implémentation du code. Selon ce principe, il est préférable de maintenir les solutions simples plutôt que de les rendre complexes. La simplicité favorise la compréhension, la maintenance et la résolution des problèmes.
  
Codez bien!! ❤️
