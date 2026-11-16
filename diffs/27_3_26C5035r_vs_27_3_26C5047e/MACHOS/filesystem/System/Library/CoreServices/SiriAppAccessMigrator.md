## SiriAppAccessMigrator

> `/System/Library/CoreServices/SiriAppAccessMigrator`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`

```diff

-3610.11.2.4.1
-  __TEXT.__text: 0x10dc
-  __TEXT.__auth_stubs: 0x200
-  __TEXT.__objc_stubs: 0x160
+3610.19.2.4.1
+  __TEXT.__text: 0x13b4
+  __TEXT.__auth_stubs: 0x250
+  __TEXT.__objc_stubs: 0x2a0
   __TEXT.__const: 0x40
-  __TEXT.__oslogstring: 0x752
-  __TEXT.__cstring: 0x1f2
-  __TEXT.__objc_methname: 0xbc
+  __TEXT.__cstring: 0x29d
+  __TEXT.__oslogstring: 0x8d3
+  __TEXT.__objc_methname: 0x1c2
   __TEXT.__unwind_info: 0x70
   __DATA_CONST.__const: 0x60
-  __DATA_CONST.__cfstring: 0x280
+  __DATA_CONST.__cfstring: 0x340
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_arraydata: 0x28
   __DATA_CONST.__objc_arrayobj: 0x18
-  __DATA_CONST.__auth_got: 0x108
-  __DATA_CONST.__got: 0x48
-  __DATA.__objc_selrefs: 0x58
+  __DATA_CONST.__auth_got: 0x130
+  __DATA_CONST.__got: 0x68
+  __DATA.__objc_selrefs: 0xa8
   __DATA.__bss: 0x20
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 5
-  Symbols:   47
-  CStrings:  59
+  Symbols:   56
+  CStrings:  80
 
Symbols:
+ _AFBackedUpPreferencesSynchronize
+ _AFBuildVersion
+ _AFIsAffectedBy2026Incident
+ _AFPublicPreferencesSynchronize
+ _OBJC_CLASS_$_AFPreferences
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_NSMutableDictionary
+ _OBJC_CLASS_$_NSUserDefaults
+ _objc_alloc
Functions:
~ sub_100000a40 : 3400 -> 4128
CStrings:
+ "Build Version"
+ "Date"
+ "Siri AI downgrade without 3.0 data sharing answer: affected — setting Siri Classic."
+ "Siri AI downgrade without 3.0 data sharing answer: already performed (%{public}@). Skipping."
+ "Siri AI downgrade without 3.0 data sharing answer: complete."
+ "Siri AI downgrade without 3.0 data sharing answer: not affected — does not apply."
+ "Siri AI downgrade without 3.0 data sharing answer: starting."
+ "SiriAIDowngradeWithoutDataSharingV3"
+ "SiriAIDowngradeWithoutDataSharingV3Completed"
+ "appendToSiriDataSharingOptInStatusHistory:previousOptInStatus:statusChangeSource:reason:"
+ "com.apple.gms.availability"
+ "com.apple.gms.enhancedSiri.wasEverAvailable"
+ "date"
+ "dictionary"
+ "initWithSuiteName:"
+ "removeAppleIntelligenceFallback"
+ "removeObjectForKey:"
+ "setObject:forKeyedSubscript:"
+ "sharedPreferences"
+ "siriDataSharingOptInStatus"
+ "synchronize"
```
