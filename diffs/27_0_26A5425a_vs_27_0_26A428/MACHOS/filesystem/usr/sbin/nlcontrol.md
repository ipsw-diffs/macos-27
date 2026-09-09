## nlcontrol

> `/usr/sbin/nlcontrol`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 676.0.0.0.0
-  __TEXT.__text: 0x6440
+  __TEXT.__text: 0x6348
   __TEXT.__auth_stubs: 0x500
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0x238
   __TEXT.__gcc_except_tab: 0x184
   __TEXT.__cstring: 0x1eee5
   __TEXT.__oslogstring: 0xe5
-  __TEXT.__unwind_info: 0x1f0
+  __TEXT.__unwind_info: 0x228
   __DATA_CONST.__const: 0x11a50
   __DATA_CONST.__auth_got: 0x288
   __DATA_CONST.__got: 0x88
Functions:
~ _GLOBAL__sub_I_nlcontrol.cpp : 120 -> 108
~ __ZN8platform18invoke_new_handlerEv : 76 -> 64
~ __ZN8platform15utf16_converter4initEPKh : 84 -> 72
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ _NetApiBufferFree : 52 -> 40
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9nqe220106Ev : 360 -> 320
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEED2Ev : 284 -> 232
~ __ZNSt3__16vectorIPvNS_9allocatorIS1_EEE6resizeEm : 284 -> 268
~ __ZN11rpc_mempool4freeEPv : 156 -> 144
~ __Z16make_rpc_bindingPKcS0_ : 1144 -> 1104
~ __ZNSt3__16vectorIPvNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_ : 196 -> 192
~ __Z22RpcExceptionToDosErrorPK14_dcethread_exc : 40 -> 28
```
