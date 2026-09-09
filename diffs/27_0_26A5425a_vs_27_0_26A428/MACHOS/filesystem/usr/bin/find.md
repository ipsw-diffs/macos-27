## find

> `/usr/bin/find`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 334.0.0.0.0
-  __TEXT.__text: 0x5498
+  __TEXT.__text: 0x5448
   __TEXT.__auth_stubs: 0x5a0
   __TEXT.__const: 0x305
   __TEXT.__cstring: 0xa8f
-  __TEXT.__unwind_info: 0x1e0
+  __TEXT.__unwind_info: 0x270
   __DATA_CONST.__const: 0x17e0
   __DATA_CONST.__auth_got: 0x2d0
   __DATA_CONST.__got: 0x40
Functions:
~ sub_100000bd8 : 32 -> 20
~ sub_10000166c -> sub_100001660 : 84 -> 72
~ sub_10000243c -> sub_100002424 : 88 -> 76
~ sub_100002f24 -> sub_100002f00 : 324 -> 320
~ sub_1000034c8 -> sub_1000034a0 : 36 -> 24
~ sub_1000034ec -> sub_1000034b8 : 24 -> 12
~ sub_100003504 -> sub_1000034c4 : 32 -> 20
~ sub_100003a28 -> sub_1000039dc : 372 -> 360
~ sub_10000410c -> sub_1000040b4 : 3568 -> 3580
~ sub_100005370 -> sub_100005324 : 620 -> 616
```
