## countryd

> `/usr/libexec/countryd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 73.0.0.0.0
-  __TEXT.__text: 0x49b4
+  __TEXT.__text: 0x4900
   __TEXT.__auth_stubs: 0x2e0
   __TEXT.__objc_stubs: 0x7a0
   __TEXT.__objc_methlist: 0x45c

   __TEXT.__objc_methname: 0x91f
   __TEXT.__objc_classname: 0x98
   __TEXT.__objc_methtype: 0x2c1
-  __TEXT.__unwind_info: 0x128
+  __TEXT.__unwind_info: 0x150
   __DATA_CONST.__const: 0x130
   __DATA_CONST.__cfstring: 0x1a0
   __DATA_CONST.__objc_classlist: 0x20
Functions:
~ sub_100001464 : 84 -> 72
~ sub_100001774 -> sub_100001768 : 72 -> 60
~ sub_1000017bc -> sub_1000017a4 : 92 -> 80
~ sub_100003990 -> sub_10000396c : 68 -> 56
~ sub_1000039d4 -> sub_1000039a4 : 68 -> 56
~ sub_10000451c -> sub_1000044e0 : 68 -> 56
~ sub_100004560 -> sub_100004518 : 72 -> 60
~ sub_1000045a8 -> sub_100004554 : 104 -> 92
~ sub_100004824 -> sub_1000047c4 : 160 -> 148
~ sub_1000048ec -> sub_100004880 : 68 -> 56
~ sub_100004ba0 -> sub_100004b28 : 108 -> 96
~ sub_100004c0c -> sub_100004b88 : 212 -> 200
~ sub_100004ce0 -> sub_100004c50 : 1056 -> 1044
~ sub_1000056ac -> sub_100005610 : 72 -> 60
~ sub_1000056f4 -> sub_10000564c : 72 -> 60
```
