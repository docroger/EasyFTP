# EasyFTP
FTP client

:::::::::::::::::::::::

EsasyFTP 1.8
------------
2025 - Docno
Windows 10/11 = x64
DonationWare

Client FTP léger qui permet de transferer des fichiers depuis/vers PC <> serveur distant.
Basé sur LibCurl.

Permet de :
 -copier (fichiers/dossiers)
 -créer des dossiers
 -supprimer (fichiers/dossiers)
 -renommer
 -lister les fichiers du répertoire distant.


Utilisation :
-----------

Menu RAZ = remise à zéro du log (zone d'affichage des infos en jaune)

Onglet Connexion :
================
Permet de paramétrer l'accès a un site.
Cliquer sur le bouton Options pour afficher un menu.
 -Nouveau : crée un nouveau site
 -Ajouter : enregistre le nouveau site
 -Modifier : enregistre les modifications
 -Supprimer : détruit un site

Dans le champs Site : entrer le nom du site (ex : monsitefree)
 -FTP : l'adresse FTP donnée par le fournisseur (ex :ftpperso.free.fr)
 -Port : en général 21 ou donné par le fournisseur
 -Login : l'identifiant (ou cocher anonyme)
 -Password : mot de passe

Une fois le site paramétré, cliquer sur le grand bouton connexion.
Il s'affiche la liste des fichiers du site dans l'onglet DISTANT.

Cliquer de nouveau sur le grand bouton pour deconnexion (cloturer la connexion).

Onglet Distant :
============== 
Liste les fichiers sur le serveur distant.
Double clic sur le nom d'un dossier pour parcourir l'arborescence.
Cliquer sur .. pour remonter.
Cliquer avec bouton droit pour afficher le menu contextuel.
 -Nouveau répertoire : crée un dossier.
 -Renommer : le fichier sélectionné.
 -Supprimer : les fichiers sélectionnés sur le serveur.
 -Copier >> DISTANT : les fichiers sélectionnés du serveur seront copiés dans le dossier affiché dans l'onglet distant.

La sélection multiple est possible (associé avec CTRL ou SHIFT).

Sélectionner le répertoire destination pour y copier des fichiers du PC.

Onglet Local :
============
Affiche les fichiers du dossier local (PC).
Bouton droit pour le menu contextuel.
 -Répertoire : permet de choisir un dossier ou un disque sur le PC
 -Copier >> LOCAL : les fichiers sélectionnés du PC seront copiés dans le dossier affiché dans l'onglet DISTANT.

Sélection multiple possible.

Sélectionner le répertoire destination pour y copier des fichiers du serveur.

Onglet Liste :
============
Permet de constituer une liste de fichiers du PC, à transférer sur le serveur.
Utiliser le glisser/déposer depuis une fenêtre d'explorateur de fichiers.

Bouton droit pour le menu contextuel.
 -Supprimer : supprime la ligne sélectionnée.
 -Effacer : efface la liste.
 -Copier >> DISTANT : copie les lignes sélectionnées dans le dossier affiché dans l'onglet DISTANT.
