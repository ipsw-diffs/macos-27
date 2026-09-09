## update_mcdp29xx

> `/usr/bin/update_mcdp29xx`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 325.0.0.0.0
-  __TEXT.__text: 0x2880
+  __TEXT.__text: 0x2840
   __TEXT.__auth_stubs: 0x3e0
   __TEXT.__cstring: 0xec2
   __TEXT.__const: 0x3
-  __TEXT.__unwind_info: 0x108
+  __TEXT.__unwind_info: 0x138
   __DATA_CONST.__const: 0x1e0
   __DATA_CONST.__cfstring: 0x140
   __DATA_CONST.__auth_got: 0x1f0
Functions:
~ ___DPFUSessionUpdateProgress : 136 -> 124
~ _OUTLINED_FUNCTION_7 : 32 -> 20
~ _logMessagev : 184 -> 172
~ ___waitForIODPDeviceMatchingCallback : 88 -> 76
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _DPFUSessionInstallMemoryPayload : 308 -> 304
```
