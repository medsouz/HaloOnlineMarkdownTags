# 0x4DAA

**Index:** ```0x4DAA```

**Tag Group:** ```CollisionModel (coll)```

## Fields

Name	| Type	| Value
---	|---	|---	|
CollisionModelChecksum	|Int32	|521081860
Errors	|TagBlock (Errors)	|0
Flags	|UInt32	|0
Materials	|TagBlock (Materials)	|[2](#materials)
Regions	|TagBlock (Regions)	|[1](#regions)
PathfindingSpheres	|TagBlock (PathfindingSpheres)	|0
Nodes	|TagBlock (Nodes)	|[5](#nodes)


## Tag Blocks

### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hard_terrain_glass_unbreakable


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hard_metal_thick


### Regions

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|default
Permutations	|TagBlock (Regions_Permutations)	|[1](#regions_permutations)


### Regions_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|default
Bsps	|TagBlock (Regions_Permutations_Bsps)	|[2](#regions_permutations_bsps)
BspPhysics	|TagBlock (Regions_Permutations_BspPhysics)	|0
BspMoppCodes	|TagBlock (Regions_Permutations_BspMoppCodes)	|0


### Regions_Permutations_Bsps

**0:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|1
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**1:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|2
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


### Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|shutter_doors
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|-1
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|1


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|door_anim_large
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|0
NextSiblingNode	|Int16	|2
FirstChildNode	|Int16	|-1


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|door_anim_small
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|0
NextSiblingNode	|Int16	|3
FirstChildNode	|Int16	|-1


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|lock_large_anim
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|0
NextSiblingNode	|Int16	|4
FirstChildNode	|Int16	|-1


**4:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|lock_small_anim
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|0
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


