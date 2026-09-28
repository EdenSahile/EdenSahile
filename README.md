
Claude Desktop (macOS), Connecté
Claude a terminé sa réponse.
Reviewing a GitHub profile README for feedback.
Reviewing a GitHub profile README for feedback.
Je vais d'abord retrouver le contenu exact de ton README GitHub pour te donner un retour précis.

Utilisé Mémoire lue, utilisé mcp__claude-code-remote__add_repo, et 18 étapes de plus
Maintenant j'ai le contenu complet. Voici mon analyse.

Analyse du README GitHub
Ce qui fonctionne bien
Le README est bien structuré et lisible. La section "Pourquoi PO et pas développeuse ?" anticipe une vraie question qu'un recruteur se poserait. Le lien vers tes deux projets IA (StoryPilot AI et Maison Buna) est bien mis en avant. Le ton est professionnel et authentique.

Points à améliorer (par ordre de priorité)
1. Le positionnement est en décalage avec ton CV

Ton CV te positionne comme Product Owner IA avec une proposition de valeur claire autour de l'IA. Ton README GitHub, lui, te positionne encore comme une PO "classique" qui "explore" l'IA. C'est contradictoire avec tout le travail qu'on a fait sur le CV.

Compare :

CV : "Product Owner IA" (titre), StoryPilot AI avec adoption par deux collègues, diagnostic d'hallucination RAG, pilotage d'agents IA de développement
README : "✨ Product Owner ✨ technique" (pas "IA"), "j'explore l'IA générative" (timide), pas de mention de Mimir
Le mot "explore" te place en posture d'apprenante, pas de praticienne. Sur GitHub, un recruteur tech va regarder ton profil en 30 secondes : le titre devrait être Product Owner IA ou AI Product Builder, pas simplement "Product Owner technique".

2. Mimir est absent

C'est ton projet le plus ambitieux, celui qui est dans la section "Culture technique" de ton CV ("pilotage d'agents IA de développement"), et il n'apparait pas du tout dans tes projets. Ton profil GitHub montre pourtant le repo Mimir avec des PRs bien structurées (TDD workflow, landing page, avatar). C'est un oubli important : un recruteur PO IA qui arrive sur ton GitHub voit StoryPilot et Maison Buna, mais pas la preuve que tu pilotes des agents IA pour construire une vraie application.

3. La liste de compétences techniques est incohérente avec ton positionnement

Plusieurs badges ne correspondent pas à ta pratique actuelle et brouillent le message :

WordPress, WooCommerce, BEM : pertinents pour ton ancien parcours, mais un recruteur PO IA n'a pas besoin de les voir
XAMPP, Firebase, MongoDB : tu ne les utilises pas dans tes projets actuels (tes projets tournent sur PostgreSQL et Node.js)
After Effects, InDesign, Invision : reliques d'une époque révolue, aucun rapport avec ton positionnement actuel
Bootstrap, Redux : anecdotiques
En revanche, il manque ce qui te caractérise réellement aujourd'hui :

Claude (API, Code) : ton outil principal
TypeScript : présent dans ton CV (Culture technique), même si tu l'apprends
Make / n8n : mentionnés dans ta section texte mais absents des badges
Aucun badge IA : pas de badge pour les LLM, RAG, ou l'automatisation IA
4. La section "Ce qui m'anime" est vide de substance

