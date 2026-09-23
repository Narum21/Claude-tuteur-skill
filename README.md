# tuteur-etudes

Skill Claude qui accompagne pas à pas un étudiant sur tout travail universitaire noté, en restant collé aux consignes et au cours du professeur.

## Ce qu'il couvre
- **Projets de données et de code** : Excel, VBA, R, Stata, Python (formules, vérification des fichiers, diagnostic d'erreurs).
- **Écrits** : dossier, rapport, commentaire, mémoire.
- **Oraux** : exposé, soutenance.
- **Révisions d'examen** : QCM et partiels (analyse des anciens sujets, pronostic, pièges, QCM blanc).
- **Indicateurs économiques** : taux trimestriel, glissement annuel, taux annuel, acquis de croissance, TCAM.

## Méthode
1. Identifier le type de travail et charger la fiche adaptée.
2. Cadrer : consignes, cours, barème, attentes implicites du correcteur, ambiguïtés.
3. Planifier à rebours depuis la date de rendu.
4. Avancer une étape à la fois : principe, essai de l'étudiant, correction, contrôle, piège.
5. Diagnostiquer les erreurs à partir des résultats obtenus.
6. Contrôle final en trois blocs : correct / à corriger / finitions.
7. Préparer la défense orale.

Par défaut, le skill guide. Il rédige quand l'étudiant le demande explicitement.

## Structure
```
tuteur-etudes/
├── SKILL.md
├── references/
│   ├── projet-donnees.md
│   ├── ecrit.md
│   ├── oral.md
│   ├── revision-examen.md
│   ├── indicateurs-economiques.md
│   └── outils/ (excel, vba, r, stata, python)
└── evals/evals.json
```

## Installation
- **Claude.ai** : téléchargez `tuteur-etudes.skill` depuis les Releases (ou zippez le dossier `tuteur-etudes/`), puis Paramètres → Capacités → Skills → Importer.
- **Claude Code** : copiez le dossier `tuteur-etudes/` dans `~/.claude/skills/`.
