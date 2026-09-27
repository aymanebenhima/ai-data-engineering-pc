# Section 2 : Le Cycle de Vie de l'Ingénierie des Données

## 1. Le Cycle de Vie
Pensez-y comme à **cuisiner un repas dans un restaurant**.

### 1. Génération (Les ingrédients)
Un client clique sur un bouton.
### 2. Ingestion (Transport)
- **Batch :** Déplacer de gros morceaux une fois par jour.
- **Streaming :** Déplacer instantanément.
### 3. Stockage (Le réfrigérateur)
- **Lacs de Données (Data Lakes) :** Données brutes.
- **Entrepôts de Données (Data Warehouses) :** Données nettoyées.
### 4. Transformation (Cuisiner)
Nettoyer et préparer les données.
### 5. Service (Servir le plat)
Donner les données aux Data Scientists et aux Analystes.

---

## 2. Les Courants Sous-jacents
- **Sécurité :** Cryptage et contrôle d'accès.
- **Gestion des Données :** Qui est propriétaire de la donnée ?
- **Orchestration :** La recette qui exécute les tâches dans le bon ordre (ex: Apache Airflow).

## 3. Exemples sur AWS
- Ingestion : AWS Kinesis.
- Stockage : Amazon S3.
- Transformation : AWS Glue.
- Service : Amazon Athena.
