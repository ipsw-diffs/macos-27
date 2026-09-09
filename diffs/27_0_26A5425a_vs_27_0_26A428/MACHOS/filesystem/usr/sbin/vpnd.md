## vpnd

> `/usr/sbin/vpnd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 1031.0.0.0.4
-  __TEXT.__text: 0xf520
+  __TEXT.__text: 0xf460
   __TEXT.__auth_stubs: 0x970
   __TEXT.__cstring: 0x355f
   __TEXT.__const: 0x8c
-  __TEXT.__unwind_info: 0x258
+  __TEXT.__unwind_info: 0x300
   __DATA_CONST.__const: 0x70
   __DATA_CONST.__cfstring: 0x1320
   __DATA_CONST.__auth_got: 0x4b8
Functions:
~ sub_100000ce0 : 204 -> 180
~ _toggle_debug : 124 -> 112
~ _add_address_range : 320 -> 308
~ _apply_address_update : 356 -> 344
~ sub_1000037b8 -> sub_10000377c : 224 -> 212
~ _addstrparam : 80 -> 68
~ _closeall : 120 -> 108
~ _get_route_interface : 104 -> 92
~ sub_100004e98 -> sub_100004e2c : 7236 -> 7228
~ sub_100006bc4 -> sub_100006b50 : 56 -> 44
~ _sockaddr_to_string : 352 -> 320
~ _ppp_process_prefs : 4720 -> 4712
~ _pfkey_send_register : 244 -> 232
~ _get_int_option : 136 -> 124
```
