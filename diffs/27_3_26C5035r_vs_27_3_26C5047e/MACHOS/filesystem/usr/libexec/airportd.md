## airportd

> `/usr/libexec/airportd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-19180.1.0.0.0
-  __TEXT.__text: 0xddc44
-  __TEXT.__auth_stubs: 0x1ff0
-  __TEXT.__objc_stubs: 0x10300
+19180.3.0.0.0
+  __TEXT.__text: 0xde2e4
+  __TEXT.__auth_stubs: 0x2040
+  __TEXT.__objc_stubs: 0x102e0
   __TEXT.__objc_methlist: 0x5680
   __TEXT.__const: 0xb28
-  __TEXT.__objc_methname: 0x14a91
+  __TEXT.__objc_methname: 0x14a74
   __TEXT.__objc_classname: 0x3be
   __TEXT.__objc_methtype: 0x3400
   __TEXT.__gcc_except_tab: 0x2114
-  __TEXT.__cstring: 0x2e0d5
-  __TEXT.__oslogstring: 0x151d
+  __TEXT.__cstring: 0x2e111
+  __TEXT.__oslogstring: 0x16dd
   __TEXT.__unwind_info: 0x2d80
   __DATA_CONST.__const: 0x3270
   __DATA_CONST.__cfstring: 0x9b00

   __DATA_CONST.__objc_arraydata: 0x2a0
   __DATA_CONST.__objc_dictobj: 0x168
   __DATA_CONST.__objc_arrayobj: 0x78
-  __DATA_CONST.__auth_got: 0x1010
+  __DATA_CONST.__auth_got: 0x1038
   __DATA_CONST.__got: 0x940
   __DATA_CONST.__auth_ptr: 0x28
   __DATA.__objc_const: 0x6938
-  __DATA.__objc_selrefs: 0x4948
+  __DATA.__objc_selrefs: 0x4940
   __DATA.__objc_ivar: 0x728
   __DATA.__objc_data: 0xb90
   __DATA.__data: 0x424

   - /usr/lib/libpcap.A.dylib
   - /usr/lib/libz.1.dylib
   Functions: 2826
-  Symbols:   832
-  CStrings:  7565
+  Symbols:   837
+  CStrings:  7573
 
Symbols:
+ _fchmod
+ _fcntl
+ _fdopen
+ _fstat
+ _rename
+ _unlink
- _fopen
Functions:
~ sub_100062794 : 2480 -> 4104
~ sub_10008fc38 -> sub_100090290 : 712 -> 784
CStrings:
+ "%@/.%@.XXXXXX"
+ "<%s[%d]> NAN real-time is active, will defer best connected scan\n"
+ "<%{public}s:%u> Not a regular file '%{public}s'"
+ "<%{public}s:%u> Path too long '%{public}s'"
+ "<%{public}s:%u> Unable to close '%{public}s'"
+ "<%{public}s:%u> Unable to create temporary file '%{public}s', errno[%d]"
+ "<%{public}s:%u> Unable to flush '%{public}s'"
+ "<%{public}s:%u> Unable to move '%{public}s' to '%{public}s', errno[%d]"
+ "<%{public}s:%u> Unable to open read file '%{public}s', errno[%d]"
+ "<%{public}s:%u> Unable to open read stream '%{public}s'"
+ "<%{public}s:%u> Unable to open write stream '%{public}s'"
- "/private/var/tmp/%@"
- "<%{public}s:%u> Unable to open read file '%{public}s'"
- "moveItemAtPath:toPath:error:"
```
