# [0x1CFA] 0x00001CFA

**Name:** ```0x00001CFA```

**Index:** ```0x1CFA```

**Tag Group:** ```Sound (snd!)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (FlagsValue)	|null
Unknown1	|Int16	|0
Unknown2	|UInt32	|10
Unknown3	|UInt32	|0
SoundClass	|Enum (SoundClassValue)	|null
SampleRate	|Enum (SampleRateValue)	|null
Unknown6	|SByte	|0
ImportType	|Enum (ImportTypeValue)	|null
PlaybackParameters	|PlaybackParameter	|BlamCore.TagDefinitions.SoundCacheFileGestalt+PlaybackParameter
Scale	|Scale	|BlamCore.TagDefinitions.SoundCacheFileGestalt+Scale
PlatformCodec	|PlatformCodecBlock	|BlamCore.TagDefinitions.SoundCacheFileGestalt+PlatformCodecBlock
Promotion	|Promotion	|BlamCore.TagDefinitions.SoundCacheFileGestalt+Promotion
PitchRanges	|TagBlock (PitchRanges)	|[1](#pitchranges)
CustomPlayBacks	|TagBlock (CustomPlayBacks)	|0
ExtraInfo	|TagBlock (ExtraInfo)	|[1](#extrainfo)
Languages	|TagBlock (Languages)	|0
Resource	|ResourceReference	|BlamCore.Cache.ResourceReference


## Tag Blocks

### PitchRanges

**0:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	||default|
PitchRangeParameters	|PitchRangeParametersBlock	|BlamCore.TagDefinitions.SoundCacheFileGestalt+PitchRangeParametersBlock
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|Int16	|-1
Unknown6	|Int16	|-1
PermutationCount	|Byte	|3
Unknown7	|Byte	|0
Unknown8	|Int16	|-1
Permutations	|TagBlock (PitchRanges_Permutations)	|[3](#pitchranges_permutations)


### PitchRanges_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|rl_proj_lp1
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|149401
PermutationNumber	|UInt32	|0
IsNotFirstPermutation	|UInt32	|0
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|rl_proj_lp2
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|158361
PermutationNumber	|UInt32	|1
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|rl_proj_lp3
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|153192
PermutationNumber	|UInt32	|2
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


### PitchRanges_Permutations_PermutationChunks

**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|0
Size	|UInt16	|2528
Unknown2	|Byte	|1
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|68064
Size	|UInt16	|6720
Unknown2	|Byte	|1
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|140320
Size	|UInt16	|4096
Unknown2	|Byte	|1
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


### ExtraInfo

**0:**

Name	| Type	| Value
---	|---	|---	|
LanguagePermutations	|TagBlock (ExtraInfo_LanguagePermutations)	|[3](#extrainfo_languagepermutations)
EncodedPermutationSections	|TagBlock (ExtraInfo_EncodedPermutationSections)	|0
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


### ExtraInfo_LanguagePermutations

**0:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**1:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**2:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


### ExtraInfo_LanguagePermutations_RawInfo

**0:**

Name	| Type	| Value
---	|---	|---	|
SkipFractionName	|StringId	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0
Unknown17	|UInt32	|0
Unknown18	|UInt32	|0
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[3](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|9
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|149401
ResourceSampleOffset	|UInt32	|0
ResourceSampleSize	|UInt32	|68064
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
SkipFractionName	|StringId	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0
Unknown17	|UInt32	|0
Unknown18	|UInt32	|0
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[3](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|9
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|158361
ResourceSampleOffset	|UInt32	|68064
ResourceSampleSize	|UInt32	|72256
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
SkipFractionName	|StringId	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0
Unknown17	|UInt32	|0
Unknown18	|UInt32	|0
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[3](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|9
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|153192
ResourceSampleOffset	|UInt32	|140320
ResourceSampleSize	|UInt32	|69632
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|0


### ExtraInfo_LanguagePermutations_RawInfo_UnknownList

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|73216
Unknown3	|UInt32	|0
Unknown4	|UInt32	|72832
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|72192
Unknown3	|UInt32	|72832
Unknown4	|UInt32	|145024
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|4352
Unknown3	|UInt32	|145024
Unknown4	|UInt32	|149376
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|34816


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|72704
Unknown3	|UInt32	|0
Unknown4	|UInt32	|72320
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|72192
Unknown3	|UInt32	|72320
Unknown4	|UInt32	|144512
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|13824
Unknown3	|UInt32	|144512
Unknown4	|UInt32	|158336
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|36864


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|72192
Unknown3	|UInt32	|0
Unknown4	|UInt32	|71808
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|72192
Unknown3	|UInt32	|71808
Unknown4	|UInt32	|144000
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|9088
Unknown3	|UInt32	|144000
Unknown4	|UInt32	|153088
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|36864


