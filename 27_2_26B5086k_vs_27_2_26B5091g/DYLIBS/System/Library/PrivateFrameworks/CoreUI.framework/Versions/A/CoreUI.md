## CoreUI

> `/System/Library/PrivateFrameworks/CoreUI.framework/Versions/A/CoreUI`

```diff

-1011.2.0.0.0
-  __TEXT.__text: 0x125530
+1011.3.0.0.0
+  __TEXT.__text: 0x125660
   __TEXT.__delay_stubs: 0x140
   __TEXT.__delay_helper: 0xa4
   __TEXT.__objc_methlist: 0xb618
   __TEXT.__const: 0xa858
-  __TEXT.__gcc_except_tab: 0x308c
-  __TEXT.__cstring: 0x2c072
+  __TEXT.__gcc_except_tab: 0x30bc
+  __TEXT.__cstring: 0x2c162
   __TEXT.__oslogstring: 0x250
   __TEXT.__swift5_typeref: 0x3b0
   __TEXT.__swift5_capture: 0x168

   __TEXT.__swift5_mpenum: 0x18
   __TEXT.__swift5_proto: 0x20
   __TEXT.__swift5_types: 0x5c
-  __TEXT.__unwind_info: 0x5c70
+  __TEXT.__unwind_info: 0x5c78
   __TEXT.__eh_frame: 0x120
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __AUTH_CONST.__objc_arrayobj: 0x4c8
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_floatobj: 0x50
-  __AUTH_CONST.__auth_got: 0x1938
+  __AUTH_CONST.__auth_got: 0x1960
   __AUTH.__objc_data: 0x1fe8
   __AUTH.__data: 0x160
   __DATA.__objc_ivar: 0xdd0
   __DATA.__data: 0x878
-  __DATA.__bss: 0x15a0
+  __DATA.__bss: 0x15b0
   __DATA.__common: 0x8
   __DATA_DIRTY.__objc_data: 0x19c8
   __DATA_DIRTY.__data: 0x34

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 6745
-  Symbols:   14058
-  CStrings:  6224
+  Symbols:   14065
+  CStrings:  6229
 
Symbols:
+ __ZGVZL15__CSIBVGCLocalevE7localeC
+ __ZZL15__CSIBVGCLocalevE7localeC
+ ___cxa_guard_abort
+ ___cxa_guard_acquire
+ ___cxa_guard_release
+ _newlocale
+ _snprintf_l
Functions:
~ _CUIUncompressDeepmap2ImageData : 1056 -> 1160
~ ___CUIUncompressDeepmap2ImageData_block_invoke : 284 -> 272
~ _CUIUncompressDeepmapImageData : 1040 -> 1144
~ ___CUIUncompressDeepmapImageData_block_invoke : 220 -> 216
~ __ZN24CSIBVGNumericListDecoder11appendValueEd : 172 -> 284
CStrings:
+ "C"
+ "CoreUI: Deepmap 2.0 block length %zu is smaller than its header"
+ "CoreUI: Deepmap 2.0 compressedBytes %llu exceeds block length %zu"
+ "CoreUI: Deepmap block length %zu is smaller than its header"
+ "CoreUI: Deepmap compressedBytes %llu exceeds block length %zu"
```
