# Batching des ouvertures

Plusieurs polynomes peuvent etre engages ensemble tout en conservant leurs degres propres.
Les requetes associent chaque etiquette a un ou plusieurs points d evaluation.
Le prouveur combine des ouvertures avec des challenges issus d un sponge cryptographique.
Le batch reduit la taille et le cout de verification par rapport a des preuves independantes.
Cette aggregation exige un transcript sans ambiguite et un ordre canonique des elements.
Les evaluations fournies au verificateur doivent couvrir exactement le QuerySet annonce.
Une erreur de domaine ou de label peut invalider la liaison entre preuve et statement.

Suite : [04 — Familles sans KZG](04-familles-sans-kzg.md).
