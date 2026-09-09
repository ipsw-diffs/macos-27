## MemoryMonitor

> `/System/Library/UserEventPlugins/MemoryMonitor.plugin/Contents/MacOS/MemoryMonitor`

### Sections with Same Size but Changed Content

- `__DATA.__const`
- `__DATA.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 393.0.2.0.0
-  __TEXT.__text: 0xd40
+  __TEXT.__text: 0xcf8
   __TEXT.__auth_stubs: 0x270
   __TEXT.__objc_stubs: 0x80
   __TEXT.__const: 0x78

   __TEXT.__cstring: 0xcb
   __TEXT.__oslogstring: 0x1e2
   __TEXT.__objc_methname: 0x38
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0xb8
   __DATA.__const: 0xf8
   __DATA.__cfstring: 0xa0
   __DATA.__objc_imageinfo: 0x8
Functions:
~ sub_a54 : 108 -> 96
~ _CleanupPidSets : 56 -> 44
~ sub_c84 -> sub_c6c : 116 -> 104
~ sub_cf8 -> sub_cd4 : 80 -> 68
~ sub_d48 -> sub_d18 : 68 -> 56
~ sub_db4 -> sub_d78 : 192 -> 180
```
