Défi
Dans cet exercice, nous allons appliquer l'ensemble de nos connaissances avec les rebasages pour travailler sur un fichier HTML comportant une liste de légumes.

Question
Exécutez les étapes suivantes :

Sur une branche master sans commits, créez un fichier index.html (cf. contenu en fin d'exercice)

Ajoutez le fichier et créez un commit nommé Add vegetable list

Poussez la branche master sur votre dépôt distant en définissant l'upstream après l'avoir créé sur GitHub

Créez une branche fix-typos depuis ce commit, placez-vous dessus, puis modifiez le texte du fichier pour corriger les fautes de frappe avec la commande sed -i 's/Pome/Pomme/g; s/Carote/Carotte/g; s/Tommate/Tomate/g; s/Cerisse/Cerise/g' index.html

Créez un commit nommé Fix typos in vegetable list, puis poussez-le sur GitHub

Créez une nouvelle branche remove-fruits depuis master puis modifiez le fichier pour corriger la liste en supprimant les fruits avec la commande sed -i '/Pome/d; /Poire/d; /Cerisse/d' index.html

Créez un commit nommé Remove fruits from vegetable list, puis poussez-le sur GitHub

Fusionnez la branche fix-typos dans la branche master, poussez master et supprimez la branche fix-typos (locale et distante)

Rebasez la branche remove-fruits à partir de la branche master (vous devriez avoir des conflits)

Résolvez les conflits en gardant les corrections des deux branches et terminez la fusion, puis poussez remove-fruits de nouveau

Sur la branche remove-fruits, modifiez le fichier pour ajouter dans la liste le légume Oignon, puis créez un nouveau commit nommé Add onion et poussez la branche

Réécrivez l'historique de votre branche pour fusionner les deux derniers commits en un, nommé Remove fruits from vegetable list and add onion, puis poussez la branche

Fusionnez la branche remove-fruits dans la branche master, poussez master et supprimez la branche remove-fruits (locale et distante)

Fichier index.html du point 1 :

