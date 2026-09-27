# Section 4 : Traduire les Exigences en Architecture

## 1. Gestion des Parties Prenantes
Une partie prenante est toute personne qui s'intéresse à vos données (Manager, Marketing, Data Scientist).

- **Marketing :** S'intéresse aux revenus (Exigences fonctionnelles - ce que fait le système).
- **Ingénieurs :** S'intéressent aux performances et à la vitesse (Exigences non fonctionnelles - comment le système le fait).

## 2. Système de Recommandation
Exemple pratique :
- Le Data Scientist a besoin de l'historique d'achat (Batch) et des clics en temps réel (Streaming).
- **Base de données vectorielle :** Utilisée pour des recherches très rapides en IA.

### Résumé du Pipeline (De bout en bout)
1. **Pipeline Streaming :** Pour capturer les clics en direct du client.
2. **Pipeline Batch :** Pour analyser l'historique d'achat pendant la nuit.
3. **Service (Serving) :** Combiner les deux pour afficher instantanément des produits recommandés à l'utilisateur !
