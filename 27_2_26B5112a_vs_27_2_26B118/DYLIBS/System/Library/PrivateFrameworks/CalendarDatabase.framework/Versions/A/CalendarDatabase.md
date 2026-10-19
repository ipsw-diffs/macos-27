## CalendarDatabase

> `/System/Library/PrivateFrameworks/CalendarDatabase.framework/Versions/A/CalendarDatabase`

```diff

 1291.2.3.0.0
-  __TEXT.__text: 0xdd0ec
+  __TEXT.__text: 0xdd084
   __TEXT.__objc_methlist: 0x1f24
-  __TEXT.__cstring: 0x20580
-  __TEXT.__const: 0xab4
+  __TEXT.__cstring: 0x20679
+  __TEXT.__const: 0xaa4
   __TEXT.__gcc_except_tab: 0x1830
-  __TEXT.__oslogstring: 0xcf31
+  __TEXT.__oslogstring: 0xce98
   __TEXT.__dlopen_cstrs: 0xc0
   __TEXT.__unwind_info: 0x4060
   __TEXT.__objc_stubs: 0x0

   __DATA_CONST.__objc_selrefs: 0x24e8
   __DATA_CONST.__objc_superrefs: 0xd0
   __DATA_CONST.__objc_arraydata: 0xc8
-  __DATA_CONST.__got: 0x9d8
+  __DATA_CONST.__got: 0x9d0
   __AUTH_CONST.__const: 0x29e0
-  __AUTH_CONST.__cfstring: 0xcc60
+  __AUTH_CONST.__cfstring: 0xcd00
   __AUTH_CONST.__objc_const: 0x37d0
   __AUTH_CONST.__objc_arrayobj: 0x78
   __AUTH_CONST.__objc_intobj: 0x30
-  __AUTH_CONST.__auth_got: 0xee0
+  __AUTH_CONST.__auth_got: 0xed8
   __AUTH.__objc_data: 0x500
   __DATA.__objc_ivar: 0x1b4
   __DATA.__data: 0x12d0

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   Functions: 4284
-  Symbols:   7680
-  CStrings:  3139
+  Symbols:   7678
+  CStrings:  3140
 
Symbols:
+ GCC_except_table55
+ __CalAttachmentFileResolveLocalURLReArchivingIfNeeded
- GCC_except_table54
- GCC_except_table61
- _NSURLCreationDateKey
- _UnzipArchive
Functions:
~ _CalAttachmentFileMigrateTables : 120 -> 468
~ __CalAttachmentFileCopyLocalURLForArchivedData : 516 -> 172
~ __CalAttachmentFileSetFileDataWithOpenFile : 2816 -> 2664
~ __CalAttachmentFileCopyLocalURL -> __CalAttachmentFileGetLocalRelativePath : 140 -> 212
~ __CalAttachmentFileGetLocalRelativePath -> __CalAttachmentFileGetCalendarDataContainerForAttachmentFile : 212 -> 292
~ __CalAttachmentFileGetCalendarDataContainerForAttachmentFile -> __CalAttachmentFileResolveLocalURLReArchivingIfNeeded : 292 -> 496
~ _CalDatabaseDeleteOrphanedAttachmentsInDirectory : 1856 -> 1544
CStrings:
+ "%@.zip"
+ "AutoArchivedPathMigrationCompleted"
+ "UPDATE AttachmentFile SET local_path = local_path || '.zip' WHERE (flags & %d) != 0 AND SUBSTR(local_path, -4) != '.zip';"
+ "UPDATE AttachmentFile SET local_path = local_path || '.zip' WHERE (flags & %d) != 0;"
+ "Unable to re-archive attachment data: %@"
- "Attachment cleanup: skipping removing file because it is archived and is too young: %@"
- "Error checking creation date for %@: %@"
- "Failed to unzip attachment (error: %@)."
- "Unable to archive data: %@"
```
