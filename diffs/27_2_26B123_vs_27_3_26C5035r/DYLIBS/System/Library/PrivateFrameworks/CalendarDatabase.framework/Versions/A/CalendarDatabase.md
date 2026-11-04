## CalendarDatabase

> `/System/Library/PrivateFrameworks/CalendarDatabase.framework/Versions/A/CalendarDatabase`

```diff

-1291.2.3.0.0
-  __TEXT.__text: 0xdd084
+1291.2.4.0.0
+  __TEXT.__text: 0xdd274
   __TEXT.__objc_methlist: 0x1f24
   __TEXT.__cstring: 0x20679
   __TEXT.__const: 0xaa4
   __TEXT.__gcc_except_tab: 0x1830
-  __TEXT.__oslogstring: 0xce98
+  __TEXT.__oslogstring: 0xcfe6
   __TEXT.__dlopen_cstrs: 0xc0
-  __TEXT.__unwind_info: 0x4060
+  __TEXT.__unwind_info: 0x4068
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x24e8
+  __DATA_CONST.__objc_selrefs: 0x24e0
   __DATA_CONST.__objc_superrefs: 0xd0
   __DATA_CONST.__objc_arraydata: 0xc8
   __DATA_CONST.__got: 0x9d0

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 4284
+  Functions: 4285
   Symbols:   7604
-  CStrings:  3140
+  CStrings:  3144
 
Symbols:
+ GCC_except_table56
+ __CalAttachmentFileStringIsSafePathComponent
- GCC_except_table55
- _objc_msgSend$containsString:
Functions:
~ -[CalAttachmentFileCleanupContext addAttachmentToDelete:] : 108 -> 200
~ __CalAttachmentFileGetAttachmentContainerURLsForStoreProperties : 404 -> 372
+ __CalAttachmentFileStringIsSafePathComponent
~ __CalAttachmentFileSetFileDataWithOpenFile : 2664 -> 2968
CStrings:
+ "Refusing to build a path for attachment file %d: its UUID is not a safe path component"
+ "Refusing to build a path for attachment file %d: the store UUID is not a safe path component"
+ "Refusing to clean up after an attachment whose UUID is not a safe path component"
+ "Refusing to write attachment file %d outside the calendar data container"
```
