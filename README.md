1. Titre et Description:
   IDS-Stochastic-Optimization: Détection d'Intrusions avec Apprentissage StochastiqueImplémentation d'un Système de Détection d'Intrusions (IDS) basé sur la méthodologie Murti et al., optimisé par un apprentissage en ligne (SGD) et une approche par ensemble.

   
2. Fonctionnalités Clés:
   Apprentissage en ligne (Online Learning) : Utilisation du SGDClassifier pour une mise à jour continue du modèle par mini-batches de 256.
   Architecture Hybride : Combinaison d'une détection par signatures (Bayes) et par anomalies statistiques.
   Allocation Dynamique de Ressources : Système de réponse graduée (HAUTE, MOYENNE, BASSE priorité) basé sur le score de menace.
   Modèle d'Ensemble : Vote par moyenne (Soft Voting) combinant SGD, Random Forest et l'algorithme initial pour atteindre 98,7% de Recall.

   
3. Technologies Utilisées:
   Langage :Python
   Bibliothèques : Scikit-learn, Pandas, NumPy, Matplotlib ,Seaborn
   Dataset : UNSW-NB15 (référence en cybersécurité)

   
4. Résultats de Performance:

Méthode                     Accuracy (%)  Recall (%)  F1-Score (%)
IDS Signature-based         85.1          87.5        88.9
Algorithme Optimisé (Final) 92.8          98.7        94.9
