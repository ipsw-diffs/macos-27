## SoftwareUpdateCore

> `/System/Library/PrivateFrameworks/SoftwareUpdateCore.framework/Versions/A/SoftwareUpdateCore`

```diff

-2718.60.3.0.0
-  __TEXT.__text: 0xb0898
-  __TEXT.__objc_methlist: 0x7ffc
-  __TEXT.__cstring: 0x1590d
+2718.60.6.0.0
+  __TEXT.__text: 0xb0610
+  __TEXT.__objc_methlist: 0x8044
+  __TEXT.__cstring: 0x152dd
   __TEXT.__const: 0x1e2
   __TEXT.__gcc_except_tab: 0x758
-  __TEXT.__oslogstring: 0xbdc3
+  __TEXT.__oslogstring: 0xc533
   __TEXT.__constg_swiftt: 0x50
   __TEXT.__swift5_typeref: 0x43
   __TEXT.__swift5_fieldmd: 0x10
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x20c8
+  __TEXT.__unwind_info: 0x20e0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1618
-  __DATA_CONST.__objc_classlist: 0x238
+  __DATA_CONST.__objc_classlist: 0x240
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4778
+  __DATA_CONST.__objc_selrefs: 0x47a0
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0x1f8
+  __DATA_CONST.__objc_superrefs: 0x200
   __DATA_CONST.__objc_arraydata: 0xe8
-  __DATA_CONST.__got: 0xab8
+  __DATA_CONST.__got: 0xac0
   __AUTH_CONST.__const: 0x14b8
-  __AUTH_CONST.__cfstring: 0x13220
-  __AUTH_CONST.__objc_const: 0xb6d8
+  __AUTH_CONST.__cfstring: 0x12ec0
+  __AUTH_CONST.__objc_const: 0xb830
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_intobj: 0x90
-  __AUTH_CONST.__auth_got: 0x598
-  __AUTH.__objc_data: 0x6d8
+  __AUTH_CONST.__auth_got: 0x5b0
+  __AUTH.__objc_data: 0x728
   __AUTH.__data: 0x98
-  __DATA.__objc_ivar: 0xa6c
+  __DATA.__objc_ivar: 0xa80
   __DATA.__data: 0x3d8
   __DATA.__bss: 0x40
   __DATA_DIRTY.__objc_data: 0xf28

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3211
-  Symbols:   7510
-  CStrings:  3180
+  Functions: 3215
+  Symbols:   7534
+  CStrings:  3179
 
Symbols:
+ -[SUCoreDownloadRateLimiter canProceed]
+ -[SUCoreDownloadRateLimiter initWithMinInterval:]
+ -[SUCoreDownloadRateLimiter reset]
+ -[SUCoreUpdateDownloader progressRateLimiter]
+ -[SUCoreUpdateDownloader stalledRateLimiter]
+ _OBJC_CLASS_$_SUCoreDownloadRateLimiter
+ _OBJC_IVAR_$_SUCoreDownloadRateLimiter._lastProceedTime
+ _OBJC_IVAR_$_SUCoreDownloadRateLimiter._lock
+ _OBJC_IVAR_$_SUCoreDownloadRateLimiter._minInterval
+ _OBJC_IVAR_$_SUCoreUpdateDownloader._progressRateLimiter
+ _OBJC_IVAR_$_SUCoreUpdateDownloader._stalledRateLimiter
+ _OBJC_METACLASS_$_SUCoreDownloadRateLimiter
+ __OBJC_$_INSTANCE_METHODS_SUCoreDownloadRateLimiter
+ __OBJC_$_INSTANCE_VARIABLES_SUCoreDownloadRateLimiter
+ __OBJC_CLASS_RO_$_SUCoreDownloadRateLimiter
+ __OBJC_METACLASS_RO_$_SUCoreDownloadRateLimiter
+ _clock_gettime_nsec_np
+ _objc_msgSend$canProceed
+ _objc_msgSend$initWithMinInterval:
+ _objc_msgSend$progressRateLimiter
+ _objc_msgSend$reset
+ _objc_msgSend$stalledRateLimiter
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
CStrings:
+ "%{public}@ [PreSUStaging] %@"
+ "%{public}@ [PreSUStaging] No need to remove PSUS assets (disabled)"
+ "%{public}@ [PreSUStaging] No optional assets to download"
+ "%{public}@ [PreSUStaging] No required assets to stage"
+ "%{public}@ [PreSUStaging] PSUS groups to stage: %@"
+ "%{public}@ [PreSUStaging] not staging optional assets: %@"
+ "%{public}@ [PreSUStaging] purge after a timeout: %@"
+ "%{public}@ [PreSUStaging] staging assets with attributes: %@"
+ "%{public}@ [PreSUStaging] using maxAllowedPreSUStagingOptionalSize = %llu"
+ "%{public}@ [Progress] %lld/%lld bytes downloaded; estimated speed: %.2lf MBps; estimated time remaining = %.2lf secs"
+ "%{public}@ [Progress] Too few progress records to report"
+ "%{public}@ [Splombo] No need to remove Splat (no Splat)"
+ "%{public}@ adjusting configuration: %@"
+ "%{public}@ decremented the number of pending operations (%d): %@ (%@) has ended"
+ "%{public}@ delegate does not respond to selector(downloadProgress:) so not reporting progress=%@"
+ "%{public}@ delegate does not respond to selector(downloadStalled:) so not reporting progress=%@"
+ "%{public}@ delegate does not respond to selector(downloaded:) so not reporting progress=%@"
+ "%{public}@ delegate does not respond to selector(downloadedFailed:) so not reporting error=%@"
+ "%{public}@ delegate does not respond to selector(updateRemoveFailed:) so not reporting error=%@"
+ "%{public}@ delegate does not respond to selector(updateRemoved) so not reporting updateRemoved"
+ "%{public}@ ignore MANonUserInitiatedDownloadsAllowed for testing"
+ "%{public}@ incremented the number of pending operations (%d): %@ (%@) has begun"
+ "2.3.0"
+ "[SUCoreUpdateDownloader] init: failed to create the FSM"
+ "[SUCoreUpdateDownloader] init: invalid param, update and updateUUID must be nonnull"
+ "[SUCoreUpdateDownloader] init: invalid udpate descriptor, descriptor type (%ld) invalid"
+ "[SUCoreUpdateDownloader] init: invalid udpate descriptor, descriptor type of splat (%ld) invalid"
+ "[SUCoreUpdateDownloader] init: not creating ma for Splat"
- "2.2.0"
- "[PreSUStaging] %@"
- "[PreSUStaging] No need to remove PSUS assets (disabled)"
- "[PreSUStaging] No optional assets to download"
- "[PreSUStaging] No required assets to stage"
- "[PreSUStaging] PSUS groups to stage: %@"
- "[PreSUStaging] not staging optional assets: %@"
- "[PreSUStaging] purge after a timeout: %@"
- "[PreSUStaging] staging assets with attributes: %@"
- "[PreSUStaging] using maxAllowedPreSUStagingOptionalSize = %llu"
- "[Progress] %lld/%lld bytes downloaded; estimated speed: %.2lf MBps; estimated time remaining = %.2lf secs"
- "[Progress] Too few progress records to report"
- "[SUCoreUpdateDownloader] %{public}@"
- "[Splombo] No need to remove Splat (no Splat)"
- "adjusting configuration: %@"
- "decremented the number of pending operations (%d): %@ (%@) has ended"
- "delegate does not respond to selector(downloadProgress:) so not reporting progress=%@"
- "delegate does not respond to selector(downloadStalled:) so not reporting progress=%@"
- "delegate does not respond to selector(downloaded:) so not reporting progress=%@"
- "delegate does not respond to selector(downloadedFailed:) so not reporting error=%@"
- "delegate does not respond to selector(updateRemoveFailed:) so not reporting error=%@"
- "delegate does not respond to selector(updateRemoved) so not reporting updateRemoved"
- "ignore MANonUserInitiatedDownloadsAllowed for testing"
- "incremented the number of pending operations (%d): %@ (%@) has begun"
- "init: failed to create the FSM"
- "init: invalid param, update and updateUUID must be nonnull"
- "init: invalid udpate descriptor, descriptor type (%ld) invalid"
- "init: invalid udpate descriptor, descriptor type of splat (%ld) invalid"
- "init: not creating ma for Splat"
```
