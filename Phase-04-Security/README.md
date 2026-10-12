# Phase-04-Security

## Objectif

Mettre en place l'approche Zero Trust.

## Réalisations

- MFA
- SSPR
- Windows Hello
- BitLocker
- Compliance Policies
- Conditional Access
  
## Blocage appareils non conformes
  ### Objectif
        -Implémenter Windows Local Administrator Password Solution (LAPS) dans Intune.

          Configuration
          - Création de la politique LAPS
          - Affectation aux appareils gérés
          -  Rotation automatique des mots de passe administrateur locaux
        Incident rencontré:
          -Le mot de passe LAPS n'était pas visible malgré la configuration correcte de la politique.
        Analyse
          -Vérification de la politique Intune
          -Vérification de l'application sur les appareils
          -Consultation de la documentation Microsoft
        Résolution
          -Ajout des rôles appropriés permettant la consultation des informations LAPS.
        Leçons apprises
          -Les autorisations RBAC et les rôles administratifs influencent l'accès aux mots de passe LAPS.
  
## Windows LAPS
  ### Objectif
        -Implémenter Windows Local Administrator Password Solution (LAPS) dans Intune.

          Configuration
            - Création de la politique LAPS
            - Affectation aux appareils gérés
            -  Rotation automatique des mots de passe administrateur locaux
          Incident rencontré:
              -Le mot de passe LAPS n'était pas visible malgré la configuration correcte de la politique.
          Analyse
            -Vérification de la politique Intune
            -Vérification de l'application sur les appareils
            -Consultation de la documentation Microsoft
          Résolution
            -Ajout des rôles appropriés permettant la consultation des informations LAPS.
          Leçons apprises
            -Les autorisations RBAC et les rôles administratifs influencent l'accès aux mots de passe LAPS.
