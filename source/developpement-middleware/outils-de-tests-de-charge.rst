Outils de tests de charge
=========================

Les outils de tests de charge, comme leur nom l’indique, sont des applications permettant de simuler une forte charge sur un service.

Cela peut être un site Web mais également une base de données, un annuaire LDAP, un webservice, etc. Les possibilités sont très nombreuses.

Une interface graphique est généralement disponible pour permettre la saisie des scénarios de tests : passage par telle page, clic sur tel menu, remplissage de tel formulaire, soumission, etc. Les scénarios en eux-mêmes peuvent être d'une grande complexité, avec des boucles, conditions, extraction et réutilisation de variables, chargement de variables depuis un fichier externe, etc.

En sortie des tests de charge, les applications proposent généralement de nombreux de graphes et statistiques exportables sous la forme de rapports.

Locust
------

:Site: https://locust.io/
:Porteur: une communauté
:Licence: MIT

Locust est un outil de test de performance facile à utiliser, scriptable et évolutif. Vous définissez le comportement de vos utilisateurs dans un code Python ordinaire, au lieu d'utiliser une interface utilisateur maladroite ou un langage spécifique à un domaine. Cela rend Locust infiniment extensible et très convivial pour les développeurs.


JMeter
------

:Site: http://jakarta.apache.org/jmeter
:Porteur: une fondation (Apache)

Jmeter est un outil d'injection de trafic édité par la fondation Apache.

Il est utilisé pour réaliser des tests de charge sur plusieurs types de serveurs : Web, LDAP, Bases de données, etc. Il dispose d'une interface graphique qui rend la création de scénarios d'utilisation plus facile. Les scénarios en eux-mêmes peuvent être d'une grande complexité, avec des boucles, conditions, extraction et réutilisation de variables, chargement de variables depuis un fichier externe, et de nombreux types de graphes et de statistiques.

JMeter est distribué sous licence Apache.

Son développement a commencé en 2001, il est réalisé en Java.


Tsung
-----

:Site: http://tsung.erlang-projects.org
:Porteur: une communauté
:Licence: GPL

Tsung est un outil d'injection de trafic, utilisé pour les tests de charge de différents types de serveurs.

Il supporte HTTP et quelques dérivés (SOAP, WebDAV), les bases MySQL et PostgreSQL, ainsi que XMPP. Réalisé en Erlang, un langage spécialisé dans les applications hautes performances, il ne souffre pas des limites traditionnelles de ce type d'outils, et peut donc simuler un trafic très important. Il dispose d'un générateur automatique de statistiques.

Initialement crée par la société française Idealx, il est désormais développé par une communauté indépendante.


FunkLoad
--------

:Site: https://github.com/nuxeo/FunkLoad
:Porteur: une société (Nuxeo)
:Licence: GPL

Funkload est un outil de tests fonctionnels et de charge pour applications et services web développé par la société française Nuxeo, pour ses besoins propres. Il a été utilisé entre autres par Google et Mozilla.

Funkload est développé en Python.
