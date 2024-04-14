# projet_INF8801A
Le script "comparaison.m" est celui que j'ai utilisé pour obtenir les graphiques
"main.m" est celui qui permets de visualiser un exemple de superpixels pour LSC, SCALP, SH et SLIC. 
SSN étant en python il faut directement le faire tourner à part "SSN/inference.py" (vous pouvez utiliser la commande par exemple "python3 inference.py --image test_img.jpg --weight .\log\bset_model.pth --nspix 100" pour visualiser un exemple) mais il faut avoir CUDA installé et fonctionnel.
Pour exécuter main.m, il faut cependant MATLAB ainsi que les add-ons MinGW-w64 si vous êtes sous Windows ainsi que Image Processing Toolbox.

La plupart des implémentations MATLAB pour les algorithmes de Superpixels ont été faites par Rémi Giraud (auteur de l'article sur la méthode SCALP et mon maître de stage au laboratoire de recherche en informatique LaBri) que je remercie!
