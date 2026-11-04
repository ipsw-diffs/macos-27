## CloudDocs

> `/System/Library/PrivateFrameworks/CloudDocs.framework/Versions/A/CloudDocs`

```diff

-5168.40.162.0.0
-  __TEXT.__text: 0x84fe8
-  __TEXT.__objc_methlist: 0x6764
+5168.60.14.0.0
+  __TEXT.__text: 0x85510
+  __TEXT.__objc_methlist: 0x67ac
   __TEXT.__const: 0x1b0
-  __TEXT.__gcc_except_tab: 0x3ef0
-  __TEXT.__cstring: 0xb202
-  __TEXT.__oslogstring: 0x8a53
+  __TEXT.__gcc_except_tab: 0x3f00
+  __TEXT.__cstring: 0xb241
+  __TEXT.__oslogstring: 0x8bd7
   __TEXT.__dlopen_cstrs: 0x4c
   __TEXT.__ustring: 0x10
-  __TEXT.__unwind_info: 0x30f8
+  __TEXT.__unwind_info: 0x3118
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0xe8
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x42c8
+  __DATA_CONST.__objc_selrefs: 0x42f0
   __DATA_CONST.__objc_protorefs: 0x68
   __DATA_CONST.__objc_superrefs: 0x240
   __DATA_CONST.__objc_arraydata: 0x60

   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_intobj: 0x540
   __AUTH_CONST.__objc_doubleobj: 0x30
-  __AUTH_CONST.__auth_got: 0xa38
+  __AUTH_CONST.__auth_got: 0xa48
   __AUTH.__objc_data: 0x1220
   __AUTH.__data: 0x80
   __DATA.__objc_ivar: 0x604

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 3087
-  Symbols:   6569
-  CStrings:  2152
+  Functions: 3095
+  Symbols:   6576
+  CStrings:  2157
 
Symbols:
+ +[BRContainer ubiquitousContainers:declarePublicDocumentScopeForContainerID:]
+ +[BRContainer(BRInternalAdditions) ubiquitousContainerPropertiesForContainerID:inUbiquitousContainers:]
+ +[NSURL(BRAdditions) br_withIOPolicyFlags:type:forBlock:]
+ -[BRContainer(BRInternalAdditions) isMetadataExtracted]
+ -[NSURL(BRCPathAdditions) brc_issueSandboxExtensionOfClass:flags:error:]
+ GCC_except_table110
+ GCC_except_table114
+ GCC_except_table116
+ GCC_except_table142
+ GCC_except_table147
+ GCC_except_table148
+ GCC_except_table172
+ GCC_except_table175
+ GCC_except_table188
+ GCC_except_table190
+ GCC_except_table191
+ GCC_except_table193
+ GCC_except_table201
+ GCC_except_table206
+ GCC_except_table220
+ GCC_except_table232
+ GCC_except_table29
+ GCC_except_table35
+ GCC_except_table42
+ GCC_except_table44
+ GCC_except_table46
+ GCC_except_table58
+ GCC_except_table68
+ GCC_except_table74
+ GCC_except_table76
+ GCC_except_table89
+ GCC_except_table93
+ GCC_except_table98
+ ___55-[BRContainer(BRInternalAdditions) isMetadataExtracted]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e16_v16?0"NSData"8l
+ _disableiopolicy_np
+ _enableiopolicy_np
+ _objc_msgSend$brc_issueSandboxExtensionOfClass:flags:error:
+ _objc_msgSend$ubiquitousContainerPropertiesForContainerID:inUbiquitousContainers:
- GCC_except_table109
- GCC_except_table113
- GCC_except_table115
- GCC_except_table118
- GCC_except_table131
- GCC_except_table137
- GCC_except_table141
- GCC_except_table146
- GCC_except_table153
- GCC_except_table163
- GCC_except_table168
- GCC_except_table177
- GCC_except_table180
- GCC_except_table182
- GCC_except_table187
- GCC_except_table197
- GCC_except_table198
- GCC_except_table212
- GCC_except_table228
- GCC_except_table32
- GCC_except_table34
- GCC_except_table47
- GCC_except_table49
- GCC_except_table52
- GCC_except_table59
- GCC_except_table65
- GCC_except_table73
- GCC_except_table75
- GCC_except_table81
- GCC_except_table88
- GCC_except_table97
- ___block_descriptor_40_e8_32bs_e16_v16?0"NSData"8l
CStrings:
+ "+[NSURL(BRAdditions) br_withIOPolicyFlags:type:forBlock:]"
+ "-[NSURL(BRCPathAdditions) brc_issueSandboxExtensionOfClass:flags:error:]"
+ "5168.60.14"
+ "[ERROR] enableiopolicy_np failed for flags: %#x, type: %d, scope: %d, errno: %d%@"
+ "[ERROR] getiopolicy_np failed when enabling flags: %#x, type: %d, scope: %d%@"
+ "[ERROR] sandbox_check: current process does not allow iopolicy syscalls, not running block%@"
+ "[WARNING] no data representation for container %@, returning nil properties - every property read off it is a default, not an answer%@"
- "-[NSURL(BRCPathAdditions) brc_issueSandboxExtensionOfClass:error:]"
- "5168.40.162"
```
