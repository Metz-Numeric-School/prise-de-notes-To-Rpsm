==découpage de plage IP==

***172.16.0.0 /23*** 

255.255.254.0 -> Subnet Mask

172.16.0.1 -> Réseau
172.16.0.254 -> Gateway
172.16.0.253 -> Broadcast

172.16.0.2 -> 172.16.0.202 = SALES
172.16.1.1 -> 172.16.1.51 = R&D
172.16.1.52 -> 172.16.1.77 = MGT
172.16.1.78 -> 172.16.1.88 = IT
172.16.1.89 -> 172.16.1.99 = Printers
172.16.1.100 -> 172.16.1.110 = Servers

***Révision classe adresse IP et modèle OSI***

![[modele-OSI-872x1024.png]]

**7.==Application :==**
	**==6.Présentation==**
		==**5.Session**== : 
			**==4.Transport==** : Firewall *(Port)* -> 16 bits -> Segment
				**==3.Réseau==** : Routeur *(Adresse IP* IPv4 => 64bits / IPv6 -> 128 bits) -> (Packet)
					**==2.Liaison de données==** : Switch *(Adresse Mac)* -> 48 bits -> (Frame)
						**==1.Physique==** : Câble, fibre, coaxiale

![[0_7GxX2NC7lEs0pK-_.png]]                                                                     **Modèle TCP / IP**


![[CCNA-IPv4-Classe.webp]]
**Classe d'adresse IP**


1000 0000 = ==128==
1100 0000 = ==192==
1110 0000 = ==224==
1111 0000 = ==240== 
1111 1000 = ==248==
1111 1100 = ==252==
1111 1110 = ==254==
1111 1111 = ==255==

![[Pasted image 20241105103836.png]]
**Routage on a stick**

![[Pasted image 20241105112637.png]]![[Pasted image 20241105114812.png]]
![[Pasted image 20241105115154.png]]
![[Pasted image 20241105115459.png]]
![[Pasted image 20241105115520.png]]
![[Pasted image 20241105120041.png]]

