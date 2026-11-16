## AppleVideoDecoder

> `/System/Library/Video/Plug-Ins/AppleVideoDecoder.bundle/Contents/MacOS/AppleVideoDecoder`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_ptr`

```diff

-995.0.0.0.0
-  __TEXT.__text: 0x14d380
+996.0.0.0.0
+  __TEXT.__text: 0x14daec
   __TEXT.__auth_stubs: 0xf80
   __TEXT.__const: 0xbf90
-  __TEXT.__oslogstring: 0x15adc
-  __TEXT.__cstring: 0x5345
+  __TEXT.__oslogstring: 0x15c38
+  __TEXT.__cstring: 0x53ab
   __TEXT.__gcc_except_tab: 0x968
-  __TEXT.__unwind_info: 0x3330
+  __TEXT.__unwind_info: 0x3350
   __DATA_CONST.__const: 0x4670
-  __DATA_CONST.__cfstring: 0x6e0
+  __DATA_CONST.__cfstring: 0x700
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x7c8
-  __DATA_CONST.__got: 0x328
+  __DATA_CONST.__got: 0x330
   __DATA_CONST.__auth_ptr: 0x10
   __DATA.__data: 0x88
   __DATA.__bss: 0x51

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3692
-  Symbols:   362
-  CStrings:  2010
+  Functions: 3702
+  Symbols:   363
+  CStrings:  2017
 
Symbols:
+ _kVTDecompressionPropertyKey_EnableStrictBitstreamValidation
CStrings:
+ "00:57:25"
+ "00:57:26"
+ "00:57:28"
+ "AVD_EnableStrictBitstreamValidation"
+ "AppleAVD: ERROR: %{public}s(): AppleAVDSetParameter call for kAppleAVDSetStrictBitstreamValidation returned ERROR\n\n"
+ "AppleAVD: ERROR: %{public}s(): bad index %u\n"
+ "AppleAVD: ERROR: %{public}s(): propertyValue (%p) is invalid!\n\n"
+ "AppleAVD: INFO: %{public}s(): cfg4: %d %d\n"
+ "AppleAVD: WARNING: %{public}s(): trying to set kAppleAVDSetStrictBitstreamValidation before videoContext was created!\n\n"
+ "Nov 10 2026"
+ "SetStrictBitstreamValidation"
+ "SetStrictBitstreamValidationProperty"
- "01:25:07"
- "01:25:08"
- "01:25:09"
- "AppleAVD: INFO: %{public}s(): cfg4: %d\n"
- "Oct 30 2026"
```
