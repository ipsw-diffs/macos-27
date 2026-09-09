## pmudiagnose

> `/usr/libexec/pmudiagnose/pmudiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__cfstring`

```diff

 743.0.4.0.0
-  __TEXT.__text: 0x2fc0
+  __TEXT.__text: 0x2f98
   __TEXT.__auth_stubs: 0x3c0
   __TEXT.__gcc_except_tab: 0xf8
   __TEXT.__cstring: 0x3ef
-  __TEXT.__unwind_info: 0x140
+  __TEXT.__unwind_info: 0x170
   __DATA_CONST.__cfstring: 0xa0
   __DATA_CONST.__auth_got: 0x1e8
   __DATA_CONST.__got: 0x60
Functions:
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE25__init_copy_ctor_externalEPKcm : 68 -> 56
~ __ZNSt3__16vectorI6regionNS_9allocatorIS1_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZNSt3__16vectorI6regionNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJS1_EEEPS1_DpOT_ : 292 -> 288
~ _ZN13PTDConnection12get_InstanceEv.cold.1 : 104 -> 92
```
