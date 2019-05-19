# 05_Animated-Lamp
An animated lamp, like the famous movie lamp. (PL_CBC)



# Complete Blender Creator - Section 5 - Animated Lamp

This is the [Complete Blender Creator course]( http://gdev.tv/cbcgithub) - one of the bestselling and highest rated Blender courses on Udemy! Continually updated in response to student suggestions, you will benefit from the fact we have already taught over 360,336 students game development and design, many shipping commercial games as a result.

You're welcome to download, fork or do whatever else legal with all the files! The real value is in our huge, high-quality online tutorials that accompany this repo. You can check out the course here: [Complete Blender Creator]( http://gdev.tv/cbcgithub)

## In This Section

### 1 Animated Lamp Introduction

+ Mikey and Ben Introduce the Animated Lamp Section.
+ Mikey gives a quick run through of what is coming up in the next section.

### Animation Design Document

### Focus On What's Important

+ We are going to do many iterations though to the end, even though the lamp won't be built fully!
+ Later on rendering times are likely to be longer that the last section.
+ We'll be making and testing the Lamp as we go.

### Creating A Backdrop

+ Decide on a scale.
+ Create a basic environment for our lamp.
+ Run through a couple of options.

### Cycles Vs Eevee

+ Blender Render is generally quick and you get a reasonable result quickly. - Uses CPU Only.
+ Cycles is a physical based renderer is accurate but takes longer. It is designed for GPUs but runs fine on CPUs.

**Why Use Cycles?**

+ We are going to use Cycles, since we are modelling a lamp!
+ The two are not cross compatible, no switching.
+ You can use other Renderers too, if you have access to them. We won't be covering these.

**Render Time Difference**

+ I will be showing you 3 Clips of a 4 second bowling ball animation.
+ Blender Render - 2 mins
+ Basic Cycles Render - 15 mins
+ Thorough Cycles Render - 4 hours!

**Your Machine Specs : CPU**

+ Lots of different machine specs- vary massively.
+ More Cores and Higher Frequency CPU.
+ You are unlikely to hit memory limits when using CPU Rendering.
+ You cannot use CPU and GPU at the same time.

**Your Machine Specs: Graphics Card**

+ nVidia cards- any that support CUDA.
+ AMD/ATi Cards - Support has started not complete.
+ You may hit memory issues if using a GPU.
+ If in doubt or having trouble switch to CPU rendering.

### Lighting Cycles Vs Eevee

+ Lighting is nearly always darker in Eevee.
+ How to create a light source as geometry and then apply an emissive material to that object- something not possible in Eevee.

### Reflections Cycles Vs Eevee 
+ Reflection are another thing that are less accurate in Eevee.
+ Reflections in Cycles are fully calculated,


### Dedicated Graphics Cards

+ Cycles runs with AMD and nVidia Cards.
+ Install the latest drivers for your GPU.
+ If you do not have a dedicated nVidia or AMD Card
+ NOT ALWAYS QUICKER!

Setup Blender For GPU Rending

+ Optional, if you do not have a **dedicated** GPU, this lecture will not apply to you.
+ You may find that your GPU is **slower** than your CPU at rendering.
+ Your CPU is free to do other things…

### Lowering Your Cycles Render Time

+ How to change your Render settings.
+ You will have to run multiple tests.
+ Different scenes will have different characteristics depending on there complexity, but in general will follow a similar pattern.

### Rendering A Small Area

+ Show you how to render just a part of your scene.
+ Great for those with slower machines.
+ Great for complex Scenes on ANY computer.

### Using Curves To Generate Geometry

+ Using curves makes it infinitely editable.
+ Changing the bézier handle type.
+ Generate a 3D object by defining curves.

### Creating Geometry From A Curve

+ Refresh our knowledge on this.
+ Converting our curve object to a mesh object.
+ We can then perform mesh operations on it.
+ We can choose to delete the original curve data if we want to.

### Altering Curve Resolution

+ Culling Unnecessary Geometry
+ We kept the curve data so have two options:
+ Remake our mesh object, from those curves.
+ Fiddle about with the geometry itself.

**Which path to take?**

+ Both are OK- depends on stage of construction.
+ We'll be altering the curve resolution AND the mesh!
+ Tidy up the rest of our geometry.

### Existing Geometry To Create New

+ Use an existing face to create a new face.
+ Separate immediately creating a new object.
+ This allows us to match up parts of our model, even when they're not exact sizes.

### Design and Considerations

+ Design a rough outline for the lamp.
+ Make it believable as an object.
+ I have chosen a simple and raw design.
+ Remember It can always be beautified later on.

### Introduction to Armatures

+ Learn about the armature object.
+ Add an Armature to your model.

### Revisiting the Mirror Modifier

+ Learn how to use another object as the point of reflection.
+ Understand that it is the origin that acts as the point of reflection.
+ See other objects rotational values change the axes of reflection.

### Adding Bones To Our Armature

+ Learn how to add additional bones to an armature.
+ Understand that a new bone does not have to be connected to the previous one.

### Applying Transforms With Animations

+ Quick Reminder
+ If not done can have some very confusing issues
+ Remember Edit mode for editing

### Pose Mode

+ Be introduced to pose mode
+ Understand that we use this mode to test our models movement.
+ Know that this the best mode to be in to parent mesh objects to individual bones, and to make alterations.

### Rest Position and Pose Position

+ Understand the differences between rest position and pose position.
+ You can see the rest position when in edit mode.
+ How to clear the pose back to the rest state.

### Constraining Bones Movement

+ Be able to lock movement to a single axis.
+ Constrain the degree of movement possible.

### The Solidify Modifier

+ Create a 3D object from just curves.
+ Give the new object thickness using the solidify modifier.

### Introduction To The Node Editor

+ Open up the node editor.
+ Create some basic materials.
+ Apply these materials to our model.
+ See how adjustments in the node editor affect our model.

### Lamps vs Emissive Materials In Cycles

+ Learn the differences between the two light sources when using the cycles engine.
+ Understand that there is time and place for both.
+ Use the blackbody node.

### Auto Inverse Kinematics (IK)

+ Learn how to turn on Auto IK.
+ Realise that this is a starting point and not perfect!
+ Understand it applies to the whole rig.
+ See that it allows us to control the connected bones all at once.
+ Auto IK ignores any existing bone constraints

### Auto IK Constraints

+ We have lost the use of our bone constraints
+ Replace now with IK constraints instead 

### The Timeline

+ Be introduced to the timeline
+ Shown how to adjust the playback and rendering range.
+ How to alter the Frames Per Second (FPS) of your animation.

### Key Frames

+ Understand what they are and how they are used.
+ Be shown how to automatically add them and remove them from the Timeline view.
+ Realise almost everything can be keyframed.
+ Be able to use key frames to animate your lamp.

### The Dope Sheet
### The Graph Editor

### Setting Up The Camera

+ Understand that the camera view is for our animation rendering as well as a normal rendering.
+ Setup the camera ready for the Animation.
+ Animate the Camera!

### Rendering An Animation

+ Learn how to render your animation.
+ How to stop the rendering.
+ What settings to use for good results.
+ How to preview an animation once it has finished rendering.

### Rendering Across Multiple Blenders

+ Use multiple computers to render an animation.
+ Learn how to use multiple instances of Blender to utilise the CPU and GPU on your computer.
+ Decide on how many samples for the final animation.

### Creating A Video of Your Animation

+ Be Introduced to the Video Editor.
+ Combine your rendered images in to a final video.
+ Explore various exporting options.
+ Export the images to a movie file.


### Exporting Your Lamp Model

+ Learn how to setup the FBX Export and understand why we use it.
+ Realise that your model is currently only suitable for Blender. The Export doesn’t fully work in the model's current state.

### Vertex Groups

+ Learn what a vertex group is.
+ Assign vertices to a vertex group.
+ See that because we created our model in parts, it is really easy to assign groupings.

### Re-Rigging Our Model

+ Un parent your lamp meshes and join them together ending up with one mesh object.
+ Rename your Vertex Groups and Bones so that they match.
+ Test your new rig.

### Exporting The Final Model

+ Export the model and test it.
+ Just watch if you don’t have Unity or Unreal installed so you can see the process.

### End of Section 5 Wrap Up

Mikey talks through the end of section wrap up.