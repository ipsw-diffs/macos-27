## ANEStorageMaintainer

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANEStorageMaintainer.xpc/Contents/MacOS/ANEStorageMaintainer`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-382.102.2.0.0
-  __TEXT.__text: 0x8984
-  __TEXT.__auth_stubs: 0x3c0
-  __TEXT.__objc_stubs: 0xfa0
+382.202.0.0.0
+  __TEXT.__text: 0x8198
+  __TEXT.__auth_stubs: 0x3a0
+  __TEXT.__objc_stubs: 0xf80
   __TEXT.__objc_methlist: 0x3e4
-  __TEXT.__const: 0xd0
-  __TEXT.__oslogstring: 0x101f
+  __TEXT.__const: 0xc8
+  __TEXT.__oslogstring: 0xf27
   __TEXT.__objc_classname: 0x86
-  __TEXT.__objc_methname: 0x1094
+  __TEXT.__objc_methname: 0x1084
   __TEXT.__objc_methtype: 0x276
-  __TEXT.__cstring: 0x1d0
-  __TEXT.__unwind_info: 0x200
+  __TEXT.__cstring: 0x1b9
+  __TEXT.__unwind_info: 0x1e8
   __DATA_CONST.__const: 0xd0
-  __DATA_CONST.__cfstring: 0x320
+  __DATA_CONST.__cfstring: 0x2c0
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x8
   __DATA_CONST.__objc_intobj: 0x18
-  __DATA_CONST.__auth_got: 0x1e8
-  __DATA_CONST.__got: 0xd0
+  __DATA_CONST.__auth_got: 0x1d8
+  __DATA_CONST.__got: 0xd8
   __DATA_CONST.__auth_ptr: 0x8
   __DATA.__objc_const: 0x450
-  __DATA.__objc_selrefs: 0x528
+  __DATA.__objc_selrefs: 0x520
   __DATA.__objc_ivar: 0x8
   __DATA.__objc_data: 0x140
   __DATA.__data: 0x130

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 113
-  Symbols:   370
-  CStrings:  341
+  Functions: 110
+  Symbols:   368
+  CStrings:  331
 
Symbols:
+ _OBJC_CLASS_$__ANECacheMaintenance
+ _objc_msgSend$accessTimeForPath:
+ _objc_msgSend$isPath:safelyWithinDirectory:
+ _objc_msgSend$setAccessTime:forPath:
+ _objc_msgSend$updateAccessTimeForPath:
- _getxattr
- _objc_msgSend$containsObject:
- _objc_msgSend$dateWithTimeIntervalSince1970:
- _objc_msgSend$hasSuffix:
- _objc_msgSend$setAccessTime:forModelFilePath:
- _objc_msgSend$stringByAppendingString:
- _setxattr
CStrings:
+ "accessTimeForPath:"
+ "setAccessTime:forPath:"
+ "updateAccessTimeForPath:"
- "%@: +setAccessTime:forFilePath failed"
- "%@: Skipping update for filePath=%@"
- "%@: filePath=%@"
- "%@: getxattr(%@, %@, %p, %lu) failed  : errno=%d"
- "%@: getxattr(%@, %@, %p, %lu) missing attribute  : errno=%d"
- "%@: setxattr(%@, %@, %p, %lu) failed  : errno=%d"
- ".."
- "/"
- "containsObject:"
- "dateWithTimeIntervalSince1970:"
- "hasSuffix:"
- "kANEAccessSeconds"
- "stringByAppendingString:"
```
