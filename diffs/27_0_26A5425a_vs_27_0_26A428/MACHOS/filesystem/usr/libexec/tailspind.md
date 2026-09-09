## tailspind

> `/usr/libexec/tailspind`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 268.0.0.0.0
-  __TEXT.__text: 0xd674
+  __TEXT.__text: 0xd590
   __TEXT.__auth_stubs: 0xa60
   __TEXT.__objc_stubs: 0x960
   __TEXT.__objc_methlist: 0x254

   __TEXT.__objc_methname: 0xd2f
   __TEXT.__objc_classname: 0x14
   __TEXT.__objc_methtype: 0x119
-  __TEXT.__unwind_info: 0x400
+  __TEXT.__unwind_info: 0x530
   __DATA_CONST.__const: 0x430
   __DATA_CONST.__cfstring: 0x780
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ sub_100000fb0 : 68 -> 56
~ sub_100000ff4 -> sub_100000fe8 : 100 -> 88
~ sub_1000016e0 -> sub_1000016c8 : 276 -> 252
~ sub_100003578 -> sub_100003548 : 140 -> 128
~ sub_1000054c0 -> sub_100005484 : 108 -> 96
~ sub_100006fc8 -> sub_100006f80 : 236 -> 224
~ sub_1000070b4 -> sub_100007060 : 148 -> 136
~ sub_1000071d8 -> sub_100007178 : 260 -> 248
~ sub_1000077c4 -> sub_100007758 : 68 -> 56
~ sub_100007808 -> sub_100007790 : 68 -> 56
~ sub_100007a38 -> sub_1000079b4 : 60 -> 48
~ sub_100007a74 -> sub_1000079e4 : 60 -> 48
~ sub_100007c70 -> sub_100007bd4 : 16 -> 20
~ sub_100007c80 -> sub_100007be8 : 20 -> 16
~ sub_100007dfc -> sub_100007d60 : 132 -> 120
~ sub_100007ff4 -> sub_100007f4c : 2744 -> 2732
~ sub_100008aac -> sub_1000089f8 : 1348 -> 1336
~ sub_100009118 -> sub_100009058 : 212 -> 200
~ sub_10000cd38 -> sub_10000cc6c : 244 -> 232
~ sub_10000cf08 -> sub_10000ce30 : 92 -> 80
```
