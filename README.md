The edits I performed are to the kemono main body shape and model file. I restructured the shapes file to have the torso and arm names align with the vanilla character file rather than the b_body used. I also removed the separeted mesh for the body parts and attached them to the original named parts, changing the model json file to correctly reference the parts for use in the mod.
For some reason I am unable to remove the b_root part of the shape as that casues all 3rd person instances of the player model to crash the game. Similiarly I am unable to configure the legs as any change from the b_leg naming structure causes all animations and part positioning to fail, changing their reference points does not solve this. I suspect this is due to internal coding needing the b_part to reference since they are in different texture files.
I have not "opened" the mod any further to try and fix these issues, just messed with the json files and texures. I would have to teach myself on how to progress any further as i do wont to know why renaminmg all of the body parts was done in the first place. 
I suspect if the mod was rebuilt to have the body part names align with vanilla, all of this mod's issues would be resloved and CO compatability would be inherent.
