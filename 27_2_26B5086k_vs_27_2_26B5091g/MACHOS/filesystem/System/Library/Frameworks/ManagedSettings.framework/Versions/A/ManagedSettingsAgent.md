## ManagedSettingsAgent

> `/System/Library/Frameworks/ManagedSettings.framework/Versions/A/ManagedSettingsAgent`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_capture`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-318.0.0.0.0
-  __TEXT.__text: 0x657cc
-  __TEXT.__auth_stubs: 0x1b30
+319.0.0.0.0
+  __TEXT.__text: 0x65d74
+  __TEXT.__auth_stubs: 0x1c40
   __TEXT.__objc_stubs: 0x900
   __TEXT.__objc_methlist: 0x504
   __TEXT.__const: 0x1b3c
-  __TEXT.__cstring: 0x7d5
+  __TEXT.__cstring: 0x825
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constg_swiftt: 0xf80
   __TEXT.__swift5_typeref: 0xe6f

   __TEXT.__objc_classname: 0x67c
   __TEXT.__objc_methtype: 0x982
   __TEXT.__objc_methname: 0x1669
-  __TEXT.__oslogstring: 0x2b72
+  __TEXT.__oslogstring: 0x2b82
   __TEXT.__swift5_protos: 0x2c
   __TEXT.__swift5_capture: 0x32c
   __TEXT.__unwind_info: 0xf10

   __DATA_CONST.__objc_protolist: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x70
-  __DATA_CONST.__auth_got: 0xda0
-  __DATA_CONST.__got: 0x480
+  __DATA_CONST.__auth_got: 0xe28
+  __DATA_CONST.__got: 0x488
   __DATA_CONST.__auth_ptr: 0x3e0
   __DATA.__objc_const: 0x1a58
   __DATA.__objc_selrefs: 0x390

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 983
-  Symbols:   676
-  CStrings:  492
+  Functions: 984
+  Symbols:   694
+  CStrings:  495
 
Symbols:
+ _$s15ManagedSettings15enableTelemetrys12StaticStringVvg
+ _$s2os12OSSignpostIDV3logACSo03OS_a1_D0C_tcfC
+ _$s2os12OSSignpostIDV8rawValues6UInt64Vvg
+ _$s2os12OSSignpostIDVMa
+ _$s2os12OSSignposterV15ManagedSettingsE5agentACvgZ
+ _$s2os12OSSignposterV9logHandleSo03OS_a1_C0Cvg
+ _$s2os12OSSignposterVMa
+ _$s2os15OSSignpostErrorO9doubleEndyA2CmFWC
+ _$s2os15OSSignpostErrorOMa
+ _$s2os23OSSignpostIntervalStateC10signpostIDAA0bF0Vvg
+ _$s2os23OSSignpostIntervalStateC2id6isOpenAcA0B2IDV_Sbtcfc
+ _$s2os23OSSignpostIntervalStateCMa
+ _$s2os28checkForErrorAndConsumeState5stateAA010OSSignpostD0OAA0i8IntervalG0C_tF
+ _$sSo18os_signpost_type_ta0A0E3endABvgZ
+ _$sSo18os_signpost_type_ta0A0E5beginABvgZ
+ _$sSo9OS_os_logC0B0E16signpostsEnabledSbvg
+ _$ss12StaticStringV11descriptionSSvg
+ __os_signpost_emit_with_name_impl
Functions:
~ sub_10002b2d8 : 1220 -> 1808
+ sub_10002b9e8
CStrings:
+ "%{public}s"
+ "[Error] Interval already ended"
+ "managedsettings-agent-updateStore"
```
