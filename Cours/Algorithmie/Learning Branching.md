pas de surcoût (stockage/mémoire) associé aux branches
facile de diviser

positionner sur la branche avec

```
git checkout [nom]
```

## ==Branches et Merges==

pour combiner le contenu de deux branches est 

```
git merge
```

`merge` («fusionner»)

```
git checkout [nom]; git merge [nom]
```

## ==Git Rebase==

```
git rebase main
```

## ==Se déplacer dans Git==

Head représente l'utilisateur 

```
git checkout [Commit]
```

## ==Références relatives==

utiliser `git log` pour connaître les identifiants.

**Les commits relatifs :**

- Revenir d'un commit en arrière avec `^`
- Revenir de plusieurs en arrière avec `~<num>`

Ainsi, `main^` est équivalent à "le premier parent de `main`".

`main^^` est le grand-parent (ancêtre de seconde génération) de `main`

on peut aussi utiliser `HEAD` comme une référence relative.

### ==L'opérateur "~"==

l'opérateur tilde (~) permet de ne pas utiliser ^ plusieurs fois.


réassigner les branches à un commit avec l'option `-f`

`git branch -f main HEAD~3`

bouge (de force) la branche main à trois parents derrière HEAD.

```
git branch -f main HEAD~3
```

## ==Annuler des changements avec Git==

deux façons d'annuler des changements avec Git : 

`git reset` et l'autre est `git revert`

```
git reset HEAD~1
```

```
git revert HEAD
```

## ==Déplacer votre travail==

La première commande de cette série est `git cherry-pick`. Elle s'utilise ainsi :

- `git cherry-pick <Commit1> <Commit2> <...>`

```
git cherry-pick [Commit] [Commit]
```

## ==Git Interactive Rebase==

Tout rebase interactif signifie utiliser la commande `rebase` avec l'option `-i`
Vous pouvez omettre certains commits. Cela est désigné par `pick`

```
git rebase -i HEAD~4
```

git rebase -i main C4
git rebase bugFix main

git rebase -i HEAD~2
git commit 
git rebase -i HEAD~2  
git rebase caption main

git commit

$ git checkout o/main

$ git commit




git clone

local branch "main" set to track remote branch "o/main"

$ git fakeTeamwork 2

$ git commit

$ git pull

git commit

$ git commit

$ git push



git clone
git fakeTeamwork
git commit
git pull --rebase
git push


git reset --hard o/main

Le comportement par défaut est un --hard reset, soyez libre d'omettre cette option !

$ git checkout -b feature C2

$ git push origin feature



git fetch

$ git rebase o/main side1

$ git rebase side1 side2

$ git rebase side2 side3

$ git rebase side3 main

$ git push



git checkout main

$ git pull

$ git merge side1

$ git merge side2

$ git merge side3

$ git push