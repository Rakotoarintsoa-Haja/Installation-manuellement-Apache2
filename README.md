# Installation-manuellement-Apache2
Installation manuellement Apache2
Ceci est un procédure d'installation manuellement Apache2 
       1er Méthode :
Vous devez télécharger d'abord le fichier code source apache2 dans cette lien : https://httpd.apache.org/downloads.cgi 
Si vous avez réussi ? félicitations maintenant vous devez suivre l'étape suivante 
Vous devez décompresser et desarchiver le fichier httpd-2.4.59.tar.bz
$ tar -xfv httpd-2.4.59.tar.gz 
Maintenant vous devez installer apr c'est une dépendance de apache2 
Télécharger le dans cet site: https://apr.apache.org/download.cgi
1)$ ./configure
2)$ make 
3)$ make install


Apres cela maintenant nous allons installer l'apache ! 
I)$ cd httpd-2.4.59
II)$ ./configure --prefix=/usr/local/apache2
III)$ make
IV)$ make install




