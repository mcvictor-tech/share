# share
share

n'hesite pas si tu n'a pas une certaine informaiton sur certaine implementation faite dans ma codebase a faire des recherche dans la code base afin de retrouver des information et avoir plus de context par exemple a faire des recherche de terme ou ficher  cible et les lire pour meiux comprend et faire des suggestion de code tres fin et precise



Résume l'état actuel de ce projet VS Code pour une autre IA :

Codebase : Décris l'architecture, les fichiers clés, et les dépendances principales.
Implémentations récentes : Pour chaque fonctionnalité majeure, décris l'objectif, les fichiers modifiés, et la logique principale.
Points d'attention : Signale les zones complexes, mal documentées, ou nécessitant une refactorisation.
Format : Clairement structuré, précis, avec liens vers les fichiers.
L'objectif est un aperçu complet et facile à comprendre pour la nouvelle IA. Commence par l'analyse de la codebase.


git clone https://github.com/StephenZAST/Projet-Alpha.git .
git checkout affiliers
git checkout 
cd ..


__________________________



ok c'st pargfait pense tu que lon peut mettre a niveau d'autre page pour les rendre aussi meilleure design que jamain ?par exemple la page offer on peut faire en sorte que cette page ai un meilleure design conformement a ce qui est rechercher (meilleure experience utilisateur que le design propose dans affilier screen par exemple )

tu est libre de lire les fichier et les analyser profondement pour comprendre leure logique methien les fonction ux pour que le nouveau design que tu va me propsoe reprennne les differente fonctonnalite permie par la page offer et ses composant tu comprend ?


__________________

token 

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

&E(;ixZ8msayQ+*$

StephenZAST


git config --global user.name "StephenZAST"
git config --global user.email "contacteasytec@gmail.com"



_____________________


Copiez-collez et exécutez la commande suivante dans la fenêtre PowerShell (Admin) :


Set-ExecutionPolicy Bypass -Scope Process -Force; `
[System.Net.ServicePointManager]::SecurityProtocol = [System.Net.SecurityProtocolType]::Tls12; `
iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))


___________


Ouvrez PowerShell en Administrateur et exécutez :

$chocopath = 'C:\ProgramData\chocolatey\bin'
[Environment]::SetEnvironmentVariable('Path', $env:Path + ';' + $chocopath, [EnvironmentVariableTarget]::Machine)


_____________


Installer Git et Node.js LTS avec Chocolatey
Dans PowerShell (vous pouvez être en session non-admin si choco fonctionne ; choco demandera l’élévation si nécessaire) :



choco install git -y



_____________________



Commande pour ajouter ces dossiers au PATH système :



$pathsToAdd = @('C:\Program Files\nodejs','C:\Program Files\Git\cmd')
$current = [Environment]::GetEnvironmentVariable('Path',[EnvironmentVariableTarget]::Machine)
foreach($p in $pathsToAdd) {
  if (-not ($current.Split(';') -contains $p)) { $current += ';' + $p }
}
[Environment]::SetEnvironmentVariable('Path',$current,[EnvironmentVariableTarget]::Machine)




choco install nodejs-lts -y
