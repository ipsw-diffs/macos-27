## Shared Screen Viewer

> `/System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Support/Shared Screen Viewer.app/Contents/MacOS/Shared Screen Viewer`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__objc_methtype`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-768.2.15.1.0
-  __TEXT.__text: 0x115fbc
-  __TEXT.__auth_stubs: 0x29c0
+768.6.0.0.0
+  __TEXT.__text: 0x116a00
+  __TEXT.__auth_stubs: 0x29e0
   __TEXT.__objc_stubs: 0x1a160
-  __TEXT.__objc_methlist: 0xe600
+  __TEXT.__objc_methlist: 0xe628
   __TEXT.__objc_classname: 0xe05
-  __TEXT.__objc_methname: 0x2588a
-  __TEXT.__cstring: 0x2b9b3
+  __TEXT.__objc_methname: 0x2593a
+  __TEXT.__cstring: 0x2bdbe
   __TEXT.__const: 0x34a0
-  __TEXT.__oslogstring: 0x17177
+  __TEXT.__oslogstring: 0x174c9
   __TEXT.__objc_methtype: 0x64a2
   __TEXT.__gcc_except_tab: 0xbc0
   __TEXT.__ustring: 0x126

   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_assocty: 0x18
   __TEXT.__swift5_proto: 0x8
-  __TEXT.__unwind_info: 0x3bf0
+  __TEXT.__unwind_info: 0x3c10
   __DATA_CONST.__const: 0x1738
   __DATA_CONST.__cfstring: 0x7300
   __DATA_CONST.__objc_classlist: 0x2f0

   __DATA_CONST.__objc_intobj: 0x108
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA_CONST.__objc_floatobj: 0x10
-  __DATA_CONST.__auth_got: 0x14f0
+  __DATA_CONST.__auth_got: 0x1500
   __DATA_CONST.__got: 0xa78
   __DATA_CONST.__auth_ptr: 0x88
-  __DATA.__objc_const: 0x11fc0
-  __DATA.__objc_selrefs: 0x8790
-  __DATA.__objc_ivar: 0xfd4
+  __DATA.__objc_const: 0x11fe0
+  __DATA.__objc_selrefs: 0x87b8
+  __DATA.__objc_ivar: 0xfd8
   __DATA.__objc_data: 0x1f40
   __DATA.__data: 0x1968
   __DATA.__bss: 0x898

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5437
-  Symbols:   1044
-  CStrings:  11900
+  Functions: 5444
+  Symbols:   1046
+  CStrings:  11925
 
Symbols:
+ _NSStringFromClass
+ _NSStringFromSelector
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
+ "deliverPendingTouchNotificationIfGestureEnded:"
+ "draggingLocation"
+ "final srp_client_mech_step: %d"
+ "isEqualToData:"
+ "mPendingTouchNotification"
+ "no final SRP data -- server had nothing to prove, authentication is failing"
+ "no need to update key"
+ "no usable RSA host key after the key request phase (error %d); not attempting authentication"
+ "not importing public key for %s: does not parse as an RSA public key"
+ "notifyDelegateWithSelector:afterGesture:"
+ "retrieveRSAPublicKeyDataWithLabel:"
+ "return %d"
+ "touch gesture ended (state %ld), delivering %s"
+ "touch not supported by server"
+ "touch not supported in absolute control"
+ "touch not supported in combined display"
+ "touch not supported off console"
- "No SecKeyRef"
```
