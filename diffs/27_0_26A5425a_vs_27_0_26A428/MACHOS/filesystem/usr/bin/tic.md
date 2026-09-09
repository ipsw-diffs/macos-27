## tic

> `/usr/bin/tic`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 81.0.0.0.0
-  __TEXT.__text: 0x6d8c
+  __TEXT.__text: 0x6d58
   __TEXT.__auth_stubs: 0x500
   __TEXT.__const: 0x2dc0
   __TEXT.__cstring: 0x18b0
-  __TEXT.__unwind_info: 0x120
+  __TEXT.__unwind_info: 0x178
   __DATA_CONST.__const: 0x28
   __DATA_CONST.__auth_got: 0x280
   __DATA_CONST.__got: 0xe0
Functions:
~ sub_1000018e8 : 8188 -> 8184
~ sub_1000038e4 -> sub_1000038e0 : 108 -> 96
~ sub_100003950 -> sub_100003940 : 304 -> 292
~ sub_100004980 -> sub_100004964 : 52 -> 40
~ sub_100005cd4 -> sub_100005cac : 100 -> 88
```
