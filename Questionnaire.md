**Questionnaire sur la sécurité applicative**


### 1-Que veut dire l'acronyme OWASP ?
* OWASP signifie Open Web Application Security Project 
* OWASP signifie Open Web Analysis Security Project
* OWASP signifie Open Web Application System Project
* OWASP signifie Open Web Application Security Protocol

La reponse: OWASP signifie Open Web Application Security Project 

### 2-Qu'est ce qu'une CVE ?
* CVE signifie Common Vulnerabilities and Exposures
* Une CVE représente une faille de sécurité
* Une CVE représente le code source d'un projet
* Une CVE représente une ville au Guatemala

La reponse: Une CVE représente une faille de sécurité

### 3-Que veut dire l'acronyme XSS ?
* XSS signifie Cross Site Scripting
* XSS signifie Cross Site Script
* XSS signifie Xtreme Security Script
* XSS signifie Xtreme Sport Script

La reponse: XSS signifie Cross Site Scripting

### 4-Qu'est ce que la méthode DEVSECOPS ?
* La méthode DEVSECOPS est une méthode de développement qui permet de sécuriser les applications web
* La méthode DEVSECOPS est une méthode qui vise à sécuriser les Administrateurs Systèmes et Réseaux
* La méthode DEVSECOPS est implémentée dans toutes les entreprises
* La méthode DEVSECOPS remplace la méthode DEVOPS

La reponse: La méthode DEVSECOPS est une méthode de développement qui permet de sécuriser les applications web

### 5-Donnez un exemple de faille de sécurité OWASP ?

Une faille d'injection: en particulier l'injection SQL, sont communes dans les
applications web. L'injection se produit quand des données écrites par
l'utilisateur sont envoyées à un interpréteur en tant qu'élément faisant partie
d'une commande ou d'une requête. Les données hostiles de l'attaquant dupent
l'interpréteur afin de l'amener à exécuter des commandes fortuites ou changer
des données


### 6-Donnez un exemple d'outils utilisé par les attaquants pour énumérer les services d'un serveur ?
"nessus". Il permet aux utilisateurs de scanner les vulnérabilités de sécurité sur les systèmes et les réseaux. Il peut être utilisé pour énumérer les services actifs sur un serveur cible et pour identifier les versions spécifiques des logiciels en cours d'exécution sur ce serveur, ce qui permet aux attaquants d'identifier les vulnérabilités connues pour ces versions spécifiques de logiciels. Il peut également être utilisé pour découvrir les faiblesses de configuration qui pourraient être utilisées pour compromettre le système.


### 7-Décrivez la faille "Directory Traversal" ?
est un type d' exploit HTTP dans lequel un pirate utilise le logiciel sur un serveur Web pour accéder aux données dans un répertoire autre que le répertoire racine du serveur. Si la tentative réussit, l'auteur de la menace peut afficher des fichiers restreints ou exécuter des commandes sur le serveur.



### 8-Donnez un exemple d'injecton SQL ?
```
select * from users where user_id =''or 1=1'
```
### 9-Qu'est ce que l'élévation de privilèges ?

L’élévation de privilèges est l’une des techniques les plus couramment employées par les cyberattaquants pour transpercer les défenses, pénétrer les systèmes et exfiltrer des données sensibles.



### 10-Terminez cette phrase : "la sécurité doit être une responsabilité ..." de RedHat?

* ... de l'administrateur système
* ... partagée par tous
* ... Du Client
* ... vis à vis du fournisseur de service

La reponse: partagée par tous


### 11-Quel est la version anglaise plus généralement adopté de cette définition : "Le durcisssement système" ?

System Hardening 


### 12-Qu'est ce que le "Bug Bounty" ?

est un programme de récompenses proposé par de nombreux sites web et développeurs de logiciel qui offre des récompenses aux personnes qui rapportent des bugs, surtout ceux associés à des vulnérabilités. Ces programmes permettent aux développeurs de découvrir et de corriger des bugs avant que les pirates informatiques et le grand public en soient informés, évitant ainsi des abus. Des primes aux bogues ont été mises en place par les sites internets Facebook1, Yahoo!2, Google3, Reddit4, et l'entreprise de paiement mobile Square

### 13-Donnez un exemple de plateforme permettant de s'entrainer du côté attaquant ?

TryHackMe


### 14-Qu'elle est la couleur de l'équipe représentant les attaquant lors d'un pentest ou un audit de sécurité? 
* Rouge
* Bleu
* Jaune
* Vert

La reponse: Rouge

### 15-Qu'elle faille de sécurité peut introduire ce code PHP ? 

```php	
$prod_id = $_GET["prod_id"];

$sql = "SELECT * FROM Products WHERE product_id = " . $prod_id;
```
injection sql

### 16-Qu'elle est la loi française qui décrit les risques encourus pour piratage ?
Loi Godfrain


### 17-Qu'est ce que la CNIL ?

La Commission Nationale de l'Informatique et des Libertés (CNIL) a été créée par la loi Informatique et Libertés du 6 janvier 1978.

Elle est chargée de veiller à la protection des données personnelles contenues dans les fichiers et traitements informatiques ou papiers, aussi bien publics que privés.

Ainsi, elle est chargée de veiller à ce que l'informatique soit au service du citoyen et qu'elle ne porte atteinte ni à l'identité humaine, ni aux droits de l'homme, ni à la vie privée, ni aux libertés individuelles ou publiques.

La CNIL est une autorité administrative indépendante (AAI), c'est-à-dire un organisme public qui agit au nom de l'Etat, sans être placé sous l'autorité du gouvernement ou d'un ministre. Elle est composée de 18 membres élus ou nommés et s'appuie sur des services.

Elle a un rôle d'alerte, de conseil et d'information vers tous les publics mais dispose également d'un pouvoir de contrôle et de sanction.

### 18-Qu'est ce qu'un rançongiciel ou ransomware ?

Technique d’attaque courante de la cybercriminalité, le rançongiciel ou ransomware consiste en l’envoi à la victime d’un logiciel malveillant qui chiffre l’ensemble de ses données et lui demande une rançon en échange du mot de passe de déchiffrement.

### 19-Donnez un exemple de scanner de vulnérabilité ?
Nuclei


### 20-Qu'est ce qu'un White Hat ?

 est un hacker éthique ou un expert en sécurité informatique qui réalise des tests d'intrusion et d'autres méthodes de test afin d'assurer la sécurité des systèmes d'information d'une organisation. Par définition, les « white hats » avertissent les auteurs lors de la découverte de vulnérabilités. Ils s'opposent aux black hats, qui sont les hackers mal intentionnés.

**Question Bonus :**

### Donnez votre définition de l'Open Source ?
est un logiciel informatique qui est publié sous une licence dans laquelle le titulaire du droit d'auteur accorde aux utilisateurs le droit d'utiliser, d'étudier, de modifier et de distribuer le logiciel et son code source à quiconque et à n'importe quelle fin.
