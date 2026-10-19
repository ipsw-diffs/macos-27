## LinkPresentation

> `/System/Library/Frameworks/LinkPresentation.framework/Versions/A/LinkPresentation`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

 317.0.0.0.0
-  __TEXT.__text: 0xf4550
+  __TEXT.__text: 0xf4600
   __TEXT.__objc_methlist: 0x1036c
   __TEXT.__cstring: 0x7bbb
   __TEXT.__gcc_except_tab: 0x202a0
   __TEXT.__const: 0x1cf4
   __TEXT.__ustring: 0x406
-  __TEXT.__oslogstring: 0x3504
+  __TEXT.__oslogstring: 0x3564
   __TEXT.__dlopen_cstrs: 0x5ac
   __TEXT.__swift5_typeref: 0x61e
   __TEXT.__constg_swiftt: 0x58c

   __DATA_CONST.__objc_protorefs: 0x78
   __DATA_CONST.__objc_superrefs: 0x598
   __DATA_CONST.__objc_arraydata: 0x1630
-  __DATA_CONST.__got: 0xd70
+  __DATA_CONST.__got: 0xd78
   __AUTH_CONST.__const: 0x3358
   __AUTH_CONST.__cfstring: 0xd460
-  __AUTH_CONST.__objc_const: 0x2ada0
+  __AUTH_CONST.__objc_const: 0x2adc0
   __AUTH_CONST.__objc_intobj: 0x2a0
   __AUTH_CONST.__objc_arrayobj: 0x630
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_doubleobj: 0x60
-  __AUTH_CONST.__auth_got: 0xcb0
+  __AUTH_CONST.__auth_got: 0xca0
   __AUTH.__objc_data: 0x2930
   __AUTH.__data: 0x160
-  __DATA.__objc_ivar: 0x1720
+  __DATA.__objc_ivar: 0x1724
   __DATA.__data: 0x18a0
   __DATA.__bss: 0x1f58
   __DATA.__common: 0x1c8

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 6351
-  Symbols:   13998
-  CStrings:  2144
+  Symbols:   13997
+  CStrings:  2145
 
Symbols:
+ OBJC_IVAR_$_LPAnimatedImageTranscoder._bufferSize
- _CVPixelBufferGetHeight
- _CVPixelBufferGetWidth
Functions:
~ -[LPAnimatedImageTranscoder encodeNextFrame] : 788 -> 964
CStrings:
+ "LPAnimatedImageTranscoder<%d>: failed, frame %zu is %gx%g, but the first frame is %gx%g"
```
