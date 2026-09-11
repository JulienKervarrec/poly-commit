# KZG, Marlin et SRS

KZG represente l evaluation polynomiale dans des groupes avec couplage bilineaire.
Sa concision depend d une chaine de reference structuree contenant des puissances secretes.
La variante Marlin ajoute le controle de degre, le batching et un masquage optionnel.
Le trim derive des cles adaptees aux bornes de degre sans refaire le setup universel.
Une SRS toxique ou mal generee compromet l extractabilite attendue du systeme.
Les etiquettes et bornes doivent rester coherentes entre commit, open et verification.
Le code distingue le KZG bas niveau du schema Marlin implementant le trait commun.

Suite : [03 — Batching des ouvertures](03-batching-des-ouvertures.md).
