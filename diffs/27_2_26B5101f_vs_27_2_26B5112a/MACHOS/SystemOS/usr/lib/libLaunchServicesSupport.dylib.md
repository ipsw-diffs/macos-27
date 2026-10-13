## libLaunchServicesSupport.dylib

> `/usr/lib/libLaunchServicesSupport.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__objc_selrefs`
- `__DATA.__objc_const`
- `__DATA.__data`

```diff

-1517.1.11.400.0
+1517.1.12.0.0
   __TEXT.__text: 0x1ff44
   __TEXT.__auth_stubs: 0xcb0
   __TEXT.__objc_stubs: 0xfa0
   __TEXT.__objc_methlist: 0x4cc
   __TEXT.__const: 0x148
   __TEXT.__cstring: 0xc07
-  __TEXT.__oslogstring: 0x5e1b
+  __TEXT.__oslogstring: 0x5e2e
   __TEXT.__gcc_except_tab: 0x2f18
   __TEXT.__objc_methname: 0xe30
   __TEXT.__objc_classname: 0x60
CStrings:
+ "applicationDeath: app=%{public}@ is non-foreground application but is entitled to execute without visible UI, so forcibly removing it from the application list."
- "applicationDeath: app=%{public}@ is non-foreground application but is allowed to execute without visible UI because of its oslaunch job type."
```
