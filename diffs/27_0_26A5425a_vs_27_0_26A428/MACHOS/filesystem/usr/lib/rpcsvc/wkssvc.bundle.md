## wkssvc.bundle

> `/usr/lib/rpcsvc/wkssvc.bundle`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 676.0.0.0.0
-  __TEXT.__text: 0xa2fc
+  __TEXT.__text: 0xa2ac
   __TEXT.__auth_stubs: 0x580
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0x444
   __TEXT.__cstring: 0x16a
   __TEXT.__gcc_except_tab: 0x308
   __TEXT.__oslogstring: 0x59
-  __TEXT.__unwind_info: 0x2b8
+  __TEXT.__unwind_info: 0x378
   __DATA_CONST.__const: 0x1e8
   __DATA_CONST.__cfstring: 0xc0
   __DATA_CONST.__auth_got: 0x2c8
Functions:
~ __ZN6darwin16cfstring_convertEPK10__CFStringj : 416 -> 404
~ __ZN8platform12config_value20placeholder_specificINSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEED0Ev : 112 -> 100
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE25__init_copy_ctor_externalEPKcm : 68 -> 56
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE24__emplace_back_slow_pathIJRKS6_EEEPS6_DpOT_ : 320 -> 316
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZNSt3__130__default_three_way_comparatorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEES6_vEclB9nqe220106ERKS6_S9_ : 112 -> 108
~ __ZNSt3__112__destroy_atB9nqe220106INS_4pairIKNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEN8platform12config_valueEEEEEvPT_ : 108 -> 96
~ __ZN8platform12config_value18invalid_conversionD0Ev : 56 -> 44
```
