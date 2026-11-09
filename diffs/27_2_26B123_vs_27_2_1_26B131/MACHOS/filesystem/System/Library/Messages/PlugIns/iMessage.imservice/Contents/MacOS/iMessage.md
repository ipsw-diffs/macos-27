## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/Contents/MacOS/iMessage`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__eh_frame`
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

-1491.200.101.1.3
-  __TEXT.__text: 0x121250
+1491.200.101.1.4
+  __TEXT.__text: 0x121258
   __TEXT.__auth_stubs: 0x2290
-  __TEXT.__objc_stubs: 0xf000
-  __TEXT.__objc_methlist: 0x3454
+  __TEXT.__objc_stubs: 0xefe0
+  __TEXT.__objc_methlist: 0x344c
   __TEXT.__const: 0x15a8
-  __TEXT.__gcc_except_tab: 0x9658
+  __TEXT.__gcc_except_tab: 0x964c
   __TEXT.__cstring: 0x410d
-  __TEXT.__oslogstring: 0x1c75b
+  __TEXT.__oslogstring: 0x1c7eb
   __TEXT.__objc_classname: 0x87f
-  __TEXT.__objc_methname: 0x15d0a
+  __TEXT.__objc_methname: 0x15c5a
   __TEXT.__objc_methtype: 0x362b
   __TEXT.__ustring: 0x4
   __TEXT.__swift5_typeref: 0xed4

   __TEXT.__swift5_builtin: 0x78
   __TEXT.__swift5_mpenum: 0x38
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x3578
+  __TEXT.__unwind_info: 0x3570
   __TEXT.__eh_frame: 0x1a80
   __DATA_CONST.__const: 0x5b70
   __DATA_CONST.__cfstring: 0x3d40

   __DATA_CONST.__objc_arrayobj: 0x60
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA_CONST.__auth_got: 0x1158
-  __DATA_CONST.__got: 0x1370
+  __DATA_CONST.__got: 0x1378
   __DATA_CONST.__auth_ptr: 0x338
   __DATA.__objc_const: 0x4168
-  __DATA.__objc_selrefs: 0x4320
+  __DATA.__objc_selrefs: 0x4318
   __DATA.__objc_ivar: 0x28c
   __DATA.__objc_data: 0xf30
   __DATA.__data: 0xff8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2744
-  Symbols:   929
+  Functions: 2743
+  Symbols:   930
   CStrings:  5425
 
Symbols:
+ _OBJC_CLASS_$_IMDIDSIDCanonicalizationRule
CStrings:
+ "Dropping group message payload of type %@ because its sender %@ is not in its from participants: %@"
+ "Dropping message because its sender %@ is not in its participant list. participants: %@"
+ "isSender:listedInParticipants:"
- "_setReplyToGUIDForMessage:messageDictionary:"
- "bestCandidateGroupChatWithFromIdentifier:toIdentifier:displayName:participants:updatingToLatestiMessageGroupID:sortedIdentifiers:serviceName:shouldUpdateExistingGroupID:"
- "setReplyToMessageGUID: %@ for message: %@"
```
