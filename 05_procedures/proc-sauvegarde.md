# Procédure de sauvegarde et restauration

## 1. Objectif

Garantir que les données importantes peuvent être restaurées en cas de suppression, panne, ransomware ou erreur humaine.

## 2. Périmètre

Les sauvegardes couvrent :
- le serveur de fichiers ;
- les données RH et administratives ;
- les configurations critiques ;
- les exports essentiels de la messagerie ou des comptes si disponible.

## 3. Principe retenu

La stratégie cible est inspirée du principe 3-2-1 :
- 3 copies des données importantes ;
- 2 supports ou emplacements différents ;
- 1 copie isolée ou difficilement modifiable par un ransomware.

## 4. Fréquence

| Données | Fréquence | Rétention |
|---|---|---|
| Serveur de fichiers | Quotidienne | 30 jours |
| Données RH/finance | Quotidienne | 30 jours |
| Configuration pare-feu | Mensuelle ou après changement | 12 mois |
| Site web | Hebdomadaire | 3 mois |

## 5. Responsabilités

| Rôle | Responsabilités |
|---|---|
| Responsable IT | Configurer les sauvegardes, surveiller les erreurs |
| Prestataire IT | Fournir les rapports et aider à la restauration |
| Responsable sécurité | Suivre les tests et preuves |
| Direction | Valider les moyens et priorités |

## 6. Contrôles réguliers

Chaque semaine :
- vérifier que les sauvegardes se terminent sans erreur ;
- contrôler l'espace disponible ;
- vérifier les alertes.

Chaque trimestre :
- réaliser un test de restauration ;
- documenter le résultat ;
- corriger les erreurs.

## 7. Test de restauration

Le test doit vérifier :
1. le fichier ou dossier restauré ;
2. la date de sauvegarde utilisée ;
3. le temps de restauration ;
4. l'intégrité des données ;
5. la personne ayant validé le test.

## 8. Réaction en cas d'échec

Si une sauvegarde échoue :
1. ouvrir un ticket ;
2. identifier la cause ;
3. relancer la sauvegarde ;
4. informer le responsable IT si l'échec dépasse 24 h ;
5. conserver la preuve de correction.

## 9. Preuves attendues

- Rapport de sauvegarde.
- Journal d'erreur.
- Capture du test de restauration.
- Ticket de correction.
- Compte rendu trimestriel.
