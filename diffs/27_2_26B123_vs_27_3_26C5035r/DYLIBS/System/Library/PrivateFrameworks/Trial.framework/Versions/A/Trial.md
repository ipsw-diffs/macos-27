## Trial

> `/System/Library/PrivateFrameworks/Trial.framework/Versions/A/Trial`

```diff

-511.1.2.0.0
-  __TEXT.__text: 0x6cabc
+511.2.2.0.0
+  __TEXT.__text: 0x6d080
   __TEXT.__delay_stubs: 0x80
   __TEXT.__delay_helper: 0xa4
-  __TEXT.__objc_methlist: 0x5c14
+  __TEXT.__objc_methlist: 0x5c2c
   __TEXT.__const: 0xe2a
-  __TEXT.__cstring: 0x8257
-  __TEXT.__oslogstring: 0x45ad
-  __TEXT.__gcc_except_tab: 0x5338
+  __TEXT.__cstring: 0x826a
+  __TEXT.__oslogstring: 0x46f6
+  __TEXT.__gcc_except_tab: 0x5378
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x2708
+  __TEXT.__unwind_info: 0x2718
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_protolist: 0xb8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x20
-  __DATA_CONST.__objc_selrefs: 0x2d78
+  __DATA_CONST.__objc_selrefs: 0x2d98
   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__objc_superrefs: 0x280
   __DATA_CONST.__objc_arraydata: 0x158
   __DATA_CONST.__got: 0x6e8
   __AUTH_CONST.__const: 0x22b0
-  __AUTH_CONST.__cfstring: 0x61e0
-  __AUTH_CONST.__objc_const: 0xa2b0
+  __AUTH_CONST.__cfstring: 0x6200
+  __AUTH_CONST.__objc_const: 0xa2d0
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x120
   __AUTH_CONST.__objc_dictobj: 0x28

   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0xe60
   __AUTH.__data: 0xb8
-  __DATA.__objc_ivar: 0x5d4
+  __DATA.__objc_ivar: 0x5d8
   __DATA.__data: 0xb94
   __DATA.__bss: 0x68
   __DATA.__common: 0x10

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2165
-  Symbols:   5463
-  CStrings:  1242
+  Functions: 2168
+  Symbols:   5472
+  CStrings:  1248
 
Symbols:
+ -[TRIActiveFactorProvidersParser _resolveExperimentEndDatesMap]
+ -[TRIActiveFactorProvidersParser isExperimentExpired:]
+ GCC_except_table43
+ _OBJC_IVAR_$_TRIActiveFactorProvidersParserGuardedData.experimentEndDatesMap
+ ___54-[TRIActiveFactorProvidersParser isExperimentExpired:]_block_invoke
+ _objc_msgSend$_resolveExperimentEndDatesMap
+ _objc_msgSend$addEntriesFromDictionary:
+ _objc_msgSend$dateWithTimeIntervalSince1970:
+ _objc_msgSend$isExperimentExpired:
CStrings:
+ "Experiment %{public}@ has expired, not returning experiment identifiers"
+ "Experiment %{public}@ has expired, skipping factor provider"
+ "Experiment %{public}@ has expired, skipping global factor provider"
+ "Experiment end dates mapping does not exist in plplist: %@"
+ "Skipping expired experiment from enumerateActiveExperiments %{public}@"
+ "TrialXP_ClientFramework-511.2.2"
+ "experimentEndDates"
- "TrialXP_ClientFramework-511.1.2"
```
