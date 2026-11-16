## GameController

> `/System/Library/Frameworks/GameController.framework/Versions/A/GameController`

```diff

-14.2.2.0.0
-  __TEXT.__text: 0x10d0a0
+14.2.3.0.0
+  __TEXT.__text: 0x10d0f8
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x10024
   __TEXT.__const: 0x244c
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ _LoadGameControllerUIFramework : 1808 -> 1804
~ +[GCController supportsHIDDevice:] : 2792 -> 2800
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFSS_Tg5 : 260 -> 284
~ _$ss22_ContiguousArrayBufferV19_uninitializedCount15minimumCapacityAByxGSi_SitcfCs5UInt8V_Tt1gq5 : 112 -> 124
~ _$ss22_ContiguousArrayBufferV19_uninitializedCount15minimumCapacityAByxGSi_SitcfCScS12ContinuationVyyt_G_Tt1g5 : 240 -> 268
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF14GameController23GCDeviceAttributeAnyKeyV_ypt_Tg5 : 316 -> 352
~ -[_GCSystemButton invalidate] : 92 -> 88
~ -[_GCSystemButtonResponder invalidate] : 92 -> 88
~ -[_GCLegacyPublishedControllerStore _publishCustomController:] : 296 -> 292
~ -[_GCLegacyPublishedControllerStore _unpublishCustomController:] : 288 -> 284
```
