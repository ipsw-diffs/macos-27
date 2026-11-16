## com.apple.Virtualization.VirtualMachine

> `/System/Library/Frameworks/Virtualization.framework/Versions/A/XPCServices/com.apple.Virtualization.VirtualMachine.xpc/Contents/MacOS/com.apple.Virtualization.VirtualMachine`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
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
- `__DATA.__thread_vars`

```diff

-308.3.3.0.0
-  __TEXT.__text: 0x40cbc4
-  __TEXT.__auth_stubs: 0x3860
-  __TEXT.__objc_stubs: 0x1d80
+308.3.6.0.0
+  __TEXT.__text: 0x40d6c0
+  __TEXT.__auth_stubs: 0x3890
+  __TEXT.__objc_stubs: 0x1da0
   __TEXT.__objc_methlist: 0xc4
   __TEXT.__const: 0x291c0
   __TEXT.__dlopen_cstrs: 0x66
-  __TEXT.__cstring: 0x10e8e
+  __TEXT.__cstring: 0x10ea0
   __TEXT.__objc_classname: 0xc6
-  __TEXT.__objc_methname: 0x18d2
+  __TEXT.__objc_methname: 0x18e2
   __TEXT.__objc_methtype: 0xd96
   __TEXT.__constg_swiftt: 0x138
   __TEXT.__swift5_typeref: 0xb4
   __TEXT.__swift5_reflstr: 0x1a7
   __TEXT.__swift5_fieldmd: 0x114
   __TEXT.__swift5_types: 0x10
-  __TEXT.__gcc_except_tab: 0x3bc54
-  __TEXT.__oslogstring: 0x48a3
-  __TEXT.__unwind_info: 0x11540
+  __TEXT.__gcc_except_tab: 0x3bcc8
+  __TEXT.__oslogstring: 0x497b
+  __TEXT.__unwind_info: 0x11548
   __DATA_CONST.__const: 0x21238
   __DATA_CONST.__cfstring: 0x1140
   __DATA_CONST.__objc_classlist: 0x30

   __DATA_CONST.__objc_arrayobj: 0x48
   __DATA_CONST.__objc_dictobj: 0x78
   __DATA_CONST.__objc_doubleobj: 0x10
-  __DATA_CONST.__auth_got: 0x1c40
+  __DATA_CONST.__auth_got: 0x1c58
   __DATA_CONST.__got: 0x638
   __DATA_CONST.__auth_ptr: 0x118
   __DATA.__objc_const: 0x698
-  __DATA.__objc_selrefs: 0x788
+  __DATA.__objc_selrefs: 0x790
   __DATA.__objc_ivar: 0x30
   __DATA.__objc_data: 0x2e8
   __DATA.__data: 0x890

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/local/lib/libVirtualBiometricServices.dylib
-  Functions: 11624
-  Symbols:   1072
-  CStrings:  3508
+  Functions: 11625
+  Symbols:   1075
+  CStrings:  3512
 
Symbols:
+ _getpeername
+ _getsockname
+ _objc_opt_respondsToSelector
CStrings:
+ "Connection to guest port %u continues with a blocking socket: the socket could not be made non-blocking (error %d)."
+ "Refusing a connection to guest port %u: the client did not provide a connected local stream socket."
+ "setSharedCachePath:"
+ "shared_cache_path"
```
