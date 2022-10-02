+++
description = "How to contribute if you are a visual artist"
title = "Art"
weight = 2
+++

---
### Motion Graphics
Motion graphics are to be developed on a per-requirement basis. Contact Fox for details.

---
### VFX
All VFX assets (Cascade or Niagara) are to be placed in the VFX folder. The VFX folder should house the actual VFX effects, while the assets for the same are to be placed in the TexMat folder inside the VFX folder.

---
### 2D - Concept(Character)
Concept art for the characters may be created in any DCC of your choice. This will be used to help 3d character artists develop game ready art. While not a necessary requirement, it's highly recommended to create a refsheet of the concept art. For example, the image on the left is concept art for our main character for Prelude, the Puppeteer, while the image on the right is the relevant refsheet for the same.:
{{< gallery "images/conceptart.png,images/refsheet.png" "Pup Concept Art::Pup Refsheet" >}}

---
### 2D - UI
UI assets must all be scaled and made to fit in a 1:1 ratio, with the exception of rectangular assets. This is to ensure correct scaling within the engine and editors, and must have a clear, transparent alpha channel.

---
### 2D - Texture
The maximum texture size to be used is 4096x4096. This is only to be used on hero assets that the player is likely to see often or up close. 1024x1024 is the recommended size for most textures, however, it's strongly recommended to use the size that's most appropriate for the asset.

---
### 3D - Environment
The choice of DCC to be used is up to the artist, however, there are a few technical guidelines to be followed. It's also highly suggested that lookdev is performed in-engine regularly against the provided lookdev scene to ensure consistency. 

We will be using a few select master materials that then have instances made from them. Please ensure you're using the instances of said materials instead of creating new ones. A fully featured PBR master material is provided in the engine.

All foliage must also be checked against the Kuwahara-blur painting post process effect.


---
### 3D - Character
Character art has special requirements for the Distributed Development project. All characters must be rigged to the Mixamo skeleton, using the Auto-Rigger. This reduces the burden of having to build a rig from scratch everytime. Additional bones may, however, be added.

Ensure that any open faces are closed up and each "part" is one single mesh, as opposed to being a composite of multiple meshes. 

Characters run on a separate post processing effect, and must be lookdev'ed in the provided lookdev scene with the post processing on the character active.

---
### 3D - Prop
See: Environment.

