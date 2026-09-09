## gssd

> `/usr/sbin/gssd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 88.0.0.0.0
-  __TEXT.__text: 0x9c5c
+  __TEXT.__text: 0x9be0
   __TEXT.__auth_stubs: 0xaa0
   __TEXT.__const: 0x70
   __TEXT.__cstring: 0x2ca1
   __TEXT.__oslogstring: 0x19
-  __TEXT.__unwind_info: 0x190
+  __TEXT.__unwind_info: 0x208
   __DATA_CONST.__const: 0x278
   __DATA_CONST.__auth_got: 0x550
   __DATA_CONST.__got: 0xc0
Functions:
~ sub_100000928 : 288 -> 276
~ sub_10000100c -> sub_100001000 : 156 -> 144
~ sub_1000012bc -> sub_1000012a4 : 220 -> 208
~ sub_1000018ec -> sub_1000018c8 : 216 -> 204
~ sub_100001db0 -> sub_100001d80 : 36 -> 24
~ sub_100002c70 -> sub_100002c34 : 4184 -> 4168
~ sub_100005160 -> sub_100005114 : 1412 -> 1408
~ sub_1000056e4 -> sub_100005694 : 236 -> 212
~ sub_100007230 -> sub_1000071c8 : 876 -> 868
~ sub_100007a18 -> sub_1000079a8 : 164 -> 152
```
