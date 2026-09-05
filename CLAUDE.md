# Concours ANP — Cadre Data Scientist — Plan de révision (4 jours)

Contexte : concours ANP (Agence Nationale des Ports), poste "Cadre Data Scientist"
(Direction Stratégie et Développement, rattaché au Service Intelligence Economique).
Épreuve dans 4 jours. Réf : `بطائق الوظيفة (بالفرنسية) (2).pdf`.

Missions clés du poste (à garder en tête pendant toute la révision, pas seulement le jour ANP) :
1. Veille économique et concurrentielle
2. Collecte, traitement et modélisation des données économiques (ML, scoring, prévision)
3. Réalisation et suivi des études
Outils cités explicitement par la fiche de poste : SQL/NoSQL, ETL, Power BI/Tableau/SAS/SPSS,
Big Data (connaissance, pas expertise profonde), anglais.

## Planning détaillé des 4 jours

### Jour 1 — Machine Learning fondamentaux + ANP partie 1

**Bloc ML (matin/après-midi) → `ML/ml.tex`, section "Concepts ML de base" (déjà rédigée) :**
- Concepts : AI vs ML vs Deep Learning ; supervised learning vs unsupervised learning ;
  classification vs régression vs clustering ; training/testing/validation ; features vs target.
- Algorithmes (principe uniquement, pas les maths) : Linear Regression, Logistic Regression,
  Decision Tree, Random Forest, XGBoost, K-Means, PCA.
- Savoir répondre : « Pourquoi choisir Random Forest plutôt que Logistic Regression ? »
- Évaluation ML :
  - Classification : Confusion Matrix (TP, TN, FP, FN), puis Accuracy, Precision, Recall,
    F1-score, ROC-AUC.
  - Régression : MAE, MSE, RMSE, R².
  - Questions typiques : différence Precision/Recall ; qu'est-ce que l'overfitting,
    comment le détecter, comment le réduire.

**Bloc ANP partie 1 (fin de journée) → `anp/anp.tex`, section "ANP partie 1" :**
- Qu'est-ce que l'ANP : Agence Nationale des Ports, autorité et régulateur du système
  portuaire marocain créé par la loi 15-02 ; établissement public à personnalité morale
  et autonomie financière.
- Loi 15-02 : pourquoi la réforme, création de l'ANP, rôle de l'autorité portuaire,
  régulation, concurrence, exploitation, séparation des rôles.
- Révision active à main levée (sans notes) :
  « Donne 3 missions de l'ANP » / « Qu'est-ce que la loi 15-02 ? » /
  « Quel est le statut juridique de l'ANP ? » / « Quel est son rôle dans le système
  portuaire ? »

### Jour 2 — Statistiques + Python + SQL + ANP partie 2

**Statistiques → `Statistiques/statistiques.tex` :**
moyenne, médiane, variance, écart-type, covariance, corrélation, distribution normale,
probabilités, probabilité conditionnelle, théorème de Bayes.

**Python / Pandas → `Python.sql/python_sql.tex` (section Python) :**
- Python : list, tuple, dict, set, comprehension, functions, exceptions, OOP basique.
- Pandas : `read_csv()`, `head()`, `info()`, `describe()`, `loc`, `iloc`, `groupby()`,
  `merge()`, `fillna()`, `dropna()`, `drop_duplicates()`, `sort_values()`.

**SQL → `Python.sql/python_sql.tex` (section SQL) :**
SELECT, WHERE, GROUP BY, HAVING, ORDER BY, JOIN, LEFT JOIN, INNER JOIN, CASE WHEN,
CTE, sous-requêtes, window functions. Priorité : savoir écrire des requêtes, pas
seulement les lire.

**ANP partie 2 → `anp/anp.tex`, section "ANP partie 2" :**
Vocabulaire portuaire de base (niveau métier, pas ingénieur maritime) : port, terminal,
quai, bassin, darse, chenal, tirant d'eau, navire, conteneur, manutention, stockage,
transit, dragage, bathymétrie, hinterland, chaîne logistique.
Objectif : comprendre le métier pour répondre à « Sur quelles données pourriez-vous
travailler dans un port ? »

### Jour 3 — Data Science profonde + Big Data + ANP partie 3

**ML avancé → `ML/ml.tex`, section "ML avancé" :**
- Preprocessing : missing values, outliers, encoding, scaling, normalization,
  standardization.
- Feature engineering, feature selection, data leakage.
- Imbalanced dataset et SMOTE.
- Cross-validation, hyperparameter tuning.
- Algorithmes avancés : Random Forest, XGBoost, K-Means, PCA, Gradient Boosting,
  Ensemble Learning.
- Questions ouvertes : comment choisir un algorithme, comment améliorer un modèle,
  que faire si les classes sont déséquilibrées, comment éviter l'overfitting.

**Big Data + Veille/BI → `Big_Data/big_data.tex` :**
- Hadoop, HDFS, MapReduce.
- Spark, RDD, DataFrame, Spark SQL, Spark Streaming.
- Kafka : Producer, Consumer, Topic, Partition, Offset, Consumer Group, Replication.
- Architecture bout en bout : Sources → Kafka → Spark → Data Lake → Data Warehouse → ML/BI.
- Veille économique et concurrentielle : identification de sources pertinentes
  (fiabilité, richesse, fraîcheur, accessibilité, coût), recoupement/validation de
  l'information, veille stratégique sectorielle et technologique.
