# Engager un polynome

Un engagement polynomial lie un prouveur a un polynome sans publier tous ses coefficients.
Il permet ensuite d ouvrir une evaluation en un point avec une preuve compacte.
Le verificateur controle que la valeur annoncee est compatible avec l engagement initial.
Cette primitive relie l arithmetisation d un calcul aux preuves succinctes de type SNARK.
Le trait PolynomialCommitment uniformise setup, trim, commit, open, check et variantes batch.
Les polynomes et points sont etiquetes afin d eviter les collisions logiques entre requetes.
Le depot prend en charge plusieurs familles avec des hypotheses cryptographiques differentes.

Suite : [02 — KZG, Marlin et SRS](02-kzg-marlin-et-srs.md).
