# Système de sauvegarde
- Date: 02.10.2017
- Intervenant: Anthony Masset

## Quoi sauvegarder ?
- Données utilisateurs
  - Base de données
  - Fichiers (bureautique)
  - Mails
- Machines virtuelles, Système d'exploitation
- Logs, journaux systèmes
- Fichiers de configuration, système, applications
  - Pare-feu: Filtrage IP, IDS, Proxy web filtrant, anti-spam
  - Borne Wifi: ESSID, clé de sécurité
  - Switch, routeur: configuration VLAN, interfaces, STP, trunking ...
  - Serveur d'authentification : Active Directory, LDAP
  - Infrastructure: DNS, DHCP
  - Serveur de messagerie
  - Serveur d'applications
  - Clusters
  - Partage de fichiers

## Où sauvegarder ?

- NAS, Serveurs de Fichiers
- Autre local: pièce, internet, VPN
- Serveur de sauvegarde
- Disque externe, clé USB
- Bandes, cartouches
- Médias optiques

## Quand sauvegarder ?

- Historique sur une semaine minimum
- Minimum: tous les jours
- Sauvegarde continue si possible
- Sauvegarde à chaud
- Peu d'impact sur l'activité de l'entreprise
- Essentiellement la nuit

## Qui ?

- Programmation de la sauvegarde: Administrateurs système
- Interaction avec les éditeurs de logiciels pour la technique de sauvegarde restauration
- Les développeurs doivent prendre en compte la notion de sauvegarde dans leurs développements: Sauvegarde, restauration, granularité

## Comment ?

- Copie complète
- Copie incrémentielle, différentielle, synchronisation
- Dump de base de données complète, incrémentielle
- Restauration: -> Coupure de service - techniques complexes propres à chaque technologies.
