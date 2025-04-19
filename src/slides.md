# Devoxx FR 2025

## La conf en elle-même

Paris, 3 jours (16-18 Avril)

13ème éditions

thèmatiques :
* ~~Java~~ (historique)
* Data
* ~~IA~~
* Front-end
* Ops
* Sécu
* Test
* Archi
* Alien

beaucouuuup de monde (4500 sur 3 jours ?)

prévoir de bonnes chaussures

cher : 860€ tarif personnel, 1100+€ tarif professionnel

des stands d'exposants

résumé des confs, dans le désordre, mais par thématique

de la musique et de vidéos IA qui me donnent la gerbe tout le temps TODO emoji vomi

pas de Python (cf mon post LinkedIn)

ne pas aimer le soleil

## Quelques stats

~280 sessions

par track :
- Architecture = 15
- Data = 49
- Deployment = 35
- Dev = 51
- Front-End = 28
- Java & Languages = 18 (dont 1 Go, 1 Kotlin, 1 Scala, 1 Node.js)
- Mind the geek = 19
- People and culture = 38
- Security = 21
- Server side = 7 (dont 5 Java)

> Devoxx France est la plus grande conférence indépendante autour du développement et de la programmation, en Europe.
> [...]
> Devoxx France est l’occasion de faire des rencontres, de venir découvrir les dernières technologies et de participer à un grand moment communautaire.
- https://www.devoxx.fr/

> Quels sont les sujets traités ?
> Les thèmes sont présentés sur la section Programme de notre site.
> Vous pouvez par ailleurs vous faire une idée du contenu en consultant notre chaîne Devoxx France sur YouTube.
> Devoxx France est d’abord une conférence pour les développeurs(.ses) passionné(e)s.
- https://www.devoxx.fr/questions-frequentes/

# Keynotes

## Mercredi 09h00 - l'IA n'existe pas

Luc Julia, ingénieur derrière Siri

un retour aux sources, un parti pris que l'IA ne nous remplacera pas

## Jeudi 09h00 - Langage, IA et propagande : la guerre des récits a déjà commencé

Elodie Mielczareck, semiologue

rien compris !! pire keynote

un ton assez monocorde, des phrases trop longues, beaucoup de termes droppés sans être expliqués, ...

théorie des 4 niveaux d'un philosophe

ce n'est pas comme la matrice car "illusion n'est pas simulation", ok mais ensuite ?

un mauvais souvenir

## Jeudi 09h35 - La territorialisation des infrastructures comme levier de pouvoir

Ophélie Coelho, en thèse sur le sujet

focus sur l'Afrique, notemment australe

comment les logiciels, les accès de données, la localisation des datacenters, et l'itinéraire des cables a des impacts (géo)politiques et territoriaux

très clair dans sa première partie, elle a manqué de temps et je trouve que la fin manquait d'illustration, j'aurais aimé en savoir +

## Vendredi 09h00 - Plongez dans l'ère quantique : décryptez et anticipez la révolution à venir

Fanny Bouton

présentation des enjeux du quantique, surtout à base d'exemples pour le luxe et de métaphores avec la Formule 1, j'ai pas beaucoup accroché

et ça présentait largement les opportunités de carrière à rejoindre l'industrie quantique, mais pas tant les impacts du quantique sur notre travail de dev (algo de chiffrement, puces pour traitement particulier)

j'ai l'impression qu'elle était largement là pour vendre sa sauce (OCH cloud)

mais un rappel important sur la souveraineté et notre expertise française sur le sujet

## Vendredi 09h35 - les LLM rêvent-ils de cavaliers électriques ?

Monsieur Phi

Même s'il est moins bon en live qu'en vidéo, ça reste intéressant de voir du Monsieur Phi

C'était une version remise-à-jour de sa vidéo d'il y a un "ChatGPT m'a vaincu aux échecs", pour dire que les LLMs peuvent se construire un world model, et ne sont donc pas seulement des perroquets stochastiques, et que de le vivre nous force à nous remettre en question

Il est meilleur en vidéo qu'en live : il était stressé, il y a eu des soucis techniques au début, il a mal géré son temps et donc rushé la fin, ...

# Data

## Mercredi 10h30 - Iceberg : pourquoi devez-vous connaître ce nouveau format de stockage de données ?

Bertrand Paquet

très intéressantes les nouvelles fonctionnalités offertes par ce nouveau format, en terme de perf sur des données mutables et historisées

JULIEN : à revoir à Kaizen ?

## Jeudi 11h35 - Apache Kafka en 2025, vers l'infini et l'au-delà

