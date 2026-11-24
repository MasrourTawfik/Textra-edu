# Trading Intelligent — CH06 v2.0 — Guide étudiant

[Manuel CH06 PDF (49 pages)](../chapters/CH06/Trading_Intelligent_CH06_Manuel_v1.0.pdf)
## Deux laboratoires complémentaires
**G1 — Visite guidée** : comprendre les calculs d’un neurone et d'un MLP, les shapes (batch, temps, caractéristiques), les RNN, LSTM, GRU, puis les premières prévisions et décisions fictives. Le notebook G1 s'exécute intégralement sans modifier de cellules.
**A2 — Atelier autonome** : partir d’une série univariée de 840 observations, construire ses fenêtres, sa séparation chronologique et des modèles MLP, RNN, GRU, LSTM ; comparer TRAIN/VALIDATION ; passer à 910 séances financières fictives et tester des décisions après coûts. A2 contient **11 exercices obligatoires**, avec tests automatiques, et s'arrête volontairement sur NotImplementedError jusqu'au remplissage des fonctions.
## Liens Google Colab
- [G1 STUDENT](https://colab.research.google.com/github/MasrourTawfik/Textra-edu/blob/trading-intelligent/notebooks/CH06/CH06_G1_Visite_Guidee_STUDENT.ipynb)
- [A2 STUDENT](https://colab.research.google.com/github/MasrourTawfik/Textra-edu/blob/trading-intelligent/notebooks/CH06/CH06_A2_Modelisation_Autonome_STUDENT.ipynb)
## Utilisation
Ouvrir G1 avant A2. Dans Colab choisir **Exécution > Tout exécuter** pour G1. Pour A2 : lire une mission, compléter le code TODO, exécuter le test adjacent avant de poursuivre. **Ne pas supprimer les tests.**
Les CSV se trouvent sous data/CH06 ; les deux notebooks sont aussi autonomes sans fichiers externes. Les modèles utilisent PyTorch sur CPU.
## Livrables de A2
1. Modélisation : matrices, shapes, cibles, chronologie et hypothèses.
2. Code : fenêtres, modèles, tests exécutés, courbes d'entraînement.
3. Comparaison : baselines, MLP/RNN/GRU/LSTM, métriques et sélection sur validation.
4. Extension : multivarié, horizons, trading après coûts et limites.
Les données sont **fictives**, sans conseil ni preuve de rentabilité.
