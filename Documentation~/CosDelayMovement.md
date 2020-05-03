# CosDelayMovement
Combined prefab: CosMovement and DelayMovement

## Object Hierachy

```
CosDelayMovement
|- Target
|- DelayMovement
   |- Target
   |- DelayBasePoint
   |  |- DelayPoint
   |     |- CosMovement
   |        |- (abbreviation)
   |- HorizonDelayBase
   |  |- (abbreviation)
   |- VerticalDelayBase
      |- (abbreviation)
```

## Usage
You add "Parent Constraint" to your model and add Target to sourcers.

Please see each prefab document when you change them.