## tracd

> `/usr/libexec/tracd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 161.0.2.0.0
-  __TEXT.__text: 0x756c
+  __TEXT.__text: 0x73e8
   __TEXT.__auth_stubs: 0x4b0
   __TEXT.__objc_stubs: 0xd60
   __TEXT.__objc_methlist: 0x404

   __TEXT.__objc_methname: 0xfff
   __TEXT.__objc_methtype: 0x47f
   __TEXT.__gcc_except_tab: 0x158
-  __TEXT.__unwind_info: 0x200
+  __TEXT.__unwind_info: 0x250
   __DATA_CONST.__const: 0x2f0
   __DATA_CONST.__cfstring: 0x660
   __DATA_CONST.__objc_classlist: 0x38
Functions:
~ sub_100000f80 : 132 -> 120
~ sub_100001390 -> sub_100001384 : 28 -> 16
~ sub_1000013dc -> sub_1000013c4 : 24 -> 12
~ sub_100001cc8 -> sub_100001ca4 : 64 -> 52
~ sub_100001d08 -> sub_100001cd8 : 60 -> 48
~ sub_100001d44 -> sub_100001d08 : 60 -> 48
~ sub_100001d84 -> sub_100001d3c : 312 -> 300
~ sub_100001ec4 -> sub_100001e70 : 460 -> 448
~ sub_100002814 -> sub_1000027b4 : 140 -> 128
~ sub_100003cac -> sub_100003c40 : 76 -> 64
~ sub_100003cf8 -> sub_100003c80 : 68 -> 56
~ sub_10000407c -> sub_100003ff8 : 80 -> 68
~ sub_1000040cc -> sub_10000403c : 56 -> 44
~ sub_10000453c -> sub_1000044a0 : 340 -> 328
~ sub_100004854 -> sub_1000047ac : 140 -> 128
~ sub_100004960 -> sub_1000048ac : 160 -> 148
~ sub_100004af4 -> sub_100004a34 : 68 -> 56
~ sub_100004b38 -> sub_100004a6c : 204 -> 192
~ sub_100004c04 -> sub_100004b2c : 72 -> 60
~ sub_100004ca0 -> sub_100004bbc : 104 -> 92
~ sub_100005854 -> sub_100005764 : 92 -> 80
~ sub_1000058fc -> sub_100005800 : 32 -> 20
~ sub_10000591c -> sub_100005814 : 204 -> 192
~ sub_1000059e8 -> sub_1000058d4 : 60 -> 48
~ sub_100005ff8 -> sub_100005ed8 : 80 -> 68
~ sub_100006048 -> sub_100005f1c : 72 -> 60
~ sub_1000060c8 -> sub_100005f90 : 92 -> 80
~ sub_100006214 -> sub_1000060d0 : 756 -> 740
~ sub_100007330 -> sub_1000071dc : 184 -> 172
~ sub_100007974 -> sub_100007814 : 216 -> 204
~ sub_100007c48 -> sub_100007adc : 144 -> 132
~ sub_100007e4c -> sub_100007cd4 : 92 -> 80
```
