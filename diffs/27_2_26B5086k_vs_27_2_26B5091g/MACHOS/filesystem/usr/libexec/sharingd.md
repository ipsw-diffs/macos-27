## sharingd

> `/usr/libexec/sharingd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2131.20.65.1.1
-  __TEXT.__text: 0x52dcc8
+2131.20.71.0.0
+  __TEXT.__text: 0x52dfac
   __TEXT.__auth_stubs: 0x9b90
   __TEXT.__objc_stubs: 0x293c0
-  __TEXT.__objc_methlist: 0x19188
+  __TEXT.__objc_methlist: 0x19198
   __TEXT.__const: 0x12700
-  __TEXT.__cstring: 0x2ed0c
+  __TEXT.__cstring: 0x2ed8c
   __TEXT.__objc_classname: 0x4711
-  __TEXT.__objc_methname: 0x3c725
+  __TEXT.__objc_methname: 0x3c735
   __TEXT.__objc_methtype: 0x96d3
-  __TEXT.__oslogstring: 0x2d2c1
+  __TEXT.__oslogstring: 0x2d331
   __TEXT.__gcc_except_tab: 0x2c84
   __TEXT.__ustring: 0x50
   __TEXT.__dlopen_cstrs: 0x1c0

   __TEXT.__swift5_types: 0x520
   __TEXT.__swift_as_entry: 0xb38
   __TEXT.__swift_as_ret: 0xbe0
-  __TEXT.__swift_as_cont: 0x1acc
+  __TEXT.__swift_as_cont: 0x1ad0
   __TEXT.__swift5_capture: 0x3ccc
   __TEXT.__swift5_protos: 0xd0
   __TEXT.__swift5_mpenum: 0x14
-  __TEXT.__unwind_info: 0x13e48
-  __TEXT.__eh_frame: 0x1d968
+  __TEXT.__unwind_info: 0x13e58
+  __TEXT.__eh_frame: 0x1d990
   __DATA_CONST.__const: 0x15210
   __DATA_CONST.__cfstring: 0x141e0
   __DATA_CONST.__objc_classlist: 0xbf8

   __DATA_CONST.__got: 0x2f00
   __DATA_CONST.__auth_ptr: 0x1530
   __DATA.__objc_const: 0x2f7f0
-  __DATA.__objc_selrefs: 0xd780
+  __DATA.__objc_selrefs: 0xd788
   __DATA.__objc_ivar: 0x22f0
   __DATA.__objc_data: 0x8508
   __DATA.__data: 0x11380

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 21037
+  Functions: 21041
   Symbols:   4297
-  CStrings:  21462
+  CStrings:  21468
 
CStrings:
+ "-[SDNearbyAgent _consoleUserChanged:]_block_invoke"
+ "Became the console user, re-evaluating AirDrop receive"
+ "Console user changed, this session %s the console\n"
+ "No longer the console user, stopping AirDrop receive"
+ "Not the console user session, deferring AirDrop receive start"
+ "_consoleUserChanged:"
+ "no longer owns"
+ "owns"
+ "updateServerState canRun(appService=%{bool}d, bonjour=%{bool}d, nearField=%{bool}d) inputs(currentConsoleUser=%{bool}d, screenStateSupportsAirDrop=%{bool}d, isAirDropDiscoverable=%{bool}d, isNearbySharingEnabled=%{bool}d, wirelessEnabled=%{bool}d, bluetoothEnabledIncludingRestricted=%{bool}d)"
- "User is logged in, starting app service server if needed"
- "User logged out, stopping servers"
- "updateServerState canRun(appService=%{bool}d, bonjour=%{bool}d, nearField=%{bool}d) inputs(screenStateSupportsAirDrop=%{bool}d, isAirDropDiscoverable=%{bool}d, isNearbySharingEnabled=%{bool}d, wirelessEnabled=%{bool}d, bluetoothEnabledIncludingRestricted=%{bool}d)"
```
