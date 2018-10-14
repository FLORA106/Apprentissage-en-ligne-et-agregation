# Apprentissage-en-ligne-et-agregation

L'apprentissage en ligne est une méthode de machine learning dans laquelle les données sont révélées au fur et à mesure du processus d'apprentissage plutôt que sous la forme d'un échantillon donné une fois pour toutes. 

Dans ce projet, nous avons implémenté l'algorithme de clustering en ligne PAC-Bayesien présenté dans l'article suivant : https://hal.inria.fr/hal-01264233v1

Face aux flux de données à haute fréquence, le clustering soulève des pièges théoriques et algorithmiques. Dans le cadre d’une hypothèse de parcimonie, un nouvel algorithme de clustering en ligne est introduit. La procédure repose sur l'approche PAC-Bayésienne, permettant une estimation dynamique (c'est-à-dire dépendant du temps) du nombre dde clusters. Dans cet article, ses mérites théoriques sont supportés par les sparsity regret bounds et une implémentation basée sur le RJMCMC appelé PACO est proposée ainsi que des expériences numériques pour évaluer son potentiel.

Nous avons ainsi l'algorithme PACO. Dans le répertoire, vous trouverez le code sous Python et notre présentation powerpoint.

