## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/Contents/MacOS/iMessage`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__cstring`
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
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1491.300.43.0.0
-  __TEXT.__text: 0x12b104
-  __TEXT.__auth_stubs: 0x2340
-  __TEXT.__objc_stubs: 0xf720
+1491.300.74.0.0
+  __TEXT.__text: 0x12b8b4
+  __TEXT.__auth_stubs: 0x2360
+  __TEXT.__objc_stubs: 0xf740
   __TEXT.__objc_methlist: 0x38a8
   __TEXT.__const: 0x1688
-  __TEXT.__gcc_except_tab: 0x96dc
+  __TEXT.__gcc_except_tab: 0x973c
   __TEXT.__cstring: 0x43a9
-  __TEXT.__oslogstring: 0x1c8bb
+  __TEXT.__oslogstring: 0x1c97b
   __TEXT.__objc_classname: 0x9af
-  __TEXT.__objc_methname: 0x16adf
+  __TEXT.__objc_methname: 0x16b5f
   __TEXT.__objc_methtype: 0x3b58
   __TEXT.__ustring: 0x4
   __TEXT.__swift5_typeref: 0xf86

   __TEXT.__swift5_builtin: 0x78
   __TEXT.__swift5_mpenum: 0x38
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__unwind_info: 0x3770
+  __TEXT.__unwind_info: 0x3780
   __TEXT.__eh_frame: 0x1e48
-  __DATA_CONST.__const: 0x5c48
-  __DATA_CONST.__cfstring: 0x3de0
+  __DATA_CONST.__const: 0x5c80
+  __DATA_CONST.__cfstring: 0x3e00
   __DATA_CONST.__objc_classlist: 0x168
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0xe0

   __DATA_CONST.__objc_arraydata: 0x28
   __DATA_CONST.__objc_arrayobj: 0x60
   __DATA_CONST.__objc_doubleobj: 0x20
-  __DATA_CONST.__auth_got: 0x11b0
-  __DATA_CONST.__got: 0x1338
+  __DATA_CONST.__auth_got: 0x11c0
+  __DATA_CONST.__got: 0x1340
   __DATA_CONST.__auth_ptr: 0x3d8
   __DATA.__objc_const: 0x4d90
-  __DATA.__objc_selrefs: 0x45c8
+  __DATA.__objc_selrefs: 0x45d0
   __DATA.__objc_ivar: 0x29c
   __DATA.__objc_data: 0x1138
   __DATA.__data: 0x12f0

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 2853
-  Symbols:   916
-  CStrings:  5581
+  Symbols:   918
+  CStrings:  5586
 
Symbols:
+ _objc_sync_enter
+ _objc_sync_exit
CStrings:
+ "Acquisition failure for message %@; failing send."
+ "Not sending gradient for message %@, attachment acquisition failed. %@"
+ "Sending scheduled message update flags 0x%lx for message %@"
+ "Transfer %@ on message %@ finished acquisition without a file. %@"
+ "guidsForStoredAttachmentPayloadData:messageGUID:isIncoming:"
+ "guidsForStoredAttachmentPayloadDataURLs:messageGUID:isIncoming:"
+ "sU"
+ "scheduledMessageUpdateFlagsForDateEdited:"
- "Unrecoverable acquisition failure for message %@; failing send."
- "guidsForStoredAttachmentPayloadData:messageGUID:"
- "guidsForStoredAttachmentPayloadDataURLs:messageGUID:"
```
