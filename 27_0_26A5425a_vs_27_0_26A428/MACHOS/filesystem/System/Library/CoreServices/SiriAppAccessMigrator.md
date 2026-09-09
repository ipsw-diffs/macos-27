## SiriAppAccessMigrator

> `/System/Library/CoreServices/SiriAppAccessMigrator`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_selrefs`

```diff

-3600.68.61.14.4
-  __TEXT.__text: 0xd1c
-  __TEXT.__auth_stubs: 0x1c0
+3600.68.61.14.6
+  __TEXT.__text: 0xf34
+  __TEXT.__auth_stubs: 0x1f0
   __TEXT.__objc_stubs: 0x120
-  __TEXT.__const: 0x38
-  __TEXT.__oslogstring: 0x4ce
-  __TEXT.__cstring: 0x135
+  __TEXT.__const: 0x40
+  __TEXT.__oslogstring: 0x64b
+  __TEXT.__cstring: 0x180
   __TEXT.__objc_methname: 0x8e
-  __TEXT.__unwind_info: 0x68
+  __TEXT.__unwind_info: 0x70
   __DATA_CONST.__const: 0x60
-  __DATA_CONST.__cfstring: 0x1c0
+  __DATA_CONST.__cfstring: 0x200
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_arraydata: 0x28
   __DATA_CONST.__objc_arrayobj: 0x18
-  __DATA_CONST.__auth_got: 0xe8
+  __DATA_CONST.__auth_got: 0x100
   __DATA_CONST.__got: 0x40
   __DATA.__objc_selrefs: 0x48
   __DATA.__bss: 0x20
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
+  - /System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/AssistantServices
   - /System/Library/PrivateFrameworks/TCC.framework/Versions/A/TCC
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 5
-  Symbols:   42
-  CStrings:  43
+  Symbols:   45
+  CStrings:  50
 
Symbols:
+ _AFIsLinwoodUserSettingOn
+ __AFPreferencesSetSiriDataSharingOptInStatus
+ __AFPreferencesSiriDataSharingOptInStatusVersionWithContext
Functions:
~ sub_1000009c8 -> sub_100000a40 : 2404 -> 2976
~ sub_10000132c -> sub_1000015e0 : 84 -> 72
~ sub_100001380 -> sub_100001628 : 72 -> 60
~ sub_1000013c8 -> sub_100001664 : 772 -> 760
CStrings:
+ "Siri AI data sharing opt-out: already performed. Skipping."
+ "Siri AI data sharing opt-out: complete."
+ "Siri AI data sharing opt-out: hasSiriAIEnabled=%{BOOL}d optInStatusVersion=%ld — cohort does not apply. Marking complete without writing."
+ "Siri AI data sharing opt-out: opting out Siri AI user at opt-in version 2.0 (version left unchanged)."
+ "Siri AI data sharing opt-out: starting."
+ "SiriAIDataSharingOptOutV2Completed"
+ "SiriAppAccessMigratorToolSiriAIOptOutV2"
```
