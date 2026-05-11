# OSINT Prospective — Analyste en renseignement stratégique

> **Skill Claude** dédié à l'analyse prospective d'événements à partir de sources ouvertes (presse, OSINT structurée), combinant méthode scientifique, détection de signaux faibles et lecture symbolique/fractale.

---

## 🎯 Finalité

Ce skill installe sur Claude une posture d'**analyste en renseignement stratégique**, spécialisé en **prospective événementielle**. Il permet de :

- **Croiser** données journalistiques, archétypes, motifs cachés et dynamiques stratégiques ;
- **Proposer** des hypothèses sur des événements futurs — y compris non causaux mais structurellement possibles ;
- **Détecter** l'invisible, le sous-estimé, l'angle mort médiatique ;
- **Produire** des livrables défendables : profils, évaluations de risque, scénarios prospectifs, recommandations.

---

## 🧭 Posture

L'analyste opère avec **discipline méthodologique** et **lucidité symbolique** :

| Dimension | Apport |
|---|---|
| **Méthode scientifique** | Hypothèses testables, traçabilité des inférences, lutte contre les biais |
| **Signaux faibles** | Lecture des dissonances, anomalies, ruptures de ton, omissions |
| **Lecture symbolique** | Détection des archétypes narratifs, motifs récurrents, mises en scène |
| **Lecture fractale** | Reconnaissance de patterns qui se répliquent à différentes échelles (micro/méso/macro) |

---

## ⚙️ Méthode en 11 étapes

```
1.  Problématisation        →  Reformuler la question en problème analytique testable
2.  Plan de collecte        →  Cibler les sources OSINT (presse, archives, registres, imagerie)
3.  Structuration           →  Codage thématique, chronologie, matrices, géolocalisation
4.  Analyse multi-pivot     →  Qualitatif + quantitatif + géographique + symbolique/fractal
5.  Hypothèses concurrentes →  Générer ≥3 hypothèses, comparer, ne jamais s'arrêter à la première
6.  Production analytique   →  Profils de cible / évaluation tactique / évaluation stratégique
7.  Scénarios prospectifs   →  Optimiste / Probable / Critique + indicateurs de bascule
8.  Évaluation du risque    →  Probabilité × Impact × Vulnérabilité × Capacité adverse
9.  Recommandations         →  Options claires, priorisées, actionnables
10. Contrôle des biais      →  ACH, red team mentale, justification explicite
11. Boucle de rétroaction   →  Surveillance des indicateurs, mise à jour des hypothèses
```

Chaque étape est documentée dans `references/`.

---

## 🚀 Déclenchement

Le skill s'active automatiquement quand l'utilisateur :

- demande une **analyse prospective** d'un événement, d'une crise, d'une dynamique géopolitique, économique, politique ou criminelle ;
- présente un **corpus de presse** ou un dossier OSINT à analyser ;
- évoque des **signaux faibles**, des **anomalies**, des **patterns** à interpréter ;
- demande des **scénarios** sur un futur possible ;
- veut **profiler** un acteur (individu, organisation, État, groupe) à partir de sources ouvertes ;
- formule une question du type *« que peut-il se passer ensuite ? »*, *« qu'est-ce qui se prépare ? »*, *« quel est l'angle mort ici ? »*.

---

## 📁 Structure du dépôt

```
osint-prospective/
├── README.md                    ← ce fichier
├── SKILL.md                     ← le skill opérationnel (avec YAML frontmatter)
└── references/
    ├── 01-problematisation.md
    ├── 02-collecte-osint.md
    ├── 03-structuration.md
    ├── 04-analyse-multi-pivot.md
    ├── 05-hypotheses-concurrentes.md
    ├── 06-production-analytique.md
    ├── 07-scenarios-prospectifs.md
    ├── 08-evaluation-risque.md
    ├── 09-recommandations.md
    ├── 10-controle-biais.md
    ├── 11-boucle-retroaction.md
    ├── archetypes-fractals.md   ← lecture symbolique et patterns récursifs
    └── format-livrable.md       ← templates des produits finaux
```

Claude charge `SKILL.md` à l'activation, puis lit les fichiers `references/` selon les besoins.

---

## 📦 Installation

### Sur Claude.ai (skill personnel)

1. Téléchargez le dossier ou le `.skill` packagé.
2. Importez-le dans **Settings → Skills**.
3. Le skill se déclenche automatiquement sur les requêtes pertinentes.

### Sur Claude Code / API

Placez le dossier dans le répertoire de skills accessible à votre instance Claude.

---

## ⚖️ Principes éthiques

L'analyste opère dans un cadre **OSINT légal** :

- Sources publiquement accessibles uniquement ;
- Pas d'incitation à la collecte clandestine ou illégale ;
- Pas de profilage nominatif intrusif sur des personnes privées ;
- Identification explicite des **niveaux d'incertitude** et des **gaps d'information** ;
- Production de **livrables défendables** : chaque inférence est traçable.

---

## 🧠 Philosophie de fond

> *La mission de l'analyste n'est pas de deviner le futur, mais d'éclairer les chemins qui y mènent.*

Le skill ne prédit pas. Il **structure l'incertitude**, **expose les hypothèses concurrentes** et **rend visibles les signaux faibles** que la couverture médiatique standard ignore ou sous-pondère.

---

## 📜 Licence

À définir par l'auteur du dépôt (MIT, CC-BY, GPL, etc.).

---

## ✍️ Contribuer

Les contributions sont bienvenues :
- enrichissement du répertoire d'archétypes (`references/archetypes-fractals.md`) ;
- nouveaux templates de livrables ;
- cas d'étude documentés ;
- amélioration des méthodes de détection de signaux faibles.
