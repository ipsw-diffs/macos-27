## deleted

> `/System/Library/PrivateFrameworks/CacheDelete.framework/deleted`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-904.40.2.0.0
-  __TEXT.__text: 0x5c590
-  __TEXT.__auth_stubs: 0xe30
-  __TEXT.__objc_stubs: 0x67a0
+904.60.1.0.1
+  __TEXT.__text: 0x5c878
+  __TEXT.__auth_stubs: 0xe50
+  __TEXT.__objc_stubs: 0x6840
   __TEXT.__objc_methlist: 0x2f6c
   __TEXT.__const: 0x180
   __TEXT.__gcc_except_tab: 0x2738
-  __TEXT.__cstring: 0x45fe
-  __TEXT.__objc_methname: 0x7c43
-  __TEXT.__oslogstring: 0xa247
+  __TEXT.__cstring: 0x4619
+  __TEXT.__objc_methname: 0x7c89
+  __TEXT.__oslogstring: 0xa28d
   __TEXT.__objc_classname: 0x3fb
   __TEXT.__objc_methtype: 0xeab
   __TEXT.__unwind_info: 0x1080

   __DATA_CONST.__objc_intobj: 0x120
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA_CONST.__objc_dictobj: 0x348
-  __DATA_CONST.__auth_got: 0x728
-  __DATA_CONST.__got: 0x2a8
+  __DATA_CONST.__auth_got: 0x738
+  __DATA_CONST.__got: 0x2b0
   __DATA_CONST.__auth_ptr: 0x8
   __DATA.__objc_const: 0x4910
-  __DATA.__objc_selrefs: 0x1ee8
+  __DATA.__objc_selrefs: 0x1f10
   __DATA.__objc_ivar: 0x38c
   __DATA.__objc_data: 0xb40
   __DATA.__data: 0x4e8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1308
-  Symbols:   3005
-  CStrings:  3103
+  Functions: 1309
+  Symbols:   3014
+  CStrings:  3111
 
Symbols:
+ GCC_except_table149
+ GCC_except_table152
+ GCC_except_table163
+ GCC_except_table245
+ _SANDBOX_CHECK_NO_REPORT
+ _connectionIsPublic
+ _objc_msgSend$auditToken
+ _objc_msgSend$coarsenDiskSpace
+ _objc_msgSend$exportedInterface
+ _objc_msgSend$protocol
+ _objc_msgSend$reduceToTotals
+ _protocol_isEqual
+ _sandbox_check_by_audit_token
- GCC_except_table148
- GCC_except_table151
- GCC_except_table162
- GCC_except_table244
Functions:
~ -[CacheDelete clientUnifiedPurgeableSpace:queryType:replyBlock:] : 1604 -> 2216
+ _connectionIsPublic
CStrings:
+ "Unknown query type! cannot determine the required entitlement"
+ "[%@] clientUnifiedPurgeableSpace queryType: %d, public: %d, info: %@"
+ "auditToken"
+ "coarsenDiskSpace"
+ "exportedInterface"
+ "protocol"
+ "reduceToTotals"
+ "sandbox_check_by_audit_token(%s) failed for %@: %{public}s"
+ "system-info"
+ "vfs.disk-space"
- "Unknown query type! can not determine the required entitelment"
- "[%@] clientUnifiedPurgeableSpace queryType: %d, info: %@"
```
