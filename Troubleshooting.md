# Troubleshooting

## Character not going behind sprites correctly.

Edit -> Project Settings -> Transparency Sort Axis -> Set Z to 0, was previously -0.26 :shrug:
Made sure Grid GameObject was Isometric Z as Y
PlayerObject and Sprite (tree) were both on 
  - Sorting Layer = Default
  - Order in Layer = 0
  - Sprite Sort Point = Pivot
  - Manually moved pivot point in sprite editor myself

## Level not showing, player not showing

Adjust the Z transform of the MainCamera gameobject, try reducing it

0.4892206
0.1569989