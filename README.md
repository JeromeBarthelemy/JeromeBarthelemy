## Jérôme Barthélemy

Développeur backend — **Python**, **C**, **Java**, **Go**.
Docteur en physique, vingt ans à enseigner les sciences puis la NSI, aujourd'hui à
plein temps à l'[École 42](https://42nice.fr) pour en faire mon métier.

J'aime les systèmes qui doivent rester debout : serveurs concurrents, protocoles
réseau, données qui ne doivent pas se perdre. J'écris des tests parce que j'ai
corrigé trop de copies pour croire un programme sur parole.

**Ce que j'utilise** — Python · C · Java · Go · SQL · Docker & Compose · NGINX · Linux · Git

[CodinGame](https://www.codingame.com/profile/e0b93d7a66709a1f5641c455a0c225221602724) — 1978ᵉ sur 1,09 M de joueurs classés, l'essentiel des points en arènes de bots multijoueurs et en optimisation.

---

### Projets sélectionnés

Les études de cas détaillées — architecture, décisions, ce qui a cassé — sont ici :
**[→ portfolio](https://github.com/JeromeBarthelemy/portfolio)**

Les dépôts publiés ne contiennent que mon propre code : sujets, moulinettes et supports
pédagogiques appartiennent à l'École 42 et n'y figurent pas.

| Projet | Ce que c'est | Stack |
|---|---|---|
| **[TAP](https://github.com/JeromeBarthelemy/tap-server)** | Serveur de jeu multijoueur TCP autour d'un protocole texte spécifié en RFC, plus deux clients. État partagé, événements asynchrones, logs JSON structurés, tests sous `-race`. | Go |
| **[Agent Smith](https://github.com/Enelsep/agent-smith)** | Harnais d'agent LLM : le modèle écrit du Python exécuté dans un interpréteur restreint, sous plafonds stricts d'itérations, de tokens et de temps. Agnostique du fournisseur. Évalué sur MBPP et SWE-bench. | Python, Docker |
| **[RAG against the machine](https://github.com/JeromeBarthelemy/RAG)** | Recherche augmentée sur la base de code vLLM : ingestion, index, réponses sourcées. Qualité mesurée en recall@k, 43 tests, mypy strict. | Python |
| **[Inception](https://github.com/JeromeBarthelemy/Inception)** | Infrastructure WordPress conteneurisée : NGINX TLS unique point d'entrée, MariaDB, Redis, huit images écrites à la main depuis alpine. | Docker, NGINX, MariaDB |
| **[Robot FTC DECODE](https://gitlab.com/ftc-civ/baguettechs/ftc-decode-2026)** | Code du robot de compétition : pilotage mecanum, orientation par centrale inertielle, asservissement du lanceur par vision. 68 commits sur 108. | Java |
