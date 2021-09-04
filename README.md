## <samp>Les Questions pour un entretien profile JAVA/JEE!</samp>

#### Partie 1: Questions divers

- 1 . JEE : C'est l’ensemble de spécifications (JPA, JAX-WS, JMS...) pour créer des applications web Java, et c'est le serveur d’application qui fournit les implémentations.
- 2 . La version courante de la specification JEE est : Jakarta EE 9 (le 25 Mai 2021)
- 3 .	Les versions LTS java sont : Java 8, 11, 17
- 4 .	AOP : La séparation des aspects métiers et des aspects techniques d'une application est rendu possible grâce à la programmation Orienté Aspect.
- 5 .	TDD : Test Driver Développement : développer d’abord les tests.
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
- 10 .	Nouveautés de Spring 5 : Vient avec des fonctionnalités suivantes:
  *  Support de java 8 / 9
  *  Support de Hibernate 5 et Junit5
  *  Support JPA 2
  *  Programmation fonctionnelle
  *  Support de kotlen
  *  Supprt Http2
#### Partie 1: Spring core
- 10 .	CotextLoaderListener est appelé par Tomcat au moment du démarrage de l’application. Ce listener cherchera le fichier de beans spring « spring-beans.xml » stocké dans le dossier WEB-INF. ce qui permet de faire l’injection des dépendances.
- 11 .	Configuration  Spring container :
  *  XML (ClassPathXmlAppContext(path xml file)
  *  Annotations (ClassPathXmlAppContext(path xml file)
  *  Code source Java (AnnotationConfigAppContext(ClassConfig.class)
- 12 .	Bean scope :
  *  Singleton
  *  Prototype
  *  Request (application web)
  *  Session (application web)


