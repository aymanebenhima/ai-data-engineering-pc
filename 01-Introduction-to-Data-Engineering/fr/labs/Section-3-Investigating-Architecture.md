# Laboratoire Section 3 : Analyser votre architecture sur AWS

## Objectif
Surveiller une application web et appliquer le cadre AWS Well-Architected.

## Surveillance de l'Application
1. Ouvrez **CloudWatch** dans AWS.
2. Regardez l'utilisation du CPU de votre serveur EC2. Si elle dépasse 80%, le serveur a du mal !

## Appliquer les Principes
Comment réparer un serveur lent ?
1. **Mise à l'échelle verticale (Vertical Scaling) :** Changer pour un serveur plus puissant (Cher).
2. **Mise à l'échelle horizontale (Horizontal Scaling) :** Utiliser l'Auto-Scaling pour lancer 5 petits serveurs lors des pics de trafic (Optimisation des coûts).
