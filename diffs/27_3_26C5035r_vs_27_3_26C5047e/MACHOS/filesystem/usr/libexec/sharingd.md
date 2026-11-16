## sharingd

> `/usr/libexec/sharingd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2131.30.43.1.1
-  __TEXT.__text: 0x53452c
-  __TEXT.__auth_stubs: 0x9c60
-  __TEXT.__objc_stubs: 0x294a0
-  __TEXT.__objc_methlist: 0x19240
+2131.30.65.0.0
+  __TEXT.__text: 0x5357bc
+  __TEXT.__auth_stubs: 0x9c70
+  __TEXT.__objc_stubs: 0x294c0
+  __TEXT.__objc_methlist: 0x19268
   __TEXT.__const: 0x12760
-  __TEXT.__cstring: 0x2ef3c
+  __TEXT.__cstring: 0x2efcc
   __TEXT.__objc_classname: 0x4731
-  __TEXT.__objc_methname: 0x3ca35
+  __TEXT.__objc_methname: 0x3ca95
   __TEXT.__objc_methtype: 0x9723
-  __TEXT.__oslogstring: 0x2dc21
+  __TEXT.__oslogstring: 0x2dcb1
   __TEXT.__gcc_except_tab: 0x2c98
   __TEXT.__ustring: 0x50
   __TEXT.__dlopen_cstrs: 0x1c0

   __TEXT.__swift5_types: 0x520
   __TEXT.__swift_as_entry: 0xb40
   __TEXT.__swift_as_ret: 0xbf0
-  __TEXT.__swift_as_cont: 0x1ae0
+  __TEXT.__swift_as_cont: 0x1ae4
   __TEXT.__swift5_capture: 0x3cc4
   __TEXT.__swift5_protos: 0xd0
   __TEXT.__swift5_mpenum: 0x14
-  __TEXT.__unwind_info: 0x13f10
-  __TEXT.__eh_frame: 0x1db00
+  __TEXT.__unwind_info: 0x13f28
+  __TEXT.__eh_frame: 0x1daf8
   __DATA_CONST.__const: 0x15298
-  __DATA_CONST.__cfstring: 0x14240
+  __DATA_CONST.__cfstring: 0x14260
   __DATA_CONST.__objc_classlist: 0xbf8
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x5c0

   __DATA_CONST.__objc_arrayobj: 0x348
   __DATA_CONST.__objc_dictobj: 0x15b8
   __DATA_CONST.__objc_doubleobj: 0x20
-  __DATA_CONST.__auth_got: 0x4e40
+  __DATA_CONST.__auth_got: 0x4e48
   __DATA_CONST.__got: 0x2f18
   __DATA_CONST.__auth_ptr: 0x1538
   __DATA.__objc_const: 0x2f948
-  __DATA.__objc_selrefs: 0xd7f0
+  __DATA.__objc_selrefs: 0xd808
   __DATA.__objc_ivar: 0x2304
   __DATA.__objc_data: 0x8520
   __DATA.__data: 0x11380

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 21088
-  Symbols:   4313
-  CStrings:  21532
+  Functions: 21093
+  Symbols:   4314
+  CStrings:  21540
 
Symbols:
+ _SFDeviceHasFaceIDProxy
CStrings:
+ "AutoUnlockUpsellStateFromNonFaceIDDevice"
+ "Client error retry skipped, %@ not in medium bubble or state not medium/close (%d)\n"
+ "Detected bio lockout, but token still armed. Must be accidental biolockout."
+ "FindMyProxyOptedIn"
+ "Upsell state was not written by a non-Face ID phone, resetting upsell defaults"
+ "hasAnyPhoneAutoUnlockCapableWatch"
+ "recordUpsellStateDevice"
+ "resetUpsellStateIfFromFaceIDDevice"
```
