## TSFeatureFlags

> `/System/Applications/Freeform.app/Contents/Frameworks/TSFeatureFlags.framework/Versions/A/TSFeatureFlags`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 656.1.2.0.0
-  __TEXT.__text: 0x454
+  __TEXT.__text: 0x40c
   __TEXT.__auth_stubs: 0x50
   __TEXT.__objc_stubs: 0x80
   __TEXT.__objc_methlist: 0xac

   __TEXT.__objc_methtype: 0x52
   __TEXT.__cstring: 0x3
   __TEXT.__const: 0x2
-  __TEXT.__unwind_info: 0x78
+  __TEXT.__unwind_info: 0x80
   __DATA_CONST.__const: 0x38
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ +[TSFeatureFlagInfo enabledFlagWithName:description:] : 176 -> 164
~ +[TSFeatureFlagInfo disabledFlagWithName:description:] : 176 -> 164
~ +[TSFeatureFlagInfo dynamicFlagWithName:description:userDefaultsKey:currentValue:] : 236 -> 224
~ +[TSFeatureFlagInfo dynamicDebugOnlyFlagWithName:description:userDefaultsKey:currentValue:] : 236 -> 224
~ -[TSFeatureFlagInfo isEnabled] : 92 -> 80
~ -[TSFeatureFlagInfo .cxx_destruct] : 80 -> 68
```
