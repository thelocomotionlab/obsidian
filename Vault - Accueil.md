# 🚂 Locomotion Lab — Coffre de connaissances

> Système de capitalisation **atomique** des connaissances, pour les restituer ensuite sous différentes formes : articles, conférences, livres.
>
> **Règle d'or : ce coffre se juge à ce qu'il *produit*, pas à ce qu'il *couvre*.**

## Par où commencer
1. Lis **[[Vault - Mode d'emploi]]** une seule fois (5 min). C'est la constitution du coffre.
2. Active le plugin *Modèles* (Réglages → Plugins internes → Modèles). Le dossier est déjà réglé sur `90 Templates`.
3. Lance-toi sur ton premier chantier réel (ci-dessous), pas sur le système lui-même.

## Les 5 dossiers
- **10 Inbox** — capture brute, en vrac. Se vide chaque semaine.
- **20 Sources** — une note par livre / étude / podcast lu. Tes mots + la référence + le niveau de fiabilité.
- **30 Notes** — les idées **atomiques** (titre = une affirmation). Le cœur du coffre. Contient aussi les **notes-ponts** (`type: pont`).
- **40 MOC** — les cartes thématiques qui organisent les notes. Elles remplacent l'arborescence.
- **50 Productions** — articles, conférences, chapitres : assemblés depuis les notes.

*(+ `90 Templates` : les modèles — `99 Pièces jointes` : images et fichiers.)*

## 🎯 Chantier en cours
- [ ] **Article — Développe ta respiration fonctionnelle**
  - MOC : [[Respiration fonctionnelle]] *(à créer)*
  - Production : [[Article - Respiration fonctionnelle]] *(à créer)*

---
## Tableau de bord *(optionnel — nécessite le plugin Dataview, à installer plus tard)*

### Notes les plus récentes
```dataview
TABLE statut AS "Statut", utilisable-pour AS "Pour"
FROM "30 Notes"
WHERE type = "note"
SORT file.mtime DESC
LIMIT 10
```

### Graines à faire mûrir
```dataview
LIST
FROM "30 Notes"
WHERE statut = "graine"
```

### Ponts & hypothèses (ma matière créative)
```dataview
LIST
FROM "30 Notes"
WHERE type = "pont"
```
