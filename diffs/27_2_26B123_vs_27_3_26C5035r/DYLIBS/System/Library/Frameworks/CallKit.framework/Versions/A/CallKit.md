## CallKit

> `/System/Library/Frameworks/CallKit.framework/Versions/A/CallKit`

```diff

-1406.200.91.0.0
-  __TEXT.__text: 0x6ac44
-  __TEXT.__objc_methlist: 0x91fc
+1406.300.51.0.0
+  __TEXT.__text: 0x6af60
+  __TEXT.__objc_methlist: 0x926c
   __TEXT.__const: 0x130
-  __TEXT.__cstring: 0x6499
-  __TEXT.__oslogstring: 0x3c35
-  __TEXT.__gcc_except_tab: 0x71c
-  __TEXT.__unwind_info: 0x28c8
+  __TEXT.__cstring: 0x64ac
+  __TEXT.__oslogstring: 0x3c62
+  __TEXT.__gcc_except_tab: 0x840
+  __TEXT.__unwind_info: 0x28e8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1d8
-  __DATA_CONST.__objc_classlist: 0x408
+  __DATA_CONST.__objc_classlist: 0x410
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x1f0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x34b0
+  __DATA_CONST.__objc_selrefs: 0x34c8
   __DATA_CONST.__objc_protorefs: 0xb8
-  __DATA_CONST.__objc_superrefs: 0x388
+  __DATA_CONST.__objc_superrefs: 0x390
   __DATA_CONST.__objc_arraydata: 0x18
-  __DATA_CONST.__got: 0x4b8
+  __DATA_CONST.__got: 0x4c0
   __AUTH_CONST.__const: 0x1230
-  __AUTH_CONST.__cfstring: 0x42c0
-  __AUTH_CONST.__objc_const: 0xeed8
+  __AUTH_CONST.__cfstring: 0x42e0
+  __AUTH_CONST.__objc_const: 0xefb0
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x13b0
-  __DATA.__objc_ivar: 0x930
+  __AUTH.__objc_data: 0x1400
+  __DATA.__objc_ivar: 0x934
   __DATA.__data: 0x1740
   __DATA.__bss: 0xb0
   __DATA_DIRTY.__objc_data: 0x14a0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 3265
-  Symbols:   6782
-  CStrings:  1007
+  Functions: 3271
+  Symbols:   6800
+  CStrings:  1008
 
Symbols:
+ +[CXSetPrimaryVideoPausedCallAction supportsSecureCoding]
+ -[CXSetPrimaryVideoPausedCallAction copyWithZone:]
+ -[CXSetPrimaryVideoPausedCallAction encodeWithCoder:]
+ -[CXSetPrimaryVideoPausedCallAction initWithCallUUID:primaryVideoPaused:]
+ -[CXSetPrimaryVideoPausedCallAction initWithCoder:]
+ -[CXSetPrimaryVideoPausedCallAction isPrimaryVideoPaused]
+ GCC_except_table108
+ _OBJC_CLASS_$_CXSetPrimaryVideoPausedCallAction
+ _OBJC_IVAR_$_CXSetPrimaryVideoPausedCallAction._primaryVideoPaused
+ _OBJC_METACLASS_$_CXSetPrimaryVideoPausedCallAction
+ __OBJC_$_CLASS_METHODS_CXSetPrimaryVideoPausedCallAction
+ __OBJC_$_INSTANCE_METHODS_CXSetPrimaryVideoPausedCallAction
+ __OBJC_$_INSTANCE_VARIABLES_CXSetPrimaryVideoPausedCallAction
+ __OBJC_$_PROP_LIST_CXSetPrimaryVideoPausedCallAction
+ __OBJC_CLASS_RO_$_CXSetPrimaryVideoPausedCallAction
+ __OBJC_METACLASS_RO_$_CXSetPrimaryVideoPausedCallAction
+ ___block_descriptor_64_e8_32s40s48s56r_e20_B24?0?<B?^>8^16l
+ ___copy_helper_block_e8_32s40s48s56r
+ ___destroy_helper_block_e8_32s40s48s56r
+ _objc_msgSend$addExtensionWithIdentifier:error:
+ _objc_msgSend$provider:performSetPrimaryVideoPausedCallAction:
- ___block_descriptor_72_e8_32s40s48s56r64r_e20_B24?0?<B?^>8^16l
- ___copy_helper_block_e8_32s40s48s56r64r
- ___destroy_helper_block_e8_32s40s48s56r64r
CStrings:
+ "Failed to create new extension: %@"
+ "New extension's unique id not found; creating"
+ "Old extension not found; nothing to migrate"
+ "primaryVideoPaused"
- "Executing migration"
- "New extension's unique id not found"
- "Old extension not found"
```
