# Dataset CH03

- **Identifiant pédagogique :** `TI_CH03_VOL_RISK_V1`
- **Fichier :** `TI_CH03_Vol_Risk_v1.csv`
- **Nature :** synthétique, déterministe et pédagogique ; il ne s'agit pas d'une série issue d'un marché réel.
- **Usage :** diagnostics de volatilité, ARCH/GARCH, asymétrie, prévision conditionnelle et évaluation VaR/ES.

Le fichier contient notamment les rendements, le prix synthétique et des variables nécessaires aux expériences du chapitre. La variable `true_sigma` sert uniquement d'oracle pédagogique pour l'évaluation : elle ne doit pas être utilisée comme une variable explicative réaliste disponible sur un marché.

Les notebooks CH03 chargent ce fichier lorsqu'il est disponible. Ils disposent également d'un mécanisme de reconstruction déterministe afin de rester exécutables dans un environnement Colab propre.
