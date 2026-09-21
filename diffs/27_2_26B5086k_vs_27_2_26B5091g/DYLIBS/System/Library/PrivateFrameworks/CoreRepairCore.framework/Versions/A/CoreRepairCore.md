## CoreRepairCore

> `/System/Library/PrivateFrameworks/CoreRepairCore.framework/Versions/A/CoreRepairCore`

```diff

-1307.40.46.0.0
-  __TEXT.__text: 0x7df8c
-  __TEXT.__objc_methlist: 0x443c
-  __TEXT.__const: 0x876
-  __TEXT.__cstring: 0x6163
-  __TEXT.__oslogstring: 0x952e
+1307.40.51.0.0
+  __TEXT.__text: 0x7e27c
+  __TEXT.__objc_methlist: 0x446c
+  __TEXT.__const: 0x886
+  __TEXT.__cstring: 0x61b6
+  __TEXT.__oslogstring: 0x959a
   __TEXT.__gcc_except_tab: 0x1600
-  __TEXT.__unwind_info: 0x20d0
+  __TEXT.__unwind_info: 0x20e8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2860
+  __DATA_CONST.__objc_selrefs: 0x2880
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x1b0
   __DATA_CONST.__objc_arraydata: 0x630
-  __DATA_CONST.__got: 0x528
+  __DATA_CONST.__got: 0x530
   __AUTH_CONST.__const: 0x11a0
-  __AUTH_CONST.__cfstring: 0x7340
+  __AUTH_CONST.__cfstring: 0x7360
   __AUTH_CONST.__objc_const: 0x6428
   __AUTH_CONST.__objc_intobj: 0x378
   __AUTH_CONST.__objc_dictobj: 0x190

   - /usr/lib/libauthinstall.dylib
   - /usr/lib/libimage4.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2471
-  Symbols:   589
-  CStrings:  2212
+  Functions: 2476
+  Symbols:   593
+  CStrings:  2215
 
Symbols:
+ _NSURLErrorDomain
+ _kCRNetworkRetryDelaySeconds
+ _kCRNetworkRetryMaxAttempts
+ _kCRNetworkRetryWindowSeconds
CStrings:
+ "+[CRUtils shouldRetryNetworkError:attempt:startedAtClock:]"
+ "[%s] retry window closed after %{public}.0fs (attempt %{public}lu/%{public}lu); failing instead of retrying"
+ "kCFErrorDomainCFNetwork"
```
