## ibv_ctl

> `/usr/bin/ibv_ctl`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`

```diff

-112.40.13.0.0
-  __TEXT.__text: 0x518
+112.40.14.0.1
+  __TEXT.__text: 0x4c8
   __TEXT.__auth_stubs: 0x110
-  __TEXT.__cstring: 0x129
+  __TEXT.__cstring: 0x12d
   __TEXT.__unwind_info: 0x88
   __DATA_CONST.__const: 0x70
   __DATA_CONST.__auth_got: 0x88
   __DATA_CONST.__got: 0x20
   __DATA.__bss: 0x8
-  - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/librdma.dylib
   Functions: 10
Symbols:
+ _ibv_darwin_set_resolver_ifname
+ _strerror
- _IOConnectCallStructMethod
- ___strlcpy_chk
Functions:
~ sub_100000888 -> sub_100000830 : 40 -> 36
~ sub_1000008b0 -> sub_100000854 : 444 -> 368
CStrings:
+ "setting resolver interface failed: %s\n"
- "darwin_bind_interface failed: %d\n"
```
