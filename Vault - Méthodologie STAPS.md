---
type: méthode
date-création: 2026-08-11
tags: [méthode, staps]
---
# 🎓 Tenir le coffre pendant le STAPS

> Le risque n'est pas de trop peu noter. C'est de tout noter.
> Une L1 STAPS déverse plusieurs centaines de pages de cours. Le coffre se juge à ce qu'il produit, pas à ce qu'il couvre — cette règle devient vitale à partir de septembre.

---

## 1. Un cours n'est pas une source

**Règle non négociable.** Un CM est une *synthèse*, donc un **point d'entrée**, jamais une preuve.

| Ce qui est autorisé | Ce qui ne l'est pas |
|---|---|
| « Mon cours m'a mis sur la piste de X, j'ai remonté à la source Y » | « D'après mon cours de physiologie… » comme argument public |
| Niveau 0-2 à partir d'un cours | **Niveau 3 à partir d'un cours seul** |

Un cours peut donc générer des notes `graine` et `mûre`, jamais directement une note `vérifiée`. Le passage à `vérifiée` exige d'avoir lu la source primaire que le cours cite — c'est exactement ce qui a corrigé la sur-interprétation de Dallam 2018.

**Une note source par UE**, pas par séance :
```yaml
type-source: cours
titre: "UE Physiologie de l'exercice — L1 STAPS UGA"
fiabilité: "synthèse — point d'entrée, remonter aux primaires citées"
```

---

## 2. Trois rythmes, et rien d'autre

### ⚡ En cours — capture brute (0 min de surcoût)
- Tout va dans `00_Inbox`, en vrac, tel quel.
- **Interdiction formelle de créer une note permanente pendant un cours.** C'est le mode de rechute principal : construire l'ontologie en direct.
- Un seul geste utile en séance : marquer d'un `⭐` ce qui accroche. Trois étoiles par cours maximum.

### 🗓️ Chaque dimanche — 25 min, minuteur lancé
1. Vider `00_Inbox` — tout ce qui n'est pas repris est **supprimé**, sans état d'âme.
2. Créer **2-3 notes permanentes maximum** (règle existante du mode d'emploi). La sélection *est* le travail.
3. Chaque note : titre-affirmation, `statut: graine`, au moins un lien commenté.
4. Ouvrir une ligne dans le journal éditorial : quelle note sert quelle production ?

Si la semaine a été chargée : on saute les notes, on garde le vidage d'inbox. L'inbox qui déborde est le seul point de non-retour.

### 📚 Une fois par mois — la session de vérification (1 h)
Le seul moment où on passe des notes en `vérifiée`.
1. Prendre les 3 notes `mûre` les plus utiles à la production en cours.
2. Remonter à la source primaire. La lire — au minimum l'abstract, les méthodes et les limites.
3. Renseigner `fiabilité` dans la note source, remplir « À vérifier / limites / biais ».
4. Passer la note en `statut: vérifiée`.

→ **Environ 3 notes vérifiées par mois. C'est le débit réel du niveau 3.** Il détermine directement la cadence de carrousels scientifiques : ~1 par mois, pas plus. Toute promesse éditoriale au-delà est intenable.

---

## 3. Le filtre d'entrée

Avant de transformer un élément de cours en note, deux tests successifs :

1. **Test d'altitude** (existant) — « cette note pourrait-elle apparaître telle quelle dans une de mes productions ? »
2. **Test de production** (nouveau) — « quelle production identifiable en a besoin, maintenant ou dans les 6 mois ? »

Si le test 2 échoue : ça reste dans les notes de cours ordinaires. Le coffre n'est pas un support de révision. **Séparer physiquement les deux** : réviser le partiel d'anatomie et alimenter le labo sont deux activités distinctes, et les confondre remplit le coffre de matière inerte.

### Ce qui mérite d'entrer
- Ce qui contredit une croyance du milieu trail / minimaliste
- Ce qui donne un **mécanisme** à une observation de terrain déjà faite
- Ce qui est chiffré, mesurable, ou testable sur soi
- Ce qui recoupe une note existante — cf. règle des deux occurrences

### Ce qui n'entre pas
- Les définitions disponibles partout
- Ce qui n'est appris que pour l'examen
- Les concepts trop abstraits sans deux notes concrètes qui les réclament

---

## 4. Champs à ajouter au frontmatter

```yaml
statut: graine        # graine → mûre → vérifiée
staps: true           # provenance
ue: "Physiologie de l'exercice"
```

Aligner le vocabulaire des statuts : le tableau de bord de `Vault - Accueil` interroge déjà `statut = "graine"`, alors que le template écrit `statut: draft`. Retenir **graine / mûre / vérifiée**, et corriger le template.

---

## 5. Garde-fous

- **Le coffre ne s'ouvre pas en période de partiels.** Il attend. Une pause assumée coûte moins qu'un inbox de 200 captures.
- **Une seule métrique** : le nombre de notes réutilisées dans une production. Jamais le total.
- **Zéro nouveau plugin avant janvier.** Dataview quand il y aura ~30 notes, pas avant.
- **Si trois semaines passent sans qu'une note serve une production** : le problème n'est pas la discipline, c'est qu'aucune production n'est ancrée. Ouvrir une note `Production` avant de reprendre les lectures.
- **Un chantier à la fois.** L'article respiration se termine avant qu'un deuxième MOC ne s'ouvre.

---

## 6. Calendrier de rodage

| Période | Objectif |
|---|---|
| **Août** | Corriger les liens morts, terminer les 3 notes Dallam, publier l'article respiration. Le coffre doit avoir produit **une** fois avant la rentrée. |
| **Sept-oct** | Rodage : dimanche hebdo tenu, 2-3 notes / semaine. Aucun objectif de volume. |
| **Nov** | Premier MOC issu du STAPS atteint 5 notes → premier carrousel scientifique. |
| **Déc-janv** | Régime de croisière : ~3 notes vérifiées / mois, 1 carrousel scientifique / mois. |
