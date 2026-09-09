## dirhelper

> `/usr/libexec/dirhelper`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 203.0.0.0.0
-  __TEXT.__text: 0x4f58
+  __TEXT.__text: 0x4f34
   __TEXT.__auth_stubs: 0x5a0
   __TEXT.__const: 0x60
   __TEXT.__cstring: 0xa06
-  __TEXT.__unwind_info: 0x100
+  __TEXT.__unwind_info: 0x118
   __DATA_CONST.__const: 0x238
   __DATA_CONST.__auth_got: 0x2d0
   __DATA_CONST.__got: 0x40
Symbols:
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libcoreservices_executables/install/TempContent/Objects/libcoreservices.build/dirhelper.build/Objects-normal/arm64e/dirhelper-f0aa499d36ffda0f85593645576fa2c0.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libcoreservices_executables/install/TempContent/Objects/libcoreservices.build/dirhelper.build/Objects-normal/arm64e/dirhelper-e32fd6027ca1e895cc244907b691b52f.o
Functions:
~ ____reset_idle_exit_block_invoke : 116 -> 104
~ _close_dotdirentriesattr : 108 -> 96
~ _free_walk : 60 -> 48
```
