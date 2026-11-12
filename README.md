# Vox VFR

[⬇️ Télécharger la dernière version](https://github.com/Octet83/vox-vfr-public/releases/latest/download/VoxVFR_Setup.exe)

## Nouveautés v1.7.0

### Nouveautés
- **Push-to-talk clavier actif simulateur au premier plan** : une touche clavier fonctionne désormais même quand la fenêtre du simulateur est active (auparavant, seul un bouton de joystick ou de yoke le permettait). Le nom de la touche s'affiche correctement sur clavier AZERTY.
- **Détresse et urgence** : MAYDAY et PAN PAN sont reconnus à tout moment, sur toutes les fréquences.
- **Traversée de piste** : « demande traversée piste 27 » → « traversez piste 27, rappelez piste dégagée », ou « maintenez avant piste 27 » si un trafic occupe la piste, puis la clairance quand elle se libère.
- **Nouvelles demandes comprises** : carburant minimal (« minimum fuel »), clôture du plan de vol, essai radio, interruption de décollage, demande de virage après le décollage, heure exacte, « est-ce que la R 162 est active ? ».

### Phraséologie plus fidèle au manuel DGAC
- Transit de CTR : vraie clairance « transitez via …, puis … » avec les points de report à rappeler.
- Arrivée dans l'axe : « exécutez approche directe, rappelez longue finale ».
- Altitudes : « montez » / « descendez » / « maintenez » selon votre altitude réelle.
- Tour de piste : séquencement « numéro 2, suivez un D-R 400 en finale », sans vent superflu ; la semi-directe donne une entrée en base.
- Sol : la clairance de roulage se termine par « rappelez prêt au départ », le transfert vers la Tour vient quand vous êtes prêt.
- SIV : code transpondeur d'abord, puis « identifié radar » après votre collationnement ; fréquences annoncées avec « décimale » ; « route » et distance pour rejoindre un aérodrome.
- ATIS : heure d'enregistrement et rappel « Informez … dès le premier contact ».
- Suggestions pilote : messages d'intention et collationnements complets, conformes au manuel (« je remets les gaz et rappelle vent arrière piste 23 »…).

### Corrections
- « Aligné piste 23 » après « rappelez aligné » donne bien la clairance de décollage.
- La clairance initiale de transit n'était pas toujours délivrée.
- Le PTT ignoré (version démo hors zone, simulateur sans données, micro refusé) affiche maintenant la raison au lieu de ne rien faire.

📘 Le guide des phrases pilote est à jour : https://www.vox-vfr.com/guide
