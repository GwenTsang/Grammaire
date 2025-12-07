# Grammaire

Nous testons la performance de différents modèles pour une tâche de détection d'erreurs grammaticales dans des phrases / paragraphes ayant des longueurs variables et toujours rédigés en français.

## Données

Le fichier `correct_sentences.csv` contient 790 phrases grammaticalement correctes. Elles peuvent avoir d'autres fautes, mais, normalement, pas de fautes d'accord ou de syntaxe.

Le fichier `incorrect_sentences.csv` contient, au contraire, des phrases ayant au moins une faute d'accord ou une faute de syntaxe.

## Résultats

On note que les différents modèles testés fonctionnent très mal pour **cibler** un sous type spécifique d'erreur grammaticale.
A notre connaissance, il n'existe aucun modèle qui réalise précisément la tâche recherchée (rupture de coréférence due à un mauvais accord grammatical dans des phrases en français).

