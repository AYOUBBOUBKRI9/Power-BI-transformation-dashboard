# 📊 Analyse de la Transformation Digitale d’un Processus Métier — Power BI

## 📌 Présentation du projet

Ce projet consiste à analyser l’impact de la transformation digitale sur un processus métier en comparant son fonctionnement **avant et après la digitalisation**.

À partir d’un journal d’événements (*Event Log*), l’objectif est d’évaluer l’évolution des performances opérationnelles, le niveau d’automatisation et les reprises de traitement, afin de mieux comprendre les bénéfices de la digitalisation et d’identifier les axes d’amélioration.

Le projet a été réalisé dans le cadre du Master Informatique — **Gouvernance et Transformation Digitale**.

## 🎯 Objectifs

- Comparer les performances du processus avant et après digitalisation.
- Analyser les délais de traitement des dossiers.
- Mesurer le taux d’automatisation des activités.
- Comparer les activités humaines et automatiques.
- Étudier l’évolution des reprises de traitement (*reworks*).
- Concevoir un tableau de bord interactif pour faciliter l’analyse et la prise de décision.

## 🛠️ Technologies utilisées

- **Power BI Desktop** : création du tableau de bord interactif.
- **Power Query** : préparation, nettoyage et transformation des données.
- **DAX** : création de mesures et calcul des indicateurs clés de performance (KPI).
- **Data Visualization** : représentation graphique et analyse comparative.

## 📂 Structure du projet

```text
PowerBI-Transformation-Digitale/
├── Dashboard_Transformation_Digitale.pbix
├── README.md
└── images/
    └── dashboard.png
```

- `Dashboard_Transformation_Digitale.pbix` : fichier Power BI contenant le modèle de données, les mesures et les visualisations.
- `README.md` : documentation du projet.
- `images/dashboard.png` : aperçu du tableau de bord.

## 🔄 Méthodologie

### 1. Compréhension des données

Les données représentent les événements associés au traitement des dossiers. Chaque événement permet d'étudier les activités réalisées dans le processus et de comparer les situations avant et après digitalisation.

### 2. Préparation des données

Les données sont préparées dans Power Query afin de faciliter leur exploitation dans Power BI. Cette étape comprend la vérification des types de données, la cohérence des informations et la préparation des champs nécessaires à l'analyse.

### 3. Modélisation et mesures DAX

Des mesures sont utilisées pour calculer les indicateurs de performance, notamment le nombre de dossiers, le nombre d'événements, les durées de traitement, le taux d'automatisation et les reprises de traitement.

### 4. Conception du tableau de bord

Les indicateurs sont présentés sous forme de cartes KPI, de graphiques comparatifs et de filtres interactifs permettant d'explorer les résultats selon la situation étudiée.

### 5. Analyse comparative

Les résultats obtenus permettent d'évaluer les changements opérationnels associés à la digitalisation et de mettre en évidence les améliorations potentielles.

## 📈 Indicateurs clés de performance (KPI)

| Indicateur | Objectif |
|---|---|
| Nombre de dossiers | Mesurer le volume de dossiers analysés |
| Nombre d'événements | Évaluer le volume d'activités enregistrées |
| Durée moyenne de traitement | Analyser l'efficacité temporelle du processus |
| Taux d'automatisation | Mesurer la part des activités automatisées |
| Activités humaines | Quantifier les interventions humaines |
| Activités automatiques | Quantifier les interventions automatisées |
| Reworks | Étudier les reprises et répétitions de traitement |

## 💡 Principaux enseignements

L'analyse comparative vise à déterminer si la digitalisation permet :

- de réduire les délais de traitement ;
- de diminuer les interventions manuelles ;
- d'augmenter la part des activités automatisées ;
- de réduire les reprises de traitement ;
- d'améliorer la visibilité sur les performances du processus.

Les conclusions doivent être interprétées à partir des résultats du tableau de bord et de la qualité des données disponibles. Une comparaison fiable des durées nécessite notamment une méthode de calcul cohérente entre les deux situations.

## 📊 Aperçu du tableau de bord

Ajoutez une capture d'écran du rapport Power BI dans le dossier `images/`, puis affichez-la ici :

```markdown
![Dashboard Power BI](images/dashboard.png)
```

Le fichier `.pbix` permet également d'ouvrir le rapport dans Power BI Desktop pour explorer les indicateurs et les filtres interactifs.

## 🚀 Installation et utilisation

1. Téléchargez ou clonez ce dépôt GitHub.
2. Installez Power BI Desktop.
3. Ouvrez le fichier `Dashboard_Transformation_Digitale.pbix`.
4. Explorez les KPI, les graphiques et le filtre de comparaison Avant/Après.

Si les données sources ne sont pas intégrées au fichier ou si les chemins de connexion ont changé, adaptez les sources de données avant l'actualisation.

## 🎓 Compétences mobilisées

- Business Intelligence et visualisation de données.
- Préparation et transformation des données.
- Création de mesures avec DAX.
- Définition et analyse de KPI.
- Analyse comparative des processus métier.
- Gouvernance et transformation digitale.
- Aide à la décision basée sur les données.

## 👤 Auteur

**Mohamed Ayoub Boubkri**

Étudiant en Master Informatique — Gouvernance et Transformation Digitale.

- **GitHub :** [AYOUBBOUBKRI9](https://github.com/AYOUBBOUBKRI9)

---

*Projet académique réalisé dans le cadre de l'étude de la performance d'un processus métier avant et après sa transformation digitale.*
