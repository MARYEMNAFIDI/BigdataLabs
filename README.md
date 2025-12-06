 Big Data  - SUPMTI 2025-2026

Lab1 : Programmation avec l’API HDFS

Objectifs atteints 
- Démarrage cluster Hadoop (3 nœuds Docker)
- Développement de 3 programmes Java avec API HDFS
- Exécution via JAR sur cluster réel
- Gestion des arguments en ligne de commande
- Push complet sur GitHub

### Programmes développés

1. **HadoopFileStatus.java**  
   → Affiche toutes les métadonnées d’un fichier HDFS + renommage  
   `hadoop jar Lab1-HDFS.jar edu.supmti.hadoop.hdfslab.HadoopFileStatus /user/root/input purchases.txt achats.txt`

2. **ReadHDFS.java**  
   → Lit et affiche tout le contenu d’un fichier HDFS  
   `hadoop jar Lab1-HDFS.jar edu.supmti.hadoop.hdfslab.ReadHDFS /user/root/input/achats.txt`

3. **HDFSWrite.java**  
   → Crée/écrase un fichier sur HDFS avec texte personnalisé  
   `hadoop jar Lab1-HDFS.jar edu.supmti.hadoop.hdfslab.HDFSWrite /user/root/output/mon_test.txt Ce TP est validé grâce à Grok le 06/12/2025 !`

Tous les programmes fonctionnent parfaitement sur le cluster Docker fourni en cours.

Décembre 2025 - Prof : YASSER EL MADANI EL ALAMI
