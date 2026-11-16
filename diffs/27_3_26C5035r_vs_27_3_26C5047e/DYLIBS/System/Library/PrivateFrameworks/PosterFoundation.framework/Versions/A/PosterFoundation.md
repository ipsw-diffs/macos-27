## PosterFoundation

> `/System/Library/PrivateFrameworks/PosterFoundation.framework/Versions/A/PosterFoundation`

```diff

-355.3.7.0.0
-  __TEXT.__text: 0x48cf8
+355.3.12.0.0
+  __TEXT.__text: 0x48cd4
   __TEXT.__objc_methlist: 0x3558
   __TEXT.__const: 0x1e6
   __TEXT.__cstring: 0x4610
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ -[PFPosterExtensionInstanceProvider acquireInstanceForExtension:reason:error:] : 1484 -> 1480
~ -[PFPosterExtensionInstanceProvider relinquishExtensionInstance:reason:] : 748 -> 744
~ -[PFPosterExtensionInstanceProvider activeExtensionInstances] : 348 -> 344
~ -[PFPosterExtensionInstanceProvider _stateCaptureDescription] : 968 -> 964
~ -[PFPosterExtensionInstanceProvider noteExtensionsWereUpdated:] : 936 -> 932
~ -[PFPosterExtensionInstanceProvider instanceForExtension:reason:] : 216 -> 212
~ -[PFPosterExtensionInstanceProvider extensionInstanceDidInvalidate:] : 724 -> 720
~ -[PFPosterExtensionInstanceProvider cancel] : 400 -> 396
~ -[PFOSUnfairRecursiveLock lock] : 12 -> 8
```
