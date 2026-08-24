## Siri

> `/System/Library/CoreServices/Siri.app/Contents/MacOS/Siri`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_proto`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3600.46.19.14.3
-  __TEXT.__text: 0x2926c
+3600.46.19.14.4
+  __TEXT.__text: 0x293e0
   __TEXT.__auth_stubs: 0xf80
   __TEXT.__objc_stubs: 0x5fa0
   __TEXT.__objc_methlist: 0x26e8

   __TEXT.__objc_methtype: 0x1cd1
   __TEXT.__cstring: 0x4404
   __TEXT.__gcc_except_tab: 0x4e0
-  __TEXT.__oslogstring: 0x3398
+  __TEXT.__oslogstring: 0x33f8
   __TEXT.__swift5_typeref: 0x20a
   __TEXT.__swift5_capture: 0x178
   __TEXT.__constg_swiftt: 0x278

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1018
+  Functions: 1019
   Symbols:   541
-  CStrings:  2198
+  CStrings:  2199
 
CStrings:
+ "%s [Invocation] Accepting connection %@ entitled:%d"
+ "%s [Invocation] Process %@ is attempting to submit text to Siri without entitlement."
+ "%s [Invocation] Received Notification with identifier '%@' from pid %d"
- "%s [Invocation] Invoking Siri with entitlement."
- "%s [Invocation] Received Notification with identifier '%@'"
```
