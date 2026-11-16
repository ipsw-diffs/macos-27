## TVRemoteCore

> `/System/Library/PrivateFrameworks/TVRemoteCore.framework/Versions/A/TVRemoteCore`

```diff

-627.20.10.0.0
-  __TEXT.__text: 0x4bfd8
-  __TEXT.__objc_methlist: 0x67e0
+627.20.15.0.0
+  __TEXT.__text: 0x4c230
+  __TEXT.__objc_methlist: 0x67f0
   __TEXT.__const: 0x242
   __TEXT.__cstring: 0x374e
   __TEXT.__gcc_except_tab: 0xbbc
-  __TEXT.__oslogstring: 0x6b5c
+  __TEXT.__oslogstring: 0x6c71
   __TEXT.__unwind_info: 0x18f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0xd8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3280
+  __DATA_CONST.__objc_selrefs: 0x3288
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x208
   __DATA_CONST.__objc_arraydata: 0xf8
   __DATA_CONST.__got: 0x4a0
   __AUTH_CONST.__const: 0x1390
   __AUTH_CONST.__cfstring: 0x4b00
-  __AUTH_CONST.__objc_const: 0xa0a0
+  __AUTH_CONST.__objc_const: 0xa0a8
   __AUTH_CONST.__objc_intobj: 0x288
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_doubleobj: 0x60

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   Functions: 2184
-  Symbols:   4746
-  CStrings:  1298
+  Symbols:   4747
+  CStrings:  1300
 
Symbols:
+ _objc_msgSend$rtiDataPayload
Functions:
~ -[TVRCKeyboardController _setCurrentState:] : 544 -> 988
~ ___36-[TVRCXPCClient deviceUpdatedState:]_block_invoke : 136 -> 292
CStrings:
+ "Keyboard state update: wasEditing %{bool}d, editing %{bool}d, old attributes %p (payload %{public}@, %lu bytes), new attributes %p (payload %{public}@, %lu bytes), same object %{bool}d, equal %{bool}d"
+ "finished delivering state update for %{public}@ (keyboard editing %{bool}d)"
```