Daniel Petisme et Frédérik Rouleau

intéressant de voir les évolutions à la fois de Kafka, et du marché (distributions spécialisées) 

# Ops

## Mercredi 11h35 - L'observabilité pour les devs : outils-clé pour survivre quand la prod plantera

Alexandre Moray et Florian Meuleman

un rappel sur les bases de l'observabilité (logs, traces, métriques)

moins bien je trouve que la conférence de Mathieu ROger (TODO lui demander de la redonner ?)

présentait SigNoz comme APM, et la suite OTel

expliquait le rôle des collecteurs intermédiaires d'OTel (indirection pour switch d'APM, authentification centralisée, traitement/filtres intermédiaires)

## Mercredi 15h40 - Kubernetes en 2025

Alain Regnier

un tour d'horizon des différentes nouvelles features

## Mercredi 17h50 - Rebase d'image Docker/OCI avec crane

Julien Wittouck

l'outil est intéressant, mais la présentation extrêmement redondante

## Vendredi 11h35 - Platform Engineering : DevOps est maintenant majeur

Alexis Morelle, Henri Gomez

présentation historique et panorame des pratiques DevOps et Platform Engineering

intéressant pour la culture générale, mais un peu générique

JULIEN : revoir à Kaizen

# Test

## Mercredi 12h35 - Maîtriser les tests de code asynchrone

Yifang Dong

un naufrage : le code était illisible, l'exemple pas clair

j'ai appliqué la loi des 2 pieds (pas officielle au Devoxx)

## Jeudi 13h00 - TDD et IA

Benoit Prioux

démonstration en live coding de la génération de test à partir de l'implèm : fais des hypothèses, et ne cherche pas à mettre en défaut (test de caractérisation)

au contraire, rédiger les tests et faire générer l'implémentation (+ refacto) serait plus safe ?

Le MCP risque de changer le game

JULIEN : à revoir ?

## Jeudi 13h30 - Vibe testing

Yann Helleboid

