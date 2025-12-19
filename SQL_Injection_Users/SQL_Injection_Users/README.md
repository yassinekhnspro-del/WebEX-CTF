# SQL Injection – Users

## Description
Injection SQL de type UNION permettant l’extraction de mots de passe hashés.

## Étapes
1. Test UNION SELECT
2. Extraction du champ countersign
3. Récupération des hashs

## Remédiation
- Requêtes préparées
- Validation des entrées
