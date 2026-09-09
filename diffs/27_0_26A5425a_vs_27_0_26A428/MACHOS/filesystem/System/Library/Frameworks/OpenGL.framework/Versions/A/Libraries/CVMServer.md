## CVMServer

> `/System/Library/Frameworks/OpenGL.framework/Versions/A/Libraries/CVMServer`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 404.0.0.0.0
-  __TEXT.__text: 0x7a20
+  __TEXT.__text: 0x7980
   __TEXT.__auth_stubs: 0x910
   __TEXT.__const: 0xa0
   __TEXT.__cstring: 0x963
   __TEXT.__oslogstring: 0xc5
-  __TEXT.__unwind_info: 0x160
+  __TEXT.__unwind_info: 0x1a8
   __DATA_CONST.__const: 0x198
   __DATA_CONST.__auth_got: 0x488
   __DATA_CONST.__got: 0x80
Functions:
~ _cvmsServerTerminate : 108 -> 96
~ _cvmsTermFreeServerThread : 120 -> 108
~ _cvmsTermFreeServerCompiler : 88 -> 76
~ _cvmsTermFreeServerElement : 140 -> 128
~ _my_xpc_connection_send_message_with_reply_sync : 172 -> 160
~ _cvmsRunTimer : 520 -> 492
~ _my_xpc_connection_release : 88 -> 76
~ _OUTLINED_FUNCTION_3 : 28 -> 16
~ _cvmsServSigTermHandler : 104 -> 92
~ ___cvmsServInitializeConnection_block_invoke : 3120 -> 3108
~ _cvmsDeletePool : 176 -> 164
~ _cvmsPoolRealloc : 552 -> 540
```
