## smb-migrate-preferences

> `/usr/libexec/smb-migrate-preferences`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 676.0.0.0.0
-  __TEXT.__text: 0x2e80
+  __TEXT.__text: 0x2e30
   __TEXT.__auth_stubs: 0x570
   __TEXT.__const: 0x2a6
   __TEXT.__cstring: 0x2f6
   __TEXT.__oslogstring: 0xb1
   __TEXT.__gcc_except_tab: 0x290
-  __TEXT.__unwind_info: 0x268
+  __TEXT.__unwind_info: 0x2b0
   __DATA_CONST.__const: 0x1f0
   __DATA_CONST.__cfstring: 0xa0
   __DATA_CONST.__auth_got: 0x2c0
Functions:
~ __ZNKSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE7compareB9nqe220106INS_17basic_string_viewIcS2_EELi0EEEiRKT_ : 84 -> 80
~ __ZN8platform12config_value18invalid_conversionD0Ev : 56 -> 44
~ __ZNSt3__112__destroy_atB9nqe220106INS_4pairIKNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEN8platform12config_valueEEEEEvPT_ : 108 -> 96
~ __ZN6darwin16cfstring_convertEPK10__CFStringj : 416 -> 404
~ __ZN8platform12config_value20placeholder_specificINSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEED0Ev : 112 -> 100
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE25__init_copy_ctor_externalEPKcm : 68 -> 56
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE24__emplace_back_slow_pathIJRKS6_EEEPS6_DpOT_ : 320 -> 316
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
```
