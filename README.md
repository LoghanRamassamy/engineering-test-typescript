# Exercice : Transformation et Analyse de Phrases (Version Modifiée)

### Étapes de l'Exercice

1. **Nettoyage et Transformation :**
   - Nettoyez chaque phrase en supprimant les espaces et en mettant tout en minuscules.
   - Supprimez les doublons et filtrez les valeurs `undefined` du tableau.

2. **Anagrammes :**
   - Pour chaque paire de phrases, déterminez si elles sont des anagrammes l'une de l'autre.

3. **Récupération des Chaînes de Longueur Paire :**
   - Identifiez et extrayez les phrases transformées qui ont une longueur paire.

4. **Application d'une Fonction :**
   - Appliquez une fonction donnée à chaque élément du tableau de phrases transformées.

### Exemple de donnée

```javascript
// Data
const phrases = [
    "A gentleman", 
    "Elegant man", 
    "Hello World", 
    undefined, 
    "a gentleman", 
    " "
];
```

### Explications

- **Nettoyage et Transformation :** Les phrases sont nettoyées pour supprimer les espaces, mettre en minuscules, éliminer les doublons et filtrer les valeurs `undefined`.
  
- **Anagrammes :** Vérification des anagrammes entre chaque paire de phrases nettoyées.
  
- **Récupération des Chaînes de Longueur Paire :** Les phrases nettoyées ayant une longueur paire sont extraites.

- **Application d'une Fonction :** Une fonction d'exemple est appliquée à chaque caractère des chaînes de longueur paire, convertissant chaque caractère en son code ASCII et ajoutant 10, avant de retourner les résultats modifiés.
