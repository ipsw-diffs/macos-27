## TCCMigration

> `/System/Library/PrivateFrameworks/TCC.framework/Versions/A/Resources/TCCMigration.bundle/Contents/MacOS/TCCMigration`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 913.3.3.0.0
-  __TEXT.__text: 0xc1c
+  __TEXT.__text: 0xbc8
   __TEXT.__auth_stubs: 0xf0
   __TEXT.__objc_stubs: 0x1e0
   __TEXT.__objc_methlist: 0x44

   __TEXT.__objc_classname: 0xd
   __TEXT.__objc_methname: 0x14b
   __TEXT.__objc_methtype: 0x34
-  __TEXT.__unwind_info: 0x80
+  __TEXT.__unwind_info: 0x88
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__cfstring: 0x280
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ sub_1044 : 160 -> 148
~ sub_10e4 -> sub_10d8 : 60 -> 48
~ sub_1120 -> sub_1108 : 60 -> 48
~ sub_115c -> sub_1138 : 152 -> 140
~ sub_1204 -> sub_11d4 : 152 -> 140
~ sub_129c -> sub_1260 : 1584 -> 1560
```
