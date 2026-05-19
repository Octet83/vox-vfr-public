# Vox VFR

[⬇️ Télécharger la dernière version](https://github.com/Octet83/vox-vfr-public/releases/latest/download/VoxVFR_Setup.exe)

## Nouveautés v0.18.0

Cette version apporte une **révision complète de la phraséologie** pour la rendre conforme au manuel de phraséologie DSNA et à l'arrêté du 27 juin 2000.

### Phraséologie conforme DGAC
- **Collationnements pilote corrigés** : « Piste 27, je décolle » / « Piste 33 droite, j'atterris » (les formes « autorisé décollage/atterrissage » sont réservées à l'ATC)
- **AFIS** recentré sur le service d'information : il informe et demande « rappelez vent arrière » au lieu de délivrer une clairance d'intégration ou une altitude
- **Tour** : ordre correct piste → vent → QNH avant la clairance d'entrée ; QNH annoncé une seule fois ; « rappelez longue finale / finale piste X » ; « piste 28, autorisé toucher / option »
- **Sol** : roulage toujours borné au point d'attente (prévention des incursions de piste)
- **Vocabulaire d'intégration réglementaire** : « entrez vent arrière / base piste X », « approche directe » (suppression de « semi-directe », « intégration en U », « verticale terrain »)
- **Indicatif complet au premier contact**, abrégé uniquement après que l'ATC l'a introduit
- **Fréquences** : prononciation corrigée (ex. 118.250 → « 118 décimale 250 »)
- **Sigles épelés** : Q-N-H, V-F-R, T-M-A, A-TIS, A-FIS
- **SIV** : « identifié radar » / « fin de service radar », information de trafic avec mouvement relatif (convergent / sens opposé / même sens), accusés simplifiés sur compte rendu de position
- Code transpondeur en clair pour les multiples de mille (« deux mille »)

### Reconnaissance vocale enrichie
- Détection des collationnements « je décolle » / « j'atterris »
- Nouveaux reports de circuit : vent traversier, montée initiale, travers mi-piste, fin de vent arrière, dernier virage
- WILCO, ROGER, « j'écoute », « affirme » reconnus dans toutes les phases
- Meilleure robustesse sur les variantes de formulation

## Corrections v0.18.0
- Correction de bugs sur la clairance d'atterrissage (consommation de la clairance, scan de fréquence)
- Gestion du contact à l'arrivée fiabilisée
- Résolution de la fréquence active améliorée
