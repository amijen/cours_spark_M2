Ce cours est enseigné à l’Université Paris 1 Panthéon-Sorbonne par le professeur [Kamila Kare](https://github.com/KamilaKare). Le contenu de ce dépôt reprend celui du professeur, en y ajoutant certaines informations ainsi que les réponses manquantes dans les notebooks.
## Guide de démarrage 

Pour ce cours, nous allons utiliser **GitHub Codespaces**. Cela vous évite d'installer Java, Python ou Spark sur votre propre ordinateur. Tout se passe dans votre navigateur.

### Étape 1 : Préparer votre dépôt

1. Connectez-vous à votre compte **GitHub**.
2. Allez sur le dépôt du cours fourni par l'enseignant.
3. Cliquez sur le bouton vert **[ <> Code ]** en haut à droite.
4. Sélectionnez l'onglet **Codespaces**, puis cliquez sur **Create codespace on main**.

### Étape 2 : Initialisation (Patientez 2 minutes)

* Une nouvelle fenêtre s'ouvre avec une interface identique à **VS Code**.
* Le système installe automatiquement **Java** et **PySpark** (grâce au fichier `.devcontainer` que j'ai configuré).
* *Note :* La première fois, cela peut prendre 1 à 2 minutes. Les lancements suivants seront instantanés.

### 💡 Astuces utiles :

* **L'interface Spark :** Quand Spark tourne, une petite notification en bas à droite vous proposera d'ouvrir le port **4040**. Cliquez dessus pour voir l'interface Spark UI et surveiller vos calculs.
* **Arrêt du travail :** Codespaces s'arrête automatiquement si vous ne l'utilisez plus (votre travail est sauvegardé). Vous pourrez le reprendre plus tard via [github.com/codespaces](https://github.com/codespaces).
* **Quota :** Vous disposez de **60 heures gratuites par mois**, ce qui est largement suffisant pour ce module.

