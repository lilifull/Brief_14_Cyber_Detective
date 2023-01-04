# Brief_14_Cyber_Detective

Projet :

L’entreprise vient de refaire une refonte son site web. Votre manager vous briefe sur les missions qui vont se décliner en plusieurs étapes:
-Récupérer les infos sur les livres : titre, prix, rating, disponibilités des livres et ( en option ) les liens vers les images de couverture des libres via un scrapper. Les informations des livres sur les 50 pages web issues du scrapper seront intégrées dans une base de données et dans un fichier csv. Une analyse est attendue.

---> Cette partie est traitée dans le notebook : scrapping_book.ipynb
La database et le fichier csv sont générés par l'exécution du script du notebook.
Une capture d'écran de la database est présente dans ce repo.
Je n'ai pas utilisée la SGBC Microsoft SQL Server car je n'ai pas réussie à l'installer sur mon macbook.


La société souhaite analyser l’intérêt des livres ( les mieux notés ) dans le réseau social Twitter. Pour cela, votre manager vous demande de collecter tous les tweets via l’API de tweeter liés à ces livres depuis le 01/06/2022. La quantité de tweet liés à chaque livre sera entre 700 et 1000. Les livres à analyser seront : the Art of War, The song of Achille, Batman : the Dark Night Return, The Picture of Dorian Gray, The Book Thief. Il vous est demandé pour la collecte des tweets associés à chaque livre. Les tweet associés à chaque livre sont exportés en csv.
Voici les visualisations au minimum attendues: une analyse nuage de mots à représenter et la fréquence des bigrammes et trigrammes

---> Cette partie est traitée dans le notebook : book_tweeter_analysis.ipynb
Les fichiers csv avec les teweets associés à chaque livre sont générés par l'exécution du script du notebook.



