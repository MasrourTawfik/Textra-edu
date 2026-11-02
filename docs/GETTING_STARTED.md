# Démarrage rapide — Trading Intelligent

Le parcours publié comprend actuellement **CH01 v2.1**, **CH02 v4.0** et **CH03 v3.0**. Il est recommandé de les suivre dans cet ordre.

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

Après CH02, CH03 passe de la prévision du rendement moyen à la modélisation du risque : variance conditionnelle, regroupement de volatilité, ARCH/GARCH, queues épaisses, asymétries, VaR, Expected Shortfall et backtesting.

1. Lire le [cours progressif CH03 v3.0](../chapters/CH03/Trading_Intelligent_CH03_Cours_Progressif_Tawfik_Masrour_v3.0.pdf).
2. Consulter le [guide pédagogique du laboratoire](CH03_LAB_DEMARRAGE.md) et la [correspondance cours-expériences](CH03_LAB_CORRESPONDANCE.md).
3. Exécuter le [laboratoire intégral STUDENT](../notebooks/CH03/CH03_Laboratoire_Integral_Volatilite_Risque_Tawfik_Masrour_STUDENT.ipynb) : 38 expériences et 46 cellules Python, avec explications Markdown guidées.
4. Utiliser les données [marché synthétique](../data/CH03/TI_CH03_LAB_MARCHE_SYNTHETIQUE_V1.csv) et [scénarios manuels](../data/CH03/TI_CH03_LAB_SCENARIOS_MANUELS_V1.csv), décrites dans le [dictionnaire](../data/CH03/DATA_DICTIONARY.md).
5. Préparer la note de décision financière argumentée proposée en fin de laboratoire.

### Google Colab — CH03

- [Ouvrir le laboratoire intégral](https://colab.research.google.com/github/MasrourTawfik/Textra-edu/blob/trading-intelligent/notebooks/CH03/CH03_Laboratoire_Integral_Volatilite_Risque_Tawfik_Masrour_STUDENT.ipynb)

## Exécution dans Colab

Dans Colab, utilisez **Runtime → Run all**.

Les notebooks publics sont autonomes : s'ils ne trouvent pas leur CSV, ils disposent d'un mécanisme de reconstruction déterministe du dataset pédagogique. Ils ne dépendent d'aucun chemin Windows ou répertoire local caché.
