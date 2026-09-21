## Vermillion

> `/System/Library/ExtensionKit/Extensions/Vermillion.appex/Contents/MacOS/Vermillion`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-44.0.0.0.0
+46.0.0.0.0
   __TEXT.__text: 0x101b8
   __TEXT.__auth_stubs: 0xdf0
   __TEXT.__objc_stubs: 0x2c0

   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__unwind_info: 0x5e0
   __TEXT.__eh_frame: 0xd18
-  __DATA_CONST.__const: 0x741
+  __DATA_CONST.__const: 0x751
   __DATA_CONST.__objc_classlist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x700

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftAVFoundation.dylib
   - /usr/lib/swift/libswiftAccelerate.dylib
+  - /usr/lib/swift/libswiftAppleArchive.dylib
   - /usr/lib/swift/libswiftCompression.dylib
   - /usr/lib/swift/libswiftCore.dylib
   - /usr/lib/swift/libswiftCoreAudio.dylib

   - /usr/lib/swift/libswiftCoreImage.dylib
   - /usr/lib/swift/libswiftCoreLocation.dylib
   - /usr/lib/swift/libswiftCoreMIDI.dylib
+  - /usr/lib/swift/libswiftCoreMediaIO.dylib
   - /usr/lib/swift/libswiftDispatch.dylib
   - /usr/lib/swift/libswiftIOKit.dylib
   - /usr/lib/swift/libswiftIntents.dylib

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 315
-  Symbols:   111
+  Symbols:   113
   CStrings:  56
 
Symbols:
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftCoreMediaIO
```
