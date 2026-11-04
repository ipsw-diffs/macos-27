## AudioVideoBridging

> `/System/Library/Frameworks/AudioVideoBridging.framework/Versions/A/AudioVideoBridging`

```diff

-1510.1.0.0.0
-  __TEXT.__text: 0x19bab8
-  __TEXT.__objc_methlist: 0x191d4
-  __TEXT.__const: 0x568
+1520.3.0.0.0
+  __TEXT.__text: 0x19c51c
+  __TEXT.__objc_methlist: 0x191fc
+  __TEXT.__const: 0x578
   __TEXT.__gcc_except_tab: 0x1760
-  __TEXT.__cstring: 0x1ae8d
-  __TEXT.__oslogstring: 0x67ba
+  __TEXT.__cstring: 0x1aeea
+  __TEXT.__oslogstring: 0x6919
   __TEXT.__ustring: 0x60
-  __TEXT.__unwind_info: 0x7690
+  __TEXT.__unwind_info: 0x76a8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x1000
   __DATA_CONST.__objc_protolist: 0x88
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8350
+  __DATA_CONST.__objc_selrefs: 0x8388
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0xdb8
   __DATA_CONST.__objc_arraydata: 0x50
-  __DATA_CONST.__got: 0xf98
+  __DATA_CONST.__got: 0xfa0
   __AUTH_CONST.__const: 0x1650
-  __AUTH_CONST.__cfstring: 0x14ac0
+  __AUTH_CONST.__cfstring: 0x14ae0
   __AUTH_CONST.__objc_const: 0x269b0
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_intobj: 0x60

   __AUTH.__objc_data: 0xa000
   __DATA.__objc_ivar: 0x1384
   __DATA.__data: 0x668
-  __DATA.__bss: 0x158
+  __DATA.__bss: 0x160
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 9160
-  Symbols:   16305
-  CStrings:  3811
+  Functions: 9167
+  Symbols:   16317
+  CStrings:  3816
 
Symbols:
+ +[AVB17221AEMMemoryObjectURL setURLBackedMemoryObjectsAllowed:]
+ +[AVB17221AEMMemoryObjectURL urlBackedMemoryObjectsAllowed]
+ +[AVBVirtualAudioConfiguration entityModelByResolvingMemoryObjectDataURLs:error:]
+ _NSURLIsRegularFileKey
+ __OBJC_$_CLASS_METHODS_AVB17221AEMMemoryObjectURL
+ _objc_msgSend$arrayWithCapacity:
+ _objc_msgSend$dictionaryWithDictionary:
+ _objc_msgSend$entityModelByResolvingMemoryObjectDataURLs:error:
+ _objc_msgSend$getResourceValue:forKey:error:
+ _objc_msgSend$initWithContentsOfURL:options:error:
+ _objc_msgSend$urlBackedMemoryObjectsAllowed
+ _sAVB17221AEMURLBackedMemoryObjectsAllowed
CStrings:
+ "Could not read the data_url of a memory object, %{private}@: %{public}@"
+ "Not resolving the data_url of a memory object: %{private}@ is not a plain file"
+ "Not resolving the data_url of a memory object: only local file URLs are supported, not %{private}@"
+ "Not resolving the data_url of a memory object: this process does not allow URL backed memory objects"
+ "The contents of %@ could not be read for a memory object of the custom virtual entity model."
```
