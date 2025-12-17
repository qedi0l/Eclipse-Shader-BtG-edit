# Eclipse BtG edit - An Eclipse edit of Bliss shader

Eclipse BtG edit is an edit of Eclipse specially for my WIP modpack "BtG". Core added feature is a celling fog layer in the overworld ported from nether. 

This celling fog appear around 100 blocks height and in case of my modpack you can't breathe free at the height ~100 blocks.

Notable changes/additions compared to Eclipse unstable:
 + Additional layer of in overworld

<img width="1920" height="1080" alt="2025-12-17_15 15 41" src="https://github.com/user-attachments/assets/f761531c-8d56-45c2-a609-51690d140820" />

Look from the top
<img width="1920" height="1080" alt="2025-12-17_15 15 28" src="https://github.com/user-attachments/assets/63a2db37-a169-4cf6-b7e5-8d9669367fb1" />
And inside of it
<img width="1920" height="1080" alt="2025-11-29_23 35 28" src="https://github.com/user-attachments/assets/7c479f38-d2f3-4331-9c21-bd98acc19522" />



Note: Currently this fog controlled by the same settings as the nether fog, but someday I will add settings for it.

### Use cases?
+ BtG modpack (WIP)
+ play with Thin Air mod

### SPECIAL THANKS:
+ Chocapic13, for the base shader
+ Xonk, for developing the great Bliss shader
+ WoMspace, for spending alot of time creating a DOF overhaul
+ Null, for doing a huge amount of work creating the voxel floodfill colored lighting
+ Emin, and Gri573, for teaching me how to stop alot of light leaking
+ RRe36 and Sixthsurge, for the great ideas to steal
+ Merlin1809 for [Eclipse shader](https://github.com/Merlin1809/Eclipse-Shader)

# You want MOAR performance?
 Delete the gbuffers_terrain.tcs and gbuffers_terrain.tes files for all world folders in the shaders.
 This will make the shader grass setting non functional BUT will increase performance, especially with high vanilla render distances!
 (If you're wondering why, Iris does NOT allow me to disable these files once they're there. So even when Shader Grass is disabled these execute and harm performance!)
