## sqlite3

> `/usr/bin/sqlite3`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`

```diff

 408.0.0.0.0
-  __TEXT.__text: 0x141a5c
-  __TEXT.__auth_stubs: 0xeb0
+  __TEXT.__text: 0x141a58
+  __TEXT.__auth_stubs: 0xec0
   __TEXT.__const: 0xafa4
   __TEXT.__cstring: 0x1fe45
   __TEXT.__oslogstring: 0x835
   __TEXT.__unwind_info: 0x3470
   __TEXT.__eh_frame: 0x88
   __DATA_CONST.__const: 0x4b90
-  __DATA_CONST.__auth_got: 0x758
+  __DATA_CONST.__auth_got: 0x760
   __DATA_CONST.__got: 0xc8
   __DATA_CONST.__auth_ptr: 0x18
   __DATA.__data: 0x5100

   - /usr/lib/libncurses.5.4.dylib
   - /usr/lib/libz.1.dylib
   Functions: 3470
-  Symbols:   281
+  Symbols:   282
   CStrings:  4358
 
Symbols:
+ _os_unfair_recursive_lock_lock
Functions:
~ sub_100051c14 : 300 -> 296
```
