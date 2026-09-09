## tftp

> `/usr/bin/tftp`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 308.0.0.0.0
-  __TEXT.__text: 0x5658
+  __TEXT.__text: 0x55e8
   __TEXT.__auth_stubs: 0x4c0
   __TEXT.__const: 0xb0
   __TEXT.__cstring: 0x1adc
-  __TEXT.__unwind_info: 0x140
+  __TEXT.__unwind_info: 0x1b0
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__auth_got: 0x260
   __DATA_CONST.__got: 0x38
Functions:
~ sub_100000700 : 780 -> 776
~ sub_100001624 -> sub_100001620 : 328 -> 304
~ sub_100002554 -> sub_100002538 : 284 -> 272
~ sub_100002670 -> sub_100002648 : 304 -> 292
~ sub_1000027a0 -> sub_10000276c : 308 -> 296
~ sub_100003070 -> sub_100003030 : 332 -> 320
~ sub_1000032ec -> sub_1000032a0 : 400 -> 384
~ sub_100003f20 -> sub_100003ec4 : 728 -> 724
~ sub_100004cc8 -> sub_100004c68 : 1208 -> 1204
~ sub_100005ac0 -> sub_100005a5c : 284 -> 272
```
