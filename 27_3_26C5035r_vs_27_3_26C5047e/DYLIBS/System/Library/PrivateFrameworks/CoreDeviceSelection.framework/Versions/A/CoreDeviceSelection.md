## CoreDeviceSelection

> `/System/Library/PrivateFrameworks/CoreDeviceSelection.framework/Versions/A/CoreDeviceSelection`

```diff

-3610.8.1.0.0
-  __TEXT.__text: 0x1087a0
-  __TEXT.__objc_methlist: 0x8c8
-  __TEXT.__const: 0xdc18
-  __TEXT.__cstring: 0x1ccf
+3610.15.1.0.0
+  __TEXT.__text: 0x109294
+  __TEXT.__objc_methlist: 0x8d8
+  __TEXT.__const: 0xdc28
+  __TEXT.__cstring: 0x1cef
   __TEXT.__swift5_typeref: 0x4284
   __TEXT.__swift5_capture: 0x2028
-  __TEXT.__swift5_fieldmd: 0x3694
-  __TEXT.__constg_swiftt: 0x411c
-  __TEXT.__swift5_reflstr: 0x251b
+  __TEXT.__swift5_fieldmd: 0x36a0
+  __TEXT.__constg_swiftt: 0x4124
+  __TEXT.__swift5_reflstr: 0x252b
   __TEXT.__swift5_builtin: 0x17c
   __TEXT.__swift5_assocty: 0x428
-  __TEXT.__oslogstring: 0x47ff
+  __TEXT.__oslogstring: 0x486f
   __TEXT.__swift5_protos: 0xe4
   __TEXT.__swift5_proto: 0x9e0
   __TEXT.__swift5_types: 0x3e8

   __TEXT.__swift_as_ret: 0x464
   __TEXT.__swift_as_cont: 0x6d4
   __TEXT.__swift5_mpenum: 0x94
-  __TEXT.__unwind_info: 0x6100
-  __TEXT.__eh_frame: 0xbf3c
+  __TEXT.__unwind_info: 0x6118
+  __TEXT.__eh_frame: 0xbf1c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x130
   __DATA_CONST.__objc_protolist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x698
+  __DATA_CONST.__objc_selrefs: 0x6a0
   __DATA_CONST.__objc_protorefs: 0x58
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0xb779
-  __AUTH_CONST.__objc_const: 0x3478
+  __AUTH_CONST.__objc_const: 0x34a0
   __AUTH_CONST.__auth_got: 0x1480
   __AUTH.__objc_data: 0x320
   __AUTH.__data: 0x1a88
-  __DATA.__data: 0x33f8
+  __DATA.__data: 0x3408
   __DATA.__bss: 0x124d0
   __DATA.__common: 0x2c9
   __DATA_DIRTY.__objc_data: 0xa0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7915
+  Functions: 7936
   Symbols:   2182
-  CStrings:  529
+  CStrings:  531
 
CStrings:
+ "#primary Election started. This device is %s%s."
+ "#wifi Shadow mode on hardware that is neither AToA Shadow Hw nor AToA Shadow Primary-only Hw: Device Selection sends no Wi-Fi traffic and never acts as the Primary."
+ "#wifi This device would have been the Primary as %{private}s, but is not AToA Shadow Hw or Primary-only Hw, so it is not acting as the Primary."
+ ", not a candidate"
+ "This device is %{public}sAToA Shadow Primary-only Hw."
- "#primary Election started. This device is %s."
- "#wifi Shadow mode on hardware other than AToA Shadow Hw: Device Selection sends no Wi-Fi traffic and never acts as the Primary."
- "#wifi This device would have been the Primary as %{private}s, but is not AToA Shadow Hw, so it is not acting as the Primary in shadow mode."
```
