## Bom

> `/System/Library/PrivateFrameworks/Bom.framework/Versions/A/Bom`

```diff

-280.0.0.0.0
-  __TEXT.__text: 0x61d7c
-  __TEXT.__cstring: 0x13dd6
+282.0.0.0.0
+  __TEXT.__text: 0x61da4
+  __TEXT.__cstring: 0x13e5e
   __TEXT.__const: 0x1738
   __TEXT.__oslogstring: 0x10b9
   __TEXT.__unwind_info: 0xfd8

   - /usr/lib/libz.1.dylib
   Functions: 1123
   Symbols:   1603
-  CStrings:  2502
+  CStrings:  2504
 
Functions:
~ __copyFile : 9700 -> 9692
~ _create_entry_filesystem : 6904 -> 6920
~ _BOMCopierCopySourceEntryToDestinationSet : 4060 -> 3996
~ _BOMStorageCopyFromBlock : 228 -> 276
~ _BOMStorageCopyFromBlockRange : 664 -> 712
CStrings:
+ "BOMStorageCopyFromBlock: bid >= storage->blockTableCount"
+ "BOMStorageCopyRangeFromBlockRange: bad block (bid >= storage->blockTableCount)"
+ "Nov  9 2026"
- "Oct 28 2026"
```
