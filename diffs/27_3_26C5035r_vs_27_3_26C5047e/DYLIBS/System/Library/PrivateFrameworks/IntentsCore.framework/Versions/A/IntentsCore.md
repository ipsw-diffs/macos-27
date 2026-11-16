## IntentsCore

> `/System/Library/PrivateFrameworks/IntentsCore.framework/Versions/A/IntentsCore`

```diff

-4016.2.7.0.0
-  __TEXT.__text: 0x11174
-  __TEXT.__objc_methlist: 0xe74
+4016.2.11.0.0
+  __TEXT.__text: 0x113d8
+  __TEXT.__objc_methlist: 0xe9c
   __TEXT.__const: 0x90
   __TEXT.__dlopen_cstrs: 0x16a
   __TEXT.__gcc_except_tab: 0x1f8
-  __TEXT.__cstring: 0x1a71
+  __TEXT.__cstring: 0x1ac0
   __TEXT.__oslogstring: 0x13c2
-  __TEXT.__unwind_info: 0x548
+  __TEXT.__unwind_info: 0x550
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xe00
+  __DATA_CONST.__objc_selrefs: 0xe38
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x80
   __DATA_CONST.__objc_arraydata: 0x18
-  __DATA_CONST.__got: 0x378
-  __AUTH_CONST.__const: 0x9a0
+  __DATA_CONST.__got: 0x388
+  __AUTH_CONST.__const: 0x970
   __AUTH_CONST.__cfstring: 0x5c0
-  __AUTH_CONST.__objc_const: 0x1f90
+  __AUTH_CONST.__objc_const: 0x1fc0
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0x0
-  __DATA.__objc_ivar: 0x128
+  __DATA.__objc_ivar: 0x12c
   __DATA.__bss: 0x30
   __DATA_DIRTY.__objc_data: 0x7d0
   __DATA_DIRTY.__data: 0x360

   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 375
-  Symbols:   1263
+  Functions: 378
+  Symbols:   1277
   CStrings:  234
 
Symbols:
+ -[INCExtensionProxy _extensionAuditTokenData]
+ -[INCExtensionTransaction _updateCurrentUserActivityForType:intent:intentResponse:intentResponseSenderAuditTokenData:]
+ -[INCExtensionTransactionState initWithType:intent:intentResponse:intentResponseSenderAuditTokenData:userActivities:]
+ -[INCExtensionTransactionState intentResponseSenderAuditTokenData]
+ GCC_except_table158
+ GCC_except_table171
+ GCC_except_table217
+ GCC_except_table237
+ GCC_except_table246
+ GCC_except_table326
+ GCC_except_table340
+ GCC_except_table363
+ GCC_except_table368
+ _OBJC_CLASS_$_NSData
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_IVAR_$_INCExtensionTransactionState._intentResponseSenderAuditTokenData
+ ___118-[INCExtensionTransaction _updateCurrentUserActivityForType:intent:intentResponse:intentResponseSenderAuditTokenData:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48s56bs_e47_v32?0"INIntentResponse"8"NSData"16"NSSet"24l
+ _class_getSuperclass
+ _objc_msgSend$_extensionAuditTokenData
+ _objc_msgSend$_setInteraction:donate:intentResponseSenderAuditTokenData:
+ _objc_msgSend$_updateCurrentUserActivityForType:intent:intentResponse:intentResponseSenderAuditTokenData:
+ _objc_msgSend$if_auditToken
+ _objc_msgSend$if_dataWithAuditToken:
+ _objc_msgSend$if_typedCopy
+ _objc_msgSend$initWithType:intent:intentResponse:intentResponseSenderAuditTokenData:userActivities:
+ _objc_msgSend$intentResponseSenderAuditTokenData
+ _objc_msgSend$processInfo
+ _object_getClass
- -[INCExtensionTransaction _updateCurrentUserActivityForType:intent:intentResponse:]
- GCC_except_table157
- GCC_except_table170
- GCC_except_table216
- GCC_except_table236
- GCC_except_table245
- GCC_except_table323
- GCC_except_table337
- GCC_except_table360
- GCC_except_table365
- ___83-[INCExtensionTransaction _updateCurrentUserActivityForType:intent:intentResponse:]_block_invoke
- ___block_descriptor_56_e8_32s40s48s_e5_v8?0l
- ___block_descriptor_64_e8_32s40s48s56bs_e36_v24?0"INIntentResponse"8"NSSet"16l
- _objc_msgSend$_setInteraction:donate:
- _objc_msgSend$_updateCurrentUserActivityForType:intent:intentResponse:
CStrings:
+ "-[INCExtensionTransaction _updateCurrentUserActivityForType:intent:intentResponse:intentResponseSenderAuditTokenData:]"
+ "-[INCExtensionTransaction _updateCurrentUserActivityForType:intent:intentResponse:intentResponseSenderAuditTokenData:]_block_invoke"
+ "v32@?0@\"INIntentResponse\"8@\"NSData\"16@\"NSSet\"24"
- "-[INCExtensionTransaction _updateCurrentUserActivityForType:intent:intentResponse:]"
- "-[INCExtensionTransaction _updateCurrentUserActivityForType:intent:intentResponse:]_block_invoke"
- "v24@?0@\"INIntentResponse\"8@\"NSSet\"16"
```
