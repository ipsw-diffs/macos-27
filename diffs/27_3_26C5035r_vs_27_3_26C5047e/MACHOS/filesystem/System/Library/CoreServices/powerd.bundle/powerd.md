## powerd

> `/System/Library/CoreServices/powerd.bundle/powerd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2043.60.6.0.0
-  __TEXT.__text: 0x6d8e0
+2043.60.10.0.1
+  __TEXT.__text: 0x6d974
   __TEXT.__auth_stubs: 0x1dc0
-  __TEXT.__objc_stubs: 0x4520
-  __TEXT.__objc_methlist: 0x1e0c
+  __TEXT.__objc_stubs: 0x4560
+  __TEXT.__objc_methlist: 0x1e3c
   __TEXT.__const: 0x340
-  __TEXT.__cstring: 0x7b22
-  __TEXT.__objc_methname: 0x5d53
-  __TEXT.__oslogstring: 0xbf88
+  __TEXT.__cstring: 0x7b28
+  __TEXT.__objc_methname: 0x5de9
+  __TEXT.__oslogstring: 0xbfdc
   __TEXT.__objc_classname: 0x2a8
   __TEXT.__objc_methtype: 0x7b5
   __TEXT.__gcc_except_tab: 0x3e4
   __TEXT.__dlopen_cstrs: 0x152
-  __TEXT.__unwind_info: 0x2010
+  __TEXT.__unwind_info: 0x2018
   __DATA_CONST.__const: 0x2590
-  __DATA_CONST.__cfstring: 0x6c00
+  __DATA_CONST.__cfstring: 0x6c20
   __DATA_CONST.__objc_classlist: 0xb0
   __DATA_CONST.__objc_protolist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__auth_got: 0xef0
   __DATA_CONST.__got: 0x390
   __DATA_CONST.__auth_ptr: 0x18
-  __DATA.__objc_const: 0x36b0
-  __DATA.__objc_selrefs: 0x16e8
-  __DATA.__objc_ivar: 0x2c0
+  __DATA.__objc_const: 0x36e0
+  __DATA.__objc_selrefs: 0x1710
+  __DATA.__objc_ivar: 0x2c4
   __DATA.__objc_data: 0x6e0
   __DATA.__data: 0x8f8
   __DATA.__bss: 0xf38

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libspindump.dylib
   - /usr/lib/libsystemstats.dylib
-  Functions: 2350
+  Functions: 2354
   Symbols:   597
-  CStrings:  3716
+  CStrings:  3725
 
CStrings:
+ ":apsd"
+ "CSPN: Skipping update state for client %@ (Trial sendCSPNStatusUpdateToAPSD is off)"
+ "TB,V_send_status_to_apsd"
+ "_send_status_to_apsd"
+ "hasSuffix:"
+ "isAPSDClientIdentifier:"
+ "send_status_to_apsd"
+ "setSend_status_to_apsd:"
+ "shouldSendStateToClient:"
```
