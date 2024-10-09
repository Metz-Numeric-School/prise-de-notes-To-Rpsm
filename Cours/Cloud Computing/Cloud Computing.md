###  **Global Infrastructure and Reliability**

- Structure mondiale d'AWS : régions, zones de disponibilité, et points de présence.
- Services permettant la haute disponibilité et la résilience, comme **Elastic Load Balancing** et **Amazon Route 53**. ==(Amazon Route 53 est un service Domain Name System d'Amazon Web Services depuis 2010. Le nom est une référence possible aux routes américaines, et « 53 » est une référence au port TCP/UDP 53, où les requêtes du serveur DNS sont adressées.)==

### **Networking**

- Concepts de mise en réseau dans AWS, comme les **Virtual Private Clouds (VPC)**.
- Configuration de sous-réseaux, tables de routage, passerelles Internet et NAT.
- Services de réseau comme **AWS Direct Connect** et **Amazon CloudFront** (CDN).

###  **Storage and Databases**

- Services de stockage AWS : **Amazon S3** (stockage d’objets), **EBS** (Elastic Block Storage), et **EFS** (Elastic File System).
- Introduction aux bases de données AWS : **Amazon RDS** (relationnelle), **Amazon DynamoDB** (NoSQL), **Amazon Redshift** (entreposage de données).
- Options de sauvegarde, réplication et récupération des données.

###  **Security**

- Services de sécurité AWS : **IAM** (Identity and Access Management), **AWS Organizations**, et **AWS KMS** (Key Management Service).
- Sécurité partagée : responsabilités du client et d’AWS.
- Surveillance et gestion des journaux avec **Amazon CloudWatch** et **AWS CloudTrail**.

### **Monitoring and Analytics**

- Outils de surveillance : **Amazon CloudWatch**, **AWS X-Ray**.
- Services analytiques : **Amazon Athena** (requêtes SQL sur S3), **Amazon QuickSight** (BI), **AWS Glue** (ETL), **Amazon EMR** (Hadoop et Spark).
- Big Data et traitement de flux avec **Amazon Kinesis**.

###  **Pricing and Support**

- Modèle de tarification AWS : Pay-as-you-go, tiers gratuits.
- Outils de gestion des coûts : **AWS Cost Explorer**, **AWS Budgets**, **AWS Trusted Advisor**.
- Plans de support AWS : Basic, Developer, Business, Enterprise.

###  **Cloud Architecture**

- Bonnes pratiques pour une architecture cloud scalable, résiliente, et efficiente en coût.
- Introduction au **Well-Architected Framework** d'AWS : cinq piliers (Excellence opérationnelle, Sécurité, Fiabilité, Efficacité de la performance, Optimisation des coûts).
- Architecture sans serveur et microservices.

![[Pasted image 20241008110200.png]]
           3 plus grosses entreprise de cloud
-==AWS (Amazon)== Leader mondial en terme de Cloud Computing
-Azure
-Google Cloud

			Services de ces entreprises
IAAS (Infrastructure As A Service) -> Virtualisation/servers/stockage/networking
PAAS (Plateforme As A Service) -> pour le développement 
SAAS (Software As A Service) -> office 365/tout dans le cloud

![[iaas_focus-paas-saas-diagram-1200x1046 1.png]]
![[Pasted image 20241008110233.png]]
Déploiement : sur site/hybride/cloud local
![[Pasted image 20241008110259.png]]

# ==Similitudes entre AWS et l'informatique traditionnelle==
![[Pasted image 20241008110340.png]]

## Avantage du cloud ? :
![[Pasted image 20241008110504.png]]
![[Pasted image 20241008110519.png]]

==6 avantages du cloud computing== 
*-Sécurité complète des données renforcée*
*-accès instantané aux données*
*-simple d'utilisation* 
*-flexibilité et évolutivité des solutions cloud*
*-investissement réduit*
*-solution personnalisable*

- **capacité commerciale**
- **business perspective**
- **people perspective**
- **gouvernance perspective**
- **perspective plateforme**
- **perspective sécurité**
- **perspective opération**
![[Pasted image 20241008111127.png]]
	AWS dans le monde
## Sécurité du cloud AWS
![[Pasted image 20241008111310.png]]
	Responsabilité partagée : ![[Pasted image 20241008111417.png]]
		responsabilité d'AWS :![[Pasted image 20241008111452.png]]
			Responsabilité du client : ![[Pasted image 20241008111519.png]]
				Caractéristique de service de responsabilité en matière de sécurité :![[Pasted image 20241008111559.png]]
				suite : ![[Pasted image 20241008111639.png]] 
Chiffrement des données au repos : ![[Pasted image 20241008111755.png]]
	Chiffrement des données en transit :![[Pasted image 20241008111824.png]]

## ==Service de Calcul==

![[Pasted image 20241008112322.png]]
**==Compute in the Cloud==**

- Services de calcul comme **Amazon EC2** (machines virtuelles).
- Types d’instances EC2 et options de tarification (On-Demand, Reserved, Spot).
- Services de conteneurs (**Amazon ECS**, **EKS**) et **AWS Lambda** (computing sans serveur).
![[Pasted image 20241008112427.png]]
services de calcul AWS : nombreux service et plusieurs catégorisation
-EC2
-Lambda
-ECS
-EKS
-Fargate
-ECR
-AWS Elastic compute cloud
		
![[Pasted image 20241008095612.png]]

AWS Lambda
![[Pasted image 20241008134039.png]]
	exemple de fonction Lambda basée sur un calendrier (démarrer et arrêter des instances EC2)![[Pasted image 20241008134146.png]]
		ici basée sur les événements (crée des images miniatures)![[Pasted image 20241008134252.png]]
		
Stockage par **bloc** (AWS EBS)

