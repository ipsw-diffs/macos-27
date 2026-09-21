## libCoreRepairState.dylib

> `/usr/lib/libCoreRepairState.dylib`

```diff

-1307.40.46.0.0
-  __TEXT.__text: 0x17908
-  __TEXT.__objc_methlist: 0xeb8
-  __TEXT.__const: 0x18b
-  __TEXT.__cstring: 0xcf6
-  __TEXT.__oslogstring: 0x1ce5
+1307.40.51.0.0
+  __TEXT.__text: 0x17bd4
+  __TEXT.__objc_methlist: 0xee0
+  __TEXT.__const: 0x1b0
+  __TEXT.__cstring: 0xd49
+  __TEXT.__oslogstring: 0x1d51
   __TEXT.__gcc_except_tab: 0x44
-  __TEXT.__unwind_info: 0x6d0
+  __TEXT.__unwind_info: 0x6e8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xcd8
+  __DATA_CONST.__objc_selrefs: 0xd08
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x50
   __DATA_CONST.__objc_arraydata: 0x218
-  __DATA_CONST.__got: 0x200
+  __DATA_CONST.__got: 0x210
   __AUTH_CONST.__const: 0x120
-  __AUTH_CONST.__cfstring: 0x1a80
+  __AUTH_CONST.__cfstring: 0x1aa0
   __AUTH_CONST.__objc_const: 0x10d8
   __AUTH_CONST.__objc_arrayobj: 0x228
   __AUTH_CONST.__objc_intobj: 0xa8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libamsupport.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 488
-  Symbols:   220
-  CStrings:  460
+  Functions: 492
+  Symbols:   225
+  CStrings:  463
 
Symbols:
+ _NSURLErrorDomain
+ _OBJC_CLASS_$_NSProcessInfo
+ _kCRNetworkRetryDelaySeconds
+ _kCRNetworkRetryMaxAttempts
+ _kCRNetworkRetryWindowSeconds
CStrings:
+ "+[CRUtils shouldRetryNetworkError:attempt:startedAtClock:]"
+ "[%s] retry window closed after %{public}.0fs (attempt %{public}lu/%{public}lu); failing instead of retrying"
+ "kCFErrorDomainCFNetwork"
```
