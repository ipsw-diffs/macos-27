## say

> `/usr/bin/say`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 4.0.2.0.0
-  __TEXT.__text: 0x531c
+  __TEXT.__text: 0x5174
   __TEXT.__auth_stubs: 0x9d0
   __TEXT.__init_offsets: 0x8
   __TEXT.__cstring: 0x8a2
   __TEXT.__const: 0xa0
   __TEXT.__gcc_except_tab: 0x120
-  __TEXT.__unwind_info: 0x1c0
+  __TEXT.__unwind_info: 0x1f8
   __DATA_CONST.__const: 0x2c8
   __DATA_CONST.__cfstring: 0x1e0
   __DATA_CONST.__auth_got: 0x4f0
Functions:
~ sub_100000a80 : 2760 -> 2752
~ sub_100001c68 -> sub_100001c60 : 936 -> 856
~ sub_100002010 -> sub_100001fb8 : 440 -> 400
~ sub_1000021c8 -> sub_100002148 : 360 -> 320
~ sub_10000238c -> sub_1000022e4 : 284 -> 232
~ sub_1000024a8 -> sub_1000023cc : 196 -> 144
~ sub_100002730 -> sub_100002620 : 196 -> 192
~ sub_10000339c -> sub_100003288 : 332 -> 320
~ sub_100003890 -> sub_100003770 : 184 -> 172
~ sub_100003ac0 -> sub_100003994 : 488 -> 464
~ sub_100003ed0 -> sub_100003d8c : 284 -> 268
~ sub_1000044f0 -> sub_10000439c : 144 -> 132
~ sub_100004820 -> sub_1000046c0 : 124 -> 112
~ sub_10000489c -> sub_100004730 : 1124 -> 1116
~ sub_100005070 -> sub_100004efc : 80 -> 68
~ sub_100005500 -> sub_100005380 : 748 -> 736
~ sub_1000057ec -> sub_100005660 : 196 -> 184
~ sub_100005bec -> sub_100005a54 : 236 -> 232
~ sub_100005cd8 -> sub_100005b3c : 92 -> 80
```
