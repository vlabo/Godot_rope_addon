# Godot_rope_addon

## Works only with godot 2 

This is an Godot addon for rope phisics.


The shape of the rope is controlled by curves. When the game starts between every two points of the curve is created a 
rigid body and connected to his neighbours whit pin joints.

You can add or remove control points of the curve and you can pin any of them.

* __Backe Interval__: Sets the distance in pixels between two adjacent points
* __Width__: Width of every rigid body
* __Softness__: Sofftnes of every pin joint
* __Mass__: Mass of every rigid body
* __Bounce__: Bouncines of every rigid body
* __Pined Points__:  Array that contains which control points are pinned. It is controlled from the UI:
the small pin icon (if it's red it means it is pined). By default the first is pined.


[Demo video](https://youtu.be/TYSG07SOMr8)