"Résoudre des problèmes complexes, améliorer continuellement les produits, et placer l'utilisateur au coeur des décisions" pourrait être écrit par n'importe quel PO. C'est exactement le genre de phrase générique que tu m'as demandé d'éviter. Soit tu la remplaces par quelque chose de spécifique (par exemple ta conviction sur l'IA comme outil au service du métier, pas comme gadget), soit tu la supprimes.

5. La section "Pourquoi PO et pas développeuse" pourrait être reformulée

Le contenu est bon, mais le titre est défensif. "Pourquoi PO et pas développeuse ?" implique que tu te justifies. Tu pourrais transformer ça en "Mon approche" ou "Ma conviction" et intégrer le fait que tu conçois, prototypes et construis avec l'IA, ce qui est plus puissant qu'un PO classique mais pas le même métier qu'un développeur.

6. Pas de mention de la certification Scrum dans la section compétences

Tu listes "Scrum (certifiée)" dans le texte, c'est bien. Mais si tu as un badge ou un lien vers la certification, ça renforce.

7. Eden IA Studio

Bonne nouvelle : Eden IA Studio n'apparait pas dans le README (cohérent avec ta contrainte CV). Rien à changer ici.

Recommandation
Je te propose de revoir le README selon ces axes :

Titre : "Product Owner IA" ou "AI Product Builder" au lieu de "Product Owner technique"
Intro : remplacer "j'explore l'IA générative" par un verbe d'action ("je conçois et construis des produits intégrant l'IA")
Projets : ajouter Mimir (en expliquant que c'est un projet construit en pilotant des agents IA de développement, avec le lien GitHub)
Badges : nettoyer radicalement. Garder React, JavaScript, Node.js, PostgreSQL, Git, Figma. Ajouter Claude, Make/n8n, TypeScript. Retirer WordPress, WooCommerce, BEM, XAMPP, Firebase, MongoDB, After Effects, InDesign, Invision, Bootstrap, Redux
"Ce qui m'anime" : remplacer par une phrase qui dit quelque chose de vrai sur ta vision (le rôle de l'IA dans le produit, la fiabilité comme obsession, etc.)
Section "Pourquoi PO et pas développeuse" : reformuler en positif ("Mon approche" + une phrase sur le fait que tu construis avec l'IA comme un builder, pas comme un spectateur)
Tu veux que je te rédige une version corrigée ?

réécris le .md complètement avec les modifs comme ca je fais un copier coller

Je réécris le README complet. Je vais aussi vérifier rapidement si Mimir est public ou privé pour adapter le lien.

Fichier créé, fichier partagé, exécuté 3 commandes
Voici le fichier. Résumé des changements :

Titre : "Product Owner IA" au lieu de "Product Owner technique"
Intro : verbes d'action ("je conçois et construis") au lieu de "j'explore"
Section "Mon approche" remplace "Pourquoi PO et pas développeuse ?" (positif au lieu de défensif) et supprime la phrase générique "Ce qui m'anime"
Compétences réorganisées en 3 blocs : Produit & Agilité, IA & Automatisation, Culture technique (alignés avec ton CV)
Mimir ajouté dans les projets, avec mention du pilotage d'agents IA
StoryPilot enrichi avec l'adoption par deux collègues (cohérent avec le CV)
Badges nettoyés : supprimés WordPress, WooCommerce, BEM, XAMPP, Firebase, MongoDB, After Effects, InDesign, Invision, Bootstrap, Redux. Ajouté TypeScript. Renommé la première colonne "Produit & IA"
Outils retirés de la section texte : Jira, Trello, Notion, Linear, Balsamiq, Miro, Adobe XD (pas besoin de les lister, tout PO les utilise)
Eden IA Studio : toujours absent, aucune mention
Un point à vérifier de ton côté : est-ce que le repo Mimir est bien public ? S'il est privé, il faudrait soit le rendre public, soit remplacer le lien par "(dépôt privé, lien disponible sur demande)" comme dans ta version anonymisée du CV.


Readme
Document·MD 



Claude est une IA et peut commettre des erreurs.


Readme · MD
 
 
<div align="center">
<img src='https://github.com/EdenSahile/EdenSahile/blob/main/img/1729276544440.jpeg' width="300px">
  </div>
 
# <div align="center">Bonjour 👋, je suis Eden </div>  
 
### Qui suis-je ?
  
✨ **Product Owner IA** ✨ avec un parcours qui mêle édition, digital, UX et développement fullstack (React, Node.js, API REST). Cette double casquette produit + technique me permet de concevoir des produits intégrant l'IA, de piloter des agents IA de développement et de dialoguer efficacement avec les équipes techniques.
 
🤖 Je conçois et construis des outils intégrant des LLM, du RAG et des workflows d'automatisation, avec une attention particulière à la fiabilité (détection d'hallucinations, tests, CI).
 
## 🚀 Mon approche
 
Ce qui me différencie : je ne me contente pas de spécifier, je construis. Mon bagage technique (formation fullstack, scripts d'automatisation, pilotage d'agents IA) me permet de prototyper, tester et livrer des produits fonctionnels, tout en gardant le cap sur la valeur métier et l'expérience utilisateur.
 
💡 **En résumé :** Product Owner qui conçoit et construit avec l'IA, pas à côté.
 
## 🛠️ Mes compétences
 
### 🎯 Produit & Agilité
 
* Scrum (certifiée), Kanban
* User stories, backlog, priorisation valeur business
* Recette & qualité : tests fonctionnels, validation livrables
* Wireframes, prototypes (Figma)
* Conduite du changement (formation des utilisateurs, modes d'emploi)
### 🤖 IA & Automatisation
 
* Claude (API, Code), pilotage d'agents IA de développement
* LLM, RAG, génération structurée
* Make, n8n
* Scripts JavaScript d'extraction et de traitement de données
### 💻 Culture technique
 
* React, TypeScript, Node.js, API REST, PostgreSQL
* Git, GitHub
* Lecture et revue de code
### 🚀 Projets IA
 
* **StoryPilot AI** : transforme un brief métier en user stories structurées (critères d'acceptation, scénarios Gherkin) à partir d'une base de connaissances (LLM, RAG) ; utilisé dans ma pratique de PO et par deux collègues. [github.com/EdenSahile/StoryPilot-ai](https://github.com/EdenSahile/StoryPilot-ai)
* **Mimir** : application construite en pilotant des agents IA de développement (Claude Code), avec workflow TDD, CI et architecture modulaire. [github.com/EdenSahile/Mimir](https://github.com/EdenSahile/Mimir)
* **Maison Buna** : application B2B de génération de devis pour un torréfacteur, avec génération de documents et automatisations. [github.com/EdenSahile/maison-buna-demo](https://github.com/EdenSahile/maison-buna-demo)
---
 
<p align="center">📫 Me contacter</p>
<p align="center"><a href="mailto:edensahile.pro@gmail.com">edensahile.pro@gmail.com</a></p>
 
  <div align="center">
<br>
  <a href="https://www.linkedin.com/in/eden-sahile-99b088112/" target="_blank">
    <img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;"/>
  </a>
  
</div> 
<br/>  
 
## My Skill Set  
<table><tr><td valign="top" width="33%">
 
 
### Produit & IA  
<div align="center">  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/figma-icon.svg" alt="Figma" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/git-scm-icon.svg" alt="Git" height="50" />  
</div>
</td><td valign="top" width="33%">
 
 
### Frontend  
<div align="center">  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/react-original-wordmark.svg" alt="React" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/javascript-original.svg" alt="JavaScript" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/typescriptlang-icon.svg" alt="TypeScript" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/css3-original-wordmark.svg" alt="CSS3" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/html5-original-wordmark.svg" alt="HTML5" height="50" />  
</div>
</td><td valign="top" width="33%">
 
 
### Backend  
<div align="center">  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/nodejs-original-wordmark.svg" alt="Node.js" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/postgresql-original-wordmark.svg" alt="PostgreSQL" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/javascript-original.svg" alt="JavaScript" height="50" />  
</div>
</td></tr></table>  
<br/>  
 
 
<br/>  
 
