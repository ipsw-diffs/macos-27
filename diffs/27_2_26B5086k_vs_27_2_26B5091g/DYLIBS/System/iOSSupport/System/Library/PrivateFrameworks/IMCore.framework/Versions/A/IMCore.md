## IMCore

> `/System/iOSSupport/System/Library/PrivateFrameworks/IMCore.framework/Versions/A/IMCore`

```diff

-1491.200.63.0.0
-  __TEXT.__text: 0x2e3344
+1491.200.73.0.0
+  __TEXT.__text: 0x2e387c
   __TEXT.__objc_methlist: 0x18bec
   __TEXT.__const: 0x116d0
-  __TEXT.__gcc_except_tab: 0x11154
+  __TEXT.__gcc_except_tab: 0x11198
   __TEXT.__cstring: 0x12fc6
-  __TEXT.__oslogstring: 0x22c09
+  __TEXT.__oslogstring: 0x22ee9
   __TEXT.__ustring: 0xc0
   __TEXT.__dlopen_cstrs: 0x184
   __TEXT.__swift5_typeref: 0x397a

   __TEXT.__swift_as_ret: 0x130
   __TEXT.__swift_as_cont: 0x2e0
   __TEXT.__swift5_mpenum: 0x40
-  __TEXT.__unwind_info: 0xdf40
+  __TEXT.__unwind_info: 0xdf48
   __TEXT.__eh_frame: 0x72c8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __AUTH_CONST.__objc_intobj: 0x198
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__auth_got: 0x21d0
-  __AUTH.__objc_data: 0x2f68
+  __AUTH.__objc_data: 0x3008
   __AUTH.__data: 0x2bd0
   __DATA.__objc_ivar: 0x12d4
   __DATA.__data: 0x62f8
   __DATA.__bss: 0x1e320
   __DATA.__common: 0x7b0
-  __DATA_DIRTY.__objc_data: 0x2ef0
+  __DATA_DIRTY.__objc_data: 0x2e50
   __DATA_DIRTY.__data: 0x740
   __DATA_DIRTY.__bss: 0x880
   __DATA_DIRTY.__common: 0x60

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 15064
+  Functions: 15066
   Symbols:   2690
-  CStrings:  4888
+  CStrings:  4898
 
CStrings:
+ "Attempting to update display name for chat GUID: %@"
+ "Chat %p is not registered under any GUID; attempting to send display name update to %@ rather than dropping it"
+ "Ignoring group identity update for chat guid: %@"
+ "Skipping display name update: chat style %ld does not allow rename (not business/Stewie/RCS) name=%@"
+ "Skipping display name update: current chat has no name and the incoming name is empty/whitespace."
+ "Skipping display name update: string-equal to current name %@"
+ "Skipping display name update: unchanged (name=%@ style=%ld)"
+ "Suppressing group-title breadcrumb (coalesced): title=%@ prevTitle=%@ sender=%@"
+ "We found fallback chat guids: %@"
+ "We have attempted to re-find the current chat but were unable to. Failed to set display name."
```
