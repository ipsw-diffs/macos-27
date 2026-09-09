## natpmpd

> `/usr/libexec/natpmpd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 118.0.0.0.0
-  __TEXT.__text: 0x4fa4
+  __TEXT.__text: 0x4f54
   __TEXT.__auth_stubs: 0x3b0
   __TEXT.__cstring: 0x8d2
   __TEXT.__const: 0x60
-  __TEXT.__unwind_info: 0x130
+  __TEXT.__unwind_info: 0x240
   __DATA_CONST.__const: 0x168
   __DATA_CONST.__auth_got: 0x1d8
   __DATA_CONST.__got: 0xc0
Functions:
~ sub_100000be0 : 1352 -> 1344
~ sub_100001444 -> sub_10000143c : 348 -> 336
~ sub_100003218 -> sub_100003204 : 64 -> 52
~ sub_100004348 -> sub_100004328 : 168 -> 156
~ sub_10000455c -> sub_100004530 : 172 -> 160
~ sub_100004750 -> sub_100004718 : 164 -> 152
~ sub_100004c6c -> sub_100004c28 : 148 -> 136
```
