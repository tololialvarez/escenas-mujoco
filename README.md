# Escenas MuJoCo iCub

Catálogo de escenas MuJoCo para el iCub, adaptando escenarios de manipulación de [robosuite](https://robosuite.ai/docs/modules/environments.html) y [DexMimicGen](https://dexmimicgen.github.io).

**[Ver informe completo con descripción de cada escena y capturas (PDF)](escenas.pdf)**

## Contenido repo
- `scenes/` — escenas .xml
- `meshes/objaverse/` — mallas usadas por `scene_icub_coffee_extra.xml` (coffee_meshes) y `scene_icub_drawer_cleanup_extra.xml` (mug_1)

## Dependencias no incluidas

Estas escenas asumen que viven dentro de `assets/scenes/` del proyecto principal (PMM_v2): referencian por ruta relativa las mallas del iCub (`../meshes/iCub/`) y las texturas base (`../textures/`), que no están en este repo.
