## patch

> `/usr/bin/patch`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 77.0.0.0.0
-  __TEXT.__text: 0x9a54
+  __TEXT.__text: 0x9998
   __TEXT.__auth_stubs: 0x5b0
   __TEXT.__const: 0x5c
   __TEXT.__cstring: 0x1aad
-  __TEXT.__unwind_info: 0x170
+  __TEXT.__unwind_info: 0x1e8
   __DATA_CONST.__const: 0xc0
   __DATA_CONST.__auth_got: 0x2d8
   __DATA_CONST.__got: 0x40
Functions:
~ sub_100000678 : 5668 -> 5664
~ sub_10000256c -> sub_100002568 : 432 -> 428
~ sub_10000271c -> sub_100002714 : 1224 -> 1200
~ sub_100002be4 -> sub_100002bc4 : 704 -> 700
~ sub_100002ea4 -> sub_100002e80 : 208 -> 196
~ sub_100002f74 -> sub_100002f44 : 88 -> 76
~ sub_100003068 -> sub_10000302c : 136 -> 124
~ sub_10000684c -> sub_100006804 : 860 -> 848
~ sub_100006dcc -> sub_100006d78 : 404 -> 392
~ sub_100007018 -> sub_100006fb8 : 2284 -> 2272
~ sub_100007edc -> sub_100007e70 : 1392 -> 1388
~ sub_1000088d8 -> sub_100008868 : 236 -> 212
~ sub_100008b38 -> sub_100008ab0 : 148 -> 136
~ sub_100008bcc -> sub_100008b38 : 56 -> 44
~ sub_100008c04 -> sub_100008b64 : 144 -> 132
~ sub_100008f24 -> sub_100008e78 : 636 -> 632
~ sub_100009544 -> sub_100009494 : 92 -> 80
```
