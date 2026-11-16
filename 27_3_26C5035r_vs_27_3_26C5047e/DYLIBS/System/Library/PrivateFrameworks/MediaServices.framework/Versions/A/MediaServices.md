## MediaServices

> `/System/Library/PrivateFrameworks/MediaServices.framework/Versions/A/MediaServices`

```diff

 4026.300.6.0.0
-  __TEXT.__text: 0x5ab3c
+  __TEXT.__text: 0x5ab30
   __TEXT.__objc_methlist: 0x57a4
   __TEXT.__const: 0x3ac
   __TEXT.__dlopen_cstrs: 0x70
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ -[MSVSonicBackgroundTaskProvider beginTaskWithName:expirationHandler:] : 980 -> 976
~ -[MSVSonicBackgroundTaskProvider endTask:] : 512 -> 508
~ -[MSVSonicBackgroundTaskProvider _taskDidTimeout:] : 368 -> 364
~ -[MSVExtendableBackgroundTaskProvider beginTaskWithName:expirationHandler:] : 660 -> 656
~ -[MSVExtendableBackgroundTaskProvider endTask:] : 380 -> 376
~ -[MSVExtendableBackgroundTaskProvider _taskDidTimeout:] : 264 -> 260
~ -[MSVExtendableBackgroundTaskProvider _assertionInvalidated:error:] : 300 -> 296
~ ___63-[MSVExtendableBackgroundTaskProvider _locked_releaseAssertion]_block_invoke : 252 -> 248
~ sub_1add2d500 -> sub_1adf6c4e0 : 272 -> 292
```
