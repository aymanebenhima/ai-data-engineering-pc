# Laboratoire Section 4 : Traduire les Exigences sur AWS

## Objectif
Implémenter un pipeline de données complet (Batch et Streaming).

## Pipeline Batch
1. Créez un bucket Amazon S3 pour les données brutes.
2. Configurez AWS Glue pour qu'il s'exécute chaque nuit.
3. Sauvegardez les données propres dans Amazon Redshift.

## Pipeline Streaming
1. Créez un flux Amazon Kinesis.
2. Connectez une fonction AWS Lambda. La fonction lira le clic en direct et l'écrira instantanément dans une base de données vectorielle.
