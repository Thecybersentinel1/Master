
<h1> Memoire de fin de cycle Master</h1>


<h2>Description</h2>
Imaginez l’application du syndrome de Stockholm dans un monde numérique pour lutter contre les cyberattaques. Face à des menaces en ligne de plus en plus sophistiquées, la détection naturelle est devenue insuffisante face à la vitesse d’exécution des attaques. Si l’IA offre de nombreux avantages en cybersécurité — détection rapide, analyses approfondies, renforcement des systèmes — son utilisation combinée aux cyberattaques génère de nouveaux vecteurs bien plus complexes auxquels les défenses classiques ne peuvent résister.
Dans cette bataille déséquilibrée, quoi de mieux pour répondre à une machine qu’une autre machine ? En faire un allié devient alors essentiel pour la cyberdéfense, à l’image du hold-up de Stockholm en 1973. Toutefois, son intégration soulève des défis majeurs :
« Comment l’intelligence artificielle peut-elle être efficacement intégrée dans les stratégies de cybersécurité pour anticiper, détecter et contrer les menaces informatiques ? »​​​​​​​​​​​​​​​​
<br />

<h2>Languages et  Technologies utilisées</h2>

- <b>SIEM : Wazuh</b>
- <b>Algorithme de Deep learning </b>
- <b> Zabbix </b>
- <b> Quicksight </b>
- <b>Python </b> 
- <b>Shell</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Linux server </b>
- <b>Kali </b> 

<h2>Procedure de fonctionnement </h2>

1. Installation et configuration du SIEM wazuh 
2. Déploiement des agents 
3. Entraînement du modèle DNN sur un dataset de type log 
4. Modification  du fichier de configuration de wazuh pour permettre notre code ia de lire fichier du collection des logs
5. Création d’un script qui permet de récupérer tous les événements logs reçus des agents et de les envoyer dans le fichier ‘‘ log_agents.log 
6. Automatisation du script 
7. Phase d’attaque

<h2>Demo :</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
