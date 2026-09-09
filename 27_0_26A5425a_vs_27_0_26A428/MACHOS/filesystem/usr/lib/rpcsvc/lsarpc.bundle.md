## lsarpc.bundle

> `/usr/lib/rpcsvc/lsarpc.bundle`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 676.0.0.0.0
-  __TEXT.__text: 0x1a1f0
+  __TEXT.__text: 0x1a0f8
   __TEXT.__auth_stubs: 0x730
   __TEXT.__init_offsets: 0x8
   __TEXT.__const: 0x2e00
   __TEXT.__gcc_except_tab: 0x3ac
   __TEXT.__oslogstring: 0x307
   __TEXT.__cstring: 0x1ecaa
-  __TEXT.__unwind_info: 0x3a8
+  __TEXT.__unwind_info: 0x548
   __DATA_CONST.__const: 0x11ba8
   __DATA_CONST.__auth_got: 0x3a0
   __DATA_CONST.__got: 0x70
Functions:
~ __ZN8platform18invoke_new_handlerEv : 76 -> 64
~ __ZN8platform15utf16_converter4initEPKh : 84 -> 72
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ _NetApiBufferFree : 52 -> 40
~ __ZNSt3__16vectorIPcNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_ : 196 -> 192
~ __Z15TokenFromHandleP8NtObject : 88 -> 68
~ __Z19GetTokenInformationP8NtObject24_TOKEN_INFORMATION_CLASSPvmPm : 596 -> 584
~ __Z23ImpersonateLoggedOnUserP8NtObject : 112 -> 100
~ __ZN8platform14tls_exhaustionD0Ev : 56 -> 44
~ _GLOBAL__sub_I_scoped_credential.cpp : 88 -> 76
~ __ZNSt3__16vectorIPvNS_9allocatorIS1_EEE6resizeEm : 284 -> 268
~ __ZN11rpc_mempool4freeEPv : 156 -> 144
~ __ZNSt3__16vectorIPvNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_ : 196 -> 192
~ __Z15RpcSsCopyStringPKt : 108 -> 96
~ __ZN6darwin12darwin_tokenD2Ev : 96 -> 84
~ __ZN6darwin12darwin_tokenD0Ev : 56 -> 44
~ __Z29NtCreateTokenFromExportedNamejPKvm : 284 -> 272
~ __Z31NtCreateTokenFromValidationInfojPK21_KERB_VALIDATION_INFO : 264 -> 252
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ __Z19NtObjectDereferenceP8NtObject : 96 -> 84
```
