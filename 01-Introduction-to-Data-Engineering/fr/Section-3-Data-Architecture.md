# Section 3 : Architecture des Données

## 1. Qu'est-ce que l'Architecture des Données ?
La conception des systèmes qui stockent et déplacent vos données. L'architecte dessine les plans !

### La loi de Conway
Si 3 équipes ne se parlent jamais, elles construiront 3 bases de données isolées !

## 2. Batch vs Streaming
- **Batch :** Traitement groupé (comme faire la lessive une fois par semaine). Moins cher et plus facile à construire.
- **Streaming :** Traitement immédiat en temps réel. Ultra rapide mais plus cher.

## 3. Choisir les Technologies
- **Monolithe :** Un outil massif qui fait tout.
- **Microservices :** De petits outils qui se connectent (comme des Lego).

## 4. Cadre AWS Well-Architected
Évaluez votre architecture sur AWS selon 6 piliers :
1. Excellence opérationnelle
2. Sécurité
3. Fiabilité (Reliability - Que se passe-t-il si un serveur tombe en panne ?)
4. Efficacité des performances
5. Optimisation des coûts
6. Durabilité
