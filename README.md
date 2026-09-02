## Jérôme Barthélemy

Développeur backend : **Python**, **C**, **Java**, **Go**.

**Docteur en physique**, j'ai passé vingt ans à enseigner la physique-chimie puis l'informatique et les sciences numériques; aujourd'hui je suis à
plein temps à l'[École 42](https://42nice.fr) pour en faire mon métier.

Avant même ma reconversion, je m'investissais déjà sur mon temps libre :
- en **algorithmie** depuis 2021 : [CodinGame](https://www.codingame.com/profile/e0b93d7a66709a1f5641c455a0c225221602724), 1978ᵉ sur 1,09 M de joueurs classés, l'essentiel des points en arènes de bots multijoueurs et en optimisation.
- en **robotique** depuis 2019 : en tant que président et mentor, je m'occupe du club de robotique du lycée international de Valbonne [Robotique CIV](https://ftc-civ.gitlab.io/index.html), avec lequel nous participons aux compétitions internationales de robotique organisées par [FIRST](https://www.firstinspires.org/programs/ftc/).

**Autres outils utilisés :** Docker & Compose · HTML/CSS/JavaScript · Linux · Git · SQL


---

### Projets sélectionnés

Pour plus de détails et plus de projets, voir ici :
**[→ portfolio](https://github.com/JeromeBarthelemy/portfolio)**


| Projet | Ce que c'est | Stack |
|---|---|---|
| **[TAP](https://github.com/JeromeBarthelemy/tap-server)** | Serveur de jeu multijoueur TCP autour d'un protocole texte spécifié en RFC, plus deux clients (graphique et textuel). État partagé, événements asynchrones, logs JSON structurés, tests sous `-race`. | Go |
| **[Agent Smith](https://github.com/Enelsep/agent-smith)** | Harnais d'agent LLM : le modèle écrit du Python exécuté dans une sandbox sécurisée (connexion aux serveurs MCP possible), sous plafonds stricts d'itérations, de tokens et de temps. Agnostique du fournisseur. Évalué sur MBPP et SWE-bench. | Python, Docker |
| **[Fly-in](https://github.com/JeromeBarthelemy/Fly-in)** | Routage d'une flotte de drones sur graphe contraint : flot de coût minimal sur un graphe étendu dans le temps, capacités de zone appliquées tour par tour. Rejeu dans un visualiseur pygame. | Python, pygame |
| **[CallMeMaybe](https://github.com/JeromeBarthelemy/CallMeMaybe)** | Traduction de requêtes en langage naturel vers des appels de fonction JSON : décodage sous contrainte avec Qwen3-0.6B en local, la grammaire garantit une sortie conforme au schéma sans post-traitement. | Python, Qwen3 |
| **[RAG against the machine](https://github.com/JeromeBarthelemy/RAG)** | Recherche augmentée sur la base de code vLLM : ingestion, index, réponses sourcées. Qualité mesurée en recall@k, mypy strict. | Python |
| **[Inception](https://github.com/JeromeBarthelemy/Inception)** | Infrastructure WordPress conteneurisée : NGINX TLS unique point d'entrée, MariaDB, Redis, huit images écrites à la main depuis alpine. | Docker, NGINX, MariaDB |
| **[Robot FTC DECODE](https://gitlab.com/ftc-civ/baguettechs/ftc-decode-2026)** | Code du robot de compétition : pilotage mecanum, orientation par centrale inertielle, asservissement du lanceur par vision. | Java |
