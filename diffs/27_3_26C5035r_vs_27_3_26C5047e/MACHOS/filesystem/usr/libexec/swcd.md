## swcd

> `/usr/libexec/swcd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1036.2.0.0.0
-  __TEXT.__text: 0x1f878
+1040.2.0.0.0
+  __TEXT.__text: 0x1fdc0
   __TEXT.__auth_stubs: 0x870
-  __TEXT.__objc_stubs: 0x3200
-  __TEXT.__objc_methlist: 0x103c
-  __TEXT.__gcc_except_tab: 0x3c5c
-  __TEXT.__cstring: 0x1d08
+  __TEXT.__objc_stubs: 0x3260
+  __TEXT.__objc_methlist: 0x1064
+  __TEXT.__gcc_except_tab: 0x3d14
+  __TEXT.__cstring: 0x1d26
   __TEXT.__const: 0xe0
-  __TEXT.__objc_methname: 0x3c0d
-  __TEXT.__oslogstring: 0x192c
+  __TEXT.__objc_methname: 0x3cde
+  __TEXT.__oslogstring: 0x1978
   __TEXT.__objc_classname: 0x1b4
-  __TEXT.__objc_methtype: 0x11d0
-  __TEXT.__unwind_info: 0xc60
-  __DATA_CONST.__const: 0xc30
+  __TEXT.__objc_methtype: 0x11df
+  __TEXT.__unwind_info: 0xca0
+  __DATA_CONST.__const: 0xc90
   __DATA_CONST.__cfstring: 0x1380
   __DATA_CONST.__objc_classlist: 0x58
   __DATA_CONST.__objc_catlist: 0x8

   __DATA_CONST.__auth_got: 0x448
   __DATA_CONST.__got: 0x278
   __DATA.__objc_const: 0x1528
-  __DATA.__objc_selrefs: 0xec8
+  __DATA.__objc_selrefs: 0xee8
   __DATA.__objc_ivar: 0xdc
   __DATA.__objc_data: 0x370
   __DATA.__data: 0x3c0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 398
+  Functions: 404
   Symbols:   223
-  CStrings:  1107
+  CStrings:  1114
 
CStrings:
+ "@32@0:8@16@?24"
+ "Ignoring associated domains for bundle record %@ because they are malformed"
+ "_entriesForApplicationIdentifier:fromJSONEnumeration:"
+ "_entriesFromAdditionalServiceDetailsForApplicationIdentifier:"
+ "_enumerateAdditionalServiceDetailsJSONFilesForApplicationIdentifier:block:"
+ "associatedDomains"
+ "v16@?0@?<v@?@\"_SWCDomain\"@C>8"
```
