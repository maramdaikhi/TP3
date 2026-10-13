# TP3 - Les formulaires HTML

Ce dépôt contient les travaux pratiques sur la création et la validation des formulaires HTML5, réalisés dans le cadre du module de Développement Web.

## Questions

1. **Quelle est la différence entre name et id ?**
   - L'attribut `id` est un identifiant unique dans toute la page, utilisé par le CSS, le JavaScript et le `label` (via l'attribut `for`). L'attribut `name`, quant à lui, sert à identifier la donnée lors de l'envoi au serveur (c'est le nom de la variable transmise).

2. **Pourquoi utiliser post plutôt que get pour un mot de passe ?**
   - La méthode `get` affiche toutes les données saisies directement dans l'URL (en clair), ce qui est extrêmement dangereux pour des informations sensibles comme les mots de passe. En revanche, la méthode `post` envoie les données cachées dans le corps de la requête HTTP, ce qui garantit la sécurité de la saisie.