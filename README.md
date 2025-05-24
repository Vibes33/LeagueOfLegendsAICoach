# LeagueOfLegendsAICoach


🌍 Présentation complète du projet

🎯 Objectif global

Créer une plateforme d’intelligence artificielle capable de coacher les joueurs de League of Legends de manière personnalisée, intelligente et interactive, en analysant leurs parties comme le ferait un entraîneur humain professionnel.

⸻

🧠 Fonctionnement global de l’application (architecture prévue)

1. 🎮 Upload du replay

L’utilisateur charge un fichier de replay .rofl (ou le lien d’un match via Riot API).

2. 🧠 Analyse contextuelle

Une IA spécialisée :
	•	détecte le rôle et le champion joué
	•	extrait les données clés du match : adversaire direct, items achetés, actions importantes, erreurs…

3. 🔍 Modules d’analyse thématiques (IA spécialisées)

Chaque module se concentre sur une dimension du gameplay :
	•	Itemisation et runes : est-ce que les objets achetés sont optimaux pour le match-up ?
	•	Phase de lane : gestion de la vague, trades, recalls, zoning
	•	Teamfights : positionnement, focus, tempo
	•	Vision : placement de wards, contrôle de map
	•	Décision-making : objectifs, roaming, priorités

4. 🧩 Superviseur intelligent (LLM)

Un grand modèle de langage (LLM) synthétise les analyses pour :
	•	produire un rapport pédagogique complet
	•	commenter le replay avec des bulles interactives (à la Chess.com)
	•	répondre à des questions de l’utilisateur sur ses erreurs

⸻

💬 Interaction et apprentissage personnalisé

L’utilisateur peut :
	•	Choisir un ou plusieurs aspects à améliorer : itemisation, vision, etc.
	•	Interagir avec l’IA en cliquant ✅ (compris) ou ❌ (pas compris)
	•	Demander des explications supplémentaires, avec stats, comparatifs pro, exemples concrets

Exemple :
“Pourquoi ce joueur Yone a-t-il acheté Malmortius à 2 objets ?”
→ L’IA répond en citant le match-up, les sources de burst AP, les statistiques de winrate dans cette configuration.

⸻

🧑‍🎓 Impact pédagogique

Le projet se positionne comme un outil éducatif pour :
	•	aider les joueurs à comprendre leurs erreurs
	•	reproduire des comportements optimaux dans les prochaines parties
	•	accéder à un coaching professionnel automatisé et accessible à tous

⸻

🕹️ Modèle économique (version future)

L’application pourrait proposer :
	•	un accès gratuit pour l’analyse d’un seul aspect du jeu
	•	des forfaits premium pour une analyse complète par tous les modules
	•	des recommandations de champions, builds, runes personnalisés selon le style de jeu

⸻

📱 Plateforme cible
	•	Site web responsive (React/Flask)
	•	Possiblement une application mobile en complément (lecture du rapport)
	•	Compatibilité avec les fichiers .rofl Riot, ou intégration API Riot pour analyse en direct

⸻

🎨 Maquettes de l'application :

🏗️🏗️🏗️🏗️🏗️🏗️🏗️🏗️🏗️🏗️🏗️🏗️🏗️🏗️🏗️🏗️🏗️🏗️
	
⸻
