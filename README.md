## Jérôme Barthélemy

Développeur backend : **Python**, **C**, **Java**, **Go**.

**Docteur en physique**, j'ai passé vingt ans à enseigner la physique-chimie puis l'informatique et les sciences numériques.
J'ai quitté l'Éducation nationale en septembre 2026 pour me consacrer au développement logiciel, et je suis
à plein temps à l'[École 42](https://42nice.fr).

Avant même ma reconversion, je m'investissais déjà sur mon temps libre :
- en **algorithmie** depuis 2021 : [CodinGame](https://www.codingame.com/profile/e0b93d7a66709a1f5641c455a0c225221602724), 1978ᵉ sur 1,09 M de joueurs classés, l'essentiel des points en arènes de bots multijoueurs et en optimisation.
- en **robotique** depuis 2010, et dans les compétitions [FIRST](https://www.firstinspires.org/programs/ftc/) depuis 2019 : co-fondateur, président et mentor du club de robotique du lycée international de Valbonne, [Robotique CIV](https://ftc-civ.gitlab.io/index.html) — une association que nous avons constituée en 2020 et qui réunit aujourd'hui 60 lycéens en quatre équipes, encadrés par une dizaine de mentors adultes, professeurs et ingénieurs de nos entreprises partenaires.

**Autres outils utilisés :** Docker & Compose · HTML/CSS/JavaScript · Linux · Git · SQL


---

### Projets sélectionnés

Pour plus de détails et plus de projets, voir ici :
**[→ portfolio](https://github.com/JeromeBarthelemy/portfolio)**


| Projet | Ce que c'est | Stack |
|---|---|---|
| **[TAP](https://github.com/JeromeBarthelemy/tap-server)** | Serveur de jeu multijoueur implémentant un protocole texte spécifié en RFC, plus deux clients (graphique et textuel) interopérables avec les implémentations d'autres équipes. État partagé, événements asynchrones, logs JSON structurés, tests sous `-race`. | Go |
| **[Agent Smith](https://github.com/Enelsep/agent-smith)** | Harnais d'agent LLM : le modèle écrit du Python exécuté dans une sandbox sécurisée (connexion aux serveurs MCP possible), sous plafonds stricts d'itérations, de tokens et de temps. Agnostique du fournisseur. Évalué sur MBPP et SWE-bench. | Python, Docker |
| **[Fly-in](https://github.com/JeromeBarthelemy/Fly-in)** | Simulation d'une flotte de drones sur graphe contraint : le temps est déplié dans la structure — flot de coût minimal sur un graphe étendu dans le temps, capacités appliquées à chaque pas. Rejeu dans un visualiseur pygame. | Python, pygame |
| **[CallMeMaybe](https://github.com/JeromeBarthelemy/CallMeMaybe)** | Traduction de requêtes en langage naturel vers des appels de fonction JSON : décodage sous contrainte avec Qwen3-0.6B en local, la grammaire garantit une sortie conforme au schéma sans post-traitement. | Python, Qwen3 |
| **[RAG against the machine](https://github.com/JeromeBarthelemy/RAG)** | Recherche augmentée sur la base de code vLLM : ingestion, index lexical BM25, réponses sourcées. Qualité mesurée en recall@k, mypy strict. | Python |
| **[Inception](https://github.com/JeromeBarthelemy/Inception)** | Infrastructure WordPress conteneurisée : NGINX TLS unique point d'entrée, MariaDB, Redis, huit images écrites à la main depuis alpine. | Docker, NGINX, MariaDB |
| **[Robot FTC](https://gitlab.com/ftc-civ/baguettechs/ftc-decode-2026)** | Contribution au code des robots de compétition, aux côtés des élèves : pilotage mecanum, orientation par centrale inertielle, asservissement du lanceur par vision. | Java |
