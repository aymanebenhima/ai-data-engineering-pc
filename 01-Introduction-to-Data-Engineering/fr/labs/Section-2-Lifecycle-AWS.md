# Laboratoire Section 2 : Le cycle de vie sur AWS

## Objectif
Mettre en place un cycle de vie d'ingénierie des données de base sur AWS.

## Lignes directrices
- Assurez-vous d'utiliser le niveau gratuit (Free Tier).
- Supprimez vos ressources à la fin !

## Configuration du Laboratoire
1. **Génération :** Utiliser un script Python pour générer de faux "clics".
2. **Ingestion :** Utiliser AWS Kinesis.
3. **Stockage :** Utiliser Amazon S3.

## Étapes
1. Ouvrez AWS et cherchez **S3**. Créez un bucket.
2. Cherchez **Kinesis Data Firehose**. Créez un flux de livraison vers votre bucket S3.
3. Exécutez le script Python pour envoyer les clics.
4. Vérifiez votre bucket S3 !
