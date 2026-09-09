## StickiesMigration

> `/System/Applications/Stickies.app/Contents/XPCServices/StickiesMigration.xpc/Contents/MacOS/StickiesMigration`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 171.0.0.0.0
-  __TEXT.__text: 0x1078
+  __TEXT.__text: 0x1060
   __TEXT.__auth_stubs: 0x1a0
   __TEXT.__objc_stubs: 0x7c0
   __TEXT.__objc_methlist: 0x248

   __TEXT.__objc_methname: 0x72a
   __TEXT.__objc_methtype: 0x20f
   __TEXT.__cstring: 0x223
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0xa8
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__cfstring: 0x320
   __DATA_CONST.__objc_classlist: 0x10
Functions:
~ sub_100001a50 : 80 -> 68
~ sub_100001aec -> sub_100001ae0 : 292 -> 280
```
