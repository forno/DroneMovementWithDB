# DroneDelayMovement
drone delay movement prefab variant from DelayMovement

## Object Hierachy

```
DelayMovement
|- Target 
|- DelayMoveGenerator
|  |- DelayBasePoint
|  |  |- DelayPoint
|  |- HorizonDelayBase
|  |  |- HorizonDelayMid
|  |     |- HorizonDelayMid
|  |- VerticalDelayBase
|     |- VerticalDelayMid
|        |- VerticalDelayMid
|- LookAtPoint
```

## Usage
You add "Parent Constraint" to your model and add Target to sourcers.

You can change LookAtPoint's z position for drone forward point.
You can change Dynamic Bone parameter of HorizonDelayBase and VerticaldelayBase.
I recommend to don't change them exclude Damping and Elasticity.

## description
The target follow DelayMove Position from last frame.
In ather words, Target are delay from DelayMovement.