## infocmp

> `/usr/bin/infocmp`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 81.0.0.0.0
-  __TEXT.__text: 0x5ae4
+  __TEXT.__text: 0x5ac8
   __TEXT.__auth_stubs: 0x3a0
   __TEXT.__const: 0x2854
   __TEXT.__cstring: 0xc8e
-  __TEXT.__unwind_info: 0x108
+  __TEXT.__unwind_info: 0x130
   __DATA_CONST.__const: 0x38
   __DATA_CONST.__auth_got: 0x1d0
   __DATA_CONST.__got: 0xb0
Functions:
~ sub_1000006b8 : 2864 -> 2888
~ sub_100002388 -> sub_1000023a0 : 236 -> 224
~ sub_100002474 -> sub_100002480 : 1628 -> 1636
~ sub_100002ad0 -> sub_100002ae4 : 332 -> 344
~ sub_1000033c0 -> sub_1000033e0 : 108 -> 96
~ sub_100003494 -> sub_1000034a8 : 160 -> 148
~ sub_1000035d4 -> sub_1000035dc : 184 -> 172
~ sub_100004920 -> sub_10000491c : 100 -> 88
~ sub_100005a78 -> sub_100005a68 : 780 -> 768
```
