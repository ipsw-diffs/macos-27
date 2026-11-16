## WindowManager

> `/System/Library/CoreServices/WindowManager.app/Contents/MacOS/WindowManager`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`

```diff

-462.2.9.0.0
-  __TEXT.__text: 0x4722b0
-  __TEXT.__auth_stubs: 0x7df0
-  __TEXT.__objc_stubs: 0x3ca0
-  __TEXT.__objc_methlist: 0x1364
-  __TEXT.__const: 0x50928
-  __TEXT.__oslogstring: 0x450b
-  __TEXT.__cstring: 0x51df
+462.2.16.0.0
+  __TEXT.__text: 0x47a95c
+  __TEXT.__auth_stubs: 0x7e00
+  __TEXT.__objc_stubs: 0x3cc0
+  __TEXT.__objc_methlist: 0x1380
+  __TEXT.__const: 0x50ce8
+  __TEXT.__oslogstring: 0x456b
+  __TEXT.__cstring: 0x521f
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__swift5_typeref: 0x11a21
+  __TEXT.__swift5_typeref: 0x11ba5
   __TEXT.__objc_classname: 0x514c
-  __TEXT.__objc_methname: 0xa3c5
-  __TEXT.__constg_swiftt: 0x17f34
-  __TEXT.__swift5_reflstr: 0x1c020
-  __TEXT.__swift5_fieldmd: 0x19c24
-  __TEXT.__swift5_capture: 0x43c4
-  __TEXT.__swift5_proto: 0x2c58
-  __TEXT.__swift5_types: 0x1b8c
-  __TEXT.__swift5_assocty: 0x4c18
-  __TEXT.__objc_methtype: 0x1751
+  __TEXT.__objc_methname: 0xa425
+  __TEXT.__constg_swiftt: 0x18048
+  __TEXT.__swift5_reflstr: 0x1c190
+  __TEXT.__swift5_fieldmd: 0x19dac
+  __TEXT.__swift5_capture: 0x442c
+  __TEXT.__swift5_proto: 0x2c90
+  __TEXT.__swift5_types: 0x1ba0
+  __TEXT.__swift5_assocty: 0x4c30
+  __TEXT.__objc_methtype: 0x17a1
   __TEXT.__swift5_builtin: 0xb04
   __TEXT.__swift5_protos: 0x268
   __TEXT.__swift5_mpenum: 0xa1c
   __TEXT.__swift_as_entry: 0xc
   __TEXT.__swift_as_ret: 0xc
   __TEXT.__swift_as_cont: 0x14
-  __TEXT.__unwind_info: 0x159f8
-  __TEXT.__eh_frame: 0xa948
-  __DATA_CONST.__const: 0x35c50
+  __TEXT.__unwind_info: 0x15b78
+  __TEXT.__eh_frame: 0xacfc
+  __DATA_CONST.__const: 0x35ff8
   __DATA_CONST.__cfstring: 0x80
   __DATA_CONST.__objc_classlist: 0x928
   __DATA_CONST.__objc_protolist: 0x168

   __DATA_CONST.__objc_protorefs: 0xb0
   __DATA_CONST.__objc_superrefs: 0x18
   __DATA_CONST.__linkguard: 0xf
-  __DATA_CONST.__auth_got: 0x3f00
+  __DATA_CONST.__auth_got: 0x3f08
   __DATA_CONST.__got: 0x18e8
-  __DATA_CONST.__auth_ptr: 0x3af0
-  __DATA.__objc_const: 0x17ce8
-  __DATA.__objc_selrefs: 0x1130
+  __DATA_CONST.__auth_ptr: 0x3b28
+  __DATA.__objc_const: 0x17dd0
+  __DATA.__objc_selrefs: 0x1140
   __DATA.__objc_ivar: 0x50
-  __DATA.__objc_data: 0x3170
-  __DATA.__data: 0x28590
+  __DATA.__objc_data: 0x3178
+  __DATA.__data: 0x28710
   __DATA.__common: 0x558
-  __DATA.__bss: 0x456e0
+  __DATA.__bss: 0x45de0
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 34063
-  Symbols:   3280
-  CStrings:  3007
+  Functions: 34185
+  Symbols:   3282
+  CStrings:  3016
 
Symbols:
+ _$ss22KeyedEncodingContainerV15encodeIfPresent_6forKeyys6UInt64VSg_xtKF
+ _$ss6UInt64VSEsWP
CStrings:
+ "Rejecting bridged window management operation %{public}s from %{public}@"
+ "Vv24@0:8@\"_WMDesktopBackgroundClickInfo\"16"
+ "Window Server visible window list changed: %{public}s"
+ "_confirmedCurrentSpaces"
+ "_hiddenSpacesForDiagnostics"
+ "confirmedCurrentSpace"
+ "didProvideVisibilityHintForSpace: %{public}llu"
+ "fromTouch"
+ "isVisibleSpace"
+ "notifyClickDidEndOnDesktopBackgroundWindowWithInfo:"
+ "requestedCurrentSpace"
+ "selectionScope"
+ "showDesktopCompositeCompletedDuringGesture"
- "Window Server visible window list changed: %s "
- "_visibleSpaces"
- "didProvideVisibilityHintForSpace: %s"
- "invokeFallback"
```
