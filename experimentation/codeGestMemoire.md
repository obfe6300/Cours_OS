# Gestionnaire de mémoire

exemple d'algorithme :

	fonction reserverMemoire (taille, zone)
		chercher dans la zone memoire concernée la premiere place disponible avec la taille précisée
		mettre dans la table des emplacements memoire reserves le pointeur de debut et la taille
	fin fonction
	
	
	fonction liberationMemoire(pointeur sur bloc memoire)
		chercher dans la table l'entree concernant ce bloc de memoire et le supprimer de la table
	fin fonction
	
	
	fonction compressionMemoire ()
		parcours les tables d'attribution de blocs memoire et essaie de les regrouper pour eviter la fragmentation ; cette fonction recopie les données contenues dans un blocs vers le nouveau bloc. (garbage collector)
	fin fonction