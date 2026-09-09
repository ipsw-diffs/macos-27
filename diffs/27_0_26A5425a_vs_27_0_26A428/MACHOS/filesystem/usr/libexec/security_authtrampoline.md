## security_authtrampoline

> `/usr/libexec/security_authtrampoline`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 55107.0.1.0.0
-  __TEXT.__text: 0x9d8
+  __TEXT.__text: 0x9c8
   __TEXT.__auth_stubs: 0x210
   __TEXT.__const: 0x60
   __TEXT.__gcc_except_tab: 0x68
   __TEXT.__cstring: 0x2c2
   __TEXT.__oslogstring: 0x53
-  __TEXT.__unwind_info: 0xb8
+  __TEXT.__unwind_info: 0xc8
   __DATA_CONST.__const: 0x1c0
   __DATA_CONST.__auth_got: 0x110
   __DATA_CONST.__got: 0x38
Functions:
~ sub_100000b4c : 164 -> 152
~ sub_100000e0c -> sub_100000e00 : 196 -> 192
```
