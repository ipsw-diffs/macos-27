## biomesyncd

> `/usr/libexec/biomesyncd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-259.2.0.2.0
-  __TEXT.__text: 0x50f28
+259.5.0.0.0
+  __TEXT.__text: 0x51228
   __TEXT.__auth_stubs: 0xb90
-  __TEXT.__objc_stubs: 0x8ce0
-  __TEXT.__objc_methlist: 0x3d5c
+  __TEXT.__objc_stubs: 0x8d20
+  __TEXT.__objc_methlist: 0x3d6c
   __TEXT.__const: 0x1368
   __TEXT.__gcc_except_tab: 0x908
-  __TEXT.__objc_methname: 0xa911
-  __TEXT.__cstring: 0x5b6f
+  __TEXT.__objc_methname: 0xa9b1
+  __TEXT.__cstring: 0x5ba1
   __TEXT.__objc_classname: 0x7f2
   __TEXT.__objc_methtype: 0x1759
   __TEXT.__oslogstring: 0x6cde
-  __TEXT.__unwind_info: 0x17c8
+  __TEXT.__unwind_info: 0x17d0
   __DATA_CONST.__const: 0x1340
   __DATA_CONST.__cfstring: 0x47a0
   __DATA_CONST.__objc_classlist: 0x1c0

   __DATA_CONST.__objc_dictobj: 0xa0
   __DATA_CONST.__linkguard: 0xf
   __DATA_CONST.__auth_got: 0x5d8
-  __DATA_CONST.__got: 0x460
-  __DATA.__objc_const: 0x7738
-  __DATA.__objc_selrefs: 0x29d8
+  __DATA_CONST.__got: 0x468
+  __DATA.__objc_const: 0x7748
+  __DATA.__objc_selrefs: 0x29e8
   __DATA.__objc_ivar: 0x3ec
   __DATA.__objc_data: 0x1180
   __DATA.__data: 0x840

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 1717
+  Functions: 1719
   Symbols:   336
-  CStrings:  3151
+  CStrings:  3155
 
CStrings:
+ "anySyncStreamHoldsFutureDatedEventsInStreamConfigurations:"
+ "anySyncStreamIsFrozenForSiteIdentifier:database:streamConfigurations:"
+ "com.apple.biomesyncd.cascade.deviceAdded"
+ "handleCompanionLinkDeviceAddedWithCompletionHandler:"
+ "rotateLocalDeviceIdentifierIfFrozenAndEveryStreamRecovered:database:streamConfigurations:"
+ "shouldRotateLocalDeviceIdentifierForPeerStatusTracker:database:streamConfigurations:"
+ "streamConfigurations"
+ "v12@?0B8"
- "anySyncStreamHoldsFutureDatedEvents"
- "anySyncStreamIsFrozenForSiteIdentifier:database:"
- "rotateLocalDeviceIdentifierIfFrozenAndEveryStreamRecovered:database:"
- "shouldRotateLocalDeviceIdentifierForPeerStatusTracker:database:"
```
