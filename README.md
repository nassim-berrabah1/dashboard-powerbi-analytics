🧠 Dashboard Power BI — Santé Mentale des Jeunes Adultes

Quels facteurs comportementaux et environnementaux (sommeil, stress, alimentation, pression académique) constituent les principaux déterminants de la dépression et des troubles de santé mentale chez les jeunes adultes ?


📌 Contexte
Projet réalisé en mars 2026 dans le cadre de la formation BUT Informatique — Sciences des Données (IUT Villetaneuse, Université Sorbonne Paris Nord), en binôme avec Bajiry Diakite.

Source des données : Kaggle — Student Depression Dataset
Données réelles : 3 000 individus, 7 pays (USA, Inde, Japon, Australie, Canada, Brésil, Allemagne)
Outil : Power BI Desktop


📊 Aperçu du Dashboard
Page 1 — Vue d'ensemble géographique
<img width="1274" height="712" alt="image" src="https://github.com/user-attachments/assets/9eaa8a55-43a6-4b0c-80fc-2ff952a45546" />

Page 2 — Analyse comportementale & facteurs de risque
<img width="1273" height="712" alt="image" src="https://github.com/user-attachments/assets/f527b3e7-4695-4078-aa83-727c195fead6" />

🗂️ Structure du rapport (2 pages)
Page 1 — Vue d'ensemble

KPI : Nombre total d'individus (3 000), Score de Bonheur moyen (5,40), âge min/max
Treemap : Répartition des individus par âge et par pays
Carte géographique (Bing Maps) : Répartition géographique des répondants
Slicers interactifs : Filtre par tranche d'âge, genre et pays

Page 2 — Facteurs comportementaux & santé mentale

Scatter plot : Corrélation entre heures de sommeil et score de bonheur
Tableau croisé DAX : Score de bonheur moyen par condition mentale (Anxiety, Depression, PTSD, Bipolar...) × niveau de stress (Low / Moderate / High)
Donut chart : Répartition par genre (Female / Male / Other)
Donut chart : Répartition par niveau de stress
Pie chart : Types de régimes alimentaires (Junk Food, Balanced, Vegetarian, Keto, Vegan)


⚙️ Compétences Power BI mobilisées
CompétenceDétailImportation de donnéesFichier CSV KaggleNettoyageTraitement des valeurs manquantes, typage des colonnesModélisationSchéma en étoile (table faits + dimensions)Mesures DAXScore moyen, comptages conditionnels, totaux croisésVisuelsKPI cards, scatter plot, treemap, donut, pie, carte Bing MapsInteractivitéSlicers, cross-filtering entre visuelsEsthétiqueThème cohérent, titres clairs, mise en page soignée

🔍 Principaux résultats

Le manque de sommeil est corrélé à un score de bonheur plus faible
Le niveau de stress "Low" est associé aux scores de bonheur les plus élevés, toutes conditions confondues
La répartition des régimes alimentaires est quasi-uniforme (~20% chacun), sans influence notable isolée
Les individus atteints de PTSD avec un faible niveau de stress affichent paradoxalement un score de bonheur plus élevé (1 189)

📁 Contenu du repo
📦 dashboard-sante-mentale-powerbi
 - 📄 rapport.pbix   ← Fichier Power BI
 - 📄 rapport.pdf
 - 📄 README.md

👤 Auteur
Nassim Berrabah — BUT Informatique, Sciences des Données
IUT de Villetaneuse, Université Sorbonne Paris Nord
