# [0x1BCF] 0x00001BCF

**Name:** ```0x00001BCF```

**Index:** ```0x1BCF```

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
PitchRanges	|TagBlock (PitchRanges)	|[2](#pitchranges)
CustomPlayBacks	|TagBlock (CustomPlayBacks)	|0
ExtraInfo	|TagBlock (ExtraInfo)	|[1](#extrainfo)
Languages	|TagBlock (Languages)	|0
Resource	|ResourceReference	|BlamCore.Cache.ResourceReference


## Tag Blocks

### PitchRanges

**0:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|double
PitchRangeParameters	|PitchRangeParametersBlock	|BlamCore.TagDefinitions.SoundCacheFileGestalt+PitchRangeParametersBlock
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|Int16	|-1
Unknown6	|Int16	|-1
PermutationCount	|Byte	|4
Unknown7	|Byte	|0
Unknown8	|Int16	|-1
Permutations	|TagBlock (PitchRanges_Permutations)	|[4](#pitchranges_permutations)


**1:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|single
PitchRangeParameters	|PitchRangeParametersBlock	|BlamCore.TagDefinitions.SoundCacheFileGestalt+PitchRangeParametersBlock
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|Int16	|-1
Unknown6	|Int16	|-1
PermutationCount	|Byte	|12
Unknown7	|Byte	|0
Unknown8	|Int16	|-1
Permutations	|TagBlock (PitchRanges_Permutations)	|[12](#pitchranges_permutations)


### PitchRanges_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|303_dirt_dbl1
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|46587
PermutationNumber	|UInt32	|0
IsNotFirstPermutation	|UInt32	|0
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|303_dirt_dbl2
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|43764
PermutationNumber	|UInt32	|1
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|308_dirt_dbl1
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|39229
PermutationNumber	|UInt32	|2
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|308_dirt_dbl2
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|41243
PermutationNumber	|UInt32	|3
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|303_dirt_sng1
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|7724
PermutationNumber	|UInt32	|4
IsNotFirstPermutation	|UInt32	|0
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|303_dirt_sng2
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|8446
PermutationNumber	|UInt32	|5
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|303_dirt_sng3
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|6254
PermutationNumber	|UInt32	|6
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|303_dirt_sng4
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|9430
PermutationNumber	|UInt32	|7
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|303_dirt_sng5
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|8873
PermutationNumber	|UInt32	|8
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|303_dirt_sng6
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|12063
PermutationNumber	|UInt32	|9
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**6:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|308_dirt_sng1
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|5125
PermutationNumber	|UInt32	|10
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**7:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|308_dirt_sng2
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|4611
PermutationNumber	|UInt32	|11
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**8:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|308_dirt_sng3
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|5444
PermutationNumber	|UInt32	|12
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**9:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|308_dirt_sng4
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|5385
PermutationNumber	|UInt32	|13
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**10:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|308_dirt_sng5
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|11422
PermutationNumber	|UInt32	|14
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**11:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|308_dirt_sng6
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|8342
PermutationNumber	|UInt32	|15
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


### PitchRanges_Permutations_PermutationChunks

**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|0
Size	|UInt16	|21402
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|21402
Size	|UInt16	|19836
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|41238
Size	|UInt16	|18270
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|59508
Size	|UInt16	|18792
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|78300
Size	|UInt16	|3654
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|81954
Size	|UInt16	|4176
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|86130
Size	|UInt16	|3132
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|89262
Size	|UInt16	|4698
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|93960
Size	|UInt16	|4176
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|98136
Size	|UInt16	|5742
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|103878
Size	|UInt16	|2610
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|106488
Size	|UInt16	|2610
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|109098
Size	|UInt16	|2610
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|111708
Size	|UInt16	|2610
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|114318
Size	|UInt16	|5220
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|119538
Size	|UInt16	|4176
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


### ExtraInfo

**0:**

Name	| Type	| Value
---	|---	|---	|
LanguagePermutations	|TagBlock (ExtraInfo_LanguagePermutations)	|[16](#extrainfo_languagepermutations)
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


**6:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**7:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**8:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**9:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**10:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**11:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**12:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**13:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**14:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**15:**

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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|46587
ResourceSampleOffset	|UInt32	|0
ResourceSampleSize	|UInt32	|21402
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|43764
ResourceSampleOffset	|UInt32	|21402
ResourceSampleSize	|UInt32	|19836
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|39229
ResourceSampleOffset	|UInt32	|41238
ResourceSampleSize	|UInt32	|18270
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|41243
ResourceSampleOffset	|UInt32	|59508
ResourceSampleSize	|UInt32	|18792
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|7724
ResourceSampleOffset	|UInt32	|78300
ResourceSampleSize	|UInt32	|3654
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|8446
ResourceSampleOffset	|UInt32	|81954
ResourceSampleSize	|UInt32	|4176
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|6254
ResourceSampleOffset	|UInt32	|86130
ResourceSampleSize	|UInt32	|3132
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|9430
ResourceSampleOffset	|UInt32	|89262
ResourceSampleSize	|UInt32	|4698
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|8873
ResourceSampleOffset	|UInt32	|93960
ResourceSampleSize	|UInt32	|4176
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|12063
ResourceSampleOffset	|UInt32	|98136
ResourceSampleSize	|UInt32	|5742
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|5125
ResourceSampleOffset	|UInt32	|103878
ResourceSampleSize	|UInt32	|2610
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|4611
ResourceSampleOffset	|UInt32	|106488
ResourceSampleSize	|UInt32	|2610
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|5444
ResourceSampleOffset	|UInt32	|109098
ResourceSampleSize	|UInt32	|2610
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|5385
ResourceSampleOffset	|UInt32	|111708
ResourceSampleSize	|UInt32	|2610
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|11422
ResourceSampleOffset	|UInt32	|114318
ResourceSampleSize	|UInt32	|5220
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|8342
ResourceSampleOffset	|UInt32	|119538
ResourceSampleSize	|UInt32	|4176
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


### ExtraInfo_LanguagePermutations_RawInfo_UnknownList

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|46976
Unknown3	|UInt32	|0
Unknown4	|UInt32	|46592
Unknown5	|UInt32	|0
Unknown6	|UInt32	|10240


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|44160
Unknown3	|UInt32	|0
Unknown4	|UInt32	|43776
Unknown5	|UInt32	|0
Unknown6	|UInt32	|10240


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|39680
Unknown3	|UInt32	|0
Unknown4	|UInt32	|39296
Unknown5	|UInt32	|0
Unknown6	|UInt32	|10240


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|41728
Unknown3	|UInt32	|0
Unknown4	|UInt32	|41344
Unknown5	|UInt32	|0
Unknown6	|UInt32	|10240


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|8192
Unknown3	|UInt32	|0
Unknown4	|UInt32	|7808
Unknown5	|UInt32	|0
Unknown6	|UInt32	|4096


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|8832
Unknown3	|UInt32	|0
Unknown4	|UInt32	|8448
Unknown5	|UInt32	|0
Unknown6	|UInt32	|4096


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|6656
Unknown3	|UInt32	|0
Unknown4	|UInt32	|6272
Unknown5	|UInt32	|0
Unknown6	|UInt32	|2048


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|9856
Unknown3	|UInt32	|0
Unknown4	|UInt32	|9472
Unknown5	|UInt32	|0
Unknown6	|UInt32	|4096


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|9344
Unknown3	|UInt32	|0
Unknown4	|UInt32	|8960
Unknown5	|UInt32	|0
Unknown6	|UInt32	|4096


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|12544
Unknown3	|UInt32	|0
Unknown4	|UInt32	|12160
Unknown5	|UInt32	|0
Unknown6	|UInt32	|4096


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|5632
Unknown3	|UInt32	|0
Unknown4	|UInt32	|5248
Unknown5	|UInt32	|0
Unknown6	|UInt32	|2048


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|5120
Unknown3	|UInt32	|0
Unknown4	|UInt32	|4736
Unknown5	|UInt32	|0
Unknown6	|UInt32	|2048


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|5888
Unknown3	|UInt32	|0
Unknown4	|UInt32	|5504
Unknown5	|UInt32	|0
Unknown6	|UInt32	|2048


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|5888
Unknown3	|UInt32	|0
Unknown4	|UInt32	|5504
Unknown5	|UInt32	|0
Unknown6	|UInt32	|2048


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|11904
Unknown3	|UInt32	|0
Unknown4	|UInt32	|11520
Unknown5	|UInt32	|0
Unknown6	|UInt32	|4096


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|8832
Unknown3	|UInt32	|0
Unknown4	|UInt32	|8448
Unknown5	|UInt32	|0
Unknown6	|UInt32	|4096


