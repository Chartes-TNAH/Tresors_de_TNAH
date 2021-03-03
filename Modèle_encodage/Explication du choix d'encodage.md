# Explication du choix d'encodage

Nous avons choisi de travailler avec un encodage Dublin Core.
Nous y trouvons plusieurs avantages. Il est plus direct quant aux informations encodées (il n'y a pas plusieurs niveaux d'encodage), mais aussi demande peu d'ajouts d'attributs. Le seul utilisable est l'attribut @xml:lang. Aujourd'hui, deux langues sont renseignées : le français ("fre") et l'anglais ("en"). L'attribut est utilisé spécialement pour le résumé du mémoire, ainsi que pour les mots-clefs qui lui sont liés. Pour ces derniers, nous en avons plusieurs qui sont obligatoires inchangées selon les mémoires. Il s'agit des mots-clefs suivants :
-  <dc:subject xml:lang="fre">Technologies Numériques Appliquées à l'Histoire</dc:subject>
- <dc:subject xml:lang="fre">Mémoire pour le master « Technologies numériques appliquées à l'histoire »</dc:subject>
Dans l'idéal, nous souhaiterions augmenter ces mots-clefs obligatoires en les traduisant dans plusieurs langues. D'autres balises sont uniquement obligatoires et leur contenu immuables : 
- <dc:type xml:lang="fre">Mémoire de master</dc:type>
- <dc:type xml:lang="en">Master Thesis</dc:type>
- <dc:language xml:lang="fre">Français</dc:language>
- <dc:language xml:lang="en">French</dc:language>

En ce qui concerne l'encodage du plan dans la balise <description>, nous avons pris la décision de retirer les numérotations de page afin, entre autres, d'assurer une meilleure lisibilité.     

Ce nombre minimal de possibilités d'encodage nous permet de rendre plus claires nos informations et plus rapide. 

Toute balise autofermante signifie forcément que les informations qui devraient y figurer n'ont pas été fournies par l'étudiant.
Il y a une exception. Pour la balise <format/>, elle est indiquée autofermante pour qu'elle puisse être utilisée en cas de réutilisation des données de ce dépôt.

Lorsque les informations encodées le demandent, nous ajoutons tout de même certains compléments, afin de ne pas rendre tout cela incompréhensible. C'est le cas pour différencier les contributeurs qui ont été tuteurs de stage professionnels ou internes à l'Ecole nationale des chartes : nous avons ajouté la mention "Tuteur de l'ENC" ou "Tuteur de l'institution". C'est également le cas pour différencier les deux balises <description> : il y en a une pour le résumé et une autre pour le plan.
