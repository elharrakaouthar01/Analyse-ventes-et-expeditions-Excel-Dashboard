# Dictionnaire de données

Fichier : `Base_de_donnees_et_KPI.xlsx`

## Feuille `Base de données` (369 lignes × 27 colonnes, année 2021)
Une ligne = un produit commandé.

| Groupe | Colonnes |
|---|---|
| Commande | N° Cmde, Date Cdme, Type Paiment |
| Client | N° Client, Nom Client, Adresse, Ville, Departement, Code Postal, Provinces |
| Commercial | Commerciaux, Region |
| Expédition | Shipped Date, Shipper Name, Ship Name, Ship Address, Ship City, Ship State, Ship ZIP/Postal Code, Ship Country/Region, Frais Expédition, JOURS |
| Produit | Nom Produit, Categories, Prix Unitaire, Quantité, Revenue |

- `JOURS` : délai de livraison en jours.
- `Revenue` : chiffre d'affaires de la ligne.
- Valeurs manquantes : `Shipped Date` (78), `Shipper Name` (39), `Type Paiment` (102), `Nom Produit` et `Categories` (3).

## Autres feuilles (référentiel de KPI)
| Feuille | Contenu |
|---|---|
| `Questions` | 7 KPI retenus pour le projet (formule, source, fréquence, service responsable) |
| `KPI Commerciales` | KPI commerciaux (prospection, conversion, fidélisation, NPS...) |
| `KPI RH` | KPI ressources humaines |
| `Finance` | KPI financiers (marge, EBIT, ROE, ROI...) |
| `Achat et logistique` | KPI achats, stocks et transport |

Données fictives.
