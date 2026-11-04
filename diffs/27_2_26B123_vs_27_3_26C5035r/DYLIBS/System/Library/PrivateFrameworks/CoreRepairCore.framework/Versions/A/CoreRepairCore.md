## CoreRepairCore

> `/System/Library/PrivateFrameworks/CoreRepairCore.framework/Versions/A/CoreRepairCore`

```diff

-1307.40.66.0.0
-  __TEXT.__text: 0x7e5b8
-  __TEXT.__objc_methlist: 0x44c4
+1307.60.20.0.0
+  __TEXT.__text: 0x85c78
+  __TEXT.__objc_methlist: 0x472c
   __TEXT.__const: 0x886
-  __TEXT.__cstring: 0x61c1
-  __TEXT.__oslogstring: 0x9652
-  __TEXT.__gcc_except_tab: 0x1610
-  __TEXT.__unwind_info: 0x2108
+  __TEXT.__cstring: 0x6982
+  __TEXT.__oslogstring: 0xa0f1
+  __TEXT.__gcc_except_tab: 0x1984
+  __TEXT.__unwind_info: 0x2308
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x268
-  __DATA_CONST.__objc_classlist: 0x2c0
+  __DATA_CONST.__objc_classlist: 0x2e0
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2898
+  __DATA_CONST.__objc_selrefs: 0x2988
   __DATA_CONST.__objc_protorefs: 0x30
-  __DATA_CONST.__objc_superrefs: 0x1b0
-  __DATA_CONST.__objc_arraydata: 0x630
-  __DATA_CONST.__got: 0x530
-  __AUTH_CONST.__const: 0x11e0
-  __AUTH_CONST.__cfstring: 0x7380
-  __AUTH_CONST.__objc_const: 0x64a8
-  __AUTH_CONST.__objc_intobj: 0x378
-  __AUTH_CONST.__objc_dictobj: 0x190
-  __AUTH_CONST.__objc_arrayobj: 0x450
-  __AUTH_CONST.__auth_got: 0xa68
-  __AUTH.__objc_data: 0x12c0
-  __DATA.__objc_ivar: 0x3b4
+  __DATA_CONST.__objc_superrefs: 0x1c8
+  __DATA_CONST.__objc_arraydata: 0x7b8
+  __DATA_CONST.__got: 0x578
+  __AUTH_CONST.__const: 0x1310
+  __AUTH_CONST.__cfstring: 0x7980
+  __AUTH_CONST.__objc_const: 0x6740
+  __AUTH_CONST.__objc_intobj: 0x3a8
+  __AUTH_CONST.__objc_dictobj: 0x320
+  __AUTH_CONST.__objc_arrayobj: 0x528
+  __AUTH_CONST.__auth_got: 0xad8
+  __AUTH.__objc_data: 0x1400
+  __DATA.__objc_ivar: 0x3bc
   __DATA.__data: 0x658
-  __DATA.__bss: 0x180
+  __DATA.__bss: 0x1d8
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0x8c0
-  __DATA_DIRTY.__bss: 0x180
+  __DATA_DIRTY.__bss: 0x190
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit

   - /usr/lib/libauthinstall.dylib
   - /usr/lib/libimage4.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2490
-  Symbols:   594
-  CStrings:  2218
+  Functions: 2601
+  Symbols:   617
+  CStrings:  2363
 
Symbols:
+ _AMSupportLogInternal
+ _CFAbsoluteTimeGetCurrent
+ _IOMobileFramebufferGetBlock
+ _IOMobileFramebufferGetMainDisplay
+ _IOServiceNameMatching
+ _OBJC_CLASS_$_CRDisplayController
+ _OBJC_CLASS_$_SPINANDClient
+ _OBJC_METACLASS_$_CRDisplayController
+ _SecCertificateCreateWithData
+ _displayAuthCloseSession
+ _displayAuthOpenSession
+ _displayAuthRefreshAccessState
+ _displayAuthUserNVMRead
+ _displayAuthUserNVMWrite
+ _kMAOptionsBAACertType
+ _kMAOptionsBAACertTypeMFi
+ _kMAOptionsBAAMFiProperties
+ _kMAOptionsBAAOIDMFiAccessoryProperties
+ _kMAOptionsBAAValidity
+ _notify_cancel
+ _notify_post
+ _notify_register_check
+ _notify_set_state
CStrings:
+ "  max: %4d %4d %4d"
+ "  med: %4d %4d %4d"
+ "  min: %4d %4d %4d"
+ "%@: %@"
+ "%s called"
+ "+[CRDisplayController getMFiCertWithOptions:certificateChain:keyBlob:error:]"
+ "+[CRDisplayController issueMFiCertWithOptions:certificateChain:keyBlob:error:]"
+ "+[CRDisplayController readBIMValuesWithOptions:error:]"
+ "/usr/lib/updaters/libVelozUpdater.dylib"
+ "ACCHWComponentAuthService"
+ "AppleGasGaugeBeadsUpdate"
+ "BICS proc_state:  %d"
+ "BICS state block version %d unsupported"
+ "BIM stats"
+ "BMFVersion"
+ "Battery FW version dict: %@"
+ "Breadcrumb ECID match"
+ "Breadcrumb ECID mismatch"
+ "Breadcrumb: %@"
+ "Burn in metric read time out after %d seconds"
+ "Burn in metric version %d unsupported"
+ "C API: Received response from ACCHWComponentAuth, authError is %x"
+ "Cached MFi cert has expired (TTL: %.0f s). Invalidating cache and requesting fresh cert."
+ "Cached MFi cert near end of validity (remaining: %.0f s). Attempting refresh..."
+ "Challenge %@ failed"
+ "Cleared cached MFi cert and key blob from group defaults"
+ "ConfigBaseID"
+ "CoreRepairLTH"
+ "Could not access group defaults for caching MFi cert"
+ "DNVD1Bank1ID"
+ "DNVD2Bank1ID"
+ "Display Auth API not available"
+ "Exception reading MFi cert cache from defaults: %@"
+ "Failed to clear MFi cert from group defaults: %@"
+ "Failed to create SecCertificateRef from leaf certificate"
+ "Failed to get LTH key state with initial cert: %@"
+ "Failed to get LTH key state: %@"
+ "Failed to get battery FW version info, error: %@"
+ "Failed to get framebuffer ref from main display, with error: 0x%x"
+ "Failed to get keyBlob"
+ "Failed to load libVelozUpdater"
+ "Failed to obtain MFi cert for readBreadcrumbECID: %@"
+ "Failed to obtain MFi cert when checking LTH key: %@"
+ "Failed to open Veloz updater dylib"
+ "Failed to parse certificate set: %d"
+ "Failed to parse certificate set: 0x%08x"
+ "Failed to read Area51 breadcrumb ECID: %@"
+ "Failed to request MFi cert: %@"
+ "Failed to resolve Veloz symbols"
+ "Failed to retrieve unique chip ID from MobileGestalt"
+ "Failed to save MFi cert to group defaults: %@"
+ "GpCD"
+ "GracePeriod"
+ "Instantiating CRVelozUpdater"
+ "Invalid breadcrumb magic: 0x%x"
+ "Invalid breadcrumb size or empty breadcrumb"
+ "Invalid breadcrumb size: %lu"
+ "Invalid breadcrumb size: %zu"
+ "Invalid cert count: %lu"
+ "Invalid parameter"
+ "LTH key state matched: %d"
+ "LTH matched: %@. unlocked: %@"
+ "MFi cert cache expired or near expiration (remaining TTL: %.0f s). Refreshing..."
+ "MFi cert cache is healthy (remaining TTL: %.0f s). No refresh needed."
+ "MFi cert cache missing. Attempting to fetch..."
+ "No breadcrumb"
+ "No certificates returned"
+ "No custom identity"
+ "No resource"
+ "No session"
+ "Parse certificate chain failed"
+ "Query UniqueChipID failed"
+ "Refresh failed (%@), falling back to valid cached cert (remaining: %.0f s)."
+ "Requesting MFi cert with validity: %@ minutes"
+ "RequireLTHMigration"
+ "Retrying lthKeyState with fresh MFi cert..."
+ "SPINANDClient is not available."
+ "Successfully cached MFi cert chain and key blob in group defaults"
+ "Successfully refreshed MFi cert near end of validity."
+ "Unable to get claim dataClass tcrt, error: %@"
+ "Unable to get claim dataClass vcrt, error: %@"
+ "Unable to read Area51 identifier:%@"
+ "Underlying battery controller is Veloz"
+ "Using valid cached MFi cert (remaining TTL: %.0f s)."
+ "Veloz"
+ "VelozGetBoardIdFromDT"
+ "VelozUpdaterCopyFirmwareWithLogging"
+ "VelozUpdaterCreate"
+ "VelozUpdaterCreate failed"
+ "VelozUpdaterCreateRequestWithLogging"
+ "VelozUpdaterExecCommand"
+ "VelozUpdaterGetInfo is not supported or missing arguments"
+ "VelozUpdaterIsDone"
+ "[%s] options: %{public}@"
+ "_createError"
+ "_lthReadBreadcrumb"
+ "_openSession"
+ "area51 requires outDeviceNonce"
+ "burn in metric read failed [%X]."
+ "cachedMFiCertificateChain"
+ "cachedMFiKeyBlob"
+ "certificateChain and keyBlob must both be present or both be nil"
+ "challenge is NULL"
+ "challenge too short: %lu"
+ "com.apple.mobilerepair.graceupdate"
+ "dLTH"
+ "dLTH key check timed out"
+ "dLTH key read failed or unexpected, error: %@"
+ "dLTH key size check failed: %@"
+ "dLTH key size: %d"
+ "dLTH read timed out"
+ "displayAuthOpenSession failed"
+ "displayAuthRefreshAccessState"
+ "displayAuthRefreshAccessState failed"
+ "displayAuthUserNVMRead failed"
+ "drLTH ECID match: 0x%llx"
+ "drLTH ECID mismatch, expected: 0x%llx, actual: 0x%llx"
+ "drLTH does not exist"
+ "drLTH header version: %d"
+ "drLTH unsupported version: %d, assuming v1 layout"
+ "forceRefresh"
+ "found area51: %d"
+ "isVelozUpdateRequired"
+ "lthKeyMatch failed: %@"
+ "lthKeyMatch timed out after %d s"
+ "lthKeyState"
+ "lthLockState"
+ "lthReadBreadcrumb failed"
+ "lthReadBreadcrumbECID"
+ "lthUnlocked failed: %@"
+ "notify_post failed with status: %u"
+ "notify_register_check failed with status: %u"
+ "notify_set_state failed with status: %u"
+ "openSession failed"
+ "queryInfo"
+ "screenOnTime and maxTime must not be nil"
+ "screenOnTime or maxTime is nil."
+ "screenOnTime: %@ maxTime: %@"
+ "seacookieLTH"
+ "signArea51Display"
+ "smc-area51"
+ "timeout"
+ "v20@?0I8@\"NSError\"12"
+ "v24@?0@\"NSData\"8@\"NSError\"16"
+ "validity"
```
