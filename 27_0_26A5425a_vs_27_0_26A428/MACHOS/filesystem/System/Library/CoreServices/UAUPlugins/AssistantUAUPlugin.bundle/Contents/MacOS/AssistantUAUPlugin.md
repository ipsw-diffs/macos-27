## AssistantUAUPlugin

> `/System/Library/CoreServices/UAUPlugins/AssistantUAUPlugin.bundle/Contents/MacOS/AssistantUAUPlugin`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3600.68.61.14.4
-  __TEXT.__text: 0x91c
-  __TEXT.__auth_stubs: 0x110
-  __TEXT.__objc_stubs: 0x1a0
-  __TEXT.__objc_methlist: 0x1ac
+3600.68.61.14.6
+  __TEXT.__text: 0xb94
+  __TEXT.__auth_stubs: 0x130
+  __TEXT.__objc_stubs: 0x260
+  __TEXT.__objc_methlist: 0x1dc
   __TEXT.__const: 0x28
-  __TEXT.__cstring: 0x117
-  __TEXT.__oslogstring: 0x41a
+  __TEXT.__cstring: 0x1aa
+  __TEXT.__oslogstring: 0x4b9
   __TEXT.__ustring: 0x34
   __TEXT.__objc_classname: 0x37
-  __TEXT.__objc_methname: 0x330
-  __TEXT.__objc_methtype: 0xed
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__objc_methname: 0x404
+  __TEXT.__objc_methtype: 0x120
+  __TEXT.__unwind_info: 0xb0
   __DATA_CONST.__const: 0x70
-  __DATA_CONST.__cfstring: 0x120
+  __DATA_CONST.__cfstring: 0x1a0
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__auth_got: 0x90
-  __DATA_CONST.__got: 0x28
-  __DATA.__objc_const: 0x268
-  __DATA.__objc_selrefs: 0x138
-  __DATA.__objc_ivar: 0x8
+  __DATA_CONST.__auth_got: 0xa0
+  __DATA_CONST.__got: 0x30
+  __DATA.__objc_const: 0x288
+  __DATA.__objc_selrefs: 0x168
+  __DATA.__objc_ivar: 0xc
   __DATA.__objc_data: 0x50
   __DATA.__data: 0xc0
   __DATA.__bss: 0x10

   - /System/Library/PrivateFrameworks/UAUPlugin.framework/Versions/A/UAUPlugin
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 13
-  Symbols:   33
-  CStrings:  91
+  Functions: 18
+  Symbols:   37
+  CStrings:  105
 
Symbols:
+ _AFSiriAIDataSharingOptOutV2ShouldRun
+ _OBJC_CLASS_$_NSNumber
+ _objc_opt_class
+ _objc_opt_isKindOfClass
CStrings:
+ "B36@0:8^{__CFString=}16^{__CFString=}24B32"
+ "Enable Offline Mode For Apple Intelligence"
+ "Siri AI data sharing opt-out: alreadyPerformed=%{BOOL}d hasSiriAIEnabled=%{BOOL}d optInStatusVersion=%ld → %{BOOL}d"
+ "Siri Data Sharing Opt-In Status Version"
+ "SiriAIDataSharingOptOutV2Completed"
+ "_dataSharingOptInStatusVersion"
+ "_isSiriAIDataSharingOptOutV2AlreadyPerformed"
+ "_needsSiriAIDataSharingOptOutV2"
+ "_prefBoolForKey:domain:defaultValue:"
+ "_shouldRunSiriAIDataSharingOptOutV2"
+ "boolValue"
+ "com.apple.assistant.backedup"
+ "includePluginInUpdateSession: needsLegacyAssistantEnabledRemoval=%{BOOL}d, needsAppAccessMigration=%{BOOL}d, needsSiriAIDataSharingOptOutV2=%{BOOL}d"
+ "q16@0:8"
+ "unsignedIntegerValue"
- "includePluginInUpdateSession: needsLegacyAssistantEnabledRemoval=%{BOOL}d, needsAppAccessMigration=%{BOOL}d"
```
