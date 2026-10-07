# Guide étudiant — CH03 v2.1

Le CH03 associe un chapitre de référence, une fiche de formules et définitions, un dataset pédagogique et deux laboratoires complémentaires autour de la volatilité conditionnelle et du risque.

## Ordre conseillé

1. **Lire le chapitre jusqu'aux faits stylisés et au test ARCH-LM.**
2. **NB01 — ARCH/GARCH & diagnostics** : observer le clustering de volatilité, l'ACF des rendements au carré, tester l'hétéroscédasticité conditionnelle et estimer un GARCH(1,1).
3. Revenir au chapitre pour approfondir **persistance, variance de long terme, demi-vie, estimation QMLE et résidus standardisés**.
4. Étudier ensuite **Student-t, asymétrie, GJR-GARCH et prévision multi-horizon**.
5. **NB02 — Asymétrie, VaR & ES** : travailler sur une séparation chronologique train/test, produire de vraies prévisions one-step-ahead et évaluer VaR/ES hors échantillon.
6. Examiner les tests de couverture de Kupiec et d'indépendance de Christoffersen.
7. Terminer les exercices et la checklist méthodologique.

## Fiche de référence

La fiche rassemble les définitions et formules essentielles : variance conditionnelle, ARCH, GARCH, persistance, variance de long terme, demi-vie, QMLE, diagnostics, Student-t, GJR-GARCH, prévisions, VaR, ES, backtesting et QLIKE.

- [Ouvrir la fiche PDF](../chapters/CH03/fiches/Trading_Intelligent_CH03_Fiche_Reference_Formules_Definitions_Tawfik_Masrour.pdf)

## Ressources

- [PDF CH03](../chapters/CH03/Trading_Intelligent_CH03_Volatilite_ARCH_GARCH_Tawfik_Masrour_v2.1.pdf)
- [Dataset CH03](../data/CH03/TI_CH03_Vol_Risk_v1.csv)
- [NB01 dans Colab](https://colab.research.google.com/github/MasrourTawfik/Textra-edu/blob/trading-intelligent/notebooks/CH03/CH03_NB01_ARCH_GARCH_Diagnostics_Tawfik_Masrour_STUDENT.ipynb)
- [NB02 dans Colab](https://colab.research.google.com/github/MasrourTawfik/Textra-edu/blob/trading-intelligent/notebooks/CH03/CH03_NB02_Asymmetry_VaR_ES_Tawfik_Masrour_STUDENT.ipynb)

## Règles méthodologiques à retenir

- Une volatilité conditionnelle est **latente** : les rendements au carré ou absolus sont des proxys, pas la volatilité elle-même.
- Une forte persistance GARCH ne signifie pas nécessairement que le régime de marché restera stable indéfiniment.
- Sous Student-t, le paramètre `nu` contrôle l'épaisseur des queues ; `nu > 2` est nécessaire pour une variance finie.
- L'estimation et l'évaluation doivent respecter strictement le temps : le futur ne doit jamais entrer dans l'ajustement du modèle.
- Un taux global de dépassements VaR correct ne suffit pas ; les exceptions doivent également être examinées dans le temps.
- `true_sigma` est un oracle pédagogique du dataset synthétique, jamais une feature réaliste à donner au modèle.

Les versions publiques ne contiennent ni solutions privées, ni notebooks MASTER, ni notes enseignant.
