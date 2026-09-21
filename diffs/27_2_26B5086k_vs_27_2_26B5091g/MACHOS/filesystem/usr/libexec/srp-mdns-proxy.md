## srp-mdns-proxy

> `/usr/libexec/srp-mdns-proxy`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-3111.40.40.0.0
-  __TEXT.__text: 0x8e37c
+3111.40.42.0.0
+  __TEXT.__text: 0x8e46c
   __TEXT.__auth_stubs: 0x14f0
   __TEXT.__const: 0x2f5
   __TEXT.__cstring: 0x91d2
-  __TEXT.__oslogstring: 0x14112
+  __TEXT.__oslogstring: 0x1419c
   __TEXT.__unwind_info: 0x848
   __TEXT.__eh_frame: 0x7c
   __DATA_CONST.__const: 0x920

   - /usr/lib/libsqlite3.dylib
   Functions: 481
   Symbols:   1120
-  CStrings:  2608
+  CStrings:  2609
 
Functions:
~ _srp_mdns_cancel_previous_instance : 524 -> 536
~ _prepare_update : 23280 -> 23296
~ _register_instance : 1704 -> 1708
~ _instance_vec_txns_forget : 368 -> 576
CStrings:
+ "%{public}s: forgetting previous sdref %p on %{public}s %p %{private, mask.hash}s instance %{private, mask.hash}s . %{private, mask.hash}s"
+ "00:29:07"
+ "Sep 12 2026"
- "21:21:11"
- "Sep  4 2026"
```
