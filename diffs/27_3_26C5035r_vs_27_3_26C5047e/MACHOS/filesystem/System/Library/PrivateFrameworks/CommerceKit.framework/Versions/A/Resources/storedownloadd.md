## storedownloadd

> `/System/Library/PrivateFrameworks/CommerceKit.framework/Versions/A/Resources/storedownloadd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-717.1.4.0.0
-  __TEXT.__text: 0xbfda8
+717.2.1.0.0
+  __TEXT.__text: 0xbff18
   __TEXT.__auth_stubs: 0xa30
-  __TEXT.__objc_stubs: 0x8180
+  __TEXT.__objc_stubs: 0x81a0
   __TEXT.__objc_methlist: 0x2954
-  __TEXT.__cstring: 0xaa6f
+  __TEXT.__cstring: 0xabb7
   __TEXT.__objc_classname: 0x560
   __TEXT.__objc_methtype: 0xe8c
   __TEXT.__gcc_except_tab: 0x1114
   __TEXT.__const: 0x8700
-  __TEXT.__objc_methname: 0x8a2d
+  __TEXT.__objc_methname: 0x8a42
   __TEXT.__unwind_info: 0xf88
   __TEXT.__eh_frame: 0x108
   __DATA_CONST.__const: 0xa3f8
-  __DATA_CONST.__cfstring: 0x62c0
+  __DATA_CONST.__cfstring: 0x62e0
   __DATA_CONST.__objc_classlist: 0x148
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x58

   __DATA_CONST.__got: 0x658
   __DATA_CONST.__auth_ptr: 0x8
   __DATA.__objc_const: 0x6c60
-  __DATA.__objc_selrefs: 0x2548
+  __DATA.__objc_selrefs: 0x2550
   __DATA.__objc_ivar: 0x300
   __DATA.__objc_data: 0xcd0
   __DATA.__data: 0x9b8

   - /usr/lib/libobjc.A.dylib
   Functions: 1132
   Symbols:   393
-  CStrings:  2739
+  CStrings:  2743
 
Functions:
~ sub_100025ddc : 252 -> 620
CStrings:
+ "%@: Rejecting a download whose asset URL does not give a valid file name"
+ "-[DownloadServiceInterface addDownload:replyBlock:]"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Commerce/CommerceKit/DownloadService/DownloadServiceInterface.m"
+ "hasSafeLocalFileName"
```
