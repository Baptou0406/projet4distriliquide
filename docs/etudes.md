---
layout: default
nav_order: 4
title: Études et choix techniques
---

# Études et choix techniques

Cette partie présente les principaux choix techniques retenus pour le projet **Mix&Go**.

## Objectif technique

L’objectif est de concevoir un système capable de distribuer automatiquement plusieurs liquides dans des verres. Le système doit être compact, stable, précis et facilement automatisable.

## Plateau tournant

Pour positionner les verres, nous avons retenu un **plateau tournant**.

Il permet de placer plusieurs verres sur une même base et de les amener automatiquement sous la zone de distribution. Cette solution est compacte et adaptée à notre prototype.

## Distribution des liquides

La distribution se fait à l’aide de **pompes**.

Chaque pompe est reliée à un réservoir. Lorsqu’un verre est bien positionné, la pompe s’active pour envoyer le liquide dans le verre. Ce système permet de contrôler la quantité distribuée et de gérer plusieurs liquides différents.

L’objectif est d’utiliser **quatre réservoirs**, chacun associé à une pompe.

## Structure mécanique

La structure doit maintenir les réservoirs, les pompes et le plateau tournant.

Nous avons retenu une structure rigide, complétée par des pièces imprimées en 3D. Cela permet d’obtenir un montage stable, adaptable et simple à modifier.

## Automatisation

L’automatisation permet de coordonner la rotation du plateau et l’activation des pompes.

Des capteurs de position pourront être ajoutés pour vérifier que les verres sont correctement placés avant la distribution.

## Synthèse

| Élément | Choix retenu |
|---|---|
| Positionnement des verres | Plateau tournant |
| Distribution | Pompes |
| Nombre de réservoirs | 4 réservoirs |
| Structure | Structure rigide + impression 3D |
| Automatisation | Rotation du plateau + commande des pompes |
| Détection | Capteurs de position |

## Conclusion

Les choix techniques retenus permettent d’obtenir un système compact, automatisable et évolutif.
