ur
# Bonjour

Aujourd'hui, nous allons apprendre les bases du C, le tout en français.

* Allons-y.

# Installation d'un compilateur

Pour commencer, nous allons installer GCC, qui va nous permettre de compiler nos programmes en C.

```bash
winget install BrechtSanders.WinLibs.POSIX.UCRT
```

Une fois l'installation terminée, vous pouvez vérifier que GCC fonctionne avec :

```bash
gcc --version
```

# Comment compiler un code

Pour compiler un fichier C, nous allons utiliser cette commande :

```bash
gcc c_fichier_nom.c -o exe_nom && .\exe_nom.exe
```

Alors, qu'est-ce que cette commande fait concrètement ?

Elle compile notre fichier C et crée un fichier exécutable avec le nom que nous avons indiqué après `-o`.

Ensuite, grâce à :

```bash
.\exe_nom.exe
```

nous lançons notre programme.

Le symbole `&&` est un opérateur qui signifie : **faire la deuxième commande seulement si la première a réussi**.

Donc ici :

```bash
gcc c_fichier_nom.c -o exe_nom && .\exe_nom.exe
```

on compile d'abord le programme, puis on le lance si la compilation s'est bien passée.

Vous allez retrouver ce genre d'opérateurs régulièrement pendant que vous apprendrez le C et les commandes du terminal.

# Notre premier programme

Nous allons maintenant créer notre premier programme en C :

```c
#include <stdio.h>

int main(void)
{
    printf("Hello, World");
    return 0;
}
```

Voyons ce que fait chaque partie.

```c
#include <stdio.h>
```

Cette ligne permet d'inclure la bibliothèque `stdio.h`.

Elle contient notamment la fonction `printf()`, qui nous permet d'afficher du texte dans le terminal.

```c
int main(void)
```

Ici, nous créons la fonction `main`.

Cette fonction est le point d'entrée de notre programme : c'est à partir d'elle que le programme commence son exécution.

Le `int` signifie que cette fonction va retourner un nombre entier.

Le `void` entre les parenthèses signifie que la fonction ne prend aucun paramètre.

```c
printf("Hello, World");
```

Ici, nous affichons `Hello, World` dans le terminal.

À retenir : en C, la plupart des instructions se terminent par un `;`.

```c
return 0;
```

Ici, nous indiquons que notre programme s'est terminé correctement.

`0` est généralement utilisé pour indiquer que tout s'est bien passé.

Plus tard, vous pourrez par exemple utiliser un autre nombre pour signaler une erreur.

# Comment lancer ce code

Imaginons que notre fichier s'appelle `main.c`.

Pour le compiler et le lancer, nous pouvons utiliser :

```bash
gcc main.c -o main && .\main.exe
```

Et voilà !

Si tout s'est bien passé, le programme va afficher dans le terminal :

```text
Hello, World
```

Aujourd'hui, nous allons apprendre les bases du C, le tout en français.

* Allons-y.

# Installation d'un compilateur

Pour commencer, nous allons installer GCC, qui va nous permettre de compiler nos programmes en C.

```bash
winget install BrechtSanders.WinLibs.POSIX.UCRT
```

Une fois l'installation terminée, vous pouvez vérifier que GCC fonctionne avec :

```bash
gcc --version
```

# Comment compiler un code

Pour compiler un fichier C, nous allons utiliser cette commande :

```bash
gcc c_fichier_nom.c -o exe_nom && .\exe_nom.exe
```

Alors, qu'est-ce que cette commande fait concrètement ?

Elle compile notre fichier C et crée un fichier exécutable avec le nom que nous avons indiqué après `-o`.

Ensuite, grâce à :

```bash
.\exe_nom.exe
```

nous lançons notre programme.

Le symbole `&&` est un opérateur qui signifie : **faire la deuxième commande seulement si la première a réussi**.

Donc ici :

```bash
gcc c_fichier_nom.c -o exe_nom && .\exe_nom.exe
```

on compile d'abord le programme, puis on le lance si la compilation s'est bien passée.

Vous allez retrouver ce genre d'opérateurs régulièrement pendant que vous apprendrez le C et les commandes du terminal.

# Notre premier programme

Nous allons maintenant créer notre premier programme en C :

```c
#include <stdio.h>

int main(void)
{
    printf("Hello, World");
    return 0;
}
```

Voyons ce que fait chaque partie.

```c
#include <stdio.h>
```

Cette ligne permet d'inclure la bibliothèque `stdio.h`.

Elle contient notamment la fonction `printf()`, qui nous permet d'afficher du texte dans le terminal.

```c
int main(void)
```

Ici, nous créons la fonction `main`.

Cette fonction est le point d'entrée de notre programme : c'est à partir d'elle que le programme commence son exécution.

Le `int` signifie que cette fonction va retourner un nombre entier.

Le `void` entre les parenthèses signifie que la fonction ne prend aucun paramètre.

```c
printf("Hello, World");
```

Ici, nous affichons `Hello, World` dans le terminal.

À retenir : en C, la plupart des instructions se terminent par un `;`.

```c
return 0;
```

Ici, nous indiquons que notre programme s'est terminé correctement.

`0` est généralement utilisé pour indiquer que tout s'est bien passé.

Plus tard, vous pourrez par exemple utiliser un autre nombre pour signaler une erreur.

# Comment lancer ce code

Imaginons que notre fichier s'appelle `main.c`.

Pour le compiler et le lancer, nous pouvons utiliser :

```bash
gcc main.c -o main && .\main.exe
```

Et voilà !

Si tout s'est bien passé, le programme va afficher dans le terminal :

```text
Hello, World
```
