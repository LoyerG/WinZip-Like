# WinZip-Like

Au démarrage le programme propose à l’utilisateur 2 possibilités :
1. Compresser un répertoire,
2. Décompresser un fichier ecf.
Il demande ensuite de saisir un répertoire et le nom du fichier ecf. Si l’utilisateur a choisi l’option 1, le
répertoire est compressé dans le fichier ecf. Si l’utilisateur a choisi l’option 2, le fichier ecf est
décompressé dans le répertoire.
Afin d’utiliser de façon optimale le CPU, la compression et l’écriture du fichier ecf se fait en parallèle.
La décompression se fait quant à elle en n’utilisant qu’un cœur du CPU.
