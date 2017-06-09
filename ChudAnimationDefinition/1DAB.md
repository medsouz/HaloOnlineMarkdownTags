# [0x1DAB] 0x00001DAB

**Name:** ```0x00001DAB```

**Index:** ```0x1DAB```

**Tag Group:** ```ChudAnimationDefinition (chad)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|UInt16	|0
Unknown	|Int16	|0
Position	|TagBlock (Position)	|[1](#position)
Rotation	|TagBlock (Rotation)	|[1](#rotation)
Size	|TagBlock (Size)	|[1](#size)
Color	|TagBlock (Color)	|0
Alpha	|TagBlock (Alpha)	|[1](#alpha)
AlphaUnknown	|TagBlock (AlphaUnknown)	|0
Bitmap	|TagBlock (Bitmap)	|0
NumberOfFrames	|Int32	|40


## Tag Blocks

### Position

**0:**

Name	| Type	| Value
---	|---	|---	|
Animation	|TagBlock (Position_Animation)	|[2](#position_animation)
Function	|Byte[]	|System.Byte[]


### Position_Animation

**0:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|0
PositionX	|Single	|0
PositionY	|Single	|0
PositionZ	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|40
PositionX	|Single	|-60
PositionY	|Single	|0
PositionZ	|Single	|0


### Rotation

**0:**

Name	| Type	| Value
---	|---	|---	|
Animation	|TagBlock (Rotation_Animation)	|[2](#rotation_animation)
Function	|Byte[]	|System.Byte[]


### Rotation_Animation

**0:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|0
XAngle	|Angle	|{ Degrees: -90, Radians: -1.570796 }
YAngle	|Angle	|{ Degrees: 0, Radians: 0 }
ZAngle	|Angle	|{ Degrees: 0, Radians: 0 }


**1:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|40
XAngle	|Angle	|{ Degrees: -90, Radians: -1.570796 }
YAngle	|Angle	|{ Degrees: 0, Radians: 0 }
ZAngle	|Angle	|{ Degrees: 0, Radians: 0 }


### Size

**0:**

Name	| Type	| Value
---	|---	|---	|
Animation	|TagBlock (Size_Animation)	|[2](#size_animation)
Unknown	|Byte[]	|System.Byte[]


### Size_Animation

**0:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|0
StretchX	|Single	|0.3
StretchY	|Single	|0.3


**1:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|40
StretchX	|Single	|0.7
StretchY	|Single	|0.8


### Alpha

**0:**

Name	| Type	| Value
---	|---	|---	|
Animation	|TagBlock (Alpha_Animation)	|[2](#alpha_animation)
Function	|Byte[]	|System.Byte[]


### Alpha_Animation

**0:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|0
Alpha	|Single	|1


**1:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|40
Alpha	|Single	|1


