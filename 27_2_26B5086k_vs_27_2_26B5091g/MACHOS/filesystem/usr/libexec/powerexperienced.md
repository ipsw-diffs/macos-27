## powerexperienced

> `/usr/libexec/powerexperienced`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-180.0.0.0.0
-  __TEXT.__text: 0x1654c
+182.40.1.0.0
+  __TEXT.__text: 0x166c0
   __TEXT.__auth_stubs: 0x520
-  __TEXT.__objc_stubs: 0x2e60
-  __TEXT.__objc_methlist: 0x1f14
+  __TEXT.__objc_stubs: 0x2ee0
+  __TEXT.__objc_methlist: 0x1f44
   __TEXT.__const: 0x138
-  __TEXT.__cstring: 0x10f1
-  __TEXT.__objc_methname: 0x3670
-  __TEXT.__oslogstring: 0x25e6
+  __TEXT.__cstring: 0x112d
+  __TEXT.__objc_methname: 0x36a1
+  __TEXT.__oslogstring: 0x262b
   __TEXT.__objc_classname: 0x347
-  __TEXT.__objc_methtype: 0x6b3
+  __TEXT.__objc_methtype: 0x6bb
   __TEXT.__gcc_except_tab: 0x38
-  __TEXT.__unwind_info: 0x7d0
+  __TEXT.__unwind_info: 0x7d8
   __DATA_CONST.__const: 0x878
-  __DATA_CONST.__cfstring: 0x11c0
+  __DATA_CONST.__cfstring: 0x1200
   __DATA_CONST.__objc_classlist: 0xd0
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_intobj: 0xc0
   __DATA_CONST.__auth_got: 0x2a0
   __DATA_CONST.__got: 0xd0
-  __DATA.__objc_const: 0x4760
-  __DATA.__objc_selrefs: 0xe98
-  __DATA.__objc_ivar: 0x218
+  __DATA.__objc_const: 0x4790
+  __DATA.__objc_selrefs: 0xeb0
+  __DATA.__objc_ivar: 0x21c
   __DATA.__objc_data: 0x820
   __DATA.__data: 0x420
   __DATA.__bss: 0x238

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 733
+  Functions: 737
   Symbols:   119
-  CStrings:  1203
+  CStrings:  1210
 
CStrings:
+ "AssertionTimeout"
+ "AssistantMode changing from %@ to %@ (siriRemoteSession=%d, siriLocalSession=%d, assistantUI=%d, nanoSiriX=%d)"
+ "Overriding InBoxUpdateMode Assertion with defaults timeout value %ld"
+ "assertionTimeout"
+ "com.apple.powerexperienced.inboxupdatemode"
+ "integerValue"
+ "numberWithInteger:"
+ "q16@0:8"
- "AssistantMode changing from %@ to %@ (siriRemoteSession=%d, siriLocalSession=%d, assistantUI=%d, siriAudio=%d)"
```
