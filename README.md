# Excuses.com



## La société excuses.com offre a ses clients de leur fournir des alibis pour éviter les diners chez les beaux parents, avec la famille et les amis pénibles.


### Pré-requis

Python

Anaconda

Spark


### Installation

Installer Anaconda

Installer vscode

Télécharger l'archive 'A201912.csv.gz' et le classeur 'Descriptif OpenDamir sur le site Internet https://www.data.gouv.fr/fr/datasets/open-damir-base-complete-sur-les-depenses-dassurance-maladie-inter-regimes/

Dans Anaconda, creer un environnement, puis installer Spark dedans

Dans le classeur, extraire en format csv chaque onglet suivants :
	- AGE_BEN_SNDS, sous le nom 'age_ben_snds_csv'
	- ASU_NAT, sous le nom 'asu_nat_csv'
	- ATT_NAT, sous le nom 'att_nat_csv'
	- BEN_QLT_COD, sous le nom 'ben_qlt_cod_csv'
	- DDP_SPE_COD, sous le nom 'ddp_spe_cod_csv'
	- EXO_MTF, sous le nom 'mdt_typ_cod_csv'
	- MDT_TYP_COD, sous le nom 'exo_mtf_csv'
	
Importer master.ipynb dans Databricks

Importer dans databricks le classeur csv extrait de l'archive sous le nom extrait_csv

Importer les septs autres classeurs csv où pour chaque classeur, la première colonne est un entier appellé 'code' et la seconde est un string appellé 'type'


### Exécution

Dans Databricks, charger la classe master

Démarrer le cluster si ce ne l'est

Dans la liste déroulante, sélectionner la tranche d'âge souhaitée

Cliquer sur l'icone 'Run all' pour tout exécuter

