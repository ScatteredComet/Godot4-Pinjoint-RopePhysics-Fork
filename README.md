# NOTICE
This is a fork of [Elij4hMartin's repo](https://github.com/Elij4hMartin/Godot4-PinJoint-RopePhysics), with:
- binary files removed
- png's moved to git lfs
- bumped to Godot v4.6
- folder structure more easily usable within other projects

I do not own and did not create any of the code, algorithms or logic. The original code is under [MIT license](/LICENSE).

# Godot4 PinJoint RopePhysics
An implementation of rope physics using Path3D nodes to procedurally generate geometry, and PinJoint3D nodes to approximate rope physics.
- Play the demo here on itch.io: https://palin-drome.itch.io/godot-4-3d-pinjoint-rope-physics
## Script usage instructions:
- Add a path_3d_rope.tscn node to your scene
- Change curve3D to your desired shape
- Change the number of segments based on the shape and length of the curve
- Adjust the number of sides the mesh has, and its thickness
- Choose to fix in place the ends of the rope by selecting, or attach rigid bodies to the ends of the rope by slecting a node
- Lastly you can change the material the procedurally generated mesh uses
- Then you can just run the project, and a rope will be procedurally generated from the Path3D
### CC0 Assets used: Kenney UI Pack, Kenney Prototype Textures
### Video DEMO and instructions:
[![VIDEO DEMO](https://img.youtube.com/vi/2hXNkVEJu10/0.jpg)](https://www.youtube.com/watch?v=2hXNkVEJu10)
