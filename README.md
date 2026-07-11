# LOGFLY ✈ — Carnet de vol numérique

Carnet de vol personnel au **format réglementaire** (carnet de vol pilote français/algérien), pour enregistrer ses heures de vol et obtenir automatiquement les reports et totaux.

## Utilisation

Ouvrez simplement `index.html` dans un navigateur — aucune installation, aucun serveur. L'application fonctionne aussi bien sur ordinateur que sur téléphone.

## Fonctionnalités

- **Saisie rapide** : date, aéronef, fonction à bord, nature du vol, temps jour/nuit — l'application ventile automatiquement les heures dans les colonnes réglementaires selon la catégorie (mono/multimoteurs, membre d'équipage) et le régime (double commande, seul, 1er/2e pilote). Un **mode détaillé** permet de remplir chaque colonne individuellement.
- **Carnet mensuel conforme** : reproduction des colonnes officielles —
  Quantième du mois · Aéronef (Type, Immatriculation) · Fonction à bord · Nature du vol ·
  Membre d'équipage (Jour/Nuit) · Pilote monomoteurs (Jour/Nuit × Double/Seul) ·
  Pilote multimoteurs (Jour/Nuit × Double/1er pilote/2e pilote) ·
  Vol aux instruments (Double/Pilote) · Link · Arrivées I.F.R. · Certification et signature —
  avec la ligne **Report des Heures** en tête de mois et **Totaux à Reporter** en pied.
- **Report initial** : reprenez les totaux de votre carnet papier actuel pour continuer la chaîne des reports sans rupture.
- **Statistiques** : totaux généraux, jour/nuit, par année, par type d'aéronef, instruments, arrivées IFR.
- **Impression / PDF** : mise en page A4 paysage du carnet, mois par mois.
- **Sauvegarde** : données stockées localement dans le navigateur, export/import JSON et export CSV.

## Format des heures

Les temps se saisissent en `h:mm` (ex. `2:35`), les séparateurs `h` et `.` sont aussi acceptés, ainsi que `235` pour 2 h 35.

## Données

Les vols sont enregistrés dans le stockage local du navigateur (`localStorage`) : ils ne quittent jamais votre appareil. Pensez à **exporter régulièrement une sauvegarde JSON** depuis l'onglet Réglages.
