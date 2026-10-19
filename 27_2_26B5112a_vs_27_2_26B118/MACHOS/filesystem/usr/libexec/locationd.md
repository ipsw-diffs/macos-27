## locationd

> `/usr/libexec/locationd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_proto`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 3186.0.22.0.0
-  __TEXT.__text: 0x67f848
+  __TEXT.__text: 0x67fdfc
   __TEXT.__auth_stubs: 0x3910
   __TEXT.__objc_stubs: 0x10f80
   __TEXT.__init_offsets: 0x188
   __TEXT.__objc_methlist: 0x12b60
   __TEXT.__const: 0x17fe8
-  __TEXT.__gcc_except_tab: 0x2acec
-  __TEXT.__cstring: 0x7b5dc
-  __TEXT.__oslogstring: 0x99dd8
+  __TEXT.__gcc_except_tab: 0x2ad24
+  __TEXT.__cstring: 0x7b60a
+  __TEXT.__oslogstring: 0x9a080
   __TEXT.__objc_methname: 0x2009e
   __TEXT.__objc_classname: 0x3404
   __TEXT.__objc_methtype: 0xf1dc

   __TEXT.__unwind_info: 0x1e3c8
   __TEXT.__eh_frame: 0x630
   __DATA_CONST.__const: 0x2c310
-  __DATA_CONST.__cfstring: 0x160e0
+  __DATA_CONST.__cfstring: 0x16100
   __DATA_CONST.__objc_classlist: 0x8d0
   __DATA_CONST.__objc_catlist: 0x78
   __DATA_CONST.__objc_protolist: 0x5b8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 27026
+  Functions: 27027
   Symbols:   1394
-  CStrings:  25071
+  CStrings:  25078
 
CStrings:
+ "#CoreLocationAgent ignoring a disconnection from a connection that does not hold the agent slot"
+ "#CoreLocationAgent rejecting an unentitled connection"
+ "#CoreLocationAgent rejecting an unentitled sender on the agent MIG port"
+ "22:02:52"
+ "Oct 13 2026"
+ "Oct 13 2026 22:04:47"
+ "com.apple.private.locationd.corelocationagent"
+ "{\"msg%{public}.0s\":\"#CoreLocationAgent ignoring a disconnection from a connection that does not hold the agent slot\", \"UserName\":%{public, location:escape_only}s, \"Connection\":%{public, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#CoreLocationAgent rejecting an unentitled connection\", \"Connection\":%{public, location:escape_only}s, \"PID\":%{public}d}"
+ "{\"msg%{public}.0s\":\"#CoreLocationAgent rejecting an unentitled sender on the agent MIG port\", \"PID\":%{public}d}"
- "03:48:12"
- "Oct  8 2026"
- "Oct  8 2026 03:49:54"
```
