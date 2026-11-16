## InternetSharing

> `/usr/libexec/InternetSharing`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-408.60.5.0.0
-  __TEXT.__text: 0x1c55c
+408.60.6.0.0
+  __TEXT.__text: 0x1c58c
   __TEXT.__auth_stubs: 0x10a0
   __TEXT.__const: 0x150
-  __TEXT.__cstring: 0x844f
+  __TEXT.__cstring: 0x848f
   __TEXT.__oslogstring: 0x1e
   __TEXT.__unwind_info: 0x5f8
   __DATA_CONST.__const: 0x490

   - /usr/lib/libmrc.dylib
   Functions: 349
   Symbols:   362
-  CStrings:  1168
+  CStrings:  1169
 
Functions:
~ sub_1000044f8 : 1536 -> 1584
CStrings:
+ "%s: network %s has no gateway interface, nothing to deconfigure"
```
