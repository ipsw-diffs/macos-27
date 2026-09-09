## powerd

> `/System/Library/CoreServices/powerd.bundle/powerd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-2043.0.47.0.3
-  __TEXT.__text: 0x6dee8
-  __TEXT.__auth_stubs: 0x1d90
+2043.1.1.0.0
+  __TEXT.__text: 0x6cf08
+  __TEXT.__auth_stubs: 0x1da0
   __TEXT.__objc_stubs: 0x4480
   __TEXT.__objc_methlist: 0x1dbc
   __TEXT.__const: 0x360
-  __TEXT.__cstring: 0x7ad7
+  __TEXT.__cstring: 0x7ae8
   __TEXT.__objc_methname: 0x5c5c
   __TEXT.__oslogstring: 0xbdb5
   __TEXT.__objc_classname: 0x2a8
   __TEXT.__objc_methtype: 0x7b1
   __TEXT.__gcc_except_tab: 0x3d4
   __TEXT.__dlopen_cstrs: 0x152
-  __TEXT.__unwind_info: 0x13c8
+  __TEXT.__unwind_info: 0x1fd8
   __DATA_CONST.__const: 0x25d0
   __DATA_CONST.__cfstring: 0x6ba0
   __DATA_CONST.__objc_classlist: 0xb0

   __DATA_CONST.__objc_dictobj: 0xf0
   __DATA_CONST.__objc_doubleobj: 0x10
   __DATA_CONST.__objc_arrayobj: 0x348
-  __DATA_CONST.__auth_got: 0xed8
+  __DATA_CONST.__auth_got: 0xee0
   __DATA_CONST.__got: 0x380
   __DATA_CONST.__auth_ptr: 0x18
   __DATA.__objc_const: 0x3648
   __DATA.__objc_selrefs: 0x16c0
   __DATA.__objc_ivar: 0x2b8
   __DATA.__objc_data: 0x6e0
-  __DATA.__data: 0x8f8
-  __DATA.__bss: 0xf38
+  __DATA.__data: 0x8fc
+  __DATA.__bss: 0xf30
   __DATA.__common: 0x1270
   __CGPreLoginApp.__cgpreloginapp: 0x0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libspindump.dylib
   - /usr/lib/libsystemstats.dylib
   Functions: 2332
-  Symbols:   592
-  CStrings:  3696
+  Symbols:   593
+  CStrings:  3698
 
Symbols:
+ _strnstr
CStrings:
+ "boot-args"
+ "debug="
```
