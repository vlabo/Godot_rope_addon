# Godot_rope_addon

This is an Godot for rope phisics


The shape of the rope is controlled by curve. When the game starts between every two points of the curve is created a 
rigid body and connected to his neighbours whit pin joint.

You can add or remove control points of the curve and you can pin every control point to the "wall".

* __Backe Interval__: Sets the distance in pixels between two adjacent cached points
* __Width__: the width of every rigid body
* __Softness__: the sofftnes of every pin joint
* __Mass__: the mass of every rigid body
* __Bounce__: the bouncines of every rigid body
* __Pined Points__: it is the array that contains which control points are pinned. It is controlled from the UI:
the small pin icon (if it's red it means it is pined). By default the first is pined


[Demo youtube video](https://youtu.be/TYSG07SOMr8)
