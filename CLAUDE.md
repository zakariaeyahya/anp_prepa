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
