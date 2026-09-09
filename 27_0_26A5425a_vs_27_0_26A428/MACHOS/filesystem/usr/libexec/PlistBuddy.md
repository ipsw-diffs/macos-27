## PlistBuddy

> `/usr/libexec/PlistBuddy`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 5.0.0.0.0
-  __TEXT.__text: 0x3980
+  __TEXT.__text: 0x3818
   __TEXT.__auth_stubs: 0x560
   __TEXT.__const: 0x10
   __TEXT.__cstring: 0x10cf
-  __TEXT.__unwind_info: 0x110
+  __TEXT.__unwind_info: 0x148
   __DATA_CONST.__const: 0x30
   __DATA_CONST.__auth_got: 0x2b0
   __DATA_CONST.__got: 0x48
Functions:
~ _ExecuteCommand : 448 -> 412
~ _DisposeCommand : 88 -> 76
~ _CleanupState : 80 -> 68
~ _CreateEntryWithValue : 684 -> 624
~ _PrintEntryXML : 104 -> 92
~ _PrintEntry : 108 -> 72
~ _CreateCopyOfEntry : 624 -> 564
~ _AddMultipleEntriesToPlist : 580 -> 568
~ _CommandAdd : 288 -> 276
~ _CommandCopy : 328 -> 316
~ _CommandMerge : 484 -> 472
~ _CommandImport : 376 -> 352
~ _CommandSet : 436 -> 424
~ _CommandPrint : 140 -> 128
~ _CommandDelete : 268 -> 256
~ _PrintHelp : 544 -> 532
~ _PrintUsage : 164 -> 152
```
