## nfs

> `/System/Library/Filesystems/NetFSPlugins/nfs.bundle/Contents/MacOS/nfs`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-356.60.3.0.0
-  __TEXT.__text: 0x13bc
+356.60.5.0.0
+  __TEXT.__text: 0x1410
   __TEXT.__auth_stubs: 0x360
-  __TEXT.__cstring: 0x1df
+  __TEXT.__cstring: 0x220
   __TEXT.__unwind_info: 0x98
   __DATA_CONST.__const: 0x28
   __DATA_CONST.__cfstring: 0x300

   - /usr/lib/libSystem.B.dylib
   Functions: 12
   Symbols:   67
-  CStrings:  45
+  CStrings:  46
 
Functions:
~ sub_c98 : 2548 -> 2632
CStrings:
+ "NFS_Create_MountOption_From_URL: ignoring empty URL mount option"
```
