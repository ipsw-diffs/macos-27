## libAppleTCONUpdater.dylib

> `/usr/lib/updaters/libAppleTCONUpdater.dylib`

```diff

-230.41.1.0.0
-  __TEXT.__text: 0x4fd4
-  __TEXT.__cstring: 0x1acc
+230.60.4.0.0
+  __TEXT.__text: 0x6228
+  __TEXT.__cstring: 0x1dde
   __TEXT.__const: 0x350
-  __TEXT.__gcc_except_tab: 0x78
-  __TEXT.__unwind_info: 0x238
+  __TEXT.__gcc_except_tab: 0x98
+  __TEXT.__unwind_info: 0x280
   __TEXT.__auth_stubs: 0x0
   __DATA_CONST.__const: 0x180
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x150
-  __AUTH_CONST.__cfstring: 0x7a0
-  __AUTH_CONST.__weak_auth_got: 0x10
-  __AUTH_CONST.__auth_got: 0x1d8
+  __AUTH_CONST.__cfstring: 0xb60
+  __AUTH_CONST.__weak_auth_got: 0x20
+  __AUTH_CONST.__auth_got: 0x268
   __DATA.__data: 0xb0
   __DATA.__bss: 0x21
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libamsupport.dylib
   - /usr/lib/libc++.1.dylib
-  Functions: 109
-  Symbols:   250
-  CStrings:  242
+  - /usr/lib/libz.1.dylib
+  Functions: 123
+  Symbols:   285
+  CStrings:  283
 
Symbols:
+ GCC_except_table4
+ _AppleTCONDPFWCreate
+ _AppleTCONDPFWDestroy
+ _AppleTCONDPFWGetConfig
+ _AppleTCONDPFWGetConfigCount
+ _AppleTCONDPFWGetImage
+ _AppleTCONDPFWGetPayload
+ _AppleTCONDPFWIsMatched
+ _CFArrayGetCount
+ _CFArrayGetTypeID
+ _CFArrayGetValueAtIndex
+ _CFDataCreateMutable
+ _CFDataGetMutableBytePtr
+ _CFDataSetLength
+ _CFStringGetTypeID
+ __ZN20AppleTCONDPUnifiedFW14decompressGzipEPK8__CFData
+ __ZN20AppleTCONDPUnifiedFW16applyBxdiffPatchEPKhmS1_m
+ __ZN20AppleTCONDPUnifiedFWC1EPK8__CFDatajjjj
+ __ZN20AppleTCONDPUnifiedFWC2EPK8__CFDatajjjj
+ __ZN20AppleTCONDPUnifiedFWD1Ev
+ __ZN20AppleTCONDPUnifiedFWD2Ev
+ __ZZN20AppleTCONDPUnifiedFW16applyBxdiffPatchEPKhmS1_mEN11Accumulator5writeEPvPKvy
+ __ZdaPv
+ __Znam
+ _bzero
+ _dlclose
+ _dlerror
+ _dlopen
+ _dlsym
+ _inflate
+ _inflateEnd
+ _inflateInit2_
+ _printf
+ _puts
+ _realloc
CStrings:
+ "/usr/lib/libParallelCompression.dylib"
+ "1.2.12"
+ "Address"
+ "AppleTCONDPUnifiedFW"
+ "AppleTCONDPUnifiedFW: BXPatch5 failed (result=%d)\n"
+ "AppleTCONDPUnifiedFW: BXPatch5 symbol not found: %s\n"
+ "AppleTCONDPUnifiedFW: gzip ISIZE is zero, file may be corrupt"
+ "AppleTCONDPUnifiedFW: gzip inflate failed, status=%d msg=%s\n"
+ "AppleTCONDPUnifiedFW: gzip input too small (%ld bytes)\n"
+ "AppleTCONDPUnifiedFW: init fails."
+ "AppleTCONDPUnifiedFW: libParallelCompression unavailable: %s\n"
+ "BXPatch5"
+ "BoardID"
+ "Build"
+ "ConfigSubCmd"
+ "Configs"
+ "Configurations"
+ "DeviceID"
+ "Digest"
+ "DirectNVMUpdatePreferred"
+ "FWConfigAPICMD"
+ "FWConfigDigest"
+ "FWConfigs"
+ "FWImg"
+ "FWImgDigest"
+ "HWConfig"
+ "ImageProperties"
+ "Length"
+ "Major"
+ "Minor"
+ "Name"
+ "Option2"
+ "PORUpdatePreferred"
+ "Patches"
+ "ProtectedRegions"
+ "bxdiff"
+ "complete_binary"
+ "major"
+ "patches_policy"
+ "unknown"
+ "version_check_policy"
```
