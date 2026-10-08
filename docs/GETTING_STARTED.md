# Démarrage rapide — Trading Intelligent

Le parcours publié comprend actuellement **CH01 v2.1**, **CH02 v2.2** et **CH03 v2.1**. Il est recommandé de les suivre dans cet ordre.

## CH01 — Comprendre le marché et ses données

1. Commencez par le [PDF du CH01](../chapters/CH01/Trading_Intelligent_CH01_Comprendre_Marche_Donnees_Tawfik_Masrour_v2.1.pdf).
2. Ouvrez **NB01** pour expérimenter bid/ask, OHLCV, microstructure et agrégation temporelle.
3. Poursuivez avec **NB02** pour les rendements, ajustements, opérations sur titres et contrôles de qualité.
4. Le dataset de référence est [TI_CH01_Market_Data_v1.csv](../data/CH01/TI_CH01_Market_Data_v1.csv), identifiant `TI_CH01_MARKET_V1`.

### Google Colab — CH01

- [NB01 — Market Data, OHLCV & Microstructure](https://colab.research.google.com/github/MasrourTawfik/Textra-edu/blob/trading-intelligent/notebooks/CH01/CH01_NB01_Market_Data_OHLCV_Microstructure_Tawfik_Masrour_STUDENT.ipynb)
- [NB02 — Returns, Adjustments & Data Quality](https://colab.research.google.com/github/MasrourTawfik/Textra-edu/blob/trading-intelligent/notebooks/CH01/CH01_NB02_Returns_Adjustments_Data_Quality_Tawfik_Masrour_STUDENT.ipynb)

## CH02 — Comprendre la dépendance temporelle

CH02 v4.0 reconstruit les séries temporelles depuis les phénomènes observables : tendance, saisonnalité, bruit, stationnarité, mémoire, AR/MA/ARMA, racines unitaires, ARIMA puis SARIMA.

1. Commencez par le [PDF du CH02](../chapters/CH02/Trading_Intelligent_CH02_Dependance_Temporelle_ARIMA_Tawfik_Masrour_v4.0.pdf).
2. Gardez la [fiche de référence](../chapters/CH02/fiches/Trading_Intelligent_CH02_Fiche_Reference_Formules_Definitions_Tawfik_Masrour_v4.0.pdf) à proximité.
3. Exécutez **NB01** après les sections sur anatomie d'une série, stationnarité et ACF.
4. Exécutez **NB02** après AR, MA, PACF, ARMA et ARIMA.
5. Exécutez **NB03** après la section saisonnalité/SARIMA.
6. Le dataset de référence est [TI_CH02_TS_MODELS_V4.csv](../data/CH02/TI_CH02_TS_MODELS_V4.csv), identifiant `TI_CH02_TS_MODELS_V4`.

### Google Colab — CH02

- [NB01 — Voir la série, stationnarité & ACF](https://colab.research.google.com/github/MasrourTawfik/Textra-edu/blob/trading-intelligent/notebooks/CH02/CH02_NB01_Voir_Serie_Stationnarite_ACF_Tawfik_Masrour_STUDENT.ipynb)
- [NB02 — AR, MA, ARMA & ARIMA](https://colab.research.google.com/github/MasrourTawfik/Textra-edu/blob/trading-intelligent/notebooks/CH02/CH02_NB02_AR_MA_ARIMA_Mecanismes_Tawfik_Masrour_STUDENT.ipynb)
- [NB03 — Saisonnalité & SARIMA](https://colab.research.google.com/github/MasrourTawfik/Textra-edu/blob/trading-intelligent/notebooks/CH02/CH02_NB03_Saisonnalite_SARIMA_Tawfik_Masrour_STUDENT.ipynb)

## CH03 — Comprendre et prévoir le risque

Après CH02, CH03 passe de la dynamique de la moyenne à celle du risque : clustering de volatilité, ARCH, GARCH, persistance, distributions à queues épaisses, asymétrie, prévisions de volatilité, VaR, Expected Shortfall et backtesting.

1. Commencez par le [PDF du CH03](../chapters/CH03/Trading_Intelligent_CH03_Volatilite_ARCH_GARCH_Tawfik_Masrour_v2.1.pdf).
2. Gardez à proximité la [fiche de référence — formules & définitions](../chapters/CH03/fiches/Trading_Intelligent_CH03_Fiche_Reference_Formules_Definitions_Tawfik_Masrour.pdf).
3. Exécutez **NB01** pour ARCH-LM, GARCH(1,1), persistance et diagnostics.
4. Revenez au chapitre pour Student-t, asymétrie, GJR-GARCH et prévisions.
5. Exécutez **NB02** sur la séparation chronologique train/test et l'évaluation hors échantillon de VaR/ES.
6. Le dataset de référence est [TI_CH03_Vol_Risk_v1.csv](../data/CH03/TI_CH03_Vol_Risk_v1.csv), identifiant `TI_CH03_VOL_RISK_V1`.

### Google Colab — CH03

- [NB01 — ARCH/GARCH & diagnostics](https://colab.research.google.com/github/MasrourTawfik/Textra-edu/blob/trading-intelligent/notebooks/CH03/CH03_NB01_ARCH_GARCH_Diagnostics_Tawfik_Masrour_STUDENT.ipynb)
- [NB02 — Asymétrie, VaR & ES](https://colab.research.google.com/github/MasrourTawfik/Textra-edu/blob/trading-intelligent/notebooks/CH03/CH03_NB02_Asymmetry_VaR_ES_Tawfik_Masrour_STUDENT.ipynb)
## Exécution dans Colab

Dans Colab, utilisez **Runtime → Run all**.

Les notebooks publics sont autonomes : s'ils ne trouvent pas leur CSV, ils disposent d'un mécanisme de reconstruction déterministe du dataset pédagogique. Ils ne dépendent d'aucun chemin Windows ou répertoire local caché.
