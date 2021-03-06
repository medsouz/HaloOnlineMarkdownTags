# [0x2BBF] objects\characters\odst\odst

**Name:** ```objects\characters\odst\odst```

**Index:** ```0x2BBF```

**Tag Group:** ```CollisionModel (coll)```

## Fields

Name	| Type	| Value
---	|---	|---	|
CollisionModelChecksum	|Int32	|521798934
Errors	|TagBlock (Errors)	|0
Flags	|UInt32	|0
Materials	|TagBlock (Materials)	|[2](#materials)
Regions	|TagBlock (Regions)	|[1](#regions)
PathfindingSpheres	|TagBlock (PathfindingSpheres)	|0
Nodes	|TagBlock (Nodes)	|[55](#nodes)


## Tag Blocks

### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|head


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|body


### Regions

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|body
Permutations	|TagBlock (Regions_Permutations)	|[1](#regions_permutations)


### Regions_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|standard
Bsps	|TagBlock (Regions_Permutations_Bsps)	|[16](#regions_permutations_bsps)
BspPhysics	|TagBlock (Regions_Permutations_BspPhysics)	|0
BspMoppCodes	|TagBlock (Regions_Permutations_BspMoppCodes)	|0


### Regions_Permutations_Bsps

**0:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|0
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**1:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|1
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**2:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|3
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**3:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|4
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**4:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|5
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**5:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|6
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**6:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|7
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**7:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|8
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**8:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|9
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**9:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|15
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**10:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|16
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**11:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|17
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**12:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|18
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**13:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|38
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**14:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|39
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**15:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|42
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


### Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|pelvis
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|-1
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|1


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|l_thigh
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|0
NextSiblingNode	|Int16	|2
FirstChildNode	|Int16	|5


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|physics_control
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|0
NextSiblingNode	|Int16	|3
FirstChildNode	|Int16	|-1


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|r_thigh
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|0
NextSiblingNode	|Int16	|4
FirstChildNode	|Int16	|6


**4:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|spine
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|0
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|7


**5:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|l_calf
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|1
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|8


**6:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|r_calf
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|3
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|9


**7:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|spine1
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|4
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|10


**8:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|l_foot
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|5
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|13


**9:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|r_foot
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|6
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|14


**10:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|l_clavicle
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|7
NextSiblingNode	|Int16	|11
FirstChildNode	|Int16	|15


**11:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|neck
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|7
NextSiblingNode	|Int16	|12
FirstChildNode	|Int16	|16


**12:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|r_clavicle
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|7
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|17


**13:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|l_toe
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|8
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


**14:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|r_toe
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|9
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


**15:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|l_upperarm
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|10
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|18


**16:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|head
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|11
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|19


**17:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|r_upperarm
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|12
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|38


**18:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|l_forearm
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|15
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|39


**19:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|eye_left
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|20
FirstChildNode	|Int16	|-1


**20:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|eye_right
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|21
FirstChildNode	|Int16	|-1


**21:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_l_brow_inner
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|22
FirstChildNode	|Int16	|-1


**22:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_l_brow_outer
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|23
FirstChildNode	|Int16	|-1


**23:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_l_cheek
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|24
FirstChildNode	|Int16	|-1


**24:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_l_eyelid_lower
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|25
FirstChildNode	|Int16	|-1


**25:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_l_eyelid_upper
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|26
FirstChildNode	|Int16	|-1


**26:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_l_lip_upper
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|27
FirstChildNode	|Int16	|-1


**27:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_l_mouth
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|28
FirstChildNode	|Int16	|-1


**28:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_l_nose_corner
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|29
FirstChildNode	|Int16	|-1


**29:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_r_brow_inner
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|30
FirstChildNode	|Int16	|-1


**30:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_r_brow_outer
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|31
FirstChildNode	|Int16	|-1


**31:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_r_cheek
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|32
FirstChildNode	|Int16	|-1


**32:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_r_eyelid_lower
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|33
FirstChildNode	|Int16	|-1


**33:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_r_eyelid_upper
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|34
FirstChildNode	|Int16	|-1


**34:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_r_lip_upper
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|35
FirstChildNode	|Int16	|-1


**35:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_r_mouth
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|36
FirstChildNode	|Int16	|-1


**36:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_r_nose_corner
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|37
FirstChildNode	|Int16	|-1


**37:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|jaw
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|16
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|40


**38:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|r_forearm
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|17
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|42


**39:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|l_hand
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|18
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|43


**40:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_l_lip_lower
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|37
NextSiblingNode	|Int16	|41
FirstChildNode	|Int16	|-1


**41:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|f_r_lip_lower
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|37
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


**42:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|r_hand
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|38
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|46


**43:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|l_index1
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|39
NextSiblingNode	|Int16	|44
FirstChildNode	|Int16	|49


**44:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|l_ring1
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|39
NextSiblingNode	|Int16	|45
FirstChildNode	|Int16	|50


**45:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|l_thumb1
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|39
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|51


**46:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|r_index1
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|42
NextSiblingNode	|Int16	|47
FirstChildNode	|Int16	|52


**47:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|r_ring1
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|42
NextSiblingNode	|Int16	|48
FirstChildNode	|Int16	|53


**48:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|r_thumb1
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|42
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|54


**49:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|l_index2
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|43
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


**50:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|l_ring2
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|44
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


**51:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|l_thumb2
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|45
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


**52:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|r_index2
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|46
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


**53:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|r_ring2
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|47
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


**54:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|r_thumb2
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|48
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


