# CTF

Vous allez avoir des énigmes à élucider selon des domaines vus en cours. Il y a des challenges plus ou moins bien 'payés' (comprenez que l'annotation montera selon les challenges résolus). Cependant je vous invite à suivre le fil comme proposé ci dessous. 

Si vous resté bloqué sur un challenge plus de 30mn:

* vous aurez un joker à savoir une (petite) aide de ma part
* les points remportés seront moindre si demande d'aide
* si malgré tout vous n'arrivez pas à résoudre le challenge, passez au suivant (max 45mn en tout)

Au delà de trouver les solutions, je vous demande de documenter vos investigations. Comment avez vous trouvé des pistes? quelles commandes ont été utilisées? C'est tout aussi important que de résoudre les challenges en eux mêmes. Un conseil, documentez au fur et à mesure pour ne pas avoir à revenir sur vos recherches.

Enfin à chaque fois, il y a un flag à indiquer (la réponse). Respectez bien le format demandé.


## (OSINT) Le soldat

1/ Quel est le prénom du soldat considéré comme étant le dernier soldat français mort sur le sol français avant l'armistice ?
2/ Quel est son numéro matricule ?

Format du flag : NBCTF{françois_752}

## (FORENSIC) Obus

-> fichier `champ_de_mines.obus` en pj 

Vous connaissez l'extension .obus ? Personnellement non... Cependant, nous savons que le fichier contient des informations textuelles parmi ce champ de mines.

Trouvez les informations cachées dans ce fichier !

## (FORENSIC) Le méchant Hacker

-> fichier `HACKED_BY_GliTcHMaSt3r69.odt` en pj

Le système informatique de <?> a été piraté et tous les fichiers ont été chiffrés. Le pirate a laissé une demande de rançon sous la forme d'un fichier odt. Nous aimerions que vous fassiez parler ce fichier. Est-ce que le pirate aurait laissé par inadvertance des informations permettant de l'identifier ?

Trouvez le logiciel, son numéro de version ainsi que le système d'exploitation utilisé pour créer ce fichier.

Format du flag attendu : NBCTF{<nom_logiciel>/$<systeme_dexploitation>}

Exemple de flag attendu : NBCTF{Paint/14.0.4.2$Windows10_X86_64}
