## replayd

> `/usr/libexec/replayd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-765.9.1.0.0
-  __TEXT.__text: 0xc6ca4
+765.11.1.0.0
+  __TEXT.__text: 0xc7084
   __TEXT.__auth_stubs: 0x1b10
   __TEXT.__objc_stubs: 0xeee0
   __TEXT.__objc_methlist: 0x768c
   __TEXT.__const: 0x430
-  __TEXT.__oslogstring: 0x158ef
-  __TEXT.__cstring: 0x17461
+  __TEXT.__oslogstring: 0x15acd
+  __TEXT.__cstring: 0x1756b
   __TEXT.__objc_classname: 0xacb
   __TEXT.__objc_methname: 0x1636a
   __TEXT.__objc_methtype: 0x40d8
   __TEXT.__gcc_except_tab: 0xfe4
   __TEXT.__dlopen_cstrs: 0x4e
-  __TEXT.__unwind_info: 0x3460
+  __TEXT.__unwind_info: 0x3470
   __DATA_CONST.__const: 0x2950
   __DATA_CONST.__cfstring: 0x63a0
   __DATA_CONST.__objc_classlist: 0x2e0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3787
+  Functions: 3792
   Symbols:   848
-  CStrings:  7445
+  CStrings:  7455
 
CStrings:
+ " [ERROR] %{public}s:%d invalid pid=%d"
+ " [ERROR] %{public}s:%d pickerDidCancel rejected: caller lacks ScreenCaptureKit private entitlement"
+ " [ERROR] %{public}s:%d pickerDidDismiss rejected: caller lacks ScreenCaptureKit private entitlement"
+ " [ERROR] %{public}s:%d pickerDidEnd rejected: caller lacks ScreenCaptureKit private entitlement"
+ " [ERROR] %{public}s:%d pickerDidUpdate rejected: caller lacks ScreenCaptureKit private entitlement"
+ " [INFO] %{public}s:%d skipping invalid pid=%@"
+ "-[RPConnectionManager pickerDidCancel:forStream:]"
+ "-[RPConnectionManager pickerDidDismiss:forStream:isCancelled:]"
+ "-[RPConnectionManager pickerDidEnd:withFilter:forStream:]"
+ "-[RPConnectionManager pickerDidUpdate:withFilter:preservedFilter:forStream:completionHandler:]"
```
