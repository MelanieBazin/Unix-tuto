# Unix


## Activités préparatoires

[Activités DataCamp](activites-preparatoires/)


## Introduction

[Diapo](diapo/)


## Tutoriel *maison*

[Un aperçu rapide du *shell* Unix](tutoriel/).

Pour reproduire les exemples présentés, lancez les commandes suivantes au préalable :
```
$ cd
$ wget https://github.com/omics-school/unix/raw/master/demo/unix.tgz
$ tar zxvf unix.tgz
$ cd unix
```
Rappel : le `$` désigne l'invite de commande de votre *shell*. Il ne faut pas le taper.


## Tutoriel Software Carpentry

[Le cours de Software Carpentry](http://swcarpentry.github.io/shell-novice/) : parties 1, 2, 3, 4 et 7.
Le [mémo](http://swcarpentry.github.io/shell-novice/reference/) des notions abordées.

Pour faire les exercices de Software Carpentry, préparez les données nécessaires avec les commandes suivantes :
```
$ cd
$ wget http://swcarpentry.github.io/shell-novice/data/data-shell.zip
$ unzip data-shell.zip
```


## Installer un *shell* Linux sur sa machine

### Linux et Mac OS X

Si vous travaillez avec les systèmes d'exploitations Linux (Ubuntu, Mint, Debian...) ou Mac OS X, vous avez déjà un *shell* installé sur votre machine.

### Windows

Si vous travaillez avec Windows 10 :

- Vous pouvez installer très rapidement un *shell* Linux. Voici quelques liens pour y arriver :
    + <https://www.windowscentral.com/how-install-bash-shell-command-line-windows-10>
    + <https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/>
    + <https://www.howtogeek.com/265900/everything-you-can-do-with-windows-10s-new-bash-shell/>

- Depuis un *shell* Linux, votre répertoire utilisateur de Windows est accessible via le chemin
    ```
    /mnt/c/Users/<login-windows>```
    où `<login-windows>` est votre *login* sous Windows. Nous vous conseillons de travailler depuis ce répertoire afin que vos fichiers puissent également être visibles depuis Windows.

Si vous souhaitez simplement un logiciel sous Windows pour vous connecter au serveur du DU en SSH. Nous vous conseillons [MobaXterm](https://mobaxterm.mobatek.net/). La version [*Free*](https://mobaxterm.mobatek.net/download.html) est suffisante. Vous trouverez quelques vidéos de démo [ici](https://mobaxterm.mobatek.net/demo.html).

Pour copier / coller entre Windows et le *shell* Linux :

- Pour copier depuis Windows (<kbd>Ctrl</kbd>+<kbd>C</kbd>) puis coller dans le *shell* : clic droit de la souris.
- Pour copier depuis le *shell* (<kbd>Ctrl</kbd>+<kbd>Maj</kbd>+<kbd>C</kbd>) puis coller dans Windows (<kbd>Ctrl</kbd>+<kbd>V</kbd>)


## Bibliographie / webographie

Livre :

- [Bioinformatics Data Skills](http://shop.oreilly.com/product/0636920030157.do), Vince Buffalo, O'Reilly Media, 2015.

Sites internet :

- [The UNIX Shell](http://swcarpentry.github.io/shell-novice/), cours en ligne de *Software Carpentry*.
- [Unix Fondamentals](https://edu.sib.swiss/pluginfile.php/2878/mod_resource/content/4/couselab-html/content.html), du *Swiss Institute of Bioinformatics*.


## Licence

![](img/CC-BY-SA.png)

Ce contenu est mis à disposition selon les termes de la licence [Creative Commons Attribution - Partage dans les Mêmes Conditions 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/deed.fr) (CC BY-SA 4.0). Consultez le fichier [LICENSE](LICENSE) pour plus de détails.

This content is released under the [Creative Commons Attribution-ShareAlike 4.0 ](https://creativecommons.org/licenses/by-sa/4.0/deed.en) (CC BY-SA 4.0) license. See the bundled [LICENSE](LICENSE) file for details.
