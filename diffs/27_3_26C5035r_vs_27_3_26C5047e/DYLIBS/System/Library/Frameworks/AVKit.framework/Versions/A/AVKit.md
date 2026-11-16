## AVKit

> `/System/Library/Frameworks/AVKit.framework/Versions/A/AVKit`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-1395.6.2.0.0
-  __TEXT.__text: 0xe48c8
+1395.9.1.0.0
+  __TEXT.__text: 0xe4a48
   __TEXT.__objc_methlist: 0xe8a8
   __TEXT.__const: 0x1e48
   __TEXT.__constg_swiftt: 0x9c4

   __DATA_CONST.__objc_catlist: 0xa8
   __DATA_CONST.__objc_protolist: 0x2b0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7fa0
+  __DATA_CONST.__objc_selrefs: 0x7fb0
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x460
   __DATA_CONST.__objc_arraydata: 0x1e0
   __DATA_CONST.__got: 0xf50
   __AUTH_CONST.__const: 0x2fa0
   __AUTH_CONST.__cfstring: 0x7f20
-  __AUTH_CONST.__objc_const: 0x190d8
+  __AUTH_CONST.__objc_const: 0x190f8
   __AUTH_CONST.__objc_doubleobj: 0xc0
   __AUTH_CONST.__objc_intobj: 0x270
   __AUTH_CONST.__objc_arrayobj: 0x1e0

   __AUTH_CONST.__auth_got: 0xd80
   __AUTH.__objc_data: 0x3ca8
   __AUTH.__data: 0x2b0
-  __DATA.__objc_ivar: 0x1474
+  __DATA.__objc_ivar: 0x1478
   __DATA.__data: 0x2868
   __DATA.__bss: 0xe80
   __DATA.__common: 0xc0

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 5429
-  Symbols:   12220
+  Symbols:   12223
   CStrings:  1515
 
Symbols:
+ _OBJC_IVAR_$_AVDesktopPlayerViewContentView._pointerLocationInWindowOverride
+ _objc_msgSend$pointValue
+ _objc_msgSend$visibleRect
Functions:
~ -[AVDesktopPlayerViewContentView mouseExited:] : 328 -> 604
~ -[AVDesktopPlayerViewContentView .cxx_destruct] : 572 -> 592
~ sub_1dd0e4410 -> sub_1dd5ad538 : 492 -> 528
~ sub_1dd0eeda0 -> sub_1dd5b7eec : 112 -> 124
~ sub_1dd0f330c -> sub_1dd5bc464 : 296 -> 288
~ sub_1dd0fd768 -> sub_1dd5c68b8 : 252 -> 276
~ sub_1dd0fd864 -> sub_1dd5c69cc : 300 -> 324
```
