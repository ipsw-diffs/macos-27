## ocspcheck

> `/usr/bin/ocspcheck`

```diff

 111.0.5.0.0
-  __TEXT.__text: 0x2248
+  __TEXT.__text: 0x2218
   __TEXT.__auth_stubs: 0x600
   __TEXT.__cstring: 0xa44
-  __TEXT.__unwind_info: 0xa8
+  __TEXT.__unwind_info: 0xd0
   __DATA_CONST.__auth_got: 0x300
   __DATA_CONST.__got: 0x38
   __DATA.__common: 0xc
Symbols:
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libressl/install/TempContent/Objects/libressl.build/libressl-3.3.build/DerivedSources/arm64e.x1/apps/ocspcheck/http.o
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libressl/install/TempContent/Objects/libressl.build/libressl-3.3.build/DerivedSources/arm64e.x1/apps/ocspcheck/ocspcheck.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libressl/install/TempContent/Objects/libressl.build/libressl-3.3.build/DerivedSources/arm64e/apps/ocspcheck/http.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libressl/install/TempContent/Objects/libressl.build/libressl-3.3.build/DerivedSources/arm64e/apps/ocspcheck/ocspcheck.o
Functions:
~ _http_free : 88 -> 76
~ _http_close : 92 -> 80
~ _http_get_free : 76 -> 64
~ _issuer_from_chain : 84 -> 72
```
