## PPPoE

> `/System/Library/SystemConfiguration/PPPController.bundle/Contents/PlugIns/PPPoE.ppp/Contents/MacOS/PPPoE`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 1031.0.0.0.4
-  __TEXT.__text: 0xde8
+  __TEXT.__text: 0xdc4
   __TEXT.__auth_stubs: 0x290
   __TEXT.__cstring: 0x581
-  __TEXT.__unwind_info: 0x88
+  __TEXT.__unwind_info: 0xa8
   __DATA_CONST.__auth_got: 0x148
   __DATA_CONST.__got: 0x70
   __DATA.__data: 0x314
Functions:
~ _pppoe_wait_input : 156 -> 144
~ _pppoe_disconnect : 120 -> 108
~ sub_12b8 -> sub_12a0 : 120 -> 108
```
