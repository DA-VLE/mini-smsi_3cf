# Mini-SMSI & mise en conformité 3CF - Aéroport Régional 3CF

## 1. Objectif du projet

Ce projet simule la mise en place d'un mini-SMSI pour une organisation fictive : **Aéroport Régional 3CF**, une structure de 50 employés exploitant un petit environnement numérique critique.

L'objectif n'est pas de prétendre obtenir une certification ISO 27001, mais de montrer une démarche structurée de gouvernance sécurité : définition du périmètre, inventaire des actifs, analyse des risques, plan de traitement, procédures et preuves attendues.

## 2. Contexte fictif

L'entreprise gère un aéroport régional avec des fonctions administratives, exploitation, sûreté, RH/finance et support informatique partiellement externalisé.

Le périmètre étudié couvre :
- la messagerie professionnelle ;
- le serveur de fichiers ;
- les comptes utilisateurs et administrateurs ;
- l'accès Internet et le pare-feu ;
- le site web public ;
- les postes utilisateurs ;
- les sauvegardes ;
- les données RH et administratives.

Sont exclus du périmètre : systèmes de contrôle aérien, radars, équipements de sûreté physique, systèmes industriels et systèmes réglementaires spécifiques au transport aérien. Ce choix permet de garder un périmètre réaliste pour un projet étudiant.

## 3. Référentiel 3CF retenu

Dans ce projet, le référentiel **3CF** est traité comme un cadre interne fictif de conformité cyber basé sur trois contrôles fondamentaux :

1. **Contrôle des accès** : comptes nominatifs, moindre privilège, MFA, revue périodique des droits.
2. **Continuité et sauvegardes** : sauvegardes régulières, test de restauration, protection contre le ransomware.
3. **Conduite face aux incidents** : procédure d'alerte, qualification, escalade, traçabilité et amélioration continue.

## 4. Méthodologie

La démarche suivie est volontairement simple :

1. Définir le périmètre du SMSI.
2. Identifier les actifs importants.
3. Evaluer les besoins en Confidentialité, Intégrité et Disponibilité.
4. Identifier les scénarios de risques.
5. Calculer le risque brut avec une matrice Probabilité x Impact.
6. Définir des mesures de traitement.
7. Prioriser les actions.
8. Formaliser les procédures principales.
9. Lister les preuves attendues pour un audit interne.

## 5. Matrice de risque utilisée

| Score | Niveau | Interprétation |
|---:|---|---|
| 1 à 3 | Faible | Risque acceptable ou à surveiller |
| 4 à 7 | Modéré | Action planifiée si coût raisonnable |
| 8 à 11 | Elevé | Action prioritaire |
| 12 à 16 | Critique | Traitement rapide nécessaire |

## 6. Principaux risques identifiés

Les risques les plus critiques sont :
- compromission d'un compte de messagerie par phishing ;
- ransomware sur le serveur de fichiers ;
- perte ou indisponibilité des sauvegardes ;
- droits d'accès trop larges sur les données RH ;
- absence de procédure claire en cas d'incident.

## 7. Livrables

| Dossier | Livrable | Rôle |
|---|---|---|
| 01_perimetre-et-politique | politique-securite.md | Fixer les règles générales et le périmètre |
| 02_inventaire-actifs | inventaire-actifs.xlsx | Identifier les actifs, propriétaires et criticités |
| 03_analyse-des-risques | registre-risques.xlsx | Evaluer les risques et les mesures de traitement |
| 04_plan-de-traitement | plan-actions-securite.xlsx | Suivre les actions, responsables, preuves et statuts |
| 05_procedures | procédures Markdown | Formaliser les pratiques opérationnelles |
| 06_sensibilisation | support phishing PDF | Sensibiliser les utilisateurs |

## 8. Ce que ce projet démontre

Ce mini-SMSI montre ma capacité à :
- structurer un périmètre de sécurité ;
- raisonner en termes de risques ;
- relier les risques à des mesures concrètes ;
- produire des documents auditables ;
- vulgariser la sécurité auprès d'utilisateurs non techniques ;
- présenter un travail clair dans un dépôt GitHub.

## 9. Limites du projet

Ce projet est une simulation. Les données, l'entreprise et les risques sont fictifs. Les mesures proposées restent volontairement simples afin d'être compréhensibles et adaptées à un environnement de PME.
