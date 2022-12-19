# Blender-particle-system-to-objects
A script for blender (3.3.0) that turns a particle system into a collection of objects. Based on a script by StackOverflow user spiraloid, which itself was based on a script by daylanKifky.
https://blender.stackexchange.com/questions/4956/convert-particle-system-to-animated-meshes

Be aware, I'm not very well versed in Python. I barely understand most of this script and just changed a few parameters. Use at your own risk.
It will use random items from a provided collection to attach to the particles. It does not randomize in the same way that Blender's own particle system works. I'm afraid it'll take a far more skilled coder to tackle that one.

To use:
Change the value of "PARTICLE_COLLECTION" to the name of the collection that contains. Then select the object that contains the particle system (and only that object, unlike the original script) and run the script. The new particles will be in a new collection called Particles, and all objects will be set to hidden in the viewport (which is not the same as "visible in viewport"), so you'll have to manually make them visible.
