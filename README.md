# synthese_traduction
La traduction automatique en chaine
Le projet de traduction en chaine a plus d’un objectif. Tout d’abord, il nous est utile de traduire automatiquement le contenu du corpus médiatique sur l’alimentation pour certaines analyses puisqu’il contient deux langues, en anglais et en français. Aussi, la mise en série de traduction d’une langue à une autre, puis d’un retour à la langue originale transforme la traduction automatique en une fonction de reformulation de phrase ; la production de paraphrase. Cette fonction peut servir à augmenter le nombre d’exemple pour l’entrainement d’un classificateur automatique qui utilise de l’apprentissage-machine supervisée. Il s’agit d’une manière de multiplier la valeur d’un ensemble de données qui aurait été manuellement catégorisé selon n’importe quelle grille d’analyse.
Le script est en format Python 3.10.8 notebook et le code est sectionné en blocs.
Il est recommande de rouler toutes les fonctions en ordre et de rouler ce code sur un échantillon du corpus complet pour évaluer le temps de traitement.
Les variables globales déclarées en début de code servent de paramètre qui peuvent être modifié selon les usages.
Il utilise le cadre de travail de Hugging face où sont déposés des modèles de langues tirés de différentes stratégies. 
Ce script utilise les modèles de type BERT et applique les contraintes de ce type de modèle (longeur maximale, type de lemmatisation etc.).
Pour consulter la documentation sur le flux de traitement consulter : https://huggingface.co/

Il est possible de modifier les modèles langues utilisé à même le code avec un plus récent.
Ce code est en construction pour l'exploitation d'un corpus sous license qui contraint sa diffusion.
