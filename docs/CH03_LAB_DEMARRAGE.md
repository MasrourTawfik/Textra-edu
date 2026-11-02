# Bienvenue dans le laboratoire CH03

**Notre objectif est de comprendre avant de programmer.** Vous n'avez pas besoin de connaître GARCH, Student-t ou la vraisemblance pour commencer. Chaque notation est construite à partir d'une expérience.

## Votre première séance (conseil)

1. Ouvrez le notebook `..._STUDENT.ipynb` dans JupyterLab, Jupyter Notebook ou Google Colab (importer le fichier).
2. Exécutez les cellules dans l'ordre, à partir de « Environnement scientifique minimal ».
3. Avant chaque bloc Python, lisez la partie **« Avant Python — sur le papier »** : écrivez votre réponse, puis confrontez-la au résultat.
4. Lisez le paragraphe **« À observer »** sans chercher uniquement le résultat numérique. Expliquez ce que signifient les axes, les signes et les unités.
5. Répondez aux **arrêts de compréhension** et aux 12 questions de la dernière section, avec vos propres mots.
6. Si une erreur d'exécution apparaît après des manipulations, redémarrez le noyau et exécutez toutes les cellules du haut vers le bas.

Les données sont fabriquées par le notebook : aucune connexion à Internet ni téléchargement de prix financiers n'est nécessaire. Les fichiers CSV livrés servent à vérifier, exporter ou travailler ailleurs.

## Ce que signifient les unités

- `rendement_pct = 2` représente **+2 %**, soit `0.02` en convention décimale.
- `variance_pct2 = 4` représente une variance de **4 en unités de pourcentage au carré**.
- `volatilite_pct = 2` est l'écart-type en **pourcentage**.
- `perte_signee_DH = 2 000` désigne une perte, alors qu'une valeur négative désigne un gain, selon la convention du notebook.

## Indicateurs de qualité

Avant de dire qu'un modèle « fonctionne », vérifiez les données auxquelles il a eu accès, les diagnostics des résidus, la taille de l'échantillon de test et le rôle exact de chaque p-value. Les résultats simulés ne constituent pas un conseil d'investissement.
