# Guide étudiant — CH02 v2.2

Le CH02 associe un chapitre de référence, une fiche de formules et définitions, un dataset pédagogique et deux laboratoires complémentaires.

## Ordre conseillé

1. **Lire le chapitre PDF jusqu'aux tests ADF/PP/KPSS.**
2. **NB01 — Stationnarité, ACF/PACF et diagnostic** : expérimenter la dépendance temporelle, la stationnarité, la différenciation et la spécification `c` / `ct`.
3. Revenir au chapitre pour étudier **ARIMA, Box–Jenkins, résidus, Ljung–Box et prévision**.
4. **NB02 — ARIMA, diagnostics et prévision hors échantillon**.
5. Comparer honnêtement **persistance, drift et ARIMA sur la même fenêtre future**.
6. Terminer les mini-laboratoires et la checklist de maîtrise.

## Fiche de référence

La fiche rassemble les définitions et formules essentielles : espérance, variance, stationnarité, bruit blanc, ACF/PACF, AR, MA, ARMA, ARIMA, ADF/PP/KPSS, Ljung–Box, AIC/BIC, baselines et métriques de prévision.

- [Ouvrir la fiche PDF](../chapters/CH02/fiches/Trading_Intelligent_CH02_Fiche_Reference_Formules_Definitions_Tawfik_Masrour.pdf)

## Ressources

- [PDF CH02](../chapters/CH02/Trading_Intelligent_CH02_Dependance_Temporelle_ARIMA_Tawfik_Masrour_v2.2.pdf)
- [Dataset CH02](../data/CH02/TI_CH02_TS_Models_v1.csv)
- [NB01 dans Colab](https://colab.research.google.com/github/MasrourTawfik/Textra-edu/blob/trading-intelligent/notebooks/CH02/CH02_NB01_Stationarity_ACF_PACF_Tawfik_Masrour_STUDENT.ipynb)
- [NB02 dans Colab](https://colab.research.google.com/github/MasrourTawfik/Textra-edu/blob/trading-intelligent/notebooks/CH02/CH02_NB02_ARIMA_Diagnostics_Forecasting_Tawfik_Masrour_STUDENT.ipynb)

## Règles méthodologiques à retenir

- AIC/BIC ne remplacent pas l'évaluation hors échantillon.
- Une p-value très petite n'est pas égale à zéro.
- KPSS peut ne fournir qu'une borne de p-value.
- Une grande p-value Ljung–Box ne prouve pas l'indépendance.
- Une méthode sophistiquée doit être comparée à plusieurs baselines raisonnables.
- CH02 utilise ici une prévision multi-pas à origine fixe ; le walk-forward sera approfondi en CH06.

Les versions publiques ne contiennent ni solutions privées, ni notebooks MASTER, ni notes enseignant.
