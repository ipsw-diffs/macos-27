## afscexpand

> `/usr/bin/afscexpand`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 182.0.0.0.0
-  __TEXT.__text: 0x165a8
+  __TEXT.__text: 0x1620c
   __TEXT.__auth_stubs: 0x320
   __TEXT.__const: 0x23888
   __TEXT.__cstring: 0xbf3
-  __TEXT.__unwind_info: 0x220
+  __TEXT.__unwind_info: 0x260
   __TEXT.__eh_frame: 0x50
   __DATA_CONST.__const: 0x11d8
   __DATA_CONST.__cfstring: 0x560

   - /usr/lib/libc++.1.dylib
   - /usr/lib/liblzma.5.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 125
+  Functions: 129
   Symbols:   61
   CStrings:  68
 
```
