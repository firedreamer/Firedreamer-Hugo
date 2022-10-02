+++
description = "How the project repository is structured"
title = "Project Structure"
weight = 1
+++

### GitHub
All contributors are requested to have an account on GitHub, which is the primary version control system that we will be using. This allows us to go back to previous versions of a file, resolve conflicts when two or more people are working on the same thing, and have an active, trackable snapshot of the game project at any given time. 

---
### Engine
Unreal 4.27.2. 

---
### Repository Folders
Each game's repository will be added on this page, and will broadly follow the same structure. 

- Prelude: [github.com/firedreamer/DD-Prelude](https://github.com/firedreamer/DD-Prelude)

The Repository houses the PreludeGame folder, which acts as the actual Unreal Project directory. Inside the Content directory, the following structure is to be followed:
- **Animations:** Character animations.
    - **MXRig:** Animations retargeted to the Mixamo character rig, renamed to match Unreal's bone names.
        - Folders to be made by category.
    - **Mannequin:** Animations that came with the Third Person sample project.
- **Audio:**  Pretty self explanatory. Cues stay within the folders, waves inside a "wave" folder.
    - **Score**
    - **Foley**
    - **Ambient**
    - **UI**
- **Blueprints:** Reusable Blueprints in the game project.
    - **Components:** Blueprint Components.
- **Character:** Individual characters have their own folders here.
- **Geometry:** Environmental models, geometry, etc.
- **Maps:** Game levels/environments.
- **Materials:** Material Masters and Material instances.
    - **Master:** Base materials to be reused.
    - **Post:** PostProcessing Materials
- **Textures:** Textures that don't go with geometry; independent textures.
- **VFX:** Niagara/Cascade VFX.