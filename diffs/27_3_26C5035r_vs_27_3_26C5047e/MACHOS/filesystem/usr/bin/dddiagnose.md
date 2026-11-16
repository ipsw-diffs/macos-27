## dddiagnose

> `/usr/bin/dddiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 129.0.1.0.0
-  __TEXT.__text: 0x33900
+  __TEXT.__text: 0x33a10
   __TEXT.__auth_stubs: 0x11c0
   __TEXT.__objc_stubs: 0xe0
   __TEXT.__objc_methlist: 0x104
Functions:
~ sub_1000016b4 : 112 -> 124
~ sub_100004e98 -> sub_100004ea4 : 260 -> 284
~ sub_100005ec0 -> sub_100005ee4 : 700 -> 704
~ sub_100007aa4 -> sub_100007acc : 260 -> 284
~ sub_1000081c8 -> sub_100008208 : 696 -> 700
~ sub_10000d3e8 -> sub_10000d42c : 252 -> 276
~ sub_10000d830 -> sub_10000d88c : 132 -> 156
~ sub_100012590 -> sub_100012604 : 140 -> 176
~ sub_10001261c -> sub_1000126b4 : 316 -> 352
~ sub_100013df0 -> sub_100013eac : 700 -> 704
~ sub_100014738 -> sub_1000147f8 : 708 -> 724
~ sub_100017864 -> sub_100017934 : 432 -> 460
~ sub_1000341e8 -> sub_1000342d4 : 316 -> 352
```
