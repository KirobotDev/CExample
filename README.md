# Apprendre le C en français

Bienvenue sur ce dépôt !

Le but de ce projet est d'apprendre les bases du **langage C**, en français, avec des explications simples et des exemples faciles à comprendre.

Je vais essayer d'expliquer les choses comme j'aurais aimé les trouver quand j'ai commencé.

## 📚 Contenu

Le cours va progressivement aborder :

* Installation de l'environnement
* Compilation d'un programme
* `printf`
* Variables
* Types
* Conditions
* Boucles
* Fonctions
* Tableaux
* Chaînes de caractères
* Pointeurs
* Structures
* Fichiers
* Allocation mémoire
* Et d'autres notions du C

Le contenu sera ajouté au fur et à mesure.

## 🛠️ Prérequis

Pas besoin d'être un expert en programmation pour commencer.

Il vous faut simplement :

* Un ordinateur
* Un compilateur C
* Un éditeur de texte ou un IDE
* Un peu de motivation

Le cours utilise **GCC** pour compiler les programmes.

## 🚀 Commencer

Commencez par le premier cours :

**[Introduction au C](./cours/01-introduction.md)**

Puis avancez progressivement dans les différents cours.

## 💻 Exemple

Voici à quoi ressemble un programme C très simple :

```c
#include <stdio.h>

int main(void)
{
    printf("Hello, World\n");
    return 0;
}
```

Pour le compiler avec GCC :

```bash
gcc main.c -o main
```

Puis pour le lancer sous Windows :

```bash
.\main.exe
```

## 🎯 Objectif

L'objectif n'est pas simplement de copier du code.

Essayez de comprendre **pourquoi** le code fonctionne et ce que chaque ligne fait.

Si quelque chose n'est pas compris, prenez le temps de chercher et de tester par vous-même.

## 🤝 Contributions

Si vous trouvez une erreur, une faute d'orthographe ou une explication qui pourrait être améliorée, vous pouvez ouvrir une **issue** ou proposer une **pull request**.

Les contributions sont les bienvenues.

## 📄 Licence

Ce projet est distribué sous licence MIT.

Voir le fichier [`LICENSE`](./LICENSE).

---

Fait avec du C et beaucoup de `;`.
