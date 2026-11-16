## findmydeviced

> `/usr/libexec/findmydeviced`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-482.22.9.13.5
-  __TEXT.__text: 0x9006c
+482.22.9.13.10
+  __TEXT.__text: 0x90b64
   __TEXT.__auth_stubs: 0x1b00
-  __TEXT.__objc_stubs: 0xdee0
-  __TEXT.__objc_methlist: 0x8b7c
+  __TEXT.__objc_stubs: 0xdfe0
+  __TEXT.__objc_methlist: 0x8c24
   __TEXT.__const: 0x1d06
-  __TEXT.__gcc_except_tab: 0x175c
-  __TEXT.__objc_methname: 0x1141b
-  __TEXT.__oslogstring: 0xb119
-  __TEXT.__cstring: 0x5d7e
+  __TEXT.__gcc_except_tab: 0x176c
+  __TEXT.__objc_methname: 0x1155b
+  __TEXT.__oslogstring: 0xb2d9
+  __TEXT.__cstring: 0x5dbe
   __TEXT.__objc_classname: 0xff6
-  __TEXT.__objc_methtype: 0x219c
+  __TEXT.__objc_methtype: 0x21ac
   __TEXT.__ustring: 0x56
   __TEXT.__swift5_typeref: 0x50a
   __TEXT.__swift5_capture: 0x240

   __TEXT.__swift_as_ret: 0x1c
   __TEXT.__swift_as_cont: 0xb8
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__unwind_info: 0x2f48
+  __TEXT.__unwind_info: 0x2f78
   __TEXT.__eh_frame: 0xeac
-  __DATA_CONST.__const: 0x4168
-  __DATA_CONST.__cfstring: 0x7140
+  __DATA_CONST.__const: 0x4198
+  __DATA_CONST.__cfstring: 0x7160
   __DATA_CONST.__objc_classlist: 0x460
   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x140

   __DATA_CONST.__auth_got: 0xd90
   __DATA_CONST.__got: 0x710
   __DATA_CONST.__auth_ptr: 0x718
-  __DATA.__objc_const: 0xe580
-  __DATA.__objc_selrefs: 0x4320
-  __DATA.__objc_ivar: 0x87c
+  __DATA.__objc_const: 0xe5c8
+  __DATA.__objc_selrefs: 0x4370
+  __DATA.__objc_ivar: 0x880
   __DATA.__objc_data: 0x2c38
   __DATA.__data: 0x1558
   __DATA.__bss: 0x2c10

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 4003
+  Functions: 4016
   Symbols:   782
-  CStrings:  5420
+  CStrings:  5443
 
CStrings:
+ "%@ Clearing financier name"
+ "%@ Financier name NVRAM write did not persist (requested length=%lu, stored length=%lu)"
+ "%@ PF locked but no financier name stored"
+ "%@ Stored financier name (length=%lu)"
+ "%@ handlePartnerFinanceLocked: locked without a financier name"
+ "%@ updateFinancierName: nameLength=%lu"
+ "%@ updateFinancierName: storing name while fmLockType=%ld; it is only returned while PFLock"
+ "%@:fm-financier"
+ "%s - stored financier name is empty, returning nil"
+ "-[FMDLocalActivationLockInfoNVRAMStore retrieveFinancierName]"
+ "T@\"NSDictionary\",&,V_rawStats"
+ "T@\"NSString\",&,N,V_financierName"
+ "_clearFinancierNameUnlessPFLock"
+ "_financierName"
+ "_handlePartnerFinanceLocked:financierName:replacesName:"
+ "_storeFinancierName:"
+ "clearFinancierName"
+ "financierName"
+ "financierNameValue"
+ "handlePartnerFinanceLocked:financierName:"
+ "retrieveFinancierName"
+ "setFinancierName:"
+ "updateFinancierName:"
+ "v32@0:8B16@20B28"
- "T@\"NSDictionary\",&,N,V_rawStats"
```
