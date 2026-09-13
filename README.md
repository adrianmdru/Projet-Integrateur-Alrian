# Projet Alrian - Infrastructure et Securite TI (Projet Academique)

> Contexte : Simulation d'infrastructure informatique pour Alrian, une entreprise fictive specialisee dans la vente de vetements de luxe disposant d'un siege social a Montreal et de deux succursales.

## A propos du projet
Ce projet presente la conception et le deploiement complet d’un environnement technologique moderne et securise pour une PME. Il couvre l'ensemble des besoins operationnels de l'entreprise, allant de la modelisation des schemas d'infrastructure jusqu’à la mise en reseau, la gestion des postes utilisateurs et la protection des donnees dans le cloud.

## Principales Realisations et Competences Demontrees

* Conception et Modelisation (Schemas) :
  * Conception des schemas logiques et physiques de l'infrastructure reseau, integrant la segmentation par VLAN, l'interconnexion des succursales et le positionnement des equipements de securite.
  * Cartographie et planification de l'adressage IP global pour l'ensemble des sites et des services.
* Architecture Reseau et Securite : 
  * Mise en place d'un pare-feu et d'un routeur central (pfSense) pour administrer les flux et cloisonner les reseaux (bureaux, succursales, Wi-Fi public invite, et zone demilitarisee DMZ).
  * Configuration et securisation des equipements de commutation (Cisco).
* Infrastructure et Virtualisation :
  * Deploiement d'un hyperviseur (VMware ESXi) centralisant les serveurs de l'entreprise.
  * Implantation d'un service d'annuaire (Active Directory) pour la gestion centralisee des identites et des acces utilisateurs.
  * Hebergement d'un site web transactionnel securise (HTTPS/SSL).
* Gestion du Parc et Postes de Travail :
  * Standardisation et automatisation de l'installation des postes de travail sous Windows (integration au domaine, application de politiques de groupe GPO).
  * Mise en place d'une solution de capture et de restauration d'images systeme pour assurer une reprise rapide en cas de panne.
* Continuite des Affaires :
  * Automatisation des sauvegardes regulieres des serveurs vers le cloud (Microsoft Azure Blob Storage) a l'aide d'une solution professionnelle (Veeam).
  * Deploiement d'un acces distant securise (VPN) pour permettre aux employes et administrateurs de teletravailler en toute securite.
