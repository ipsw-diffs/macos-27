## usbpowerd

> `/usr/libexec/usbpowerd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 1617.0.12.0.0
-  __TEXT.__text: 0x2a80
+  __TEXT.__text: 0x2a3c
   __TEXT.__auth_stubs: 0x440
   __TEXT.__objc_stubs: 0x580
   __TEXT.__objc_methlist: 0x194

   __TEXT.__cstring: 0x257
   __TEXT.__objc_classname: 0xf
   __TEXT.__objc_methtype: 0xda
-  __TEXT.__unwind_info: 0xe0
+  __TEXT.__unwind_info: 0x150
   __DATA_CONST.__const: 0xe0
   __DATA_CONST.__cfstring: 0x160
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ sub_1000011ec : 164 -> 152
~ sub_10000158c -> sub_100001580 : 84 -> 72
~ sub_1000016f0 -> sub_1000016d8 : 312 -> 300
~ sub_1000018ac -> sub_100001888 : 168 -> 164
~ sub_100001ccc -> sub_100001ca4 : 72 -> 68
~ sub_100001fcc -> sub_100001fa0 : 116 -> 104
~ sub_100002054 -> sub_10000201c : 28 -> 16
```
