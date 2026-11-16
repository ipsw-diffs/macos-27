## ScreenSharing

> `/System/Library/PrivateFrameworks/ScreenSharing.framework/Versions/A/ScreenSharing`

```diff

-786.5.0.0.0
-  __TEXT.__text: 0x12428c
-  __TEXT.__objc_methlist: 0xec68
-  __TEXT.__cstring: 0x2df8e
+788.2.0.0.0
+  __TEXT.__text: 0x124cd0
+  __TEXT.__objc_methlist: 0xec90
+  __TEXT.__cstring: 0x2e399
   __TEXT.__const: 0x3580
-  __TEXT.__oslogstring: 0x17e84
+  __TEXT.__oslogstring: 0x181d6
   __TEXT.__gcc_except_tab: 0xd38
   __TEXT.__ustring: 0x17c
   __TEXT.__swift5_typeref: 0x132

   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_assocty: 0x18
   __TEXT.__swift5_proto: 0x8
-  __TEXT.__unwind_info: 0x40d8
+  __TEXT.__unwind_info: 0x40f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x1d8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8cf8
+  __DATA_CONST.__objc_selrefs: 0x8d20
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x308
   __DATA_CONST.__objc_arraydata: 0x3b8
   __DATA_CONST.__got: 0xcb0
   __AUTH_CONST.__const: 0x16b8
   __AUTH_CONST.__cfstring: 0x7d20
-  __AUTH_CONST.__objc_const: 0x12f70
+  __AUTH_CONST.__objc_const: 0x12f90
   __AUTH_CONST.__objc_intobj: 0x108
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_floatobj: 0x10
-  __AUTH_CONST.__auth_got: 0x1780
+  __AUTH_CONST.__auth_got: 0x1788
   __AUTH.__objc_data: 0x2210
   __AUTH.__data: 0x100
-  __DATA.__objc_ivar: 0x10c4
+  __DATA.__objc_ivar: 0x10c8
   __DATA.__data: 0x1938
   __DATA.__bss: 0x90c
   __DATA.__common: 0x19

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5776
-  Symbols:   12177
-  CStrings:  5391
+  Functions: 5784
+  Symbols:   12183
+  CStrings:  5410
 
Symbols:
+ +[RSAKeyPair retrieveRSAPublicKeyDataWithLabel:]
+ -[SSFrameBufferView deliverPendingTouchNotificationIfGestureEnded:]
+ -[SSFrameBufferView notifyDelegateWithSelector:afterGesture:]
+ GCC_except_table119
+ _NSStringFromClass
+ _OBJC_IVAR_$_SSFrameBufferView.mPendingTouchNotification
+ _RFBParseSupportListWithLength
+ _objc_msgSend$deliverPendingTouchNotificationIfGestureEnded:
+ _objc_msgSend$draggingLocation
+ _objc_msgSend$isEqualToData:
+ _objc_msgSend$notifyDelegateWithSelector:afterGesture:
+ _objc_msgSend$retrieveRSAPublicKeyDataWithLabel:
- GCC_except_table117
- _objc_msgSend$retrieveRSAPublicKeyWithLabel:
- _objc_msgSend$touchInputUnsupportedByServer
- _objc_msgSend$touchInputUnsupportedInAbsoluteControl
- _objc_msgSend$touchInputUnsupportedInCombinedDisplay
- _objc_msgSend$touchInputUnsupportedOffConsole
CStrings:
+ "+[RSAKeyPair loadRSAPublicKeyWithLabel:]"
+ "-[SSFrameBufferView deliverPendingTouchNotificationIfGestureEnded:]"
+ "-[SSFrameBufferView notifyDelegateWithSelector:afterGesture:]"
+ "RSA host key changed; SRP must verify it before it is committed"
+ "RSA public key store holds %s, not data; ignoring it"
+ "SRP did not verify the server (%d , Failing the authentication as a protocol error."
+ "SRP verified the server but the rotated RSA host key could not be committed"
+ "committed rotated RSA host key after SRP verified the server"
+ "deferring %s until the touch gesture ends"
+ "final srp_client_mech_step: %d"
+ "no final SRP data -- server had nothing to prove, authentication is failing"
+ "no need to update key"
+ "no usable RSA host key after the key request phase (error %d); not attempting authentication"
+ "not importing public key for %s: does not parse as an RSA public key"
+ "return %d"
+ "touch gesture ended (state %ld), delivering %s"
+ "touch not supported by server"
+ "touch not supported in absolute control"
+ "touch not supported in combined display"
+ "touch not supported off console"
- "No SecKeyRef"
```
