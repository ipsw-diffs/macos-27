## AUSettings

> `/System/Library/PrivateFrameworks/AUSettings.framework/Versions/A/AUSettings`

```diff

-1587.40.33.0.0
-  __TEXT.__text: 0x74c4
-  __TEXT.__objc_methlist: 0x86c
+1587.60.11.0.0
+  __TEXT.__text: 0x791c
+  __TEXT.__objc_methlist: 0x88c
   __TEXT.__const: 0xa0
-  __TEXT.__cstring: 0xf10
-  __TEXT.__oslogstring: 0x24b
+  __TEXT.__cstring: 0x100a
+  __TEXT.__oslogstring: 0x2c1
   __TEXT.__gcc_except_tab: 0x28
-  __TEXT.__unwind_info: 0x2f8
+  __TEXT.__unwind_info: 0x308
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x530
+  __DATA_CONST.__const: 0x550
   __DATA_CONST.__objc_classlist: 0x28
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x618
+  __DATA_CONST.__objc_selrefs: 0x630
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x28
   __DATA_CONST.__got: 0xd0
   __AUTH_CONST.__const: 0x230
-  __AUTH_CONST.__cfstring: 0xfa0
+  __AUTH_CONST.__cfstring: 0xfe0
   __AUTH_CONST.__objc_const: 0x12d0
+  __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0xa0
   __DATA.__objc_ivar: 0xa0

   - /System/Library/PrivateFrameworks/CoreUARP.framework/Versions/A/CoreUARP
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 203
-  Symbols:   644
-  CStrings:  183
+  Functions: 208
+  Symbols:   653
+  CStrings:  192
 
Symbols:
+ -[AUDeveloperSettingsDatabase copyAccessoryGroupForAccessory:]
+ -[AUDeveloperSettingsDatabase isValidPallasAudience:]
+ -[AUDeveloperSettingsDatabase updateAccessory:pallasAudience:]
+ _OBJC_CLASS_$_NSConstantIntegerNumber
+ _OUTLINED_FUNCTION_3
+ ___kCFBooleanTrue
+ _kAUSettingsLocationPallasAirPodsDeveloperSeed
+ _kAUSettingsLocationPallasAirPodsPublicSeed
+ _objc_msgSend$copyAccessoryGroupForAccessory:
+ _objc_msgSend$isValidPallasAudience:
- ___kCFBooleanFalse
CStrings:
+ "%s: Ignoring unsupported pallas audience %lu"
+ "%s: Updating pallas audience = %{public}@ for accessoryName = %{public}@"
+ "-[AUDeveloperSettingsDatabase copyAccessoryGroupForAccessory:]"
+ "-[AUDeveloperSettingsDatabase updateAccessory:pallasAudience:]"
+ "AIRPODS_DEVELOPER_SEED_AUDIENCE"
+ "AIRPODS_PUBLIC_SEED_AUDIENCE"
+ "AirPods Developer Seed Audience"
+ "AirPods Public Seed Audience"
+ "Q"
```
