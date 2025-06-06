# Notes Reponses

Je viens de faire le réseau complet sur gns3, la je vais faire l'adressage réseau et le dhcp



## le réseau commercial

adresse réseau : 54.98.153.128/25
adresse du routeur eth0 : 54.98.153.129/25
adresse du routeur eth0 : ?
PC6 : auto
PC5 : 54.98.153.130

adresses réservé : 
54.98.153.129 - 54.98.153.139


Commandes pour pc 1 : 
Commandes pour pc 2 : 
Commandes pour pc 3 : 
ip 54.98.153.2/25 -> pour l’adresse ip
ip 54.98.153.130/25 54.98.153.129 -> pour le gateway

Commandes pour pc 4 : 

Commandes pour pc 5 : 
ip 54.98.153.130/25 -> pour l’adresse ip
ip 54.98.153.130/25 54.98.153.129 -> pour le gateway




Commandes pour r1 : 

Commandes pour r2 : 
ip route 54.98.153.128 255.255.255.128 54.98.152.3

Commandes pour r3 : 
ip route 54.98.153.0 255.255.255.128 54.98.152.2

Commandes pour r4 : 
