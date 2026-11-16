## MobileAssetDaemon

> `/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/Versions/A/MobileAssetDaemon`

```diff

-2215.60.7.0.0
-  __TEXT.__text: 0x28165c
-  __TEXT.__objc_methlist: 0x12c34
+2215.60.11.0.0
+  __TEXT.__text: 0x282998
+  __TEXT.__objc_methlist: 0x12c5c
   __TEXT.__const: 0x154a
-  __TEXT.__cstring: 0x3f9e3
-  __TEXT.__oslogstring: 0x59887
-  __TEXT.__gcc_except_tab: 0xd388
+  __TEXT.__cstring: 0x3fc63
+  __TEXT.__oslogstring: 0x59b87
+  __TEXT.__gcc_except_tab: 0xd410
   __TEXT.__constg_swiftt: 0xf0
   __TEXT.__swift5_typeref: 0x146
   __TEXT.__swift5_fieldmd: 0x3c

   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_proto: 0x24
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x5990
+  __TEXT.__unwind_info: 0x59a8
   __TEXT.__eh_frame: 0x10c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1120
+  __DATA_CONST.__const: 0x1198
   __DATA_CONST.__objc_classlist: 0x490
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xae90
+  __DATA_CONST.__objc_selrefs: 0xaeb8
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x360
-  __DATA_CONST.__objc_arraydata: 0x1038
+  __DATA_CONST.__objc_arraydata: 0x1058
   __DATA_CONST.__got: 0x1210
   __AUTH_CONST.__const: 0x3340
-  __AUTH_CONST.__cfstring: 0x33100
+  __AUTH_CONST.__cfstring: 0x333a0
   __AUTH_CONST.__objc_const: 0x18db0
-  __AUTH_CONST.__objc_arrayobj: 0x390
+  __AUTH_CONST.__objc_arrayobj: 0x3c0
   __AUTH_CONST.__objc_intobj: 0x13b0
   __AUTH_CONST.__objc_dictobj: 0x2d0
-  __AUTH_CONST.__auth_got: 0x1168
+  __AUTH_CONST.__auth_got: 0x1170
   __AUTH.__objc_data: 0x878
   __AUTH.__data: 0xc0
   __DATA.__objc_ivar: 0x17fc

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7393
-  Symbols:   16475
-  CStrings:  10974
+  Functions: 7398
+  Symbols:   16486
+  CStrings:  10999
 
Symbols:
+ +[MADAutoAssetAuthorizationPolicy _accessibleAssetTypesContainSoftwareUpdateAssetType:]
+ +[MADAutoAssetAuthorizationPolicy _assetTypes:authorizedForAccessibleAssetTypes:]
+ +[MADAutoAssetAuthorizationPolicy authorizationAssetTypesFromMessage:alreadyOnStateQueue:]
+ +[MADAutoAssetSecure isPersonalized:forDescriptor:]
+ _IOServiceGetMatchingServices
+ __copyPCIID
+ _objc_msgSend$_accessibleAssetTypesContainSoftwareUpdateAssetType:
+ _objc_msgSend$_assetTypes:authorizedForAccessibleAssetTypes:
+ _objc_msgSend$assetProperties
+ _objc_msgSend$authorizationAssetTypesFromMessage:alreadyOnStateQueue:
+ _objc_msgSend$isPersonalized:forDescriptor:
+ _objc_msgSend$typeDescriptor
- GCC_except_table36
CStrings:
+ "%@:isPersonalized"
+ "; the stage-target-all sentinel needs a software-update asset type"
+ "AssetBundle"
+ "Compatibility versions mismatch"
+ "CryptexCompatibilityVersion"
+ "CryptexInfo %@ key is missing required %@ key."
+ "CryptexInfo plist is missing required %@ key."
+ "FizzCSeed"
+ "Guardrail framework does not have a valid on-disk type descriptor."
+ "Guardrail framework's type descriptor is missing required %@ key."
+ "IOPCIDevice"
+ "Loaded built-in MobileAssetDaemon_Framework Nov 10 2026 05:22:55"
+ "MAAutoAssetStage-target-all-asset-types"
+ "RegionCodeCompatibilityVersion"
+ "SystemCompatibilityVersion"
+ "VMAICapability"
+ "VMAICapabilityPreference"
+ "com.apple.MobileAsset.CN.Guardrail"
+ "com.apple.MobileAsset.CN.GuardrailFramework"
+ "device-id"
+ "pvane"
+ "pvcoreai"
+ "vendor-id"
+ "{DecideNeedPersonalize} [singleton] newer asset-version already personalized, not personalizing older | assetType:%{public}@ | assetSpecifier:%{public}@ | assetVersion:%{public}@ | personalizedVersion:%{public}@"
+ "{_assetTypes:authorizedForAccessibleAssetTypes:} accessible-asset-types entitlement is %{public}@, expected an array | assetType:%{public}@"
+ "{_assetTypes:authorizedForAccessibleAssetTypes:} asset type not covered by accessible-asset-types entitlement (exact entry or com.apple.MobileAsset.<prefix>.* wildcard)%{public}@ | assetType:%{public}@, accessibleAssetTypes:%{public}@"
+ "{authorizationAssetTypesFromMessage} Found asset types: %{public}@, for message: %{public}@"
+ "{authorizationAssetTypesFromMessage} Found multiple asset types (not formally supported): %{public}@, for message: %{public}@, authorizing all of them"
+ "{isConnection:authorizedForMessage:}(%{public}@) Client does not have all requested asset types: %{public}@ (found: %{public}@)"
+ "{isConnection:authorizedForMessage:}(%{public}@) Ignoring bypass entitlement of unexpected type: %{public}@ (expected a BOOL or a string)"
- "FizzSeedUpdate"
- "Loaded built-in MobileAssetDaemon_Framework Oct 29 2026 04:15:39"
- "{authorizationAssetTypeFromMessage} Found asset type: %{public}@, for message: %{public}@"
- "{authorizationAssetTypeFromMessage} Found multiple asset types: %{public}@, for message: %{public}@, using first asset type found"
- "{isConnection:authorizedForMessage:}(%{public}@) Client does not have requested asset type: %@ (found: %@)"
```
