# Etude-et-r-alisation-d-un-Robots-suiveurs-assistants-humains ( The Familaire V1.0 ) 

Il y a une infinité de choses à découvrir sur la robotique. 
Beaucoup de choses sont tout simplement trop fantastiques pour que les gens y croient.

# Introduction Générale :

Les robots sont la nécessité de notre époque et nous croyons à cette opinion. 
Nous avons donc pensé à faire un robot qui a à la fois la fonctionnalité autonome et la fonctionnalité de contrôle manuel.

# Besoin de robot

<pre>

<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/92098387/174496551-137346b9-8614-4bda-99a8-50f77292d4a0.png">
</p>


Nous utiliserons la puissance du signal ou le décibel par mètre (Dbm) pour localiser la cible.

</pre>

<pre>

<p align="center">
  <img width="660" height="800" src="https://user-images.githubusercontent.com/92098387/174496553-0189d4aa-a058-4000-98f1-d09b688c4761.png">
</p>

Le robot se déplace sans aucun contrôle
humain et évite les obstacles s'ils existent et atteint sa destination à la fin.

</pre>

# Outils et logiciel

# 1.Solidworks




<pre>

<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/92098387/174496715-883b1c93-bd2f-4dc7-877d-c6f28f1723ba.png">
</p>
<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/92098387/174496749-7179003a-9748-45b1-b18c-44332ab31376.jpeg">
</p>

SolidWorks est un programme informatique de conception assistée par ordinateur (CAO) et
d'ingénierie assistée par ordinateur (IAO) de modélisation des solides.

Nous avons utilisé SolidWorks pour concevoir toutes les pièces mécaniques de notre projet.

</pre>


# 2.EasyEDA


<pre>

<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/92098387/174496836-550a3f67-66c4-4d7e-a729-7100c5b9350d.png">
</p>


Nous avons utilisé EasyEDA pour concevoir tous les circuits électroniques.

</pre>


# 3.DietPi OS

<pre>


Nous avons choisi ce système car nous voulions atteindre une performance,
vitesse et stabilité ultimes tout en consommant moins d'énergie.

<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/92098387/174496898-73576d42-2948-4bc0-b674-edc4ac26c318.jpeg">
</p>



</pre>

<pre>

<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/92098387/174496914-8832abed-12fa-45ee-b448-198086730625.jpg">
</p>


CPU: ARM 700 MHz
RAM: 512 MB 
Tension: 5V
Amperage: 3A
Puissance Maximale: 15W


</pre>



# Python

<pre>

le language python est l'un des languages de programmtion les plus accessibles , 
car il possede une systemes simplifiées et non compliquée 


<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/92098387/175809197-befb82bb-e8b2-4f1a-acf8-d33797d6a806.png">
</p>



</pre> 

 

# GPIO 

<pre>

nous avons reglé toutes les broches de moteur pour le controler 


<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/92098387/175809218-f8f59a6b-2dfe-4b89-b3c2-545516d8a820.png">
</p>


</pre>



# IWLIST 

<pre> 

IWLIST affiche les informations sur tous les Réseaux WIFI disponible 

<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/92098387/175809264-5c256065-1fb0-4fcc-a11d-48e6f6387996.png">
</p>

<p align="center">
  <img width="860" height="600" src="https://user-images.githubusercontent.com/92098387/175809362-e0a95af7-2473-4cd6-857e-330e2cdf8551.png">
</p>





</pre> 



# Controle manuel du robot 

<pre> 

https://user-images.githubusercontent.com/92098387/175809373-ccdeb622-f9b8-4791-bffe-05fa89c1dd19.png
https://user-images.githubusercontent.com/92098387/175809377-574128d9-825b-40db-8b2c-4b1654f16782.png


</pre>
 
<pre> 

# Moteur Visseuse

On a essayé d’utiliser des anciennes visseuse pour extraire  des moteurs fonctionnelles ,
apres on a demander une coup du main d’un Tourneur pour personnaliser les pieces et 
pour qu’ils soient adaptables à nos roues 

</pre> 

<pre> 

# Conception 3D 


</pre> 

<pre> 

# Conception de la chassis 

- pLaque métallique 
 nous avons donc essayé de rendre notre robot aussi robuste que possible. 


- Roues 
 On a utiliser des roues de dimensions trés élevées pour les terrains difficiles

- Boulon poelier acier 
 Serrage des différents éléments de la chassis 
 
 </pre> 
 
 
 <pre>
 
 # Batterie 12V 
 
 La batterie est composée de cellules au lithium, chacune à 3,7V / 3A. 
 Nous avons donc construit un bloc contenant trois cellules en série et 
 nous avons relié trois de ces blocs en parallèle. 
 
 
 </pre>
 
 <pre> 
 
 # Bloc Transformation de tension 220V AC vers 12V DC 
 
 - Transformateur abaisseur de tension 
 
  on a utiliser le transformateur pour abauisser la tension fournit par le secteur de 220V à 12V seulement 
  
  
- Pont du Graitez 
 utilisé pour le redressemnt double alternances 
 
- Capacite de filtrage 
 utilise pour le filtrage du signal 
 
 - Regulateur IC 
  utilise pour render le signal purement continu 
  
<pre>

# Bloc régulateur du tension 12V vers 5v

- LM2576 : composant electronique pour reguler la tension 

<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/92098387/175809036-61394989-08ad-4414-8fea-249080d3359b.png">
</p>


<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/92098387/175809064-5bdb7ca8-dd8f-405a-8a94-492adc35349a.png">
</p>



</pre>
