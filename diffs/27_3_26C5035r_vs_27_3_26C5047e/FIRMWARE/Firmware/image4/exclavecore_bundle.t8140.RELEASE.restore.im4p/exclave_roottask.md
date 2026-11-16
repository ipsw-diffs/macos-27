## exclave_roottask

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_roottask`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__chain_fixups`
- `__TEXT.__eh_frame`
- `__DATA.__shared_cache`
- `__DATA.__mod_init_func`
- `__DATA.__auth_ptr`
- `__DATA.__const`
- `__DATA.__got`
- `__DATA.__thread_vars`

```diff

 1490.60.7.0.0
-  __TEXT.__text: 0x4f4200
+  __TEXT.__text: 0x4f5688
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__const: 0xf28e0
-  __TEXT.__cstring: 0x3e7d2
-  __TEXT.__swift5_typeref: 0xd104
+  __TEXT.__const: 0xf2930
+  __TEXT.__cstring: 0x3e8f2
+  __TEXT.__swift5_typeref: 0xd148
   __TEXT.__swift5_capture: 0x15c4
   __TEXT.__swift5_entry: 0x8
   __TEXT.__swift5_reflstr: 0xb3ec

   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x80
   __TEXT.__eh_frame: 0x222bc
-  __DATA.__data: 0xcfe8
+  __DATA.__data: 0xd020
   __DATA.__shared_cache: 0x70
   __DATA.__mod_init_func: 0x58
   __DATA.__auth_ptr: 0x1188

   __DATA_CONST.__mod_term_func: 0x0
   __PDATA.__mod_init_func: 0x0
   __PDATA.__shared_cache: 0x0
-  Functions: 19360
+  Functions: 19370
   Symbols:   29
-  CStrings:  6120
+  CStrings:  6125
 
CStrings:
+ "Builtin.FixedArray of %zd elements with stride %zu is too large to be representable\n"
+ "Tried to build a Builtin.FixedArray without metadata for the element type"
+ "type bound to a value generic parameter"
+ "type where a Builtin.FixedArray count is required"
+ "unresolved Builtin.FixedArray element type"
```
