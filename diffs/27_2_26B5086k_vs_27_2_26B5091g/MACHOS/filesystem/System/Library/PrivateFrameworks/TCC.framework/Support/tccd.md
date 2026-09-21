## tccd

> `/System/Library/PrivateFrameworks/TCC.framework/Support/tccd`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-918.0.0.0.0
-  __TEXT.__text: 0x8bda8
+919.0.0.0.0
+  __TEXT.__text: 0x8c0a0
   __TEXT.__auth_stubs: 0x1600
   __TEXT.__lazy_helpers: 0x54
-  __TEXT.__objc_stubs: 0x9c60
-  __TEXT.__objc_methlist: 0x42d4
-  __TEXT.__cstring: 0x12641
+  __TEXT.__objc_stubs: 0x9d20
+  __TEXT.__objc_methlist: 0x435c
+  __TEXT.__cstring: 0x12724
   __TEXT.__const: 0x648
   __TEXT.__gcc_except_tab: 0x3528
-  __TEXT.__objc_methname: 0x10273
-  __TEXT.__oslogstring: 0xf070
+  __TEXT.__objc_methname: 0x10568
+  __TEXT.__oslogstring: 0xf0bc
   __TEXT.__objc_classname: 0x4ae
   __TEXT.__objc_methtype: 0x14f3
-  __TEXT.__unwind_info: 0x2040
-  __DATA_CONST.__const: 0x2758
-  __DATA_CONST.__cfstring: 0x8500
+  __TEXT.__unwind_info: 0x2050
+  __DATA_CONST.__const: 0x2760
+  __DATA_CONST.__cfstring: 0x85a0
   __DATA_CONST.__objc_classlist: 0x188
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x158
+  __DATA_CONST.__objc_doubleobj: 0x10
+  __DATA_CONST.__objc_arraydata: 0x17f8
+  __DATA_CONST.__objc_arrayobj: 0xf0
   __DATA_CONST.__objc_intobj: 0x540
-  __DATA_CONST.__objc_arraydata: 0x17f0
-  __DATA_CONST.__objc_arrayobj: 0xd8
   __DATA_CONST.__objc_dictobj: 0xf78
   __DATA_CONST.__auth_got: 0xb10
   __DATA_CONST.__got: 0x4a8
   __DATA_CONST.__auth_ptr: 0x30
-  __DATA.__objc_const: 0x7f78
-  __DATA.__objc_selrefs: 0x2d80
-  __DATA.__objc_ivar: 0x688
+  __DATA.__objc_const: 0x8008
+  __DATA.__objc_selrefs: 0x2dd8
+  __DATA.__objc_ivar: 0x694
   __DATA.__objc_data: 0xf50
   __DATA.__lazy_load_got: 0x8
   __DATA.__data: 0x34c

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 2628
-  Symbols:   504
-  CStrings:  5222
+  Functions: 2640
+  Symbols:   505
+  CStrings:  5246
 
Symbols:
+ _OBJC_CLASS_$_NSConstantDoubleNumber
CStrings:
+ "%s: last drain for %{public}@ is %.0fs in the future, ignoring the throttle"
+ "+[TCCDReminderMonitor milestoneOverrideFromDefaultsForKey:]"
+ "-[TCCDReminderMonitor enqueueReminderWithContext:deferrals:]"
+ "-[TCCDReminderMonitor isServiceThrottled:atTime:]"
+ "-[TCCDReminderMonitor showReminderPrompt:result:accessCount:]"
+ "A\""
+ "REMINDER_ACCESS_INFO_COUNT"
+ "REMINDER_ACCESS_INFO_COUNT_ONE"
+ "T@\"NSArray\",C,N,V_researchMilestoneOverride"
+ "T@\"NSString\",&,N,V_reminderAccessCountFormatLocalizationKey"
+ "T@\"NSString\",&,N,V_reminderAccessCountSingularLocalizationKey"
+ "_reminderAccessCountFormatLocalizationKey"
+ "_reminderAccessCountSingularLocalizationKey"
+ "_researchMilestoneOverride"
+ "com.apple.developer.healthkit.research"
+ "deferrals"
+ "enqueueReminderWithContext:deferrals:"
+ "healthResearchReminderMilestoneOverride"
+ "milestoneOverrideFromDefaultsForKey:"
+ "reminderAccessCountFormatLocalizationKey"
+ "reminderAccessCountFormatLocalizationKeyNameForServiceName:"
+ "reminderAccessCountSingularLocalizationKey"
+ "reminderAccessCountSingularLocalizationKeyNameForServiceName:"
+ "reminderInfoTextForService:accessCount:"
+ "researchMilestoneOverride"
+ "setReminderAccessCountFormatLocalizationKey:"
+ "setReminderAccessCountSingularLocalizationKey:"
+ "setResearchMilestoneOverride:"
+ "showReminderPrompt:result:accessCount:"
+ "\xf0\xf0\xf0\xf0!\xf0c"
- "+[TCCDReminderMonitor milestoneOverrideFromDefaults]"
- "-[TCCDReminderMonitor enqueueReminderWithContext:]"
- "-[TCCDReminderMonitor showReminderPrompt:result:]"
- "A!"
- "milestoneOverrideFromDefaults"
- "\xf0\xf0\xf0\xf1\xf0c"
```
