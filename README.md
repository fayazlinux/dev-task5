
This is about DevOps-AL Task-5 : 

where our main traget is to create and deploy a Monotroing tools on the Top of Kubernetes .
       	1.Prometheous 
	2.Graphana 

Where our data should be presistences . once my Pod deleted but my data remain same.!! 

Here i  have created a Steps to follow in order to acivhe your above goals .

Prometheous : 
#############

1. Create the PVC in order to store the data in persistence volumen.
	Achive this you may run and check  file name : pvcpro.yml 

2. Create deployemnt configuration of proemthous  on kubernetes : 
	Achive this your may run and check the file name :   prom.yml 

3. Create a configMap file where we make Or mount a file for persistence. 
	Achive this you may run and check the file name : configMap.yml 

4. IN last you have to expose your service our the internet or Outside the world. 
	Achive this task you may run and check the file name:  svcpro.yml

In the End , kustomization.yml file helps us to creates multiple Kubernetes Service in one single command
-k option in kubectl create automatically creates the kustomization.yml file in the current directory.

	Achive this you may check the file name   :  kustomization.yml 


Graphana :
##########

1. Create the PVC in order to store the data in persistence volumen.
	Achive this you may run and check  file name : pvcgrp.yml 

2. Create deployemnt configuration of Graphana   on kubernetes : 
	Achive this your may run and check the file name :  graphan.yml

3. Create a configMap file where we make Or mount a file for persistence. 
	Achive this you may run and check the file name : configMap.yml 

4. IN last you have to expose your service our the internet or Outside the world. 
	Achive this task you may run and check the file name:  svcgra.yml

In the End , kustomization.yml file helps us to creates multiple Kubernetes Service in one single command
-k option in kubectl create automatically creates the kustomization.yml file in the current directory.

	Achive this you may check the file name   :  kustomization.yml 


NOTE: The Specail things in this task it configMAP which is used to mount the file as persistence .Mean if pods have 
been crash due to some reaseon then data will never loss .

if you have any confusion or want to know about more in deep . kindly email me : fayazlinux@gmail.com 
