# [Symfony Live - Paris 2020](http://paris2019.live.symfony.com/) talks

- All talks are in **french**.
- You can send feedback and love to speakers on their twitter account

## Keynote

~~Slides~~  
~~Video~~

By [Fabien Potencier](https://connect.symfony.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)

---

## Le cache, ça paie !

<dl>
  <dt>Description</dt>
  <dd>Parce que vos serveurs méritent toute votre attention, il faut penser à leur santé. Et rien de mieux que du cache pour les soulager de tâches répétitives.

Que ce soit du cache HTTP, l'utilisation d'un CDN ou encore côté applicatif avec le composant Cache, les solutions ne manquent pas.

Ce retour d'expérience sur un projet à destination de plusieurs centaines de milliers d'utilisateurs abordera les différentes solutions adoptées pour supporter la charge malgré les différentes contraintes techniques.</dd>
</dl>

[Slides](https://docs.google.com/presentation/d/e/2PACX-1vQNHzDQruZ1L5x5jbv7XIGKtrnObJucqCraY-leYi1elv4-BUN2VohC6Lyy4ja9AbKQPihtRqnFkBtO/pub)  
~~Video~~

By [Hubert Lenoir](https://connect.symfony.com/profile/hubert_lenoir)  
![github](icon/github.png) [@Jean-Beru](https://github.com/Jean-Beru)  
![twitter](icon/twitter.png) [@jean_beru](https://twitter.com/jean_beru)

---

## Lock et Semaphore : les gardiens de vos ressources

<dl>
  <dt>Description</dt>
  <dd>Arrivé avec Symfony 3.4, le composant Lock permet de limiter les accès concurrents aux ressources partagées. 3 ans plus tard, son petit frère, le composant Semaphore, arrive avec Symfony 5.2 et vient ainsi compléter le panel d'outil à notre disposition.

Bien au delà du classic `flock()` ou `sem_acquire()`, ces composants permettent de couvrir des usages plus complèxes tels que le maintient d'un verrou sur plusieurs pages ou l'intégration dans une infrastructure distribuée et de haute disponibilité.

Je vous propose, au travers d'exemples métier, d'étudier le fonctionnement de ces deux composants.
Nous verrons l'étendue des possibilités qu'ils nous offrent ainsi que leurs limites.</dd>
</dl>

[Slides](https://slides.com/jderusse/lock-semaphore)  
~~Video~~

By [Jérémy Derussé](https://connect.symfony.com/profile/jderusse)  
![github](icon/github.png) [@jderusse](https://github.com/jderusse)  
![twitter](icon/twitter.png) [@jderusse](https://twitter.com/jderusse)

---

## Migrer vers une architecture micro-services : points de contrôle pour une migration réussie

<dl>
  <dt>Description</dt>
  <dd>J'ai passé ces dernières années dans différentes sociétés, qui toutes essaient d'accomplir la même chose : migrer vers une architecture orientée micro-services. Cette migration dans laquelle elles se sont toutes engagées ont beaucoup de similitudes, mais aussi de grosses différences. Comme tout long voyage, une seule chose est sûre : vous savez quand vous commencez, mais vous ne savez jamais vraiment ce qu'il se passera vraiment, ni ce que vous trouverez sur votre chemin ! Pour réussir votre voyage, il est important de savoir où vous allez, les différents choix qui s'offrent à vous et les bons éléments pour prendre les bonnes décisions.
Cette conférence répondra aux questions essentielles que sont : comment séparer son code, comment gérer les tests multi-applications, comment analyser un bug, comment gérer les appels d'APIs, comment s'intégrer avec les tiers, et toutes les autres questions que vous devez vous poser si vous avez décidé de migrer.</dd>
</dl>

[Slides](https://speakerdeck.com/alexandresalome/migrer-vers-une-architecture-micro-services-points-de-controle-pour-une-migration-reussie)  
~~Video~~

By [Alexandre Salomé](https://connect.symfony.com/profile/alexandresalome)  
![github](icon/github.png) [@alexandresalome](https://github.com/alexandresalome)  
![twitter](icon/twitter.png) [@alexandresalome](https://twitter.com/alexandresalome)

---

## La compilation JIT, le fil rouge vers PHP 8

<dl>
  <dt>Description</dt>
  <dd>Avec l'arrivée de PHP 8, la compilation "Just-In-Time" fait parler d'elle. Depuis les années 80, tous les langages interprétés cherchent à atteindre ce graal supposé de performance. Lors de cette conférence, je vous propose de remonter le temps jusqu'à PHP 5.5, le temps d'un rappel sur "opcache", disponible nativement depuis lors. Nous analyserons ensuite chaque progrès de performance, version après version. À travers des exemples de code repris depuis Symfony, nous verrons que toutes les améliorations désormais acquises (opcache, boost PHP7, preloading, etc.) sous-tendent un même fil rouge : permettre un jour la compilation JIT. PHP 8 nous permet enfin de toucher au but. Le voyage en valait-il la peine ? C'est ce que nous essayerons d'établir.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Valentine Boineau](https://connect.symfony.com/profile/valentineboineau)  
![github](icon/github.png) [@ValentineBoineau](https://github.com/ValentineBoineau)  
![twitter](icon/twitter.png) [@BoineauV](https://twitter.com/BoineauV)

---

## Monolithe Modulaire : Pourquoi ? Comment ?

<dl>
  <dt>Description</dt>
  <dd>La mode des microservices est retombée. On peut enfin prendre du recul et se demander si vraiment c'est une solution adaptée à toutes les situations... (spoiler alert: non).
Alors comment structurer des applications qui grossissent au fur et à mesure ?
Comment sortir la tête de l'eau quand on a un legacy de 10 ans et qu'on souhaite en reprendre le contrôle ?
La solution pour moi c'est le monolithe ! Mais modulaire...
Et ça tombe bien car Symfony aujourd'hui peut grandement nous y aider !
En 2 temps nous verrons :
Comment bien organiser son code à l'intérieur d'une app Symfony pour le rendre aussi indépendant que possible et se donner la possibilité d'y mettre l'architecture qu'on souhaite (DDD, Crud, Hexagonal, whatever).
Et comment s'y prendre quand on a déjà un monolithe mais pas modulaire pour en reprendre le contrôle. On parlera alors de différentes stratégies concrètes pour s'en sortir sans tout révolutionner du jour au lendemain.</dd>
</dl>

[Slides](https://slides.com/tyx/sflive2020-bb8c28)  
~~Video~~  

By [Timothée Barray](https://connect.symfony.com/profile/tyx)  
![github](icon/github.png) [@tyx](https://github.com/tyx)  
![twitter](icon/twitter.png) [@timbarray](https://twitter.com/timbarray)

---

## Redis, ce n'est pas que pour le cache

<dl>
  <dt>Description</dt>
  <dd>Redis sait faire bien plus que du stockage clé/valeur simple.
Grâce à des structures de données évoluées et a ses performances hors du commun,
il devient un allié très puissant à ajouter dans sa stack préféré.

Des statistiques à la persistance de session en passant par les leaders board ou
la gestion de coordonnées, vous ne verrez plus ce SGBD du même oeil !

A travers une série d'exemples, des trucs & astuces, nous verrons comment
utiliser Redis depuis une application PHP.</dd>
</dl>

[Slides](https://speakerdeck.com/lyrixx/redis-ce-nest-pas-que-pour-le-cache-v2-41bf480e-c296-4540-8b02-462431acc595)  
~~Video~~


By [Grégoire Pineau](https://connect.symfony.com/profile/lyrixx)  
![github](icon/github.png) [@lyrixx](https://github.com/lyrixx)  
![twitter](icon/twitter.png) [@lyrixx](https://twitter.com/lyrixx)

---

## Mettre la cryptographie au service de vos apps Symfony

<dl>
  <dt>Description</dt>
  <dd>Hacher les mots de passe, chiffrer les clefs applicatives, voire chiffrer les données elles-mêmes.
Les dernières versions de Symfony mettent tous les outils nécessaires à disposition pour protéger vos utilisateurs contre les fuites ou autres vols de données.

SHA512, Argon2id, BLAKE2/3, ChaCha20-Poly1305, etc. derrière ces noms barbares se cachent des algorithmes qui fondent les nouveaux standards de protection de la vie privée.
Depuis PHP 7.2, l'extension "sodium" donne accès sans difficulté à toute l'intelligence des spécialistes en cryptographie.
Son API volontairement simplifiée est un trésor pour le reste du monde. Tout y est.

Lors de cette conférence, je vous propose de démystifier ces outils et l'utilisation qui en est faite dans Symfony.</dd>
</dl>

~~Slides~~   
~~Video~~

By [Nicolas Grekas](https://connect.symfony.com/profile/nicolas-grekas)  
![github](icon/github.png) [@nicolas-grekas](https://github.com/nicolas-grekas)  
![twitter](icon/twitter.png) [@nicolasgrekas](https://twitter.com/nicolasgrekas)

---

## API: Spécifications, Sécurité et Monitoring

<dl>
  <dt>Description</dt>
  <dd>Les API (Application Programming Interfaces) sont au coeur des systèmes d'information et sont devenues un moteur important de croissance des entreprises (monétiser les données, forger des partenariats rentables, ouvrir de nouvelles voies d'innovation et de croissance).
Il est donc important de comprendre les fondamentaux pour mieux exploiter leurs potentiels.
Comment concevoir une API en suivant les spécifications ?
Comment sécuriser les accès aux APIs ?
Comment mesurer les métriques et gérer les alertes ?
Au cours de cette conférence nous présenterons les différentes solutions et leurs implémentations en Symfony, en analysant les principales étapes du cycle de vie d'une API: conception, documentation, sécurité, logs et monitoring.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Danielle KAYUMBI BONKOTO](https://connect.symfony.com/profile/hoddan)  
![github](icon/github.png) [@dkwavetech](https://github.com/dkwavetech)  
![twitter](icon/twitter.png) [@danielleKayumbi](https://twitter.com/danielleKayumbi)

---

## Stream processing: un autre type d’architecture

<dl>
  <dt>Description</dt>
  <dd>Votre produit grossi, vous avez plusieurs (micro-)services et/ou partagez des données avec des partenaires. Plutôt que d’échanger des fichiers CSV ou d’utiliser uniquement des APIs, il existe une autre option : utiliser un "message bus" et faire du “stream processing”.

Après avoir décrit l’intérêt d’une telle architecture, nous discuterons de ses conséquences telles que le besoin d’idempotence dans nos “handlers” Symfony Messenger, comment garder une “strong consistency” et comment fonctionnent les bus qui garantissent l’ordre des messages.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Samuel Roze](https://connect.symfony.com/profile/sroze)  
![github](icon/github.png) [@sroze](https://github.com/sroze)  
![twitter](icon/twitter.png) [@samuelroze](https://twitter.com/samuelroze)

---

## Retour d'expérience sur l'optimisation de performance de la stack Symfony

<dl>
  <dt>Description</dt>
  <dd>Sur un projet Symfony avec une stack assez commune (API avec APIP, beaucoup d'entités doctrine, plein de fichiers de config YAML, environnement de développement sur docker), le projet grossissant, nous avons commencé à subir des ralentissements, aussi bien en environnement de développement qu'en production.

Souhaitant proposer une meilleure expérience de développement à mes équipes, équipé d'une superbe frontale (coucou Blackfire), j'ai étudié en profondeur le fonctionnement interne de Symfony à la recherche d'améliorations possibles. Cela a débouché sur de nombreuses pull-requests et un impact conséquent sur les performances.

Cette présentation retracera ce parcours initiatique dans le fonctionnement interne de Symfony, l'outillage utilisé et les leçons apprises. Elle sera à la fois pratique (quoi / comment / pourquoi chercher) mais aussi théorique (fonctionnement interne de Symfony sur quelques chemins critiques).</dd>
</dl>

~~Slides~~  
~~Video~~

By [Bastien Jaillot](https://connect.symfony.com/profile/bastnic)  
![github](icon/github.png) [@bastnic](https://github.com/bastnic)  
![twitter](icon/twitter.png) [@bastnic](https://twitter.com/bastnic)

---

## Le frontend pragmatique pour les développeurs backend

<dl>
  <dt>Description</dt>
  <dd>Le développement front-end devient de plus en plus vaste est complexe. Cela crée de nombreuses nouvelles opportunités... mais cela peut aussi être assez impressionant !

L'objectif de cette conférence est de vous fournir des idées et des conseils pragmatiques sur les différentes techniques pour mettre en place un environnement de développement frontend riche et moderne avec Symfony, React, Bootstrap et Twig.

Nous aborderons les différentes options pour organiser votre code et le transfert des données entre votre frontend et votre backend et nous évoquerons les différents avantages et inconvénients de chacune.

Fabriquons des interfaces de qualité pour nos utilisateurs !</dd>
</dl>

~~Slides~~  
~~Video~~

By [Titouan Galopin](https://connect.symfony.com/profile/tgalopin)  
![github](icon/github.png) [@tgalopin](https://github.com/tgalopin)  
![twitter](icon/twitter.png) [@titouangalopin](https://twitter.com/titouangalopin)

---

## WebAuthn – Technologie et intégration dans un projet Symfony

<dl>
  <dt>Description</dt>
  <dd>Nous vivons dans un monde où chacun utilise chaque jour différents mots de passe afin de s’identifier auprès des services qu’il utilise.
Ce sont donc naturellement ces mots de passe qui font actuellement l’objet de près de 80% des attaques informatiques.
Pourtant des solutions existent déjà pour solutionner ce problème : Le projet FIDO2 et le nouveau standard WebAuthn permettent désormais de s’authentifier en toute sécurité auprès d’un service web et, ce, sans recourir à un facteur mémoriel tel qu’un mot de passe.
Cette session vous présentera ce que propose ce standard, comment il fonctionne et comment l’implémenter sur vos projets Symfony notamment via l’API JS et certains bundles Symfony.
Je vous ferai part de mon retour d’expérience sur ces implémentations et nous verrons comment ce standard est aujourd’hui implémenté dans le monde web.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Stefan Richter](https://connect.symfony.com/profile/brokoskokoli)  
![github](icon/github.png) [@brokoskokoli](https://github.com/brokoskokoli)  
![twitter](icon/twitter.png) [@stean1990](https://twitter.com/stean1990)

---

## HYPErmedia : tirer parti d'HTTP/2 pour créer des API mieux conçues, et plus rapides

<dl>
  <dt>Description</dt>
  <dd>Au fil des ans, de nombreux formats d'API ont été créés pour améliorer les performances des API Web (n+1, sur-extraction, sous-extraction)… La solution en vogue se nomme GraphQL. Il s'agit d'un hack réseau très malin, mais que HTTP/2 et HTTP/3 rendent un peu désuet !

Ces nouvelles versions du protocole disposent désormais de fonctionnalités natives permettant de créer des API rapides et idiomatiques : multiplexage, Server Push, déduplication des en-têtes, compression, connexions persistentes (cf. Mercure)… Utiliser les capacités d'HTTP/2 et HTTP/3 permet de révéler la vraie puissance de l'architecture du Web (l'hypermédia), sans compromis niveau performances.

Le framework API Platform supporte désormais le protocole Vulcain qui permet de mettre en place des APIs de ce type. Au cours de cette présentation, nous découvrirons cette nouvelle façon d'architecturer les APIs, et verrons comment les implémenter et les consommer grâce à API Platform et Symfony.

HATEOAS is the new hype!</dd>
</dl>

~~Slides~~  
~~Video~~

By [Kévin Dunglas](https://connect.symfony.com/profile/dunglas)  
![github](icon/github.png) [@dunglas](https://github.com/dunglas)  
![twitter](icon/twitter.png) [@dunglas](https://twitter.com/dunglas)
