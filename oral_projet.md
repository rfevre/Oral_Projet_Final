=> Pourquoi avoir choisi PostGreSQL :

PostgreSQL est un syst�me de gestion de bases de donn�es relationnel robuste et puissant, avec des fonctionnalit�s 
riches et avanc�es, capable de manipuler en toute fiabilit� de gros volumes de donn�es, m�mes dans des 
situations critiques.

Il dispose aussi de son propre PL / pgSQL qui est similaire � PL / SQL d'Oracle.

Pour rappel PL / pgSQL permet :

	- De cr�er des fonctions standards,

	- D'ajouter des structures de contr�le au langage SQL,

	- D'effectuer des traitements complexes


=> Parler du MCD et MLD



=> Parler des contraintes d'int�grit�

table do_eval => MARK                 FLOAT                   DEFAULT 0,
table evaluation => COEFF                FLOAT                   DEFAULT 1,
table INTERNSHIP_LOG => DATE_LOG             TIMESTAMP               DEFAULT CURRENT_TIMESTAMP,

=> Parler des Vues

vue pour les notes d'un �tudiant avec toute les informations necessaire au prochaine vue
	- vue liste des moyennes des matieres par etudiant 
	- vue liste des moyennes des UE par etudiant
	- vue liste des moyennes des semestres par etudiant 

