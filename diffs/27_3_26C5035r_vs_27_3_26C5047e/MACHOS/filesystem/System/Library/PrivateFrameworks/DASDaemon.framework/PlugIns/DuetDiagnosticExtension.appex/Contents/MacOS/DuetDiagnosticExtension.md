## DuetDiagnosticExtension

> `/System/Library/PrivateFrameworks/DASDaemon.framework/PlugIns/DuetDiagnosticExtension.appex/Contents/MacOS/DuetDiagnosticExtension`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_classlist`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-2467.60.9.0.0
-  __TEXT.__text: 0xbd8
-  __TEXT.__auth_stubs: 0xd0
-  __TEXT.__objc_stubs: 0x2e0
-  __TEXT.__objc_methlist: 0x44
-  __TEXT.__const: 0x18
-  __TEXT.__oslogstring: 0x29a
-  __TEXT.__cstring: 0x30
+2467.60.20.0.0
+  __TEXT.__text: 0x418
+  __TEXT.__auth_stubs: 0xc0
+  __TEXT.__objc_stubs: 0x1c0
+  __TEXT.__objc_methlist: 0x2c
+  __TEXT.__const: 0x10
+  __TEXT.__cstring: 0x64
+  __TEXT.__oslogstring: 0x85
   __TEXT.__objc_classname: 0x18
-  __TEXT.__objc_methname: 0x260
-  __TEXT.__objc_methtype: 0x29
-  __TEXT.__unwind_info: 0x78
-  __DATA_CONST.__cfstring: 0x80
+  __TEXT.__objc_methname: 0x12f
+  __TEXT.__objc_methtype: 0x13
+  __TEXT.__unwind_info: 0x70
+  __DATA_CONST.__cfstring: 0xa0
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__auth_got: 0x70
-  __DATA_CONST.__got: 0x48
+  __DATA_CONST.__objc_arraydata: 0x10
+  __DATA_CONST.__objc_dictobj: 0x28
+  __DATA_CONST.__auth_got: 0x68
+  __DATA_CONST.__got: 0x40
   __DATA.__objc_const: 0x90
-  __DATA.__objc_selrefs: 0xc8
+  __DATA.__objc_selrefs: 0x80
   __DATA.__objc_data: 0x50
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
-  - /System/Library/PrivateFrameworks/DASDaemon.framework/Versions/A/DASDaemon
   - /System/Library/PrivateFrameworks/DiagnosticExtensions.framework/Versions/A/DiagnosticExtensions
+  - /System/Library/PrivateFrameworks/PowerLog.framework/Versions/A/PowerLog
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 6
-  Symbols:   32
-  CStrings:  54
+  Functions: 4
+  Symbols:   31
+  CStrings:  27
 
Symbols:
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NSConstantDictionary
+ _PLQueryRegistered
- _NSSearchPathForDirectoriesInDomains
- _OBJC_CLASS_$_NSString
- _OBJC_CLASS_$__DASLogExtractor
- _arc4random_uniform
CStrings:
+ "/private/var/log/"
+ "BackgroundProcessingLog"
+ "DEExtensionAttachmentsParamConsentProvidedKey"
+ "[BGProcessingDE] Attaching %@"
+ "[BGProcessingDE] Consent not provided, stopping"
+ "[BGProcessingDE] No log path returned for query %@: %@"
+ "arrayWithObjects:count:"
+ "attachmentForRegisteredQuery:"
+ "boolValue"
+ "fileExistsAtPath:"
+ "folder"
+ "objectForKeyedSubscript:"
+ "path"
- "%@.txt"
- ","
- "@32@0:8@16@24"
- "Activity Name:\n%@%@"
- "ActivityName is nil, skipping"
- "ActivityName is nil, stopping"
- "Could not find directory to clean up files, skipping"
- "Could not find directory to write file, skipping"
- "Deleted file: %@"
- "DiagnosisString is nil, stopping"
- "Encountered error while deleting file %@: %@"
- "Encountered error while enumerating directory %@: %@"
- "Extractor couldn't get result string"
- "Extractor failed with error %d"
- "Failed to create extractor, stopping"
- "Failed to save activity info file for %@"
- "Failed to write file %@"
- "Finding summary for activity: %@"
- "Getting summary for %@"
- "No activity names found, stopping"
- "No parameters specified, stopping"
- "Saved %@"
- "Summary for %@ is empty, skipping"
- "Summary for %@:\n%@"
- "activitySummaryForActivityName:withExtractor:"
- "cleanUpDocumentsDirectory"
- "componentsSeparatedByString:"
- "contentsOfDirectoryAtPath:error:"
- "copyActivitySummary:startDate:endDate:detail:error:"
- "extractorForArchive:"
- "firstObject"
- "kDuetActivityNames"
- "objectAtIndexedSubscript:"
- "objectForKey:"
- "removeItemAtPath:error:"
- "stringByAppendingPathComponent:"
- "stringWithFormat:"
- "v16@0:8"
- "writeDiagnosisStringToFile:forActivity:"
- "writeToFile:atomically:encoding:error:"
```