en utilisant Dinootoo (plateforme/toolbox d'Orange) pour avoir des prompts, en fournissant le code source de son application, il fait générer son plan de test IEEE 29119-3, puis ses différentes suites de test (API : fonctionnel/load/sécu, web : fonctionnel/a11y/sécu) qui sont 90% OK pour quelques dizaines de centimes

l'IA change le game

titre mensonger néanmoins : il faut tout le recul et l'expérience du testeur pour bien en tirer parti, donc ce n'est pas du "vibe"-testing, mais juste du test assisté par IA

## Vendredi 10h30 - Et si on faisait du simulation-driven development ?

Pierre Zemb

mocker toutes les IO (même le multithreading, les latences réseaux, ...), insérer du random depuis une seed primaire, et comme ça avoir des simulations répétables

un peu poussif : 25 minutes d'introduction au besoin, et au final très peu decode résenté, résultats un peu flous

réservés à des besoins extrêmes

intéressant néamoins

## Vendredi 13h00 - Apprenez à votre IA à faire du TDD

Manuel Camargo

A l'aide de Copilot Chat (plutôt que Edit, qui semble moins avancé), et du fichier `.copilot-instructions`, on peut améliorer la pratique des 3 étapes du TDD à Copilot, mais sans avoir de gains de temps/qualité pour autant pour l'instant

## Vendredi 13h30 - IA Générative; TDD et Architecture Héxagonale : une synergie révolutionnaire ?

Clément Virieux et Florine Chevrier

rediff pour moi de Lyon Craft, mais je voulais un second regard

stack = VSCode + Cline + Open Router + Claude

utiliser des cline rules

JULIEN : à revoir à Kaizen

# Sécu

## Mercredi 13h30 - Vol au-dessus d'un nid de vulnérabilités

Damien Lucas

présentation des 2 standards concurrents SPDX (Linux FOundation) et CycloneDX (OWASP) ainsi que les outillages liés

évolutions règlementaires : NIS2, CRA, ...

JULIEN : à creuser

JULIEN : avancer sur dependency-track

## Mercredi 14h35 - OAuth2& OpenID : sous le capot

Daniel garnier-Moiroux

j'en avais entendu parler en bien, je confirme que le live coding rend les choses très claires

même si ça reste une implèm archi minimale, ça aide à bien comprendre

JULIEN : à revoir à Kaizen

## Mercredi 17h00 - Top 3 des outils de l'OWASP

Florian Bernard

présentation de 3 outils :
* dependency-track, très utile
* Zed Attack Proxy, très impressionnant : à partir d'une simple navigation via browser, il essaye d'exploiter les endpoints révélés
* Mod-Security, intéressant

## Jeudi 12h35 - 403 Forbidden : panorama de la gestion des autorisations

François Eckert

présentation de l'évolution au cours du temps (ACL, RBAC, ABAC, ReBAC, GitOps, Zanzibar), et quelques outils actuels

# Archi

## Jeudi 10h30 - Les clés de l'architecture pour les devs

Cyrille Martraire + Eric Le Merdy

Cyrille est une valeur sûre, et je n'ai pas été déçu

plein de bons conseils d'architecture

mentionne les quality attributes (cf ISO/IEC 25010)

JULIEN : à revoir à Kaizen

## Vendredi 15h40 : The DDD Horror Picture Show

Thomas Pierrain, Pauline Jamin

2 parties : quelques mauvaises pratiques autour du DDD, puis des considérations plus générales sur l'architecture de solutions

# Dev

## Vendredi 12h35 - Et si Git n'était pas toujours la réponse ? Alternatives avec Pijul et Darcs

Anis Chaabani

présentation très superficielle de l'avantage (moins de conflits ?) et conclusion très limitée

On avait fait un lunch sur Sapling, dont il a mentionné un concurrent : Jujutsu

## Vendredi 17h00 - Modéliser votre domaine métier grâce aux types

Jordane Grenat

live-coding de refacto sur un exemple de code qui a des bugs, et de comment les rendre impossible grâce aux types :
- primitive obsession
- value object encapsulation
- phantom/branded types (distinguishable by the compiler, not at runtime)
- types algébriques : somme et produit

JULIEN : à revoir à Kaizen

# People & Culture + Mind the Geek

## Mercredi 13h00 - Les podcasts tech en France

Alexis Slawny

un petit tour d'horizon, un peu orienté biz, des différents podcasts

## Jeudi 14h35 - Savez-vous ce qu'est la couleur ? Découvrez la science derrière les pixels

Julien Sulpis

une masterclass : de superbes visualisations, un sujet bien vulgarisé, des conclusions utiles, ...

JULIEN : à revoir à Kaizen

## Jeudi 15h40 - Le tic-tac de l'horloge : la standardisation pourquoi ça compte vraiment ?

Caroline Boyer

je m'attendais à ce que ça parle + de technique de gestion du temps, et en relisant l'abstract je me suis rendu compte que j'avais mal compris

parle très en longueur du process de standardisation (la talkeuse ayant travaillé au NIST)

je n'étais pas du tout captivé, donc je suis passé à côté

mais ça m'a donné le temps de rédiger la première motié de ces slides TODO emoji sourrire

## Vendredi 13h30 - Staff Engineer : les défis, les galères et comment les surmonter

Alice Bonhomme-Biais et Théotime Levêque

une suite de situations problématiques, et quelques pistes de solution autour du métier de staff

un peu intéressant, mais à la limite de l'enfonçage de porte ouverte

mais j'ai bien aimé la recommandation de ne pas répondre à des messages privés, de demander à ce que les questions soient posées en public, pour que d'autres contribuent et partager l'apprentissage

# Ce que j'ai loupé TODO emoji triste

## Mercredi 11h35 - Arcane : quand la technologie n'est pas le produit : une série d'animation

j'ai entendu dire que ce n'était pas si bien ?

## Mercredi 11h35 - Les équipes se plient en 4 pour répondre aux éxigences du Cyber Resilience Act

j'avais peur que ce soit chiant (et par des gens de Thales)

## Jeudi 10h30 - Evolution continue de clusters Kubernetes/NoSQL supportant 300 millions de QPS

par Criteo, intéressant pour les chiffres sur le plus gros cluster européen

## Jeudi 11h35 - Kubernetes : 5 façons créatives de flinguer sa prod

semblait trop orienté "administration du cluster"

## Jeudi 11h35 - Comment allonger notre build nous a fait gagner du temps ?

en lisant l'abstract, j'avais l'impression que leur réponse c'était surtout l'ajout de linters

ce qu'ils citent : Gradle, PMD (analyse statique pour Java), dependabot

## Jeudi 15h40 - Vos requêtes SQL jusqu'à 10000 fois plus rapides, durablement

semble une mine d'or de bons conseils sur PG, et on me l'a recommandée

JULIEN : à revoir à Kaizen ?

## Jeudi 19h00 - Ensemble faisons progresser et grandir les développeurs débutants

ça semblait intéressant

## Jeudi 20h00 - Comment organiser des évènements plus inclusifs ?

j'étais curieux d'avoir d'autres pistes
