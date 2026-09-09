## secd

> `/usr/libexec/secd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-62460.1.2.0.0
-  __TEXT.__text: 0x28ab4c
+62460.1.3.0.0
+  __TEXT.__text: 0x283acc
   __TEXT.__auth_stubs: 0x40d0
-  __TEXT.__objc_stubs: 0x1d8a0
-  __TEXT.__objc_methlist: 0x15ea0
+  __TEXT.__objc_stubs: 0x1d880
+  __TEXT.__objc_methlist: 0x15e98
   __TEXT.__const: 0x920
   __TEXT.__objc_classname: 0x2506
-  __TEXT.__objc_methname: 0x2e53a
+  __TEXT.__objc_methname: 0x2e52a
   __TEXT.__objc_methtype: 0xb011
   __TEXT.__constg_swiftt: 0x274
   __TEXT.__swift5_typeref: 0x35e

   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_proto: 0x24
   __TEXT.__swift5_types: 0x20
-  __TEXT.__cstring: 0x21922
-  __TEXT.__oslogstring: 0x2f9d3
+  __TEXT.__cstring: 0x21937
+  __TEXT.__oslogstring: 0x2f9ca
   __TEXT.__swift5_capture: 0x1bc
   __TEXT.__swift_as_entry: 0x40
   __TEXT.__swift_as_ret: 0x3c
   __TEXT.__swift_as_cont: 0x48
-  __TEXT.__gcc_except_tab: 0xa0a8
+  __TEXT.__gcc_except_tab: 0xa0ac
   __TEXT.__dlopen_cstrs: 0xb4
-  __TEXT.__unwind_info: 0x69a0
+  __TEXT.__unwind_info: 0x7dc8
   __TEXT.__eh_frame: 0xa60
-  __DATA_CONST.__const: 0x15a08
-  __DATA_CONST.__cfstring: 0x1ba40
+  __DATA_CONST.__const: 0x15a10
+  __DATA_CONST.__cfstring: 0x1ba60
   __DATA_CONST.__objc_classlist: 0x910
   __DATA_CONST.__objc_catlist: 0x68
   __DATA_CONST.__objc_protolist: 0x258

   __DATA_CONST.__got: 0x1468
   __DATA_CONST.__auth_ptr: 0x1d8
   __DATA.__objc_const: 0x23cd0
-  __DATA.__objc_selrefs: 0x9858
+  __DATA.__objc_selrefs: 0x9850
   __DATA.__objc_ivar: 0x1ae8
   __DATA.__objc_data: 0x5d98
   __DATA.__data: 0x3098

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 10038
+  Functions: 10037
   Symbols:   1843
   CStrings:  16268
 
CStrings:
+ "Couldn't verify signature of TLKShare (%@) without tlkOwnershipProof as part of dataForSigning; trying again with tlkOwnershipProof"
+ "PhotoRevocationCheck"
+ "verifySignature:verifyingPeer:acceptSigWithProof:error:"
+ "verifySignature:verifyingPeer:ckrecord:acceptSigWithProof:error:"
- "Couldn't verify signature of TLKShare (%@) that includes tlkOwnershipProof as part of dataForSigning; trying again without tlkOwnershipProof"
- "dataForSigning"
- "verifySignature:verifyingPeer:acceptProoflessSig:error:"
- "verifySignature:verifyingPeer:ckrecord:acceptProoflessSig:error:"
```
