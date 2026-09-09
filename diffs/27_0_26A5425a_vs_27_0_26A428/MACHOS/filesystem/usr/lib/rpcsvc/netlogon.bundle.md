## netlogon.bundle

> `/usr/lib/rpcsvc/netlogon.bundle`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 676.0.0.0.0
-  __TEXT.__text: 0x1e64c
+  __TEXT.__text: 0x1e45c
   __TEXT.__auth_stubs: 0xcf0
   __TEXT.__init_offsets: 0xc
   __TEXT.__const: 0x2f11
   __TEXT.__gcc_except_tab: 0x9a0
   __TEXT.__cstring: 0x1f0fb
   __TEXT.__oslogstring: 0xbf2
-  __TEXT.__unwind_info: 0x720
+  __TEXT.__unwind_info: 0x8f0
   __DATA_CONST.__const: 0x11f20
   __DATA_CONST.__cfstring: 0x300
   __DATA_CONST.__auth_got: 0x680
Functions:
~ __ZN14NL_SESSION_KEY10encryptKeyEP16_LM_OWF_PASSWORDS1_ : 88 -> 76
~ __ZN21NL_SHA256_SESSION_KEYD0Ev : 56 -> 44
~ __ZN18NL_MD5_SESSION_KEY25computeNetlogonCredentialEPK20_NETLOGON_CREDENTIALPS0_ : 80 -> 68
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ _OUTLINED_FUNCTION_2 : 24 -> 12
~ __ZN17NL_CLIENT_SESSIOND0Ev : 56 -> 44
~ _GLOBAL__sub_I_nlsession.cpp : 136 -> 124
~ __ZN21NL_PROXY_SAM_PROVIDERD0Ev : 152 -> 140
~ __ZN21NL_PROXY_SAM_PROVIDER17encryptLogonLevelE25NETLOGON_LOGON_INFO_CLASSP15_NETLOGON_LEVEL : 264 -> 252
~ __ZN21NL_PROXY_SAM_PROVIDER17decryptLogonLevelE25NETLOGON_LOGON_INFO_CLASSP15_NETLOGON_LEVEL : 264 -> 252
~ __ZN21NL_PROXY_SAM_PROVIDER28decryptValidationInformationE30NETLOGON_VALIDATION_INFO_CLASSP20_NETLOGON_VALIDATION : 340 -> 328
~ __ZN16NL_CLIENT_POLICYD0Ev : 56 -> 44
~ __ZL20NlpGetChannelOptionsPK14__CFDictionaryPhS2_S2_S2_S2_ : 172 -> 160
~ __ZL14NlpGetCFStringPK10__CFString : 176 -> 164
~ __ZL21NlpGetBooleanPropertyPK14__CFDictionaryPK10__CFStringPh : 124 -> 112
~ _OUTLINED_FUNCTION_1 : 32 -> 20
~ _GLOBAL__sub_I_nlpolicy.cpp : 136 -> 124
~ __ZNSt3__130__default_three_way_comparatorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEES6_vEclB9nqe220106ERKS6_S9_ : 112 -> 108
~ __ZN8platform12config_value18invalid_conversionD0Ev : 56 -> 44
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE25__init_copy_ctor_externalEPKcm : 68 -> 56
~ __ZNSt3__112__destroy_atB9nqe220106INS_4pairIKNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEN8platform12config_valueEEEEEvPT_ : 108 -> 96
~ _NetApiBufferFree : 52 -> 40
~ __Z15TokenFromHandleP8NtObject : 88 -> 68
~ __Z19GetTokenInformationP8NtObject24_TOKEN_INFORMATION_CLASSPvmPm : 596 -> 584
~ __Z23ImpersonateLoggedOnUserP8NtObject : 112 -> 100
~ __ZNSt3__16vectorIPvNS_9allocatorIS1_EEE6resizeEm : 284 -> 268
~ __ZN11rpc_mempool4freeEPv : 156 -> 144
~ __ZNSt3__16vectorIPvNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_ : 196 -> 192
~ __Z22RpcExceptionToNtStatusPK14_dcethread_exc : 40 -> 28
~ __Z15RpcSsCopyStringPKt : 108 -> 96
~ __ZN6darwin12darwin_tokenD2Ev : 96 -> 84
~ __ZN6darwin12darwin_tokenD0Ev : 56 -> 44
~ __Z29NtCreateTokenFromExportedNamejPKvm : 284 -> 272
~ __Z31NtCreateTokenFromValidationInfojPK21_KERB_VALIDATION_INFO : 264 -> 252
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ __Z19NtObjectDereferenceP8NtObject : 96 -> 84
~ __ZN6darwin16cfstring_convertEPK10__CFStringj : 416 -> 404
~ __ZN8platform12config_value20placeholder_specificINSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEED0Ev : 112 -> 100
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE24__emplace_back_slow_pathIJRKS6_EEEPS6_DpOT_ : 320 -> 316
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZN8platform18invoke_new_handlerEv : 76 -> 64
~ __ZN8platform13utf16_strndupEPKtm : 124 -> 120
```
