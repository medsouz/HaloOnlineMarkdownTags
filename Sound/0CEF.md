# [0x0CEF] 0x00000CEF

**Name:** ```0x00000CEF```

**Index:** ```0x0CEF```

**Tag Group:** ```Sound (snd!)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (FlagsValue)	|null
Unknown1	|Int16	|0
Unknown2	|UInt32	|0
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
PermutationCount	|Byte	|6
Unknown7	|Byte	|0
Unknown8	|Int16	|-1
Permutations	|TagBlock (PitchRanges_Permutations)	|[6](#pitchranges_permutations)


### PitchRanges_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|grtcem_shuf1
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: -2.49877 }
SampleSize	|UInt32	|25211
PermutationNumber	|UInt32	|0
IsNotFirstPermutation	|UInt32	|0
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|grtcem_shuf2
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: -2.498775 }
SampleSize	|UInt32	|31458
PermutationNumber	|UInt32	|1
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|grtcem_shuf3
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: -2.498775 }
SampleSize	|UInt32	|34913
PermutationNumber	|UInt32	|2
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|grtcem_shuf4
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: -2.498775 }
SampleSize	|UInt32	|30135
PermutationNumber	|UInt32	|3
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|grtcem_shuf5
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: -2.498775 }
SampleSize	|UInt32	|23667
PermutationNumber	|UInt32	|4
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|grtcem_shuf6
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: -2.498775 }
SampleSize	|UInt32	|25137
PermutationNumber	|UInt32	|5
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


### PitchRanges_Permutations_PermutationChunks

**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|0
Size	|UInt16	|50454
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|50454
Size	|UInt16	|62948
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|113402
Size	|UInt16	|4322
Unknown2	|Byte	|1
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|183260
Size	|UInt16	|60302
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|243562
Size	|UInt16	|47366
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|290928
Size	|UInt16	|50306
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


### ExtraInfo

**0:**

Name	| Type	| Value
---	|---	|---	|
LanguagePermutations	|TagBlock (ExtraInfo_LanguagePermutations)	|[6](#extrainfo_languagepermutations)
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


**3:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**4:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**5:**

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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[1](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|3
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|25211
ResourceSampleOffset	|UInt32	|0
ResourceSampleSize	|UInt32	|50454
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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[1](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|3
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|31458
ResourceSampleOffset	|UInt32	|50454
ResourceSampleSize	|UInt32	|62948
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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[1](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|3
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|34913
ResourceSampleOffset	|UInt32	|113402
ResourceSampleSize	|UInt32	|69858
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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[1](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|3
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|30135
ResourceSampleOffset	|UInt32	|183260
ResourceSampleSize	|UInt32	|60302
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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[1](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|3
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|23667
ResourceSampleOffset	|UInt32	|243562
ResourceSampleSize	|UInt32	|47366
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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[1](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|3
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|25137
ResourceSampleOffset	|UInt32	|290928
ResourceSampleSize	|UInt32	|50306
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
Unknown2	|UInt32	|25600
Unknown3	|UInt32	|0
Unknown4	|UInt32	|25216
Unknown5	|UInt32	|0
Unknown6	|UInt32	|6144


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|31872
Unknown3	|UInt32	|0
Unknown4	|UInt32	|31488
Unknown5	|UInt32	|0
Unknown6	|UInt32	|8192


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|35328
Unknown3	|UInt32	|0
Unknown4	|UInt32	|34944
Unknown5	|UInt32	|0
Unknown6	|UInt32	|8192


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|30592
Unknown3	|UInt32	|0
Unknown4	|UInt32	|30208
Unknown5	|UInt32	|0
Unknown6	|UInt32	|6144


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|24064
Unknown3	|UInt32	|0
Unknown4	|UInt32	|23680
Unknown5	|UInt32	|0
Unknown6	|UInt32	|6144


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|25600
Unknown3	|UInt32	|0
Unknown4	|UInt32	|25216
Unknown5	|UInt32	|0
Unknown6	|UInt32	|6144


