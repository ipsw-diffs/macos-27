## L2TP

> `/System/Library/SystemConfiguration/PPPController.bundle/Contents/PlugIns/L2TP.ppp/Contents/MacOS/L2TP`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 1031.0.0.0.4
-  __TEXT.__text: 0xea48
+  __TEXT.__text: 0xe9a0
   __TEXT.__auth_stubs: 0xa10
   __TEXT.__const: 0x120
   __TEXT.__cstring: 0x39fa
-  __TEXT.__unwind_info: 0x210
+  __TEXT.__unwind_info: 0x2c0
   __DATA_CONST.__const: 0xf8
   __DATA_CONST.__cfstring: 0xfe0
   __DATA_CONST.__auth_got: 0x508
Functions:
~ _l2tp_send_SCCRQ : 88 -> 76
~ _l2tp_send_CDN : 276 -> 264
~ _l2tp_send_StopCCN : 264 -> 252
~ _l2tp_disconnect : 240 -> 228
~ sub_2c88 -> sub_2c58 : 92 -> 80
~ _l2tp_resolver_thread : 416 -> 408
~ sub_5390 -> sub_534c : 104 -> 92
~ sub_5ba4 -> sub_5b54 : 120 -> 108
~ _pfkey_send_register : 244 -> 232
~ sub_8544 -> sub_84dc : 7236 -> 7228
~ sub_a270 -> sub_a200 : 56 -> 44
~ _sockaddr_to_string : 352 -> 320
~ _get_int_option : 136 -> 124
```
