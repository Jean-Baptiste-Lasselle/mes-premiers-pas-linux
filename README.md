
# Mes Premiers Pas Linux

Dans les équipes dans lesquelles je travaille, je collabore avec des professionnels qui ne sont pas du secteur de l' `IT` (Information Technologies).

Parfois, il arrvie que ce soit mes équipes, qui gèrent le poste utilisateur de ces professionnels "`non-IT`".
Et en toute circonstances, je fixe à mes équipes l'objectif `100 %` de popstes utilsiateurs (téléphones et tablettes comprises), sous un `OS` Linux, quelque soit la distribution.

Lorsque mes équipes font passer un de ces collaborateurs, d'un poste Windows, à un poste Linux, un plan de formation est inclut dans le plan de conduite du changement (Change Management).

Ce repo constitue un support de formation dans le cadre de plans de formations, eux-mêmes incluts dans de tels plans de conduite du changement :  "Migration Linux des postes utilisateurs"

Il s'agit d'une suit de tutoriels, destinés au périmètre des collaborateurs `non-IT`, dfestinés à les familiariser avec l'utilisation de leur nouveau poste Linux. 

Les formations sont faites sur des postes `Debian Stretch - GNOME`

Ce tutoriel propose une approche de la technologie Linux spécifiquement destinée aux professionnels non-issus du secteur des technologies de l'information.

Cette approche a ceci de caractéristique qu'elle propose à ces professionels une approche que je qualifie de `git-first approach` :  Là où l'écrasante majorité de notre corporation considèrerait probablement qu'un logiciel tel que `git`, est absolument inabordable pour le personnel "`non-IT`", je me demande si cet à priori ne serait pas une erreur qui nous fait manquer quelque chose... de valeur.

> "Believe me, Linux is nothing, compared to Git."
_Linus Torvalds_ 
_(Et je suis entièrement d'accord avec lui)_


C'est le sens de cette expérience : Si l'on écoute dire Linus Torvalds, `Git`, est plus fort en nouveau concept, que Linux. Avec les enfants, les concepts les plus difficiles, doivent être apportés au plus jeune, pour mûrir.

Alors il peut-être tmeps de démarrer les initiations Linux, en commençant par `Git` au plus tôt.


## MEMENTO #! Shell/sh/bash/bin

Notions de systèmes de fichiers : 

| Commande | Acronyme de  | Effet | Exemple |
| ---| ---| ---| ---|
| ```bash pwd ``` | `**P**rint **W**orking **D**irectory` | affiche le chemin absolu du répertoire dans lequel vous vous trouvez. | ccc |
| ```bash cd ``` | `Change Directory` | ccc | ccc |
| ```bash mkdir ``` | `**m**a**k**e **dir**ectory` | créée le répertoire avec un nom à préciser. | ```bash mkdir /home/beatrice/dossier_commercial_euronextltd  ``` crééera le répertoire de nom `dossier_commercial_euronextltd` dans le réertoire `/home/beatrice` |
| ```bash ls ``` | `list` | affiche la liste des fichiers et répertoires présents dans un répertoire à préciser. Si aucun nom de répertoire n'est précisé, c'est le contenu du réertoire courant qui est listé. | ```bash ls -allh /home/beatrice ``` |
| ```bash git clone URL_REPO_GIT ``` | ccc | ccc | ccc |
| ```bash # vous modifiez des fichiers textes ``` | ccc | ccc | ccc |
| ```bash git add --all ``` | ccc | ccc | ccc |
| ```bash git commit -m "votre message pour ce commit" ``` | ccc | ccc | ccc |
| ```bash git push ``` | ccc | ccc | ccc |


## Exercices

### Exercice 1 : systèmes de fichiers


### Exercie 2 : `tree`

`tree` est un logiciel. Il est possible de l'installer sous votre machine Linux, avec la commande : 

_Intallation_

```bash
sudo apt-get install -y tree
```


_Utilisation_

Exécutez une par une, les lignes ci-dessous.
Si une ligne provoque une erreur, passez à la suivante, san la ré-essayer.

```bash
ls 
tree
tree .
mkdir torvaldsgitfirst
ls -allh torvaldsgitfirst
pwd
cd torvaldsgitfirst
pwd
tree
mkdir rep2
tree
mkdir rep1/rep3
tree
mkdir rep1
tree
mkdir rep5/rep9
tree
mkdir -p rep5/rep9
tree
```




### Exercice 3 : bitbucket repo privé + cycle git local


