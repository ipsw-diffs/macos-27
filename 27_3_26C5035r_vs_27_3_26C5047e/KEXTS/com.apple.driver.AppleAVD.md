## com.apple.driver.AppleAVD

> `com.apple.driver.AppleAVD`

```diff

-995.0.0.0.0
-  __TEXT.__os_log: 0x1a49d
+996.0.0.0.0
+  __TEXT.__os_log: 0x1a526
   __TEXT.__cstring: 0x705e
   __TEXT.__const: 0xc724c
-  __TEXT_EXEC.__text: 0x5afbc
+  __TEXT_EXEC.__text: 0x5b100
   __TEXT_EXEC.__auth_stubs: 0x710
   __DATA.__data: 0x1334
   __DATA.__common: 0x78

   __DATA_CONST.__got: 0xd8
   __DATA_CONST.__auth_ptr: 0x10
   Functions: 1886
-  Symbols:   4176
-  CStrings:  1751
+  Symbols:   4178
+  CStrings:  1753
 
Symbols:
+ __ZN10CAvdApComm14validateFieldsEPhjj
+ __ZZN10CAvdApComm14validateFieldsEPhjjE11_os_log_fmt
+ __ZZN10CAvdApComm14validateFieldsEPhjjE11_os_log_fmt_0
+ __ZZN15CAvdApCommViola18patchSliceDataSizeEPh28_DecryptSliceDataSizePatcherjE11_os_log_fmt_5
- __ZN10CAvdApComm14validateFieldsEPhj
- __ZZN10CAvdApComm14validateFieldsEPhjE11_os_log_fmt
Functions:
~ __ZN10CAvdApComm14validateFieldsEPhj -> __ZN10CAvdApComm14validateFieldsEPhjj : 324 -> 464
~ __ZN13PriorityQueue24insertDecodeFrameCommandEP8sPQEntry : 604 -> 672
~ __ZN15CAvdApCommViola18patchSliceDataSizeEPh28_DecryptSliceDataSizePatcherj : 716 -> 832
CStrings:
+ "AppleAVD: ERROR: %s(): Invalid workOffset=%u, numWorks=%u\n"
+ "AppleAVD: ERROR: %s(): Validation failed - buffer codec %u, session codec %u\n"
```
