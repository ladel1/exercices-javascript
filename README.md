# 🚀 Exercices JavaScript - Débutant à Avancé

Ce dépôt contient une collection d'exercices JavaScript classés du niveau débutant au niveau avancé. Chaque exercice vous permet de pratiquer différentes facettes du langage. La solution complète est cachée dans un seul bloc de code à la fin de ce document.

---

## Table des Matières

- [Exercices Débutant](#exercices-débutant)
- [Exercices Intermédiaire](#exercices-intermédiaire)
- [Exercices Avancé](#exercices-avancé)
- [Corrections](#corrections)

---

## 🔹 Débutant (20 Exercices)

### 1. Afficher "Hello, World!" dans la console
```javascript
// Écrivez votre code ici
```
<details>
  <summary>Solution</summary>

  ```javascript
  console.log("Hello, World!");
  ```
</details>

### 2. Déclarer deux variables et les additionner
```javascript
// Écrivez votre code ici
```
<details>
  <summary>Solution</summary>

  ```javascript
  let a = 5, b = 10;
  console.log(a + b);
  ```
</details>

### 3. Vérifier si un nombre est pair ou impair
```javascript
// Écrivez votre code ici
```
<details>
  <summary>Solution</summary>

  ```javascript
  function pairOuImpair(n) {
      return n % 2 === 0 ? "Pair" : "Impair";
  }
  console.log(pairOuImpair(7));
  ```
</details>

### 4. Trouver le maximum entre trois nombres
```javascript
// Écrivez votre code ici
```
<details>
  <summary>Solution</summary>

  ```javascript
  function maxTrois(a, b, c) {
      return Math.max(a, b, c);
  }
  console.log(maxTrois(3, 7, 9));
  ```
</details>

### 5. Inverser une chaîne de caractères
```javascript
// Écrivez votre code ici
```
<details>
  <summary>Solution</summary>

  ```javascript
  function inverser(chaine) {
      return chaine.split('').reverse().join('');
  }
  console.log(inverser("JavaScript"));
  ```
</details>

### 6. Calculer la somme des éléments d’un tableau
```javascript
// Écrivez votre code ici
```
<details>
  <summary>Solution</summary>

  ```javascript
  function sommeTableau(tab) {
      return tab.reduce((acc, val) => acc + val, 0);
  }
  console.log(sommeTableau([1, 2, 3, 4, 5]));
  ```
</details>

### 7. Générer un nombre aléatoire entre 1 et 100
```javascript
// Écrivez votre code ici
```
<details>
  <summary>Solution</summary>

  ```javascript
  function nombreAleatoire() {
      return Math.floor(Math.random() * 100) + 1;
  }
  console.log(nombreAleatoire());
  ```
</details>

### 8. Compter le nombre de voyelles dans une chaîne
```javascript
// Écrivez votre code ici
```
<details>
  <summary>Solution</summary>

  ```javascript
  function compterVoyelles(chaine) {
      return (chaine.match(/[aeiouy]/gi) || []).length;
  }
  console.log(compterVoyelles("Programmation"));
  ```
</details>

### 9. Vérifier si une année est bissextile
```javascript
// Écrivez votre code ici
```
<details>
  <summary>Solution</summary>

  ```javascript
  function estBissextile(annee) {
      return (annee % 4 === 0 && annee % 100 !== 0) || (annee % 400 === 0);
  }
  console.log(estBissextile(2024));
  ```
</details>

### 10. Trouver le plus petit élément d’un tableau
```javascript
// Écrivez votre code ici
```
<details>
  <summary>Solution</summary>

  ```javascript
  function minTableau(tab) {
      return Math.min(...tab);
  }
  console.log(minTableau([3, 7, 2, 9, 5]));
  ```
</details>

### 11. Vérifier si un mot est un palindrome

```javascript
// Écrivez votre code ici
```
<details>
  <summary>Solution</summary>

  ```javascript
  function estPalindrome(mot) {
      let nettoye = mot.toLowerCase().replace(/[^a-z0-9]/g, '');
      return nettoye === nettoye.split('').reverse().join('');
  }
  console.log(estPalindrome("radar"));
  ```
</details>

