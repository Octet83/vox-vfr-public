## VOX VFR 1.4.0 — Compréhension du pilote

Cette version corrige une série de défauts remontés par vos rapports de vol,
tous liés à la manière dont le contrôleur interprète vos transmissions.

### Collationnement

Collationner une instruction ne fait plus croire au contrôleur que vous y êtes déjà.
Répondre « je rappelle en sortie de zone » à un « rappelez en sortie de zone » vous
faisait sortir de la zone pour de bon. Le moteur
distingue désormais un engagement (« je rappelle… ») d'un compte rendu de position,
quelle que soit la formulation et quelle que soit l'instruction rappelée.

### Cohérence des instructions

- Une remise de gaz n'est plus contredite par une autorisation d'atterrissage
- Plus de « montez à 1600 pieds » alors que vous êtes en approche finale
- « Atterrissage incomplet » est compris comme un posé-décollé, plus comme un complet

### Le contrôleur ne se tait plus

- Après « quittez sans rappeler », une nouvelle demande relance l'échange, 
  vous pouvez repartir pour un tour de piste sans changer de fréquence
- « Prêt au départ » n'a plus besoin d'être répété
- « Aligné 23 », « merci », « piste dégagé » : formulations désormais reconnues

### Divers

- 122.800 est traitée comme fréquence d'auto-information
- Une phase de vol n'est plus restaurée à tort après un balayage de fréquences
- Correction de deux blocages du moteur vocal (plus de coupure définitive du son)

**Téléchargement :** https://github.com/Octet83/vox-vfr-public/releases/latest/download/VoxVFR_Setup.exe
