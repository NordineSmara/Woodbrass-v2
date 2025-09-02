# Woodbrass-v2
## Nom de l'entreprise :
Hurst 
## Le site vend :
meubles
## Quelles sont les principales entités (tables) de la base de données ?
User > Cart : un utilisateur peut avoir panier 
product
cart 
ProductCart

User > Cart : un utilisateur peut avoir 

Cart > ProductCart : un panier peut contenir plusieurs produits via la table de liaison

Product > ProductCart : un produit peut apparaître dans plusieurs paniers via ProductCart.

ProductCart > table de liaison entre Product et Cart (relation Many-to-Many).

