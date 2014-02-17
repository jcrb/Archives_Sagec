Archives_Sagec
==============

Archives SAU-Services  

Création: 2014-02-17  

Ce dossier regroupe:

- certaines tables de la base de donnée de Sagec version historique. Il s'agit d'un dump effectué en février 2014 et qui concerne la tables suivantes:
  - lits
  - lits_fermes
  - lits_journal
  - uf
  - veille_deces
  - veille_dg
  - veille_samu
  - veille_SAU
  - veille_sau  
Ces tables ont été enregistrées dans une BD spécifique appelée *archives*.  
Les données originales sont stockées dans le dossier *data_nold* et sont exclues de l'archive Git.

- les archives des SU récupérées manuellement sur le serveur Sagec et stockées dans le dossier *archives SAU*. Ces archives devraient être redondabtes avec la table *veille_SAU*. Ce dossier est ecvlu de l'archive Git.

TODO
====
- récupérer les données des tables de *archives* sous forme de dataframe et les stocker au format R.
