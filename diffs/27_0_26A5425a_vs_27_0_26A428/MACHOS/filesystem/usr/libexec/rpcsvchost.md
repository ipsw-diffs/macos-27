## rpcsvchost

> `/usr/libexec/rpcsvchost`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 676.0.0.0.0
-  __TEXT.__text: 0x2ccc
+  __TEXT.__text: 0x2cb4
   __TEXT.__auth_stubs: 0x4a0
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0x80
   __TEXT.__gcc_except_tab: 0x1f0
   __TEXT.__oslogstring: 0x50e
   __TEXT.__cstring: 0x4a5
-  __TEXT.__unwind_info: 0x108
+  __TEXT.__unwind_info: 0x130
   __DATA_CONST.__const: 0x40
   __DATA_CONST.__auth_got: 0x258
   __DATA_CONST.__got: 0x50
Functions:
~ __ZNSt3__16vectorINS_4pairINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEiEENS5_IS8_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZNSt3__16vectorIPcNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_ : 196 -> 192
~ __ZNSt3__16vectorINS_4pairIPK13rpcsvc_pluginPK22rpc_if_handle_vector_tEENS_9allocatorIS8_EEE24__emplace_back_slow_pathIJRKS8_EEEPS8_DpOT_ : 196 -> 192
~ __ZN6darwin14launch_checkinERNS_10launch_jobE : 1380 -> 1376
```
