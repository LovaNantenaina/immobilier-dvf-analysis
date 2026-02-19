markdown
# 🏠 Analyse du Marché Immobilier Français (DVF 2025)

## 📌 Présentation du Projet
Ce projet consiste en une analyse de bout en bout des transactions immobilières en France pour l'année 2025. L'objectif est de transformer les données brutes de l'État en une cartographie interactive permettant de visualiser les tensions de prix par zone géographique.

## 🛠️ Compétences Techniques
- **Langage :** Python 3.x
- **Librairies :** [Pandas](https://pandas.pydata.org) (Data Cleaning), [Folium](https://python-visualization.github.io) (Cartographie), [Numpy](https://numpy.org)
- **Données :** [DVF (Demandes de Valeurs Foncières)](https://www.data.gouv.fr) - Source officielle Etalab.
- **Géocodage :** Utilisation de l'[API Adresse](https://adresse.data.gouv.fr) pour la conversion des adresses en coordonnées GPS.

## 🚀 Étapes Réalisées
1. **Acquisition :** Récupération du dataset officiel DVF 2025.
2. **Nettoyage :** 
   - Filtrage des ventes (hors dépendances et adjudications).
   - Traitement des valeurs manquantes et aberrantes (Outliers).
   - Calcul du **prix au m²** par transaction.
3. **Visualisation :** Création d'une **Heatmap interactive** avec Folium pour identifier les zones les plus onéreuses.

## 📊 Résultats
La carte permet d'identifier visuellement les quartiers où la demande est la plus forte. 
<img width="1365" height="634" alt="image" src="https://github.com/user-attachments/assets/41cd42aa-0a78-46b5-b2eb-6e7de2f075ab" />

🔍 Interprétation des Résultats (Insights)

1. Concentration des prix (L'Analyse de l'Histogramme)
"La distribution des prix au 
 montre une forte concentration autour de la médiane de [Insérez votre chiffre] €. On observe une 'longue traîne' vers la droite, indiquant un segment de marché 'Luxe' minoritaire mais bien présent, avec des biens dépassant les 15 000 €/
."
2. Corrélation Surface vs Prix (Le Nuage de Points)
"Le nuage de points confirme une corrélation linéaire positive entre la surface et le prix total. Cependant, l'analyse montre que les petites surfaces (Appartements) présentent souvent un prix au 
 plus élevé que les maisons de grande surface, un phénomène classique de forte demande locative urbaine."
3. Zones de Tension (Le Top 10 des Villes)
"Le Top 10 met en évidence une fracture territoriale nette. L'écart de prix entre la commune la plus chère ([Ville 1]) et la 10ème ([Ville 10]) est de [X]%, ce qui suggère des opportunités d'investissement dans les communes limitrophes en pleine gentrification."






## 🔮 Prochaines Étapes
- [ ] Entraînement d'un modèle de régression pour prédire le prix d'un bien.
- [ ] Création d'un dashboard interactif avec [Streamlit](https://streamlit.io).


