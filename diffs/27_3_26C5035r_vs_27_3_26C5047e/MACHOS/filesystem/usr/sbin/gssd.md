## gssd

> `/usr/sbin/gssd`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`

```diff

-88.0.0.0.0
-  __TEXT.__text: 0x9be0
-  __TEXT.__auth_stubs: 0xaa0
+90.0.0.0.0
+  __TEXT.__text: 0x9bd8
+  __TEXT.__auth_stubs: 0xab0
   __TEXT.__const: 0x70
   __TEXT.__cstring: 0x2ca1
   __TEXT.__oslogstring: 0x19
   __TEXT.__unwind_info: 0x208
   __DATA_CONST.__const: 0x278
-  __DATA_CONST.__auth_got: 0x550
+  __DATA_CONST.__auth_got: 0x558
   __DATA_CONST.__got: 0xc0
   __DATA_CONST.__auth_ptr: 0x18
   __DATA.__data: 0x220

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   Functions: 99
-  Symbols:   205
+  Symbols:   206
   CStrings:  368
 
Symbols:
+ _strcmp
Functions:
~ sub_100005768 : 1052 -> 1044
```
