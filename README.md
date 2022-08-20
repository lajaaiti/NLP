## la data
pour les données de notre projet il est necessaire de telecharger un fichier csv en suivant ce lien: (https://simplonline-v3-prod.s3.eu-west-3.amazonaws.com/media/file/csv/289df373-42e6-40fe-a3ab-8c8110f0a571.csv). renommer le fichier comme suit : data.csv; ensuite enregistrez ce fichier dans un nouveau dossier nomme data1.

## le projet:

- vu le volume important des sequences (16201), j'ai commencé par difinir une longueur maximal de 3000 et entrainer un model avec 7 epochs qui a donné une accuracy de 91%. ensuite j'ai entrainé un autre model avec 2500 sequences et 7 epochs tjrs qui a donné 88%. il est a noté que cet entrainnement etait realise sur googlecolab.
- j'ai essayé de faire un entrainement en local sur ma machine :
        * 1000 sequences et 5 epochs pour un score de 78%
        * 1200 sequences et 10 epochs => accuracy : 93%
        

https://colab.research.google.com/drive/1WUO7XnrS1nMcUnU_9c2y_TxNajQE1jED#scrollTo=yCgO89DVITct (2500 sequences et 7 epochs).

https://colab.research.google.com/drive/1TxMLsATXIyxeGfyQyK2MxuDcrHyNr_VG#scrollTo=__5OwgDOITcp (3000 sequences et 7 epochs)