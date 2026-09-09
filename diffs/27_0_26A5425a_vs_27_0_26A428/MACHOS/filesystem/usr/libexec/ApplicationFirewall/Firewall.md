## Firewall

> `/usr/libexec/ApplicationFirewall/Firewall`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 328.0.0.0.0
-  __TEXT.__text: 0x105c
+  __TEXT.__text: 0x1050
   __TEXT.__auth_stubs: 0x1d0
   __TEXT.__cstring: 0x9b
   __TEXT.__const: 0x10
   __TEXT.__oslogstring: 0x1bb
-  __TEXT.__unwind_info: 0xa8
+  __TEXT.__unwind_info: 0xc0
   __DATA_CONST.__const: 0x68
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__auth_got: 0xe8
Functions:
~ sub_100000928 : 128 -> 116
~ sub_100001594 -> sub_100001588 : 20 -> 12
~ sub_1000015a8 -> sub_100001594 : 12 -> 20
```
