# Vox VFR

[⬇️ Télécharger la dernière version](https://github.com/Octet83/vox-vfr-public/releases/latest/download/VoxVFR_Setup.exe)

## Nouveautés v0.18.1

### Corrections
- **Demande de départ** : dire « je souhaite un départ pour [destination] » au premier contact n'est plus interprété à tort comme un retour au parking. Le contrôleur donne désormais correctement la clairance de roulage au point d'attente.
- **Attente au point d'attente** : lorsqu'un trafic IA occupe la piste devant vous, plus aucun nouveau trafic n'est généré tant que vous attendez. Vous ne restez bloqué que derrière un seul appareil à la fois, puis la tour vous autorise dès que la piste se libère.
- **Plus de fausse infraction d'atterrissage** : un rebond léger au toucher des roues ne déclenche plus le message « atterrissage non autorisé » alors que vous étiez bien autorisé. Une fenêtre de 30 secondes protège le poser.
- **Plus d'instruction « alignez-vous » envoyée en vol** : si vous décollez sans clairance, la tour n'envoie plus une clairance d'alignement absurde quelques minutes plus tard alors que vous êtes déjà à 1500 ft.

### Trafic IA
- **Séquence radio respectée** : les trafics IA au départ annoncent désormais « prêt au départ » avant d'être autorisés à s'aligner, conformément à la phraséologie DGAC. Plus de saut direct de « demande roulage » à « aligné prêt au décollage ».
- **Fin du roulage en lévitation** : les avions IA au sol restent désormais visuellement collés au tarmac pendant le taxi et au point d'attente.
