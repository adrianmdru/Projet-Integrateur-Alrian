# Projet Alrian - Infrastructure et Sécurité TI (Projet Académique)

> Contexte : Simulation d'infrastructure informatique pour Alrian, une entreprise fictive spécialisée dans la vente de vêtements de luxe disposant d'un siège social à Montréal et de deux succursales.

## À propos du projet

Ce projet présente la conception et le déploiement complet d’un environnement technologique moderne et sécurisé pour une PME. Il couvre l'ensemble des besoins opérationnels de l'entreprise, allant de la modélisation des schémas d'infrastructure jusqu’à la mise en réseau, la gestion des postes utilisateurs et la protection des données dans le cloud.

## Principales Réalisations et Compétences Démontrées

* Conception et Modélisation (Schémas) : 
  * Conception des schémas logiques et physiques de l'infrastructure réseau, intégrant la segmentation par VLAN, l'interconnexion des succursales et le positionnement des équipements de sécurité.
  * Cartographie et planification de l'adressage IP global pour l'ensemble des sites et des services.
* Architecture Réseau et Sécurité : 
  * Mise en place d'un pare-feu et d'un routeur central (pfSense) pour administrer les flux et cloisonner les réseaux (bureaux, succursales, Wi-Fi public invité, et zone démilitarisée DMZ).
  * Configuration et sécurisation des équipements de commutation (Cisco).
* Infrastructure et Virtualisation :
  * Déploiement d'un hyperviseur (VMware ESXi) centralisant les serveurs de l'entreprise.
  * Implantation d'un service d'annuaire (Active Directory) pour la gestion centralisée des identités et des accès utilisateurs.
  * Hébergement d'un site web transactionnel sécurisé (HTTPS/SSL).
* Gestion du Parc et Postes de Travail :
  * Standardisation et automatisation de l'installation des postes de travail sous Windows (intégration au domaine, application de politiques de groupe GPO).
  * Mise en place d'une solution de capture et de restauration d'images système pour assurer une reprise rapide en cas de panne.
* Continuité des Affaires :
  * Automatisation des sauvegardes régulières des serveurs vers le cloud (Microsoft Azure Blob Storage) à l'aide d'une solution professionnelle (Veeam).
  * Déploiement d'un accès distant sécurisé (VPN) pour permettre aux employés et administrateurs de télétravailler en toute sécurité.
