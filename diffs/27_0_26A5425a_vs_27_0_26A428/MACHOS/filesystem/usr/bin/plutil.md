## plutil

> `/usr/bin/plutil`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 5027.0.69.0.0
-  __TEXT.__text: 0x1fb60
+  __TEXT.__text: 0x1f4f8
   __TEXT.__auth_stubs: 0xbb0
   __TEXT.__objc_stubs: 0xf00
   __TEXT.__objc_methlist: 0x298

   __TEXT.__swift5_builtin: 0x3c
   __TEXT.__swift5_mpenum: 0x10
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__unwind_info: 0x430
-  __TEXT.__eh_frame: 0x828
+  __TEXT.__unwind_info: 0x4f0
+  __TEXT.__eh_frame: 0x830
   __DATA_CONST.__const: 0xcd8
   __DATA_CONST.__cfstring: 0x1000
   __DATA_CONST.__objc_classlist: 0x18
Symbols:
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/Foundation/install/TempContent/Objects/Foundation.build/plutil.build/Objects-normal/arm64e/PLUContext-6b0d9e4b920eacfd24df6453b8d8f677.o
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/Foundation/install/TempContent/Objects/Foundation.build/plutil.build/Objects-normal/arm64e/PLUContext-85fe1b2ef7813111b9832035a4d17f97.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/Foundation/install/TempContent/Objects/Foundation.build/plutil.build/Objects-normal/arm64e/PLUContext-9fbb4fb7b7a449a9cbab295f97fc2476.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/Foundation/install/TempContent/Objects/Foundation.build/plutil.build/Objects-normal/arm64e/PLUContext-a6c61091ef9b63668b80dab822da89b0.o
Functions:
~ -[PLUMutableArray valueForKey:] : 180 -> 168
~ -[PLUMutableArray setValue:forKeyPath:atIndex:] : 296 -> 236
~ -[PLUMutableArray setValue:forKeyPath:] : 272 -> 260
~ +[PLUMutableDictionary dictionaryWithObjects:forKeys:count:] : 84 -> 72
~ -[PLUMutableDictionary setValue:forKeyPath:] : 336 -> 312
~ +[PLUContext contextWithArguments:outputFileHandle:errorFileHandle:] : 88 -> 76
~ -[PLUContext execute] : 1628 -> 1580
~ _newPropertyListWithInternalTypes : 860 -> 848
~ _propertyListIsValidForLiteralFormat : 636 -> 624
~ _newPropertyListByEnshrinkening : 956 -> 944
~ ___processPlist_block_invoke : 140 -> 128
~ ___copy_helper_block_e8_32o40o48o : 96 -> 84
~ ___destroy_helper_block_e8_32o40o48o : 80 -> 68
~ ___escapeKeysInPlist_block_invoke : 108 -> 96
~ ___unescapeKeysInPlist_block_invoke : 108 -> 96
~ ___copy_helper_block_e8_32b40r : 80 -> 68
~ ___destroy_helper_block_e8_32b40r : 68 -> 56
~ _compareKeys : 148 -> 136
~ ____swiftLiteralDictionaryWithPropertyList_block_invoke : 212 -> 200
~ ___copy_helper_block_e8_32o40o48r : 96 -> 84
~ ___destroy_helper_block_e8_32o40o48r : 80 -> 68
~ ____objCLiteralVariblePrintIntoString_block_invoke : 148 -> 136
~ ____objCLiteralDictionaryWithPropertyList_block_invoke : 220 -> 208
~ ____rawDictionaryWithPropertyList_block_invoke : 104 -> 92
~ ___prettyprint_internal_block_invoke : 160 -> 148
~ ___copy_helper_block_e8_32o40o48o56o64r : 128 -> 116
~ ___destroy_helper_block_e8_32o40o48o56o64r : 104 -> 92
~ _$s6plutil5value9atKeyPath2inypSgSS_yptF : 108 -> 96
~ _$s6plutil6_value9atKeyPath2in09remainingdE0ypSgSaySSG_yps10ArraySliceVySSGtF : 1300 -> 1292
~ _$s6plutil12_removeValue9atKeyPath2in09remainingeF0ypSgSaySSG_yps10ArraySliceVySSGtKF : 2708 -> 2712
~ _$s6plutil12_removeValue9atKeyPath0D5Index2of09remainingeF0ypSaySSG_SiSayypGs10ArraySliceVySSGtKF : 904 -> 908
~ _$s6plutil12_insertValue_9atKeyPath2in09remainingeF09replacing9appendingypyp_SaySSGyps10ArraySliceVySSGS2btKF : 4144 -> 4148
~ _$s6plutil12_insertValue_9atKeyPath0D5Index2of09remainingeF09replacing9appendingSayypGyp_SaySSGSiAIs10ArraySliceVySSGS2btKF : 2072 -> 2080
~ _$sSlsE5split9maxSplits25omittingEmptySubsequences14whereSeparatorSay11SubSequenceQzGSi_S2b7ElementQzKXEtKFSS_Tg5 : 968 -> 972
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFSs_Tg5 : 268 -> 260
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFyp_Tg5 : 272 -> 264
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFSS_Tg5 : 268 -> 260
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFyp_Tg5 : 272 -> 264
~ _$ss22__RawDictionaryStorageC4findys10_HashTableV6BucketV6bucket_Sb5foundtxSHRzlFSS_Tg5 : 120 -> 108
~ _$sSS8_copyingySSSsFZ : 344 -> 332
~ _$ss22_ContiguousArrayBufferV19_uninitializedCount15minimumCapacityAByxGSi_SitcfCs5UInt8V_Tt1gq5 : 116 -> 112
~ _$ss17_NativeDictionaryV20_copyOrMoveAndResize8capacity12moveElementsySi_SbtFSS_ypTg5 : 700 -> 680
~ _$ss17_NativeDictionaryV4copyyyFSS_ypTg5 : 392 -> 384
~ _$ss17_NativeDictionaryV8setValue_6forKey8isUniqueyq_n_xSbtFSS_ypTg5 : 328 -> 304
~ _$sSa6append10contentsOfyqd__n_t7ElementQyd__RszSTRd__lFyp_SayypGTg5 : 256 -> 252
~ _$ss20_ArrayBufferProtocolPsE15replaceSubrange_4with10elementsOfySnySiG_Siqd__ntSlRd__7ElementQyd__AGRtzlFs01_aB0VyypG_s010CollectionH3OneVyypGTg5 : 332 -> 344
~ ___swift_destroy_boxed_opaque_existential_0 : 68 -> 48
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFSS_Tg5 : 268 -> 260
~ _$s6plutil19PLUContextArgumentsVwet : 72 -> 68
~ _$s6plutil32swiftLiteralDataWithPropertyList_16originalFileName10Foundation0D0Vyp_SStKF : 436 -> 416
~ _$s6plutil33_swiftLiteralDataWithPropertyList33_EB6C302B92FDEB1088B3414E11C53718LL_5depth6indent16originalFilenameSSyp_SiSbSStKF : 4832 -> 4792
~ _$s6plutil31objcLiteralDataWithPropertyList_16originalFileName03newiJ010Foundation0D0Vyp_S2StKF : 460 -> 440
~ _$s6plutil32_objcLiteralDataWithPropertyList33_EB6C302B92FDEB1088B3414E11C53718LL_5depth6indent16originalFilename06outputR0SSyp_SiSbS2StKF : 2208 -> 2212
~ _$s6plutil37objcLiteralHeaderDataWithPropertyList_16originalFileName03newjK010Foundation0E0Vyp_S2StKF : 456 -> 436
~ _$s6plutil35_objCLiteralVaribleWithPropertyList33_EB6C302B92FDEB1088B3414E11C53718LL_9forHeader16originalFilename06outputR0SSyp_SbS2StKF : 1832 -> 1812
~ _$s6plutil35propertyListIsValidForLiteralFormat_6formatSbyp_AA0gH0OtF : 888 -> 884
~ __swift_exist.box.addr_destructor : 56 -> 44
~ ___swift_project_boxed_opaque_existential_0 : 68 -> 48
~ _$sSr15_stableSortImpl2byySbx_xtKXE_tKFySryxGz_SiztKXEfU_SS_Tg5 : 1312 -> 1308
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFSnySiG_Tgq5 : 260 -> 252
~ _$ss22_ContiguousArrayBufferV19_uninitializedCount15minimumCapacityAByxGSi_SitcfCSS_Tt1g5 : 132 -> 128
~ _$sSTsE21_copySequenceContents12initializing8IteratorQz_SitSry7ElementQzG_tFSD4KeysVySSyp_G_Tg5 : 332 -> 328
~ _$s10Foundation4DataV15_RepresentationOWOy : 84 -> 72
~ _$s10Foundation4DataV15_RepresentationOWOe : 84 -> 72
~ _$s6plutil11LintCommandV7executeSbyKF : 2012 -> 1972
~ _$s6plutil11HelpCommandV7executeSbyKF : 400 -> 380
~ _$s6plutil14ConvertCommandV7executeSbyKF : 1856 -> 1816
~ _$s6plutil13InsertCommandV7executeSbyKF : 8880 -> 8804
~ _$s6plutil13RemoveCommandV7executeSbyKF : 5800 -> 5720
~ _$s6plutil14ExtractCommandV7executeSbyKF : 6216 -> 6136
~ _$s6plutil12PrintCommandV7executeSbyKF : 3524 -> 3464
~ _$s6plutil13CreateCommandV7executeSbyKF : 3124 -> 3064
~ _$s6plutil10PLUCommandO9arguments16outputFileHandle05erroreF0ACSaySSG_So06NSFileF0CAItKcfC : 3932 -> 3912
~ _$sSS6plutilE13lastComponentSSSgvg : 240 -> 220
~ _$sSYsSHRzSH8RawValueSYRpzrlE4hash4intoys6HasherVz_tF6plutil16PlutilExpectTypeO_Tg5 : 300 -> 288
~ _$s6plutil15PLUContextErrorO11descriptionSSvg : 688 -> 696
~ _$sSo12NSFileHandleC6plutilE5writeyySSF : 308 -> 288
~ _$sSo12NSFileHandleCs16TextOutputStream6plutilsACP5writeyySSFTW : 312 -> 292
~ _$sSo12NSFileHandleC6plutilE5write_9aboutPathySS_SStF : 592 -> 572
~ _$sSo12NSFileHandleC6plutilE5write_9aboutPathys5Error_p_SStF : 1316 -> 1300
~ _$s6plutil17writePropertyList_4path14standardOutput12outputFormat0H4Name09extensionJ015originalKeyPath8readable18terminatingNewline0H10ObjCHeaderyyp_SSSo12NSFileHandleCAA014PlutilEmissionI0OSSSgA2PS3btKF : 3816 -> 3756
~ _$s6plutil12PrintCommandV06prettyB0_6indent7spacingSSyp_S2itKF : 4260 -> 4224
~ _$s6plutil18sortDictionaryKeys4key14key2SbSS_SStF : 488 -> 468
~ _$s6plutil31propertyListIsValidForRawFormatySbypF : 568 -> 548
~ _$s6plutil25rawStringWithPropertyListySSypKF : 1452 -> 1412
~ _$sSS6plutilE4stemSSvg : 328 -> 308
~ _$ss22__RawDictionaryStorageC4findys10_HashTableV6BucketV6bucket_Sb5foundtxSHRzlFs11AnyHashableV_Tg5 : 68 -> 56
~ _$sSa6append10contentsOfyqd__n_t7ElementQyd__RszSTRd__lFSS_SaySSGTg5 : 252 -> 248
~ _$s6plutil16PlutilExpectTypeO12propertyListACyp_tcfCTf4nd_n : 672 -> 652
~ _$sSa15replaceSubrange_4withySnySiG_qd__nt7ElementQyd__RszSlRd__lFSS_s15EmptyCollectionVySSGTg5Tf4ndn_n : 192 -> 188
~ _$s6plutil16PlutilExpectTypeO8rawValueACSgSS_tcfCTf4nd_n : 76 -> 68
~ _$s6plutil15PLUContextErrorOWOy : 104 -> 80
~ _$s6plutil15PLUContextErrorOWOe : 104 -> 80
~ _$s6plutil11HelpCommandVwet : 72 -> 68
~ _$s6plutil14ConvertCommandVwet : 72 -> 68
~ _$s6plutil13RemoveCommandVwet : 72 -> 68
~ _$s6plutil14ExtractCommandVwet : 72 -> 68
~ _$s6plutil11LintCommandVwetTm : 72 -> 68
~ _$s6plutil13InsertCommandVwetTm : 72 -> 68
```
