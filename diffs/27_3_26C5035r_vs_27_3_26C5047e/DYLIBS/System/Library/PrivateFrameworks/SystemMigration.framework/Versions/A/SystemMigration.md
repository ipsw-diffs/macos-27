## SystemMigration

> `/System/Library/PrivateFrameworks/SystemMigration.framework/Versions/A/SystemMigration`

```diff

-6164.60.5.0.0
-  __TEXT.__text: 0xfe4e4
-  __TEXT.__objc_methlist: 0x109e8
+6164.60.7.0.0
+  __TEXT.__text: 0xff8c8
+  __TEXT.__objc_methlist: 0x10c10
   __TEXT.__const: 0x214
   __TEXT.__gcc_except_tab: 0x3c10
-  __TEXT.__cstring: 0x23bfa
+  __TEXT.__cstring: 0x23f1a
   __TEXT.__oslogstring: 0x402
   __TEXT.__ustring: 0x147c
   __TEXT.__constg_swiftt: 0x8c
   __TEXT.__swift5_typeref: 0x1a
   __TEXT.__swift5_fieldmd: 0x20
   __TEXT.__swift5_types: 0x8
-  __TEXT.__unwind_info: 0x3cf0
+  __TEXT.__unwind_info: 0x3d58
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0xd50
-  __DATA_CONST.__objc_classlist: 0x5e8
+  __DATA_CONST.__objc_classlist: 0x5f0
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x188
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x85e8
+  __DATA_CONST.__objc_selrefs: 0x8730
   __DATA_CONST.__objc_protorefs: 0x88
-  __DATA_CONST.__objc_superrefs: 0x4b0
+  __DATA_CONST.__objc_superrefs: 0x4b8
   __DATA_CONST.__objc_arraydata: 0x778
-  __DATA_CONST.__got: 0xed0
-  __AUTH_CONST.__const: 0x1bd0
-  __AUTH_CONST.__cfstring: 0x19c80
-  __AUTH_CONST.__objc_const: 0x17558
-  __AUTH_CONST.__objc_intobj: 0x780
+  __DATA_CONST.__got: 0xee0
+  __AUTH_CONST.__const: 0x1bf0
+  __AUTH_CONST.__cfstring: 0x19ee0
+  __AUTH_CONST.__objc_const: 0x178a0
+  __AUTH_CONST.__objc_intobj: 0x738
   __AUTH_CONST.__objc_arrayobj: 0x438
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0x9a0
-  __AUTH.__objc_data: 0x3ab0
+  __AUTH_CONST.__auth_got: 0x9d0
+  __AUTH.__objc_data: 0x3b00
   __AUTH.__data: 0x98
-  __DATA.__objc_ivar: 0x12ac
-  __DATA.__data: 0x1310
-  __DATA.__bss: 0x158
+  __DATA.__objc_ivar: 0x12dc
+  __DATA.__data: 0x1318
+  __DATA.__bss: 0x160
   __DATA.__common: 0x28
   __DATA_DIRTY.__objc_data: 0x78
   __DATA_DIRTY.__data: 0x28

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5709
-  Symbols:   13210
-  CStrings:  4071
+  Functions: 5754
+  Symbols:   13323
+  CStrings:  4089
 
Symbols:
+ +[SMWindowsMacPathMapper diskNameOfReceptacleNamed:]
+ +[SMWindowsUtilities getOwnerOfItemAtPath:uid:gid:]
+ +[SMWindowsUtilities getOwnerOfUser:uid:gid:]
+ +[SMWindowsUtilities getSharedContentOwnerForRequest:contextUser:uid:gid:]
+ +[SMWindowsUtilities isItemAtURL:belowRoot:includingRoot:]
+ +[SMWindowsUtilities staffGroupID]
+ -[SMCopyEngineWindowsCopier copyAction:attributesForNewItemAtURL:forFile:isDirectory:]
+ -[SMCopyEngineWindowsCopier copyAction:shouldWriteFile:toURL:]
+ -[SMCopyEngineWindowsCopier ownedRootOfDomainOfXMURLString:reason:]
+ -[SMCopyEngineWindowsCopier ownershipByDomain]
+ -[SMCopyEngineWindowsCopier resolveOwnershipOfXMURLString:]
+ -[SMCopyEngineWindowsCopier setOwnershipByDomain:]
+ -[SMCopyEngineWindowsCopier userDictionaryForWindowsName:]
+ -[SMCopyEngineWindowsPathCopier copyAction:attributesForNewItemAtURL:forFile:isDirectory:]
+ -[SMCopyEngineWindowsPathCopier ownership]
+ -[SMCopyEngineWindowsPathCopier resolveOwnership]
+ -[SMCopyEngineWindowsPathCopier setOwnership:]
+ -[SMCopyEngineWindowsPathCopier setSourceUserDictionary:]
+ -[SMCopyEngineWindowsPathCopier sourceUserDictionary]
+ -[SMDPairing_XPCClientConnection discoverySession]
+ -[SMDPairing_XPCClientConnection setDiscoverySession:]
+ -[SMDSystemScanner_XPCClientConnection discoverySession]
+ -[SMDSystemScanner_XPCClientConnection requestScannerState:]
+ -[SMDSystemScanner_XPCClientConnection setDiscoverySession:]
+ -[SMDXPCClientConnection beginDiscoverySessionUnlessRunLoaded]
+ -[SMMacUser_Client isPlatformSSOTemporaryUser]
+ -[SMMacUser_Client setIsPlatformSSOTemporaryUser:]
+ -[SMMacUser_Daemon isPlatformSSOTemporaryUser]
+ -[SMPaths platformBinariesAmongOutOfBandCollisions]
+ -[SMTelemetryHandler endDiscoverySession:]
+ -[SMTelemetryHandler lastDiscoverySession]
+ -[SMTelemetryHandler openDiscoverySession]
+ -[SMTelemetryHandler sendPayloadDictionary:]
+ -[SMTelemetryHandler setLastDiscoverySession:]
+ -[SMTelemetryHandler setOpenDiscoverySession:]
+ -[SMUser isPlatformSSOTemporaryUser]
+ -[SMWindowsMacPathMapper encodedDomainForXMURLString:]
+ -[SMWindowsMigrateComponentStep finishAfterCopy]
+ -[SMWindowsMigrateComponentStep finishReceptacleAtURL:localizedName:]
+ -[SMWindowsMigrateComponentStep localizeReceptacle:named:localizedName:]
+ -[SMWindowsMigrateOtherComponentsStep finishAfterCopy]
+ -[SMWindowsMigrateSystemComponentsStep finishAfterCopy]
+ -[SMWindowsOwnedRoot .cxx_destruct]
+ -[SMWindowsOwnedRoot attributesForItemAtURL:isDirectory:]
+ -[SMWindowsOwnedRoot gid]
+ -[SMWindowsOwnedRoot includesRoot]
+ -[SMWindowsOwnedRoot initWithRoot:uid:gid:includingRoot:]
+ -[SMWindowsOwnedRoot root]
+ -[SMWindowsOwnedRoot uid]
+ GCC_except_table54
+ GCC_except_table72
+ GCC_except_table80
+ GCC_except_table83
+ _OBJC_CLASS_$_SMWindowsOwnedRoot
+ _OBJC_CLASS_$_XMArchiveStream
+ _OBJC_IVAR_$_SMCopyEngineWindowsCopier._ownershipByDomain
+ _OBJC_IVAR_$_SMCopyEngineWindowsPathCopier._ownership
+ _OBJC_IVAR_$_SMCopyEngineWindowsPathCopier._sourceUserDictionary
+ _OBJC_IVAR_$_SMDPairing_XPCClientConnection._discoverySession
+ _OBJC_IVAR_$_SMDSystemScanner_XPCClientConnection._discoverySession
+ _OBJC_IVAR_$_SMMacUser_Client.isPlatformSSOTemporaryUser
+ _OBJC_IVAR_$_SMTelemetryHandler._lastDiscoverySession
+ _OBJC_IVAR_$_SMTelemetryHandler._openDiscoverySession
+ _OBJC_IVAR_$_SMUser._isPlatformSSOTemporaryUser
+ _OBJC_IVAR_$_SMWindowsOwnedRoot._gid
+ _OBJC_IVAR_$_SMWindowsOwnedRoot._includesRoot
+ _OBJC_IVAR_$_SMWindowsOwnedRoot._root
+ _OBJC_IVAR_$_SMWindowsOwnedRoot._uid
+ _OBJC_METACLASS_$_SMWindowsOwnedRoot
+ __OBJC_$_INSTANCE_METHODS_SMWindowsOwnedRoot
+ __OBJC_$_INSTANCE_VARIABLES_SMDSystemScanner_XPCClientConnection
+ __OBJC_$_INSTANCE_VARIABLES_SMWindowsOwnedRoot
+ __OBJC_$_PROP_LIST_SMWindowsOwnedRoot
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SMNWindowsCopyPathActionDelegate
+ __OBJC_$_PROTOCOL_REFS_SMNWindowsCopyPathActionDelegate
+ __OBJC_CLASS_RO_$_SMWindowsOwnedRoot
+ __OBJC_METACLASS_RO_$_SMWindowsOwnedRoot
+ ___34+[SMWindowsUtilities staffGroupID]_block_invoke
+ _fchmod
+ _fchown
+ _ftruncate
+ _getgrnam
+ _mkdirat
+ _objc_msgSend$SM_pathLooksLikeMachO
+ _objc_msgSend$attributeFailureCount
+ _objc_msgSend$attributedCount
+ _objc_msgSend$attributesForItemAtURL:isDirectory:
+ _objc_msgSend$beginDiscoverySessionUnlessRunLoaded
+ _objc_msgSend$discoverySession
+ _objc_msgSend$diskNameOfReceptacleNamed:
+ _objc_msgSend$encodedDomainForXMURLString:
+ _objc_msgSend$endDiscoverySession:
+ _objc_msgSend$finishAfterCopy
+ _objc_msgSend$finishReceptacleAtURL:localizedName:
+ _objc_msgSend$getOwnerOfItemAtPath:uid:gid:
+ _objc_msgSend$getOwnerOfUser:uid:gid:
+ _objc_msgSend$getSharedContentOwnerForRequest:contextUser:uid:gid:
+ _objc_msgSend$hasDirectoryPath
+ _objc_msgSend$includesRoot
+ _objc_msgSend$initWithRoot:uid:gid:includingRoot:
+ _objc_msgSend$isDirectory
+ _objc_msgSend$isItemAtURL:belowRoot:includingRoot:
+ _objc_msgSend$isPlatformSSOTemporaryUser
+ _objc_msgSend$localConnectionMethod
+ _objc_msgSend$localizeReceptacle:named:localizedName:
+ _objc_msgSend$ownedRootOfDomainOfXMURLString:reason:
+ _objc_msgSend$ownership
+ _objc_msgSend$ownershipByDomain
+ _objc_msgSend$path:isContainedInRoot:
+ _objc_msgSend$pathNamingRealSystemFolder:
+ _objc_msgSend$platformBinariesAmongOutOfBandCollisions
+ _objc_msgSend$resolveOwnership
+ _objc_msgSend$resolveOwnershipOfXMURLString:
+ _objc_msgSend$sendPayloadDictionary:
+ _objc_msgSend$setDiscoverySession:
+ _objc_msgSend$setOwnership:
+ _objc_msgSend$setOwnershipByDomain:
+ _objc_msgSend$setSourceUserDictionary:
+ _objc_msgSend$skippedCount
+ _objc_msgSend$sourceUserDictionary
+ _objc_msgSend$staffGroupID
+ _objc_msgSend$userDictionaryForWindowsName:
+ _objc_msgSend$writeCompletelyToFd:buffer:length:
+ _openat
+ _staffGroupID.once
+ _staffGroupID.staffGID
- +[SMWindowsUtilities setAttributesOnDirectory:deepEnumeration:attributes:error:]
- -[SMCopyEngineWindowsCopier createLocalizedDirectoryAtPath:localizedName:attributes:error:]
- -[SMTelemetryHandler didFlushDiscoverySnapshot]
- -[SMTelemetryHandler flushDiscoverySnapshotIfNeeded]
- -[SMTelemetryHandler setDidFlushDiscoverySnapshot:]
- -[SMWindowsMigrateFilesStep copierSuceeded:]
- GCC_except_table55
- GCC_except_table71
- GCC_except_table79
- _OBJC_IVAR_$_SMTelemetryHandler._didFlushDiscoverySnapshot
- _objc_msgSend$createLocalizedDirectoryAtPath:localizedName:attributes:error:
- _objc_msgSend$flushDiscoverySnapshotIfNeeded
- _objc_msgSend$setAttributesOnDirectory:deepEnumeration:attributes:error:
CStrings:
+ "-[SMCopyEngineWindowsCopier copyAction:shouldWriteFile:toURL:]"
+ "-[SMCopyEngineWindowsCopier resolveOwnershipOfXMURLString:]"
+ "-[SMPaths platformBinariesAmongOutOfBandCollisions]"
+ "-[SMTelemetryHandler sendPayloadDictionary:]"
+ "-[SMWindowsMigrateComponentStep finishReceptacleAtURL:localizedName:]"
+ ".."
+ "Failed to create localized directory: %@ - %@: %s"
+ "Found a Platform SSO temporary account, not adding to view"
+ "MISSING (source copy only)"
+ "Ownership: %@ attributed %lu, failed %lu, skipped %lu"
+ "Ownership: domain %@ is refused: %@"
+ "Ownership: domain %@: items below %@ get %u:%u (%@)"
+ "Ownership: finished %@: folder %u:%u %o"
+ "Refusing %@ at %@: outside its domain"
+ "Unable to get the attributes of /Users/Shared: %s"
+ "Unable to give %@ the attributes of /Users/Shared: %s"
+ "Unable to open %@: %s"
+ "[SMPaths] Found %lu system files after out-of-band adjustment"
+ "[SMPaths] No source root available; skipping platform binary protection for %lu colliding paths"
+ "[SMPaths] Not protecting %@"
+ "[SMPaths] Platform binary protection: %lu colliding paths (%lu directories skipped), %lu signature checks, %lu protected, template root %@"
+ "[SMPaths] Protecting platform binary from out-of-band demotion: %@"
+ "an empty, \".\" or \"..\" user name"
+ "dsAttrTypeNative:PlatformSSOTemporaryUser"
+ "isPlatformSSOTemporaryUser"
+ "localized"
+ "migrated user"
+ "no migrated account and no live folder, so root"
+ "no migrated account, so the owner of the live folder"
+ "not a user, shared or disk domain"
+ "resolved"
+ "the Shared content rule"
- "+[SMWindowsUtilities setAttributesOnDirectory:deepEnumeration:attributes:error:]"
- "-[SMCopyEngineWindowsCopier copyPathForXMURLString:sandboxed:]"
- "-[SMTelemetryHandler sendEvent]"
- "-[SMWindowsMigrateFilesStep copierSuceeded:]"
- "-[SMWindowsMigrateOtherComponentsStep process]"
- "-[SMWindowsMigrateSystemComponentsStep process]"
- "-[SMWindowsMigrateUserComponentsStep process]"
- "Could not get path for file: %@: %@"
- "Could not set attributes for %@: %@"
- "Failed to create localized directory: %@ - %@: %@"
- "Unable to change permissions for path %@: %@"
- "Unable to fix permissions for shared item %@: %@"
- "Unable to fix permissions for user's home %@: %@"
- "Unable to get the attributes of /Users/Shared: %@"
```
