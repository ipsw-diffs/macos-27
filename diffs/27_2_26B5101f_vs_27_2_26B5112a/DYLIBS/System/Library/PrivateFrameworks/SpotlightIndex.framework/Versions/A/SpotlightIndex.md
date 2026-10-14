## SpotlightIndex

> `/System/Library/PrivateFrameworks/SpotlightIndex.framework/Versions/A/SpotlightIndex`

```diff

-2465.1.7.0.0
-  __TEXT.__text: 0x4df044
+2465.1.9.0.0
+  __TEXT.__text: 0x4df3b8
   __TEXT.__objc_methlist: 0x404
   __TEXT.__const: 0xacf2
-  __TEXT.__cstring: 0x3ef80
+  __TEXT.__cstring: 0x3f0ec
   __TEXT.__gcc_except_tab: 0x27c
-  __TEXT.__oslogstring: 0x1f454
+  __TEXT.__oslogstring: 0x1f551
   __TEXT.__ustring: 0x400
   __TEXT.__dof_mds: 0x29b
   __TEXT.__unwind_info: 0x76a0

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6b98
+  __DATA_CONST.__const: 0x6b38
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x698
   __DATA_CONST.__objc_superrefs: 0x18
   __DATA_CONST.__objc_arraydata: 0x78
   __DATA_CONST.__got: 0x608
-  __AUTH_CONST.__const: 0xd3d8
-  __AUTH_CONST.__cfstring: 0x12e00
+  __AUTH_CONST.__const: 0xd468
+  __AUTH_CONST.__cfstring: 0x12e60
   __AUTH_CONST.__objc_const: 0x5e8
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x18

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 8110
-  Symbols:   10930
-  CStrings:  9621
+  Functions: 8111
+  Symbols:   10931
+  CStrings:  9629
 
Symbols:
+ GCC_except_table7085
+ _lazySetupMissingOids
- GCC_except_table7084
CStrings:
+ "%s:%d: duplicate oid sweep not deleting - indexMarkDirty failed for %s, oid %lld left in place"
+ "%s:%d: orphan sweep abandoned - indexMarkDirty failed for %s, oid %lld left in place"
+ "%s:%d: orphan sweep skipped - read only index %s, oid %lld left in place"
+ "((((newIndex->coreSpotlight)?({ ((uint8_t *)newIndex->groups)[docId]; }):({ uint32_t __where=(uint32_t)docId; uint32_t __slot = __where/5; uint32_t __shift= (__where-(__slot*5))*6; uint32_t __word = ((uint32_t)(newIndex->groups[__slot])); (__word >> __shift) & 0x3F ; })) & (((((void)(newIndex->coreSpotlight)), 0)) ? 0xFF : (~0x20)))) == 0"
+ "2465.1.9"
+ "_Bool processOneCS(SIRef, int64_t, oid_t, CFStringRef, CFStringRef, int, MDPlistObject, MDPlistObject, CFStringRef, size_t, CFAllocatorRef, _Bool, dispatch_group_t, si_syndication_change_s *, Boolean *)"
+ "_CIDeleteByOidsBulk"
+ "_CIDeleteDuplicates"
+ "duplicate oid sweep not deleting - indexMarkDirty failed for %s, oid %lld left in place"
+ "orphan sweep abandoned - indexMarkDirty failed for %s, oid %lld left in place"
+ "orphan sweep skipped - read only index %s, oid %lld left in place"
+ "void _si_delete_attributes_inner(SIRef, oid_t, _Bool, _Bool, _Bool, _Bool, RLEOIDMutableArrayRef, si_syndication_change_s *, uint32_t)"
- "(((newIndex->coreSpotlight?({ ((uint8_t *)newIndex->groups)[docId]; }):({ uint32_t __where=(uint32_t)docId; uint32_t __slot = __where/5; uint32_t __shift= (__where-(__slot*5))*6; uint32_t __word = ((uint32_t)(newIndex->groups[__slot])); (__word >> __shift) & 0x3F ; }))&(~0x20))) == 0"
- "2465.1.7"
- "_Bool processOneCS(SIRef, int64_t, oid_t, CFStringRef, CFStringRef, int, MDPlistObject, MDPlistObject, CFStringRef, size_t, CFAllocatorRef, _Bool, dispatch_group_t, _Bool *, Boolean *)"
- "void _si_delete_attributes_inner(SIRef, oid_t, _Bool, _Bool, _Bool, _Bool, RLEOIDMutableArrayRef, _Bool *, uint32_t)"
```
