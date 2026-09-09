## fdisk

> `/usr/sbin/fdisk`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 766.0.1.0.0
-  __TEXT.__text: 0x3228
+  __TEXT.__text: 0x31e4
   __TEXT.__auth_stubs: 0x290
   __TEXT.__cstring: 0x1841
   __TEXT.__const: 0x10
-  __TEXT.__unwind_info: 0x140
+  __TEXT.__unwind_info: 0x1b8
   __DATA_CONST.__const: 0xb40
   __DATA_CONST.__auth_got: 0x148
   __DATA_CONST.__got: 0x40
Functions:
~ sub_100001dec : 1184 -> 1188
~ sub_100002548 -> sub_10000254c : 132 -> 120
~ sub_100002908 -> sub_100002900 : 28 -> 16
~ sub_100002b0c -> sub_100002af8 : 364 -> 352
~ sub_100002c78 -> sub_100002c58 : 240 -> 228
~ sub_100003298 -> sub_10000326c : 136 -> 124
~ sub_10000358c -> sub_100003554 : 188 -> 176
```
