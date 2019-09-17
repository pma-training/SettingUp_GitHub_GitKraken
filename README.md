# Setting Up GitHub and GitKraken
How to set up a GitHub account, sync the account with GitKraken, and setup GitKraken for use with the PMADM GitHub System  (_Français ci-dessous_)

_Video:_ [Setting Up GitHub and GitKraken](https://www.youtube.com/watch?v=1rMN2W1Dcug&list=PLaCCIQf3NY979c70cnegKx8Cmo3Wltkia&index=3&t=0s)


### Summary 
Walks users through how to set up GitHub and GitKraken.


#### By the end of this video, you should be able to:
- Create an account on GitHub
- Set-up GitHub email notifications
- Download GitKraken 
- Integrate GitHub and GitKraken
- Create a Working Directory
- Clone repositories to a working directory
- Verify that repositories have been successfully cloned onto a computer


### How Tos
#### How to create an account on GitHub:
1. Navigate to the GitHub website
2. In the sign up box:
    - Enter a username
    - Enter the email that you check most often for PMA work
    - Create a password
3. Verify your account :
    - Click on “Verify” under “Please solve this puzzle to verify that you are a real person”
    - Possible puzzles include
      - Rotating the animal by clicking on the arrows until it is standing upright
      - Clicking on the animal that is the right way up
      - Etc.
    - Click on “Done”
    - NOTE : if you do not complete the puzzle in fewer than 10 seconds, you will need to redo it
4. Confirmation page
    - Do not change any of the settings, and click on “Continue”
5. Welcome to GitHub page
    - Navigate to the bottom, and click on “Skip this step"
6. You will now receive an email from GitHub asking you to verify your account, 
    - In the email, click on “Verify email address”
    
#### How to update settings on GitHub:
1. Go to the image at the top right corner of GitHub, click on it and navigate down to “Settings”
2. Email Settings
    - Verify that your primary email address is the email you check most often for work
    - Verify that “block command line pushes that expose my email” is NOT selected
3. Notification Settings
    - Click on “automatically watch repositories”
    - Under “Participating” select “email” and “web”
    - Under “Watching” select “email” and “web”
    
#### How to gain access to PMA GitHub Organizations:
1. Send an email to the PMA GitHub System Manager (see PMA Git, GitHub and GitKraken SOP) that includes your username and requests the following:
    - Access to the PMA_DM Organization
    - Access to your PMA_Country Organization
    - Access to the PMA_Training Organization
    - The password to access to the GitKraken Installation instructions on Dropbox
    
#### How to install GitKraken on a computer:
1. Navigate to the following folder in Dropbox: DataRoutines > GitHub_VersionControl > DownloadLink_License
2. Open the GitKraken_DownloadInstructions file
    - To open, use the password that the PMA GitHub System Managers shared with you
3. Click on the link in Step 1 of the instructions
4. This will open a webpage instructing you to download GitKraken
    - Download the correct version of the software for your computer
5. Click on the instillation file and follow the instillation instructions
6. Open the GitKraken application, GitKraken will ask you for an Enterprise license
    - Click on “add license”
    - Navigate to the following folder in Dropbox: DataRoutines > GitHub_VersionControl > DownloadLink_License
    - Open the .dat file
7. Fill in the GitKraken profile information

#### How to connect your GitKraken and GitHub accounts:
1. Open a “New Tab” in GitKraken and click on “Preferences”
2. Click on “Authentication” in the right menu
3. Click on GitHub Enterprise
4. Next to “host domain” enter: https://github.com
5. Under “Personal Access Token” click on the link that says “GitHub needs a token from github.com”
    - This will open your web browser and take you to the New Personal Access Token Page on GitHub
6. Keep everything as is on the page, scroll to the bottom, and click on “Generate Token”
7. On the next page, copy the number that is in the green bar
8. Navigate back to GitKraken (“New Tab” > “Preferences” > “Authentication” > “Git Hub Enterprise”)
9. Paste your token code next to “Personal Access Token”
10.	Click on “Connect”

#### How to set up a Working Directory
1. Create a new folder outside of Dropbox, Microsoft Teams, or any other cloud file sharing application
    - For example, the Documents folder
    - This new folder should only be used for repositories

#### How to clone a repository to your computer
1. In GitKraken, click on the folder icon in the top left corner
2. Click on “Clone”
3. Click on “GitHub Enterprise”
4. Next to “Where to clone to”, click on browse, and select your working directory
5. Next to “Repository to clone” scroll down to the name of the repository that you want to clone
    - If it is a forked repository, make sure you are cloning the correct version from the correct organization
6. Click on “Clone the Repo”


### Glossary of terms:
| Term | Definition |
| ---- | ---------- |
| Clone | A clone is a copy of a repository that is located on your computer instead of on a server, it allows you to be able to use a Git editor, such as GitKraken, to track changes without needing to be online. All changes are then synced between the repository on the server and the cloned repository. All PMA staff should clone repositories that contain .do files that they use onto their computer using GitKraken |
| Organization | A workspace where teams can collaborate across many projects at once. PMA uses organizations to organize .do files by purpose and country. |
| Private Repository | A repository that can only be viewed or contributed to by their creator and specified collaborators. All PMA repositories are private so no external person can access personally identifying information stored in .do files. |
| Repository | Contains all of the project files and documentation and stores each file’s revision history. Can have multiple collaborators. PMA keeps its .do files in repositories that are organized by survey type and action |
| Working Directory | Currently checked out version of the files in the local repository. It is the location on the computer where all repositories and .do files are stored |



_________________________________________________________________



# Configuration de GitHub et GitKraken
Comment paramétrer un compte GitHub, le synchroniser avec GitKraken, et configurer GitKraken pour l’utiliser avec le système de PMADM sur GitHub.

_Vidéo:_ [Configuration de GitHub et GitKraken](https://www.youtube.com/watch?v=Fd-ILAQ5Pis&list=PLaCCIQf3NY97bYG9q4ha8mEUlM8W7kJpE&index=3&t=0s)


### Résumé  
Explique aux utilisateurs et utilisatrices comment paramétrer GitHub et GitKraken.

#### A la fin de la vidéo, vous devriez être en mesure de :
- Créer un compte sur GitHub
- Confirmer les notifications par email de GitHub 
- Télécharger GitKraken 
- Intégrer GitHub et GitKraken
- Créer un Working Directory
- Cloner les repositories sur votre working directory
- Vérifier que les repositories aient bien été clonés sur votre ordinateur


### Comment Faire
#### Comment créer un compte sur GitHub :
1. Allez sur le site internet GitHub 
2. Dans la case de connexion :
    - Saisissez votre nom d’utilisateur/trice
    - Saisissez l’email que vous utilisez le plus souvent pour votre travail PMA 
    - Créez un mot de passe
3. Vérifiez votre compte :
    - Cliquez sur “Verify” sous “Please solve this puzzle to verify that you are a real person” (« Veuillez résoudre cette énigme pour vérifier que vous êtes une vraie personne »).
    - Énigmes possibles :
      - Faire tourner un animal en cliquant sur la flèche jusqu’à ce qu’il se tienne debout. 
      - Cliquer sur l’animal qui se tient debout. 
      - Etc.
    - Cliquez sur “Done”
    - NB : si vous ne résolvez pas l’énigme en moins de 10 secondes, vous devrez recommencer.
4. Page de confirmation
    - Ne changez aucun des paramètres, puis cliquez sur “Continue”.
5. Bienvenue sur la page GitHub 
    - Allez en bas, et cliquez sur “Skip this step" (Sauter cette étape)
6. Vous recevrez un email de GitHub vous demandant de vérifier votre compte : 
    - Dans l’email, cliquez sur “Verify email address” (Vérifier mon adresse email)

#### Comment mettre à jour les paramètres de GitHub :
1. Allez sur l’image en haut à droite de la page GitHub, cliquez dessus et descendez dans “Settings” (Paramètres)
2. Email Settings (Paramètres d’email)
    - Vérifiez que votre adresse email principale soit celle que vous utilisez le plus souvent pour PMA.
    - Vérifiez que “block command line pushes that expose my email” ne soit PAS sélectionné.
3. Notification Settings (Paramètres de notification)
    - Cliquez sur “automatically watch repositories”
    - Sous “Participating”, sélectionnez “email” et “web”
    - Sous “Watching”, sélectionnez “email” et “web”

#### Comment accéder aux organizations GitHub de PMA :
1. Envoyez un email au Gestionnaire du système GitHub de PMA (cf. Procédures opérationnelles standard de PMA Git, GitHub et GitKraken) en incluant votre nom d’utilisateur/trice et demandez les choses suivantes :
    - Accès à l’Organization PMA_DM 
    - Accès à votre Organization PMA_Pays
    - Accès à l’Organization PMA_Training 
    - Le mot de passe pour accéder aux instructions d’installation de GitKraken sur Dropbox

#### Comment installer GitKraken sur un ordinateur :
1. Allez dans le dossier suivant sur to Dropbox : DataRoutines > GitHub_VersionControl > DownloadLink_License
2. Ouvrez le fichier GitKraken_DownloadInstructions 
    - Pour l’ouvrir, utilisez le mot de passe que les gestionnaires du système GitHub de PMA vous ont communiqué.
3. Cliquez sur le lien indiqué à l’Étape 1 dans les instructions
4. Cela ouvrira une page internet vous indiquant de télécharger GitKraken
    - Téléchargez la version adéquate du logiciel pour votre ordinateur 
5. Cliquez sur le fichier d’installation et suivez les instructions 
6. Ouvrez l’application GitKraken ; GitKraken vous demandera un numéro de licence d’entreprise 
    - Cliquez sur “add license”
    - Allez dans le dossier suivant sur Dropbox : DataRoutines > GitHub_VersionControl > DownloadLink_License
    - Ouvrez le fichier .dat 
7. Remplissez vos informations de profile GitKraken 

#### Comment connecter vos comptes GitKraken et GitHub :
1. Ouvrez un nouvel onglet (“New Tab”) dans GitKraken et cliquez sur “Preferences”
2. Cliquez sur “Authentication” dans le menu de droite
3. Cliquez sur « GitHub Enterprise »
4. En face de “host domain”, tapez : https://github.com
5. Sous “Personal Access Token”, cliquez sur le lien indiquant “GitHub needs a token from github.com”
    - Cela ouvrira votre moteur de recherche internet et vous redirigera vers une nouvelle page « New Personal Access Token » sur GitHub
6. Ne changez rien sur cette page, allez en bas de la page et cliquez sur “Generate Token”
7. Sur la page suivante, copiez le numéro dans la barre verte 
8. Revenez sur GitKraken (“New Tab” > “Preferences” > “Authentication” > “Git Hub Enterprise”)
9. Collez votre code en face de “Personal Access Token”
10.	Cliquez sur “Connect”

#### Comment configurer un Working Directory
1. Créez un nouveau dossier en dehors de Dropbox, Microsoft Teams ou toute autre application de partage de fichiers sur serveur cloud
    - Par exemple, le dossier Documents 
    - Ce nouveau dossier ne devrait être utilisé que pour les repositories

#### Comment cloner un repository sur votre ordinateur
1. Dans GitKraken, cliquez sur l’icône du dossier en haut à gauche 
2. Cliquez sur “Clone”
3. Cliquez sur “GitHub Enterprise”
4. À côté de “Where to clone to”, cliquez sur « browse » et sélectionnez votre working directory
5. À côté de “Repository to clone”, faites dérouler jusqu’au nom du repository que vous souhaitez cloner
    - Si c’est un repository forké, assurez-vous de cloner la bonne version de la bonne organization.
6. Cliquez sur “Clone the Repo”


### Glossaire :
| Terme | Definition |
| ---- | ---------- |
| Clone | Copie d’un repository situé sur un ordinateur plutôt que sur un serveur, permettant d’utiliser un éditeur Git, comme GitKraken, pour suivre les modifications sans avoir à être en ligne. Toutes les modifications sont ensuite synchronisées entre le repository sur le serveur et le repository cloné. Tous les collaborateurs de PMA devraient cloner les repositories contenant les .do files qu’ils utilisent sur leurs ordinateurs à l’aide de GitKraken.| 
| Organization | Espace de travail où les équipes peuvent collaborer sur différents projets en même temps. PMA utilise des organizations pour organiser ses .do files selon leur objectif et par pays |
| Private Repository | Un repository qui ne pouvant être visionné que par son créateur ou ses collaborateurs, ou auquel seuls son créateur et des collaborateurs spécifiés peuvent contribuer. Tous les repositories de PMA sont privés pour qu’aucune personne externe ne puisse avoir accès aux données personnelles stockées dans les .do files |
| Repository | Contient tous les fichiers et la documentation du projet, et stocke l’historique de révision de chaque fichier. Peut avoir plusieurs collaborateurs. PMA garde ses .do files dans des repositories organisés par type d’enquête et d’action |
| Working Directory | Version actuellement « checked out » des fichiers dans le repository local. C’est l’endroit sur l’ordinateur où tous les repositories et les .do files sont stockés. |