- BI : rester sur les concepts théoriques transversaux plutôt que sur les noms
  d'outils (Power BI/Tableau/SAS/SPSS ne sont que des implémentations) :
  cube OLAP, dimensions vs mesures, schéma en étoile (star schema) vs schéma en
  flocon (snowflake schema), table de faits vs table de dimension, granularité,
  opérations OLAP (drill-down, roll-up, slice, dice, pivot), ETL vs ELT,
  Data Warehouse vs Data Mart, KPI et tableau de bord stratégique.

**ANP partie 3 → `anp/anp.tex`, section "ANP partie 3" (niveau entretien institutionnel) :**
- Statut : établissement public.
- Rôle : autorité portuaire / régulation.
- Loi fondatrice : loi 15-02.
- Périmètre : ports du Royaume, à l'exception du complexe Tanger Med / zone couverte
  par une loi spécifique.
- Missions (article 33 de la loi 15-02) : développement, maintenance, modernisation,
  optimisation de l'outil portuaire, compétitivité, simplification des procédures,
  régulation, contrôle, sécurité.

**Actualité ANP → `anp/anp.tex`, section "Actualité ANP" (à refaire aussi le Jour 4) :**
Site officiel ANP, actualités, projets, appels d'offres, grands projets portuaires,
digitalisation, environnement, sécurité, performance portuaire.

### Jour 4 — Simulation réelle (examen blanc, 08:00–10:00)

Pas de nouveau cours : un sujet blanc complet en conditions réelles, qui pioche dans
les 5 fichiers `.tex` existants.

| Partie | Barème | Source | Contenu |
|--------|--------|--------|---------|
| A — ANP | 10 pts | `anp/anp.tex` | 3 missions ANP, loi 15-02, rôle d'une autorité portuaire, 5 notions portuaires, intérêt de la digitalisation des ports |
| B — Statistiques | 10 pts | `Statistiques/statistiques.tex` | Questions courtes |
| C — Data Science / ML | 30 pts | `ML/ml.tex` | ML, classification vs régression, Precision vs Recall, overfitting, cross-validation, Random Forest, XGBoost, K-Means, PCA |
| D — Python / SQL | 20 pts | `Python.sql/python_sql.tex` | Exercices pratiques |
| E — Big Data | 10 pts | `Big_Data/big_data.tex` | Hadoop/Spark/Kafka |
| F — Cas pratique | 20 pts | Transverse (pas de fichier dédié, à traiter à la main) | Ex. : « L'ANP souhaite prédire le temps d'attente des navires. Proposez une approche Data Science » → rédiger : 1. Collecte, 2. Nettoyage, 3. EDA, 4. Feature Engineering, 5. Train/Test, 6. Modèle, 7. Évaluation, 8. Déploiement, 9. Monitoring, 10. Dashboard. |

## Structure du dossier = structure des fichiers LaTeX

Règle : **un seul fichier `.tex` par dossier**, pas plus. 5 dossiers existent déjà à la racine
de `d:/anp` → donc **5 fichiers LaTeX au total** pour tout le plan de révision.

| # | Dossier              | Fichier LaTeX à créer         | Contenu (thème du planning)                                   |
|---|----------------------|--------------------------------|-----------------------------------------------------------------|
| 1 | `ML/`                | `ML/ml.tex`                   | Jour 1 (fondamentaux ML) + Jour 3 partie ML avancé/preprocessing |
| 2 | `Statistiques/`      | `Statistiques/statistiques.tex` | Jour 2 partie Statistiques                                     |
| 3 | `Python.sql/`        | `Python.sql/python_sql.tex`   | Jour 2 partie Python/Pandas + SQL                               |
| 4 | `Big_Data/`          | `Big_Data/big_data.tex`       | Jour 3 partie Big Data (Hadoop/Spark/Kafka) + Veille économique/concurrentielle et outils BI (Power BI/Tableau/SAS/SPSS) |
| 5 | `anp/`               | `anp/anp.tex`                 | Jour 1 partie ANP-1, Jour 2 partie ANP-2, Jour 3 partie ANP-3, actualité ANP |

Le Jour 4 (simulation réelle) n'est PAS un fichier de cours séparé : c'est un examen blanc
qui pioche des questions dans les 5 fichiers ci-dessus (Partie A=anp.tex, B=statistiques.tex,
C=ml.tex, D=python_sql.tex, E=big_data.tex, F=cas pratique transverse écrit à la main).

Ne pas créer de 6e dossier ni de fichier `.tex` supplémentaire (pas de fichier par jour,
pas de fichier séparé pour le cas pratique) — tout rentre dans les 5 fichiers existants.

## Conventions LaTeX à respecter dans les 5 fichiers

- Classe : `article`, format A4, `\usepackage[french]{babel}` pour les titres de section en français.
- Un fichier = un document autonome compilable seul (pas de sous-fichiers `\input`).
- Structurer avec `\section`, `\subsection` — pas de découpage en fichiers multiples même
  si le contenu est long (le heuristique "300 lignes" du reste du CLAUDE.md ne s'applique
  pas ici : ce sont des fiches de révision, la longueur est normale).
- Privilégier des listes (`itemize`/`enumerate`) et des tableaux courts plutôt que de longs
  paragraphes — ce sont des fiches de révision à relire vite, pas un rapport.
- Mettre en gras (`\textbf`) les termes techniques qui doivent être sus "par cœur"
  (ex. TP/TN/FP/FN, Loi 15-02, article 33).
