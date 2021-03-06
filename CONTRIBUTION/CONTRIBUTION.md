# Guide du contributeur

## Bienvenue

Victoire est un projet open-source, orienté vers la communauté.
Nous sommes toujours heureux de recevoir votre participation au développement du produit et toute aide est bienvenue, quelque soit votre niveau de maîtrise et serons très heureux de vous compter parmi la liste de nos chers [contributeurs](https://github.com/Victoire/Victoire/contributors)

## Gestion de projet

Nous utilisons le système natif d'[Issues](https://github.com/Victoire/victoire/issues) de github mais nous suivons quelques conventions:
- une issue doit être priorisée:
    - [Priority : Low](https://github.com/Victoire/victoire/labels/Priority%20%3A%20Low)
    - [Priority : Medium](https://github.com/Victoire/victoire/labels/Priority%20%3A%20Medium)
    - [Priority : High](https://github.com/Victoire/victoire/labels/Priority%20%3A%20High)
- une issue doit être catégorisée:
    - [Type : Bug](https://github.com/Victoire/victoire/labels/Type%20%3A%20Bug)
    - [Type : Feature](https://github.com/Victoire/victoire/labels/Type%20%3A%20Feature)
    - [Type : Technical debt](https://github.com/Victoire/victoire/labels/Type%20%3A%20Technical%20debt)

Les tags contextuels commencent par le caractère ~ (`tilde`), utilisez-les à votre convenance.

Pour une meilleure visibilité sur les différentes tâches liées à l'écosystème Victoire, nous utilisons [Waffle](http://waffle.io/Victoire/victoire), allez jeter un petit coup d'oeil !

## Poser une question

Vous pouvez posez vos questions et suivre celles liées à Victoire sur [StackOverflow](http://stackoverflow.com/questions/tagged/victoire)

## Commencer tranquillement

Si vous voulez aider mais que vous ne savez pas trop quelle tâche prendre, vous serez surement contents d'apprendre qu'il existe un tag contextuel recensant les tâches faisable sans d'expérience particulière sur Victoire, il s'agit des [~EasyPick](https://github.com/Victoire/victoire/labels/~EasyPick)

## Workflow

### Version Majeure

Lors de l'évolution de l'API externe de Victoire, notamment au niveau des Widgets et des BusinessEntities, un incrémentation majeur sera effectuée => `X.0.0`. 
Dans le cas des Widgets, une incrémentation majeur implique des changements à opérer dans chaque widget. Ceux-ci subieront eux aussi une incrémentation de leurs version majeure => `X.0.0`.

### Version mineure

L'équipe Core de Victoire travaille sur le ou les prochains Milestones et effectue ses Pull Request vers la branche `master`. Quand ces développements seront finalisés, une version mineure sera tagguée => `1.X.0`.

### Patche

Toute nouvelle fonctionnalité, amélioration ou correctif développé en dehors d'un milestone, par la communauté ou par l'équipe CORE doit faire l'objet d'une Pull Request vers les branches supportées, la branche la plus récente et la LTS le cas échéant. Une version de patch sera alors tagguée => `0.0.X`. Ces modifications seront récupérées lors de la création de la release mineure suivante => `1.X.0`.

## Road Map

Victoire étant un DCMS Open Source cela signifie qu’il est gratuit et que tout le monde peut avoir accès au code source et le modifier. De cette façon, notre CMS se base sur une importante communauté de développeurs et d’utilisateurs qui font évoluer le logiciel grâce à l’addition de nouveaux modules.

Pour permettre aux utilisateurs et / ou contributeurs d’avoir une vision de l’état d’avancement de Victoire, nous mettons à disposition une road map chargée de détailler les futures fonctionnalités prévues ainsi que les mises à jour - regroupées dans un planning.

