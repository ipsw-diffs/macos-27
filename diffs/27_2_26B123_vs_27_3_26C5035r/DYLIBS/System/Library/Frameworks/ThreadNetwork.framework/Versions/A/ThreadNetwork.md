## ThreadNetwork

> `/System/Library/Frameworks/ThreadNetwork.framework/Versions/A/ThreadNetwork`

```diff

-446.0.5.0.0
-  __TEXT.__text: 0xf7c8
-  __TEXT.__objc_methlist: 0xe18
+447.0.1.0.0
+  __TEXT.__text: 0x10938
+  __TEXT.__objc_methlist: 0xe98
   __TEXT.__const: 0xb8
-  __TEXT.__cstring: 0x1931
+  __TEXT.__cstring: 0x1b3f
   __TEXT.__oslogstring: 0xc8f
   __TEXT.__gcc_except_tab: 0x190
-  __TEXT.__unwind_info: 0x590
+  __TEXT.__unwind_info: 0x5f8
+  __TEXT.__eh_frame: 0x108
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x80
-  __DATA_CONST.__objc_classlist: 0x60
+  __DATA_CONST.__objc_classlist: 0x68
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x840
+  __DATA_CONST.__objc_selrefs: 0x880
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0x58
-  __DATA_CONST.__got: 0x138
-  __AUTH_CONST.__const: 0x600
-  __AUTH_CONST.__cfstring: 0x8a0
-  __AUTH_CONST.__objc_const: 0x1be8
-  __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0xa0
-  __DATA.__objc_ivar: 0xfc
+  __DATA_CONST.__objc_superrefs: 0x60
+  __DATA_CONST.__got: 0x140
+  __AUTH_CONST.__const: 0x630
+  __AUTH_CONST.__cfstring: 0x8c0
+  __AUTH_CONST.__objc_const: 0x1cb8
+  __AUTH_CONST.__auth_got: 0x220
+  __AUTH.__objc_data: 0xf0
+  __DATA.__objc_ivar: 0x100
   __DATA.__data: 0x130
-  __DATA.__bss: 0x28
+  __DATA.__bss: 0x50
   __DATA_DIRTY.__objc_data: 0x320
   __DATA_DIRTY.__bss: 0x50
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libTelephonyUtilDynamic.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 400
-  Symbols:   881
-  CStrings:  237
+  Functions: 420
+  Symbols:   930
+  CStrings:  256
 
Symbols:
+ +[THNearbyNetworkCredentials supportsSecureCoding]
+ -[THClient handleActiveNearbyNetworksResponse:preferredNetworkRecord:error:apiName:isInternal:nearbyType:completion:]
+ -[THClient retrieveNearbyNetworkCredentialsInternallyWithCompletion:]
+ -[THClient retrieveNearbyNetworkCredentialsWithCompletion:]
+ -[THNearbyNetworkCredentials encodeWithCoder:]
+ -[THNearbyNetworkCredentials initThreadCredentials:extendedPANID:borderAgentID:activeOperationalDataSet:PSKC:networkKey:channel:panID:creationDate:lastModificationDate:isPreferredNetworkCredentials:]
+ -[THNearbyNetworkCredentials initThreadCredentials:isPreferredNetworkCredentials:]
+ -[THNearbyNetworkCredentials initWithActiveDataSetRecord:isPreferredNetworkCredentials:]
+ -[THNearbyNetworkCredentials initWithCoder:]
+ -[THNearbyNetworkCredentials isPreferredNetworkCredentials]
+ _OBJC_CLASS_$_THNearbyNetworkCredentials
+ _OBJC_IVAR_$_THNearbyNetworkCredentials._isPreferredNetworkCredentials
+ _OBJC_METACLASS_$_THNearbyNetworkCredentials
+ __MergedGlobals
+ __OBJC_$_CLASS_METHODS_THNearbyNetworkCredentials
+ __OBJC_$_INSTANCE_METHODS_THNearbyNetworkCredentials
+ __OBJC_$_INSTANCE_VARIABLES_THNearbyNetworkCredentials
+ __OBJC_$_PROP_LIST_THNearbyNetworkCredentials
+ __OBJC_CLASS_RO_$_THNearbyNetworkCredentials
+ __OBJC_METACLASS_RO_$_THNearbyNetworkCredentials
+ ___59-[THClient retrieveNearbyNetworkCredentialsWithCompletion:]_block_invoke
+ ___59-[THClient retrieveNearbyNetworkCredentialsWithCompletion:]_block_invoke_2
+ ___69-[THClient retrieveNearbyNetworkCredentialsInternallyWithCompletion:]_block_invoke
+ ___69-[THClient retrieveNearbyNetworkCredentialsInternallyWithCompletion:]_block_invoke_2
+ ___assert_rtn
+ ___block_descriptor_48_e8_32s40bs_e77_v32?0"NSSet"8"THThreadNetworkCredentialsActiveDataSetRecord"16"NSError"24l
+ ___isOSVersionAtLeast
+ ___isPlatformOrVariantPlatformVersionAtLeast
+ ___isPlatformVersionAtLeast
+ __availability_version_check
+ __initializeAvailabilityCheck
+ _compatibilityInitializeAvailabilityCheck
+ _dispatch_once_f
+ _dlsym
+ _fclose
+ _fopen
+ _fread
+ _free
+ _fseek
+ _ftell
+ _initializeAvailabilityCheck
+ _malloc
+ _objc_msgSend$containsValueForKey:
+ _objc_msgSend$handleActiveNearbyNetworksResponse:preferredNetworkRecord:error:apiName:isInternal:nearbyType:completion:
+ _objc_msgSend$initThreadCredentials:extendedPANID:borderAgentID:activeOperationalDataSet:PSKC:networkKey:channel:panID:creationDate:lastModificationDate:isPreferredNetworkCredentials:
+ _objc_msgSend$initWithActiveDataSetRecord:isPreferredNetworkCredentials:
+ _objc_msgSend$isEqualToData:
+ _objc_msgSend$isPreferredNetworkCredentials
+ _objc_retainBlock
+ _rewind
+ _sscanf
- -[THClient handleActiveNearbyNetworksResponse:error:isInternal:completion:]
- _objc_msgSend$handleActiveNearbyNetworksResponse:error:isInternal:completion:
CStrings:
+ "%d.%d.%d"
+ "/System/Library/CoreServices/SystemVersion.plist"
+ "CFDataCreateWithBytesNoCopy"
+ "CFDictionaryGetValue"
+ "CFGetTypeID"
+ "CFPropertyListCreateFromXMLData"
+ "CFPropertyListCreateWithData"
+ "CFRelease"
+ "CFStringCreateWithCStringNoCopy"
+ "CFStringGetCString"
+ "CFStringGetTypeID"
+ "Platform2 == PLATFORM_MACOS && \"unexpected platform\""
+ "ProductVersion"
+ "THNearbyNetworkCredentials.isPreferred"
+ "__isPlatformOrVariantPlatformVersionAtLeast"
+ "kCFAllocatorNull"
+ "os_version_check.c"
+ "r"
+ "v32@?0@\"NSSet\"8@\"THThreadNetworkCredentialsActiveDataSetRecord\"16@\"NSError\"24"
```
