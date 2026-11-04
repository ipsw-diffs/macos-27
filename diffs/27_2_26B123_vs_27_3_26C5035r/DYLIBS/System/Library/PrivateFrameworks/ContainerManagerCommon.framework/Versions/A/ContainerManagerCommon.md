## ContainerManagerCommon

> `/System/Library/PrivateFrameworks/ContainerManagerCommon.framework/Versions/A/ContainerManagerCommon`

```diff

-833.40.18.0.1
-  __TEXT.__text: 0x10e2bc
-  __TEXT.__objc_methlist: 0xb4dc
-  __TEXT.__const: 0x15d0
+833.60.4.0.1
+  __TEXT.__text: 0x10ee0c
+  __TEXT.__objc_methlist: 0xb53c
+  __TEXT.__const: 0x15c0
   __TEXT.__swift5_typeref: 0x871
   __TEXT.__oslogstring: 0xef96
-  __TEXT.__cstring: 0xa958
+  __TEXT.__cstring: 0xaa0e
   __TEXT.__constg_swiftt: 0x790
   __TEXT.__swift5_reflstr: 0x52a
   __TEXT.__swift5_fieldmd: 0x5d4

   __TEXT.__swift5_protos: 0x18
   __TEXT.__gcc_except_tab: 0x2408
   __TEXT.__ustring: 0x16c
-  __TEXT.__unwind_info: 0x3ea8
+  __TEXT.__unwind_info: 0x3ec8
   __TEXT.__eh_frame: 0xaac
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x628
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3968
+  __DATA_CONST.__objc_selrefs: 0x3988
   __DATA_CONST.__objc_protorefs: 0x1b0
   __DATA_CONST.__objc_superrefs: 0x4a8
   __DATA_CONST.__objc_arraydata: 0x3d0
   __DATA_CONST.__got: 0x558
   __AUTH_CONST.__const: 0x2c10
-  __AUTH_CONST.__cfstring: 0x5760
-  __AUTH_CONST.__objc_const: 0x17cb8
+  __AUTH_CONST.__cfstring: 0x5780
+  __AUTH_CONST.__objc_const: 0x17d40
   __AUTH_CONST.__objc_dictobj: 0x3e8
   __AUTH_CONST.__objc_intobj: 0x15d8
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__auth_got: 0x1288
   __AUTH.__objc_data: 0xe08
   __AUTH.__data: 0x1b8
-  __DATA.__objc_ivar: 0xc48
-  __DATA.__data: 0x3de0
+  __DATA.__objc_ivar: 0xc4c
+  __DATA.__data: 0x3df0
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0xc98
   __DATA.__common: 0x48

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3918
-  Symbols:   8591
-  CStrings:  2143
+  Functions: 3925
+  Symbols:   8598
+  CStrings:  2148
 
Symbols:
+ -[MCMContainerCacheEntry adoptCreatorFromMetadata:]
+ -[MCMContainerCacheEntry creator]
+ -[MCMContainerCacheEntry initWithIdentifier:containerPath:schemaVersion:posixOwnership:instanceUUID:uuid:creator:metadata:userIdentityCache:]
+ -[MCMContainerCacheEntry setCreator:]
+ -[MCMContainerClassCache _concurrent_generateCacheEntryWithURL:identifier:containerPath:schemaVersion:posixOwnership:instanceUUID:uuid:creator:metadata:]
+ GCC_except_table3031
+ _OBJC_IVAR_$_MCMContainerCacheEntry._creator
+ _objc_msgSend$_concurrent_generateCacheEntryWithURL:identifier:containerPath:schemaVersion:posixOwnership:instanceUUID:uuid:creator:metadata:
+ _objc_msgSend$_creator
+ _objc_msgSend$adoptCreatorFromMetadata:
+ _objc_msgSend$initWithIdentifier:containerPath:schemaVersion:posixOwnership:instanceUUID:uuid:creator:metadata:userIdentityCache:
+ _objc_msgSend$initWithIdentifier:uuid:schemaVersion:instanceUUID:creator:
+ _objc_msgSend$setCreator:
- -[MCMContainerCacheEntry initWithIdentifier:containerPath:schemaVersion:posixOwnership:instanceUUID:uuid:metadata:userIdentityCache:]
- -[MCMContainerClassCache _concurrent_generateCacheEntryWithURL:identifier:containerPath:schemaVersion:posixOwnership:instanceUUID:uuid:metadata:]
- GCC_except_table3028
- _objc_msgSend$_concurrent_generateCacheEntryWithURL:identifier:containerPath:schemaVersion:posixOwnership:instanceUUID:uuid:metadata:
- _objc_msgSend$initWithIdentifier:containerPath:schemaVersion:posixOwnership:instanceUUID:uuid:metadata:userIdentityCache:
- _objc_msgSend$initWithIdentifier:uuid:schemaVersion:instanceUUID:
CStrings:
+ "23:46:13"
+ "<%@: %p; identifier = %@, generation = %llu, containerPath = %@, schemaVersion = %@, uuid = %@, posixOwnership = %@, fsNode = %@, instanceUUID = %@, creator = %@%s%s>"
+ "Identity record creator field is unterminated"
+ "Identity record creator is not an acceptable "
+ "Identity record creator is not valid UTF-8"
+ "MobileContainerManager-833.60.4.0.1~454"
+ "Oct 28 2026"
+ "creator"
+ "creator: "
+ "\xa1"
- "16:04:38"
- "<%@: %p; identifier = %@, generation = %llu, containerPath = %@, schemaVersion = %@, uuid = %@, posixOwnership = %@, fsNode = %@, instanceUUID = %@%s%s>"
- "MobileContainerManager-833.40.18.0.1~84"
- "Oct  3 2026"
- "\x91"
```
