# Grammaire

Nous testons la performance de différents modèles pour une tâche de détection d'erreurs grammaticales dans des phrases en français.

## Données

Le fichier `correct_sentences.csv` contient 790 phrases grammaticalement correctes. Elles peuvent avoir d'autres fautes, mais, normalement, pas de fautes d'accord ou de syntaxe.

Le fichier `incorrect_sentences.csv` contient, au contraire, des phrases ayant au moins une faute d'accord ou une faute de syntaxe.
Ces phrases ont été rédigées par des étudiants et ont des longueurs variables.

## Résultats

On note que les différents modèles testés fonctionnent très mal pour **cibler** un sous type spécifique d'erreur grammaticale.
A notre connaissance, il n'existe aucun modèle qui réalise précisément la tâche recherchée (détection d'erreur de coréférence sur des phrases en français).

