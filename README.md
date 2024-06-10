# CRISalid-notebooks 🦋


Qui est affilié à mon établissement ? Qui a quels identifiants auteur ? Qui a publié quoi dans HAL ? Pourquoi ce chercheur est-il affilié au mauvais labo dans OpenAlex ? Pour valoriser la production de ses chercheurs dans HAL, mesurer l’adoption d’ORCID ou analyser la production scientifique dans OpenAlex, chaque établissement se pose ces questions. Vous trouverez ici des petits outils créés par des bibliothécaires pour des bibliothécaires, utiles pour aligner les identifiants chercheurs, repérer des affiliations à corriger ou mettre à jour les notices d'autorité dans IdRef.  


## Notebooks : 

### Export .csv de la liste des chercheurs et de leurs IdHal affiliés à une liste de laboratoires dans HAL

Objectif : mettre à jour l'annuaire de son établissement avec les IdHal, aligner les identifiants chercheurs, mettre à jour IdRef  
Voir le notebook : [export_csv_chercheurs-idhal_selon_id_struct.ipynb](demo/export_csv_chercheurs-idhal_selon_id_struct.ipynb)

### Export .csv de la liste des signatures des chercheurs affiliés à une institution dans OpenAlex

Objectif : comparer les signatures des auteurs d'une institution avec les affiliations attribuées automatiquement dans OpenAlex pour repérer des erreurs ou suivre le respect de la charte de signature. Vous pourrez ensuite demander des corrections sur [works-magnet](https://works-magnet.staging.dataesr.ovh).   
Voir le notebook : [export-signatures-openalex.ipynb](demo/export-signatures-openalex.ipynb)

### Export .csv de la liste des identifiants présents dans les notices IdRef d'une liste de chercheurs

Objectif : comparer les identifiants présents dans IdRef avec des identifiants présents dans un fichier interne à l'institution comme un annuaire de chercheurs pour mettre à jour la base IdRef  
Voir le notebook : [export-identifiants-idref.ipynb](demo/export-identifiants-idref.ipynb)
