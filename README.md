# Force Field VFX · three.js WebGPU + TSL

Démo en ligne : https://djanni974.github.io/force-field-vfx/

Un lance-flammes et un jet de plasma contre un bouclier d'énergie, en temps réel dans le navigateur.

- Feu simulé sur GPU : fluide 3D eulérien (advection, flottabilité non-Boussinesq, confinement de vorticité, pression de Jacobi) et combustion à une étape d'Arrhenius, avec suie et refroidissement radiatif
- Transition flamme, rentrée atmosphérique, plasma, pilotée par la densité d'énergie (puissance × constriction)
- Bouclier qui chauffe, se fissure, se perce et se régénère
- Propane, hydrogène ou napalm, avec vent, pluie, sol brûlé et vitrifié, et onde de choc
- Son dynamique : effets générés avec ElevenLabs puis pilotés en direct par la simulation
- Modes Low, Medium, High et Ultra (`?q=low`, `?q=medium`, `?q=high`, `?q=ultra`)

Commandes : ZQSD/WASD pour se déplacer, la souris pour viser, Espace pour tirer, T pour le tir auto, M pour le son.

Nécessite WebGPU (Chrome, Edge ou Safari récent).

D'après la [démo Force Field VFX de lejrimostfa](https://lejrimostfa.github.io/force-field-vfx-threejs/). Recréée et étendue par [Djanni Studio](https://www.djannistudio.fr).
