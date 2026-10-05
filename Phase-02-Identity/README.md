# Phase 02 - Identity Management

## Objectif

Mettre en place les identités et groupes.

## Réalisations

- Création de comptes utilisateurs en masse a partir d un fichier csv
- Attribution des licences
- Gestion des rôles Entra ID
- Création de groupes de sécurité 
- Création de groupes dynamiques pour appareil et utilisateur

## Requêtes dynamiques utilisés :
- (device.deviceTrustType -eq "AzureAD") pour trier les pc gerés par intune
- (device.deviceTrustType -eq "Workplace") pour trier les pc externe :BYOD
- (device.devicePhysicalIDs -any (_ -contains "[ZTDId]")) trie les pc inscrit a autopilot  a partir de leur Harware Id
- (device.deviceModel -eq "VMware20,1") trie toutes les VMs du labs
