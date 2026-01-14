# 📊 Analyse Data : Diagnostics de Performance Énergétique (DPE)

![Badge Master](https://img.shields.io/badge/Cadre-Master%201-blue) ![Badge R](https://img.shields.io/badge/Langage-R-276DC3) ![Badge DataMining](https://img.shields.io/badge/Skill-Data%20Mining-orange)

**Note :** Ce projet vise à confronter la théorie (DPE) à la réalité (consommation réelle 2024) pour identifier les déterminants de l'efficacité énergétique.

## 🎯 Objectif
Structurer et segmenter les données énergétiques des logements pour identifier des profils types et isoler les "passoires thermiques".

## 🛠️ Chaîne de Traitement Statistique
Nous avons appliqué une méthodologie multidimensionnelle complète :
1.  **ACP (Analyse en Composantes Principales) :** des variables quantitatives (consommation, coûts, surface).
2.  **AFC (Analyse Factorielle des Correspondances) :** Étude de la dépendance forte entre étiquettes DPE et émissions de GES.
3.  **ACM (Analyse des Correspondances Multiples) :** Analyse simultanée des caractéristiques physiques et historiques.
4.  **Clustering (CAH) :** Classification Ascendante Hiérarchique pour créer une typologie des logements.

## 💡 Résultats Clés : Les 3 Profils Types
L'analyse a permis de segmenter les logements en 3 classes distinctes (validées par l'inertie intra/inter-classe) :

* 🟢 **Cluster 1 "Les Logements Modernes et Vertueux" :**
    * Logements récents (majoritairement post-1980).
    * Performance énergétique élevée (DPE A, B ou C).
    * Faible consommation réelle.
* 🟠 **Cluster 2 "Les Logements Intermédiaires (Trente Glorieuses)" :**
    * Grands logements construits entre 1945 et 1968.
    * Performance moyenne (DPE D/E) et consommation élevée due à la surface.
* 🔴 **Cluster 3 "Les Logements Anciens et Précaires" :**
    * Petites surfaces construites avant 1945.
    * Passoires thermiques critiques (DPE F/G).

## 👥 Auteurs
* **Ibrahima Caba BAH**
* Kenny Jean-Elie
* Ndèye Fatou DIOP
