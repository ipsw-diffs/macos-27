## syspolicyd

> `/usr/libexec/syspolicyd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__dof_security_`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 823.40.13.0.0
-  __TEXT.__text: 0xb0fdc
+  __TEXT.__text: 0xb15f4
   __TEXT.__auth_stubs: 0x2c60
-  __TEXT.__objc_stubs: 0xa680
+  __TEXT.__objc_stubs: 0xa6c0
   __TEXT.__init_offsets: 0x4
-  __TEXT.__objc_methlist: 0x53cc
+  __TEXT.__objc_methlist: 0x53dc
   __TEXT.__const: 0x1ff8
-  __TEXT.__objc_methname: 0xd2ca
+  __TEXT.__objc_methname: 0xd31a
   __TEXT.__cstring: 0x11c43
   __TEXT.__objc_classname: 0x838
-  __TEXT.__objc_methtype: 0x27f0
-  __TEXT.__oslogstring: 0xa266
-  __TEXT.__gcc_except_tab: 0x1c98
+  __TEXT.__objc_methtype: 0x2800
+  __TEXT.__oslogstring: 0xa336
+  __TEXT.__gcc_except_tab: 0x1c80
   __TEXT.__swift5_typeref: 0x410
   __TEXT.__swift5_capture: 0x1b4
   __TEXT.__constg_swiftt: 0x4a0

   __TEXT.__swift5_proto: 0x40
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__dof_security_: 0x325
-  __TEXT.__unwind_info: 0x3400
+  __TEXT.__unwind_info: 0x3410
   __TEXT.__eh_frame: 0x1b8
   __DATA_CONST.__const: 0x3c98
   __DATA_CONST.__cfstring: 0x8e40

   __DATA_CONST.__auth_got: 0x1648
   __DATA_CONST.__got: 0x8f8
   __DATA_CONST.__auth_ptr: 0x208
-  __DATA.__objc_const: 0x9f78
-  __DATA.__objc_selrefs: 0x2f48
-  __DATA.__objc_ivar: 0x814
+  __DATA.__objc_const: 0x9fb8
+  __DATA.__objc_selrefs: 0x2f58
+  __DATA.__objc_ivar: 0x81c
   __DATA.__objc_data: 0x2208
   __DATA.__data: 0xdb2
   __DATA.__bss: 0xac0

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3604
+  Functions: 3611
   Symbols:   1066
-  CStrings:  5595
+  CStrings:  5605
 
CStrings:
+ "Failed bundle integrity check: %d, %d"
+ "Failed to stat target: %s error: %s"
+ "Target identity is not verified on %s: %s"
+ "Target identity mismatch, refusing to act on it: %@"
+ "Target is not the object that was scanned: (%d,%llu) != (%d,%llu), %s"
+ "Unable to open target: %d, %s"
+ "Unable to stat target: %d, %s"
+ "Unable to unregister app bundle: %d, %d"
+ "_objectDev"
+ "_objectIno"
+ "i24@0:8^i16"
+ "openVerifiedDescriptorWithError:"
+ "reportTargetIdentityMismatch:"
- "Failed bundle integrity check: %d, %@"
- "Unable to open app for integrity check: %d, %@"
- "Unable to unregister app bundle: %d, %@"
```
