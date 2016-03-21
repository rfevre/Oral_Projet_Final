# Pourquoi avoir choisi PostGreSQL :

PostgreSQL est un système de gestion de bases de données relationnel robuste et puissant, avec des fonctionnalités 
riches et avancées, capable de manipuler en toute fiabilité de gros volumes de données, mêmes dans des 
situations critiques.

Il dispose aussi de son propre PL / pgSQL qui est similaire à PL / SQL d'Oracle.

Pour rappel PL / pgSQL permet :
	- De créer des fonctions standards,
	- D'ajouter des structures de contrôle au langage SQL,
	- D'effectuer des traitements complexes

# Parler du MCD et MLD



# Parler des contraintes d'intégrité

table do_eval => MARK                 FLOAT                   DEFAULT 0,
table evaluation => COEFF                FLOAT                   DEFAULT 1,
table INTERNSHIP_LOG => DATE_LOG             TIMESTAMP               DEFAULT CURRENT_TIMESTAMP,

# Parler des Vues

vue pour les notes d'un étudiant avec toute les informations necessaire au prochaine vue
	- vue liste des moyennes des matieres par etudiant 
	- vue liste des moyennes des UE par etudiant
	- vue liste des moyennes des semestres par etudiant 

