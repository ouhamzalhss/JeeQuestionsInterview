## <samp>Les Questions pour un entretien profile JAVA/JEE!</samp>

#### Partie 1: Questions divers

- 1 . JEE : C'est l’ensemble de spécifications (JPA, JAX-WS, JMS...) pour créer des applications web Java, et c'est le serveur d’application qui fournit les implémentations.

- 2 . La version courante de la specification JEE est : Jakarta EE 9 (le 25 Mai 2021)

- 3 .	Les versions LTS Java sont : Java 8, 11, 17

- 4 .	AOP : La séparation des aspects métiers et des aspects techniques d'une application est rendu possible grâce à la programmation Orienté Aspect.

- 5 .	TDD : Test Driven Développement : développer d’abord les tests.

- 6 .	Statefull et Statless : Deux approches pour sécuriser application web.
  *  Statfull : la session de l’utilisateur authentifié est gérée par le serveur (avec état)
  *  Stateless : la session de l’utilisateur authentifié est gérée par le client.

- 7 .	Les méthodes Agile comme Scrum ou l'eXtreme Programming (XP) partent du constat que le cycle de développement en cascade est un échec.
  *  Des cycles de développement itératifs,
  *  L’implication du client final tout au long du projet,
  *  Des spécifications réduites en début de projet,

- 8 .	Maven est un outil permettant d'automatiser la gestion de projets Java. Il offre les fonctionalités suivantes: 
  *   Gérer les dépendances
  *   Lancer la compilation des sources
  *   Lancer les Test Unitaires
  *   Générer les packages (jar, war, ear)
  *   Installer les packages dans le repository 
  *   Déployer l’application dans le serveur 
  *   Générer la documentation du projet	

- 9 .	Lombok : une librairie java pour la génération de code automatique. Getter et setter …

- 10 .	DevTools : une librairie java vient avec spring boot, permet le rechargement automatiquement des classes Java et leur configuration côté serveur. Après les changements côté serveur, il s'est déployé dynamiquement,

#### Partie 2: Spring framework
- 11 . Spring : est un framework open source pour construire et définir l'infrastructure d'une application Java, dont il facilite le développement et les tests.

- 12 . Spring : est un framework de l’inversion contrôle pour créer des applications entreprises, on peut le sembler avec un conteneur web (tomcat) pour avoir un serveur application.

- 13 .	CotextLoaderListener est un listener appelé par Tomcat au moment du démarrage de l’application. Ce listener cherchera le fichier de beans spring. ce qui permet de faire l’injection des dépendances.

- 14 .	DispatcherServlet : Une Servlet qui joue le rôle de front contrôleur, pour traiter les requêtes de clients.

- 15 .	Differentes Configuration de Spring container :
  *  XML (ClassPathXmlAppContext(path xml file)
  *  Annotations (ClassPathXmlAppContext(path xml file)
  *  Code source Java (AnnotationConfigAppContext(ClassConfig.class)

- 16 .	Bean scope :
  *  Singleton ( scope par défaut )
  *  Prototype
  *  Request (Application web)
  *  Session (Application web)
  *  Global-session (Application web)

- 17 .	C'est quoi Spring container: 
  *  Création et gestion des beans (IOC)
  *  Injecter ces beans pour l’utiliser (DI)

- 18 .	Les types d’injection d’un Bean Spring:
  *  Via le constructeur (recommandé)
  *  Sous forme attribut avec l’annotation @Autoward

- 19 .	C’est quoi la differnec entre :
  *  @Param : Un parametre Spring Data
  *  @RequestParam : Un parametre Spring MVC, sous la forme ( url?variable=valeur ).
  *  @PathVariable : Un parametre Spring MVC, sous la forme ( url/varibale ).
  *  @PathParam : Un parametre Jersey
  *  @WebParam : Un parametre JAX-WS

- 20 .	Nouveautés de Spring 5 : Vient avec des fonctionnalités suivantes:
  *  Support de java 8 / 9
  *  Support de Hibernate 5 et Junit 5
  *  Support JPA 2
  *  Programmation fonctionnelle
  *  Support de kotlen
  *  Supprt de Http2

- 21 .	Spring boot : un module spring, ou une super couche de spring pour créer des applications spring avec zéro configuration.

- 22 .	Avantages spring boot :
  *  Auto configuration
  *  Serveur web intégré (Tomcat)
  *  Gestion de dépendances ( starters )
  *  Création des applications standalone (jar)

- 23 .	@SpringBootApplication : C'est une annotation de spring boot qui combine trois autres annotations:
  *  @Configuration: pour marquer une classe comme une classe de configuration,
  *  @EnableAutoConfiguration: pour activer la configuration automatique de spring boot.
  *  @ComponentScan: pour scanner les différentes classes constituant les Beans de notre application.

- 24 . Actuator: Une dépendance spring boot pour faire le monitoring de votre application en production.

- 25 . C'est quoi la différence entre @Controller et @RestController: Les deux servent à marquer une classe comme contrôleur, la différence est le type de retour, les méthodes de @Controller renvoient une vue HTML ou JSP, Tandis que celles de @RestController renvoient les données aux formats JSON, XML... ( @RestController = @Controller + @ResponseBody)

## <samp>La video youtube : https://youtu.be/QEE5W-6wBjE </samp>
