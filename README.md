# Force Field VFX · three.js WebGPU + TSL

Démo en ligne : https://djanni974.github.io/force-field-vfx/

Un lance-flammes et un jet de plasma contre un bouclier d'énergie, en temps réel dans le navigateur.

- Feu simulé sur GPU : fluide 3D eulérien (advection, flottabilité non-Boussinesq, confinement de vorticité, pression de Jacobi) et combustion à une étape d'Arrhenius, avec suie et refroidissement radiatif
- Transition flamme, rentrée atmosphérique, plasma, pilotée par la densité d'énergie (puissance × constriction)
- Bouclier qui chauffe, se fissure, se perce et se régénère
- Propane, hydrogène ou napalm, avec vent, pluie, sol brûlé et vitrifié, et onde de choc
- Décor de crépuscule entièrement procédural : playa craquelée en relief (l'eau stagne dans les fentes sous la pluie), ciel étoilé, lune, brume, et un plan d'ouverture de la caméra
- Son dynamique : effets générés avec ElevenLabs puis pilotés en direct par la simulation (fichiers dans `sons/`, téléchargés après l'affichage de la scène)
- Modes Low, Medium, High et Ultra (`?q=low`, `?q=medium`, `?q=high`, `?q=ultra`)

Commandes : ZQSD/WASD pour se déplacer, la souris pour viser, Espace pour tirer, T pour le tir auto, M pour le son.

Sur téléphone : glisser pour orbiter, pincer pour zoomer, toucher pour viser ; le tir automatique et le son se règlent dans le panneau « Réglages ».

Nécessite WebGPU (Chrome, Edge ou Safari récent).

D'après la [démo Force Field VFX de lejrimostfa](https://lejrimostfa.github.io/force-field-vfx-threejs/). Recréée et étendue par [Djanni Studio](https://www.djannistudio.fr).
