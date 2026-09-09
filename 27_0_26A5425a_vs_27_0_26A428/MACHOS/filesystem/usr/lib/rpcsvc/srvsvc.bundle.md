## srvsvc.bundle

> `/usr/lib/rpcsvc/srvsvc.bundle`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 676.0.0.0.0
-  __TEXT.__text: 0x1b6b0
+  __TEXT.__text: 0x1b480
   __TEXT.__auth_stubs: 0xd40
   __TEXT.__init_offsets: 0xc
   __TEXT.__const: 0x30d0
   __TEXT.__gcc_except_tab: 0xa48
   __TEXT.__oslogstring: 0xe75
   __TEXT.__cstring: 0x1f0ee
-  __TEXT.__unwind_info: 0x6f0
+  __TEXT.__unwind_info: 0x8a0
   __DATA_CONST.__const: 0x11e68
   __DATA_CONST.__cfstring: 0x140
   __DATA_CONST.__auth_got: 0x6a8
Functions:
~ __ZN16sharepoint_table5resetERN8platform11counted_ptrIS_EE : 196 -> 184
~ __ZN10sharepointD0Ev : 56 -> 44
~ __ZNSt3__130__default_three_way_comparatorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEES6_vEclB9nqe220106ERKS6_S9_ : 112 -> 108
~ __ZN8platform12config_value18invalid_conversionD0Ev : 56 -> 44
~ __ZNSt3__112__destroy_atB9nqe220106INS_4pairIKNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEN8platform12config_valueEEEEEvPT_ : 108 -> 96
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _GLOBAL__sub_I_netr_share.cpp : 120 -> 108
~ __ZNSt3__14pairIK14sharepoint_keyN8platform11counted_ptrI10sharepointEEED1Ev : 108 -> 96
~ __Z19rpc_ss_copy_wstringPKt : 108 -> 96
~ __ZN16sharepoint_tableD0Ev : 108 -> 96
~ __ZNSt3__112__destroy_atB9nqe220106INS_4pairIK14sharepoint_keyN8platform11counted_ptrI10sharepointEEEEEEvPT_ : 108 -> 96
~ __ZN6darwin16cfstring_convertEPK10__CFStringj : 416 -> 404
~ __ZN8platform12config_value20placeholder_specificINSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEED0Ev : 112 -> 100
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE25__init_copy_ctor_externalEPKcm : 68 -> 56
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE24__emplace_back_slow_pathIJRKS6_EEEPS6_DpOT_ : 320 -> 316
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZN8platform18invoke_new_handlerEv : 76 -> 64
~ __ZN8platform6detail21lock_shared_memory_fdEisj : 352 -> 348
~ __ZN8platform15utf16_converter4initEPKh : 84 -> 72
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ _NetApiBufferFree : 52 -> 40
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9nqe220106Ev : 360 -> 320
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEED2Ev : 284 -> 232
~ __Z21ConvertSidToStringSidPK4_SIDPPh : 708 -> 668
~ __ZNSt3__16vectorIPcNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_ : 196 -> 192
~ __Z15TokenFromHandleP8NtObject : 88 -> 68
~ __Z19GetTokenInformationP8NtObject24_TOKEN_INFORMATION_CLASSPvmPm : 596 -> 584
~ __Z17EqualAnonymousSidPK4_SID : 212 -> 200
~ __Z23ImpersonateLoggedOnUserP8NtObject : 112 -> 100
~ __ZN8platform14tls_exhaustionD0Ev : 56 -> 44
~ _GLOBAL__sub_I_scoped_credential.cpp : 88 -> 76
~ __ZNSt3__16vectorIPvNS_9allocatorIS1_EEE6resizeEm : 284 -> 268
~ __ZN11rpc_mempool4freeEPv : 156 -> 144
~ __ZNSt3__16vectorIPvNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_ : 196 -> 192
~ __ZN6darwin12darwin_tokenD2Ev : 96 -> 84
~ __ZN6darwin12darwin_tokenD0Ev : 56 -> 44
~ __Z29NtCreateTokenFromExportedNamejPKvm : 284 -> 272
~ __Z31NtCreateTokenFromValidationInfojPK21_KERB_VALIDATION_INFO : 264 -> 252
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ __Z19NtObjectDereferenceP8NtObject : 96 -> 84
```
