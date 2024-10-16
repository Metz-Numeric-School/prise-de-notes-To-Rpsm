
DNS 
	*==Domain Name System==*
	*==Domain Name Service = Service TCP/IP====*
		
		-Permet la correspondance entre un nom de domaine qualifié FQDN (Full Qualified Domain Name) (il doit toujours se terminé par un point) et une adresse IP
		
		-Domaine inverse ==> Résolution d'une adresse IP en nom de domaine avec l'ajout d'un domaine spécial in-addr.arpa à la fin

			-Transfert de zones entre serveur maîtres (primaire) et un autre serveur (secondaire) chacun ayant autorité sur la zone.



				-Serveur cache => Effectuer des requetes DNS pour se rappeler de la réponse pour la prochaine requete.
				-Serveur Primaire => Contient des enregistrements DNS d'un nom de domaine enregistré, un ensemble d'enregistrements DNS pour un nom de domaine est appelé une "Zone".
				-Serveur secondaire => Contient une copie des zones configurées sur le serveur maître.
				-Serveur Stub => Idem que le serveur secondaire mais copie uniquement les données du serveur et pas les données de l'hôte.


*==Domain Name Server====*

-L'ICANN est un organisme qui gère la liste des **Top Level Domain** (TLD)
==Il existe une TLD par pays (.fr / .it / .de)==
==et des TLD générales (.com / .net / .org)==

-L'ICANN délègue la gestion de chaque TLD à un organisme **(Registry)**

-Les **registry** doivent tenir à jour la liste des domaines définis sur sa ou ses TLD
**AFNIC** tient le registre des *.fr*
**VeriSign** tient le registre des *.com / .net / .org*

-Les **Registrars** ont un rôle commercial (vendent les noms de domaines)

-Les **ccTLD** (country-code TLD) sont les TLD de chaque pays qui correspond à son code pays ISO
13 serveurs racines (DNS Root Servers) répartit partout dans le monde, chaque serveurs racine sont reliés entre eux en fibre optique. 

![[Pasted image 20241015102005.png]]

