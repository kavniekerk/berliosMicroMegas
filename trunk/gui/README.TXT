Ceci est un programme permettant de visualiser des arborescences cr�es par ARF.
Pour compiler, jdom doit se trouver dans le classpath.
Pour fonctionner, il faut avoir cr�� une arborescence � partir d'une table (voir dans src/table).
Le programme "arf" g�n�r� � partir de src/Makefile doit �tre une commande accessible par l'interface ( -> besoin d'un symlink ou d'integrer le programme au PATH).

Les fichiers g�n�r�s par arf lors de la cr�ation de l'arborescence � partir de la table (arf -i ...table.xml) doivent se trouver au m�me endroit que le fichier arbo.xml, le plus simple etant de travailler dans le dossier courant.

Il faut ensuite lancer l'interface compil�e, et ouvrir l'arborescence, soit directement par la ligne de commande (java ui arbo.xml) soit en passant par le menu ouvrir.