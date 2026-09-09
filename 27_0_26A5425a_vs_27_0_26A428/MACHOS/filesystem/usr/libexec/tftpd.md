## tftpd

> `/usr/libexec/tftpd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 308.0.0.0.0
-  __TEXT.__text: 0x3e44
+  __TEXT.__text: 0x3e20
   __TEXT.__auth_stubs: 0x3f0
   __TEXT.__const: 0x78
   __TEXT.__cstring: 0xdf8
-  __TEXT.__unwind_info: 0xf8
+  __TEXT.__unwind_info: 0x138
   __DATA_CONST.__const: 0x30
   __DATA_CONST.__auth_got: 0x1f8
   __DATA_CONST.__got: 0x20
Functions:
~ sub_10000076c : 332 -> 320
~ sub_1000009e8 -> sub_1000009dc : 400 -> 384
~ sub_1000014a4 -> sub_100001488 : 728 -> 724
~ sub_100002128 -> sub_100002108 : 1208 -> 1204
```
