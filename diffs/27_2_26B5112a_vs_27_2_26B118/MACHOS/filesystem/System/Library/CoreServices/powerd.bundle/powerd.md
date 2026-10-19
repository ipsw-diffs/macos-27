## powerd

> `/System/Library/CoreServices/powerd.bundle/powerd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

 2043.40.52.0.2
-  __TEXT.__text: 0x6d8e0
-  __TEXT.__auth_stubs: 0x1dc0
+  __TEXT.__text: 0x6d92c
+  __TEXT.__auth_stubs: 0x1dd0
   __TEXT.__objc_stubs: 0x4520
   __TEXT.__objc_methlist: 0x1e0c
   __TEXT.__const: 0x340
-  __TEXT.__cstring: 0x7b22
+  __TEXT.__cstring: 0x7b33
   __TEXT.__objc_methname: 0x5d53
   __TEXT.__oslogstring: 0xbf88
   __TEXT.__objc_classname: 0x2a8

   __DATA_CONST.__objc_dictobj: 0xf0
   __DATA_CONST.__objc_doubleobj: 0x10
   __DATA_CONST.__objc_arrayobj: 0x348
-  __DATA_CONST.__auth_got: 0xef0
+  __DATA_CONST.__auth_got: 0xef8
   __DATA_CONST.__got: 0x390
   __DATA_CONST.__auth_ptr: 0x18
   __DATA.__objc_const: 0x36b0
   __DATA.__objc_selrefs: 0x16e8
   __DATA.__objc_ivar: 0x2c0
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
   Functions: 2350
-  Symbols:   597
-  CStrings:  3716
+  Symbols:   598
+  CStrings:  3718
 
Symbols:
+ _strnstr
Functions:
~ sub_100062f10 : 344 -> 420
CStrings:
+ "boot-args"
+ "debug="
```
