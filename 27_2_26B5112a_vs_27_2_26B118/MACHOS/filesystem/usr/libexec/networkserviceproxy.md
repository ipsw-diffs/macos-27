## networkserviceproxy

> `/usr/libexec/networkserviceproxy`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 990.40.2.0.0
-  __TEXT.__text: 0xcdfc0
+  __TEXT.__text: 0xce008
   __TEXT.__auth_stubs: 0x1740
   __TEXT.__objc_stubs: 0xd0e0
   __TEXT.__objc_methlist: 0x5044
   __TEXT.__const: 0x290
   __TEXT.__dlopen_cstrs: 0x64
   __TEXT.__gcc_except_tab: 0x3894
-  __TEXT.__oslogstring: 0x1177f
-  __TEXT.__cstring: 0xe000
+  __TEXT.__oslogstring: 0x117be
+  __TEXT.__cstring: 0xe00b
   __TEXT.__objc_methname: 0x102f3
   __TEXT.__objc_classname: 0xc2e
   __TEXT.__objc_methtype: 0x2a60
   __TEXT.__unwind_info: 0x2058
   __DATA_CONST.__const: 0x25d8
-  __DATA_CONST.__cfstring: 0x8c60
+  __DATA_CONST.__cfstring: 0x8c80
   __DATA_CONST.__objc_classlist: 0x2d8
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0xf0

   - /usr/lib/libobjc.A.dylib
   Functions: 2254
   Symbols:   618
-  CStrings:  6314
+  CStrings:  6316
 
Functions:
~ sub_100010060 : 3224 -> 3288
~ sub_100047c40 -> sub_100047c80 : 604 -> 612
CStrings:
+ "Ignoring proxy match dictionary, not applicable for internal"
+ "Ignoring proxy match dictionary, not applicable for public"
+ "Internal"
+ "Public"
- "Ignoring proxy match dictionary, not applicable for seed"
- "Seed"
```
