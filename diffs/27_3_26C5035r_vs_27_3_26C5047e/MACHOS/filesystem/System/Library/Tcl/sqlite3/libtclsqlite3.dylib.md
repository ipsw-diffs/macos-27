## libtclsqlite3.dylib

> `/System/Library/Tcl/sqlite3/libtclsqlite3.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`

```diff

 408.0.0.0.0
-  __TEXT.__text: 0x102ff0
-  __TEXT.__auth_stubs: 0xf10
+  __TEXT.__text: 0x102fec
+  __TEXT.__auth_stubs: 0xf20
   __TEXT.__const: 0x9368
   __TEXT.__cstring: 0xd303
   __TEXT.__oslogstring: 0x835
   __TEXT.__unwind_info: 0x2a48
   __DATA_CONST.__const: 0x3588
-  __DATA_CONST.__auth_got: 0x788
+  __DATA_CONST.__auth_got: 0x790
   __DATA_CONST.__got: 0x98
   __DATA_CONST.__auth_ptr: 0x10
   __DATA.__data: 0x4130

   - /System/Library/Frameworks/Tcl.framework/Versions/8.5/Tcl
   - /usr/lib/libSystem.B.dylib
   Functions: 2787
-  Symbols:   3312
+  Symbols:   3313
   CStrings:  2431
 
Symbols:
+ _os_unfair_recursive_lock_lock
Functions:
~ _sqlite3_shutdown : 300 -> 296
```
