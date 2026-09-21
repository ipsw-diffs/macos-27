## assetutil

> `/usr/bin/assetutil`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1011.2.0.0.0
-  __TEXT.__text: 0xe57c4
-  __TEXT.__auth_stubs: 0x2710
+1011.3.0.0.0
+  __TEXT.__text: 0xe58c4
+  __TEXT.__auth_stubs: 0x2760
   __TEXT.__objc_stubs: 0xbb20
   __TEXT.__objc_methlist: 0x7290
   __TEXT.__const: 0x74e18
-  __TEXT.__gcc_except_tab: 0x1338
+  __TEXT.__gcc_except_tab: 0x1368
   __TEXT.__objc_methname: 0x11482
   __TEXT.__objc_classname: 0x1071
   __TEXT.__objc_methtype: 0x41f1
-  __TEXT.__cstring: 0x15645
+  __TEXT.__cstring: 0x15745
   __TEXT.__oslogstring: 0x28
   __TEXT.__swift5_typeref: 0x8a
   __TEXT.__swift5_capture: 0x68

   __TEXT.__swift5_builtin: 0x3c
   __TEXT.__swift5_proto: 0x10
   __TEXT.__swift5_types: 0x20
-  __TEXT.__unwind_info: 0x3310
+  __TEXT.__unwind_info: 0x3320
   __TEXT.__eh_frame: 0x30c
   __DATA_CONST.__const: 0x5388
   __DATA_CONST.__cfstring: 0x8180

   __DATA_CONST.__objc_arraydata: 0x2a0
   __DATA_CONST.__objc_arrayobj: 0x138
   __DATA_CONST.__objc_dictobj: 0x28
-  __DATA_CONST.__auth_got: 0x13a0
+  __DATA_CONST.__auth_got: 0x13c8
   __DATA_CONST.__got: 0x638
   __DATA_CONST.__auth_ptr: 0x100
   __DATA.__objc_const: 0xb6e8

   __DATA.__objc_data: 0x24e0
   __DATA.__data: 0x810
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x1ce8
+  __DATA.__bss: 0x1cf8
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/Frameworks/HIServices.framework/Versions/A/HIServices
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   Functions: 3919
-  Symbols:   823
-  CStrings:  5839
+  Symbols:   828
+  CStrings:  5843
 
Symbols:
+ ___cxa_guard_abort
+ ___cxa_guard_acquire
+ ___cxa_guard_release
+ _newlocale
+ _snprintf_l
Functions:
~ sub_10001f060 : 948 -> 1052
~ sub_10001f414 -> sub_10001f47c : 220 -> 216
~ sub_100027b38 -> sub_100027b9c : 964 -> 1068
~ sub_100027efc -> sub_100027fc8 : 284 -> 272
~ sub_100052ff0 -> sub_1000530b0 : 172 -> 284
~ sub_100084c78 -> sub_100084da8 : 136 -> 88
CStrings:
+ "CoreUI: Deepmap 2.0 block length %zu is smaller than its header"
+ "CoreUI: Deepmap 2.0 compressedBytes %llu exceeds block length %zu"
+ "CoreUI: Deepmap block length %zu is smaller than its header"
+ "CoreUI: Deepmap compressedBytes %llu exceeds block length %zu"
```
