## latency

> `/usr/bin/latency`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 1071.0.1.0.0
-  __TEXT.__text: 0x4080
+  __TEXT.__text: 0x405c
   __TEXT.__auth_stubs: 0x340
   __TEXT.__const: 0x80
   __TEXT.__cstring: 0x136d
-  __TEXT.__unwind_info: 0xb8
+  __TEXT.__unwind_info: 0xd8
   __DATA_CONST.__auth_got: 0x1a0
   __DATA_CONST.__got: 0x20
   __DATA.__data: 0xe8
Functions:
~ sub_1000021c4 : 3652 -> 3644
~ sub_100003008 -> sub_100003000 : 176 -> 164
~ sub_100003224 -> sub_100003210 : 620 -> 608
~ sub_1000042c0 -> sub_1000042a0 : 316 -> 312
```
