## Système de nomenclature CSS
- J'ai décidé de nommer mes sections en BEM avec le nom de la section elle-même pour faciliter la lisibilité. Le tout utilise une habitude constante de nomenclature pour éviter l'abondance.
--- 

## Variables CSS et design tokens (logique d’organisation)
- Pour le système de token, j'ai dû changer quelques valeurs de la maquette pour éviter qu'il y avait trop de valeurs. J'ai aussi décidé d'avoir des valeurs répétées en forme de classe pour qu'elles soient appliquées dans la classe de HTML au lieu de le répéter dans mon fichier CSS.
---

## Liste des composants réutilisables
- Liens de navigation
- Les boutons
- Les titres de section
- Les sous-titres de section
- Carte de programmation
- Badge de programmation
- Carte d'horaire
- Carte d'artiste
- Variante en vedette de carte d'artiste
- Carte de billets
- Carte de partenaires
- Carte de témoins
- Section de contact
- Liens de footer
---

## Decision flexbox pour les layouts complexes
- Pour les layouts plus complexes, j'ai établi des widths et heights en pourcentage pour la flexibilité de la page. En même temps, j'ai mis des gaps larges pour que rien ne soit en collision. Il y a des justify-content et des align-items qui sont en flex-start pour que le layout soit le même que sur la maquette.

## Defis et solutions
- J'ai eu de la difficulté à avoir l'exact même espacement entre les éléments qui sont sur la maquette. Comme solution, j'ai dû enlever certains gaps ou paddings ou changer la valeur pour que les distances soient les même.
