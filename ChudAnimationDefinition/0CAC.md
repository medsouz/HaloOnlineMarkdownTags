# [0x0CAC] 0x00000CAC

**Name:** ```0x00000CAC```

**Index:** ```0x0CAC```

**Tag Group:** ```ChudAnimationDefinition (chad)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|UInt16	|0
Unknown	|Int16	|0
Position	|TagBlock (Position)	|0
Rotation	|TagBlock (Rotation)	|0
Size	|TagBlock (Size)	|[1](#size)
Color	|TagBlock (Color)	|0
Alpha	|TagBlock (Alpha)	|[1](#alpha)
AlphaUnknown	|TagBlock (AlphaUnknown)	|0
Bitmap	|TagBlock (Bitmap)	|0
NumberOfFrames	|Int32	|1800


## Tag Blocks

### Size

**0:**

Name	| Type	| Value
---	|---	|---	|
Animation	|TagBlock (Size_Animation)	|[3](#size_animation)
Unknown	|Byte[]	|System.Byte[]


### Size_Animation

**0:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|200
StretchX	|Single	|1.15
StretchY	|Single	|1.15


**1:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|300
StretchX	|Single	|1
StretchY	|Single	|1


**2:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|1800
StretchX	|Single	|1
StretchY	|Single	|1


### Alpha

**0:**

Name	| Type	| Value
---	|---	|---	|
Animation	|TagBlock (Alpha_Animation)	|[4](#alpha_animation)
Function	|Byte[]	|System.Byte[]


### Alpha_Animation

**0:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|100
Alpha	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|200
Alpha	|Single	|0.8


**2:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|1400
Alpha	|Single	|0.8


**3:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|1800
Alpha	|Single	|0


