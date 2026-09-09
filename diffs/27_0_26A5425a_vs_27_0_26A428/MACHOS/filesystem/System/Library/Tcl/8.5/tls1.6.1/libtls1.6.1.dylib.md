## libtls1.6.1.dylib

> `/System/Library/Tcl/8.5/tls1.6.1/libtls1.6.1.dylib`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 154.0.0.0.0
-  __TEXT.__text: 0x4688
+  __TEXT.__text: 0x4604
   __TEXT.__auth_stubs: 0x670
   __TEXT.__const: 0x20
   __TEXT.__cstring: 0x662
-  __TEXT.__unwind_info: 0xd8
+  __TEXT.__unwind_info: 0x110
   __DATA_CONST.__const: 0x70
   __DATA_CONST.__auth_got: 0x338
   __DATA_CONST.__got: 0x8
Functions:
~ _Tls_Error : 672 -> 660
~ _Tls_Free : 72 -> 60
~ _InfoCallback : 776 -> 764
~ _TlsGetOptionProc : 216 -> 204
~ _TlsWatchProc : 408 -> 396
~ _TlsGetHandleProc : 96 -> 84
~ _TlsBlockModeProc : 176 -> 164
~ _Tls_GetParent : 184 -> 172
~ _TlsChannelHandler : 316 -> 304
~ _TlsChannelHandlerTimer : 136 -> 124
~ _BioPuts : 72 -> 60
```
