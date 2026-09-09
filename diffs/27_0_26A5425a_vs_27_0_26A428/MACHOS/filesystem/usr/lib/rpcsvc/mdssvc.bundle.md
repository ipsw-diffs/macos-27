## mdssvc.bundle

> `/usr/lib/rpcsvc/mdssvc.bundle`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 676.0.0.0.0
-  __TEXT.__text: 0xc570
+  __TEXT.__text: 0xc3e8
   __TEXT.__auth_stubs: 0xb30
   __TEXT.__init_offsets: 0x8
   __TEXT.__const: 0x700
   __TEXT.__gcc_except_tab: 0x870
   __TEXT.__oslogstring: 0x199d
   __TEXT.__cstring: 0x4ec
-  __TEXT.__unwind_info: 0x490
+  __TEXT.__unwind_info: 0x528
   __DATA_CONST.__const: 0x330
   __DATA_CONST.__cfstring: 0x220
   __DATA_CONST.__auth_got: 0x5a0
Functions:
~ __ZN17darwin_sharepointD0Ev : 56 -> 44
~ __Z19find_ipc_sharepointPK10__CFStringRj : 552 -> 540
~ __ZNSt3__130__default_three_way_comparatorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEES6_vEclB9nqe220106ERKS6_S9_ : 112 -> 108
~ __ZN8platform12config_value18invalid_conversionD0Ev : 56 -> 44
~ __ZNSt3__112__destroy_atB9nqe220106INS_4pairIKNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEN8platform12config_valueEEEEEvPT_ : 108 -> 96
~ _GLOBAL__sub_I_darwin_share.cpp : 96 -> 84
~ __ZN6darwin16cfstring_convertEPK10__CFStringj : 416 -> 404
~ __ZN8platform12config_value20placeholder_specificINSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEED0Ev : 112 -> 100
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE25__init_copy_ctor_externalEPKcm : 68 -> 56
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE24__emplace_back_slow_pathIJRKS6_EEEPS6_DpOT_ : 320 -> 316
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZN8platform18invoke_new_handlerEv : 76 -> 64
~ __ZN8platform15utf16_converter4initEPKh : 84 -> 72
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9nqe220106Ev : 360 -> 320
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEED2Ev : 284 -> 232
~ __Z21ConvertSidToStringSidPK4_SIDPPh : 708 -> 668
~ __ZNSt3__16vectorIPcNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_ : 196 -> 192
~ __Z15TokenFromHandleP8NtObject : 88 -> 68
~ __Z19GetTokenInformationP8NtObject24_TOKEN_INFORMATION_CLASSPvmPm : 596 -> 584
~ __Z17EqualAnonymousSidPK4_SID : 212 -> 200
~ __ZN6darwin12darwin_tokenD2Ev : 96 -> 84
~ __ZN6darwin12darwin_tokenD0Ev : 56 -> 44
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ __Z19NtObjectDereferenceP8NtObject : 96 -> 84
```
