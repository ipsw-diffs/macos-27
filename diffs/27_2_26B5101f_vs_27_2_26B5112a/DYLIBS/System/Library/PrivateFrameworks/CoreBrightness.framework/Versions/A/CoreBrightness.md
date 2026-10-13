## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/Versions/A/CoreBrightness`

```diff

-2300.40.47.0.4
-  __TEXT.__text: 0x1667c4
-  __TEXT.__objc_methlist: 0xd7c8
-  __TEXT.__cstring: 0xd0d5
-  __TEXT.__const: 0x12950
+2300.41.8.0.0
+  __TEXT.__text: 0x167f10
+  __TEXT.__objc_methlist: 0xd888
+  __TEXT.__cstring: 0xd12a
+  __TEXT.__const: 0x129e8
   __TEXT.__gcc_except_tab: 0x210c
-  __TEXT.__oslogstring: 0x18f5d
+  __TEXT.__oslogstring: 0x18ffd
   __TEXT.__dlopen_cstrs: 0x10d
-  __TEXT.__swift5_typeref: 0xf35
+  __TEXT.__swift5_typeref: 0xf36
   __TEXT.__constg_swiftt: 0xd80
-  __TEXT.__swift5_reflstr: 0xbfe
+  __TEXT.__swift5_reflstr: 0xbf4
   __TEXT.__swift5_assocty: 0x288
   __TEXT.__swift5_fieldmd: 0x1240
   __TEXT.__swift5_builtin: 0x168

   __TEXT.__swift5_proto: 0x308
   __TEXT.__swift5_types: 0x144
   __TEXT.__swift5_mpenum: 0x28
-  __TEXT.__unwind_info: 0x76c0
+  __TEXT.__unwind_info: 0x7738
   __TEXT.__eh_frame: 0xbd0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1210
-  __DATA_CONST.__objc_classlist: 0x718
+  __DATA_CONST.__objc_classlist: 0x720
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x350
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x58c0
+  __DATA_CONST.__objc_selrefs: 0x5938
   __DATA_CONST.__objc_protorefs: 0x138
   __DATA_CONST.__objc_superrefs: 0x5c8
-  __DATA_CONST.__objc_arraydata: 0xb90
-  __DATA_CONST.__got: 0x7b0
-  __AUTH_CONST.__const: 0x5f58
-  __AUTH_CONST.__cfstring: 0xe880
-  __AUTH_CONST.__objc_const: 0x360b0
+  __DATA_CONST.__objc_arraydata: 0xc40
+  __DATA_CONST.__got: 0x7b8
+  __AUTH_CONST.__const: 0x5f88
+  __AUTH_CONST.__cfstring: 0xe8e0
+  __AUTH_CONST.__objc_const: 0x36758
   __AUTH_CONST.__weak_auth_got: 0x20
-  __AUTH_CONST.__objc_intobj: 0xcd8
+  __AUTH_CONST.__objc_intobj: 0xd08
   __AUTH_CONST.__objc_floatobj: 0x180
-  __AUTH_CONST.__objc_arrayobj: 0x2a0
-  __AUTH_CONST.__objc_dictobj: 0x5f0
+  __AUTH_CONST.__objc_arrayobj: 0x2d0
+  __AUTH_CONST.__objc_dictobj: 0x690
   __AUTH_CONST.__objc_doubleobj: 0x40
-  __AUTH_CONST.__auth_got: 0x12f8
-  __AUTH.__objc_data: 0x28d0
-  __AUTH.__data: 0x690
-  __DATA.__objc_ivar: 0x17d8
-  __DATA.__data: 0x670c0
-  __DATA.__bss: 0x6430
+  __AUTH_CONST.__auth_got: 0x1300
+  __AUTH.__objc_data: 0x2940
+  __AUTH.__data: 0x6c0
+  __DATA.__objc_ivar: 0x17ec
+  __DATA.__data: 0x670c8
+  __DATA.__bss: 0x6440
   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0x21e8
   __DATA_DIRTY.__data: 0x510

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 8381
-  Symbols:   13131
-  CStrings:  4730
+  Functions: 8417
+  Symbols:   13170
+  CStrings:  4738
 
Symbols:
+ -[BacklightDriverPWM nitsUpdateLogType]
+ -[CBDisplayContainerSKL clearCachedALSEvents]
+ -[CBDisplayContainerSKL handleDisplayBrightnessFactorUpdate:]
+ -[CBDisplayContainerSKL handleDisplayPowerStateEvent:]
+ -[CBDisplayContainerSKL shouldDiscardALSEvent:]
+ -[CBHIDEventManager addUnfilteredClient:]
+ OBJC_IVAR_$_CBDisplayContainerSKL._alsNodes
+ OBJC_IVAR_$_CBDisplayContainerSKL._coexTracker
+ OBJC_IVAR_$_CBDisplayContainerSKL._lastEventByServiceID
+ OBJC_IVAR_$_CBDisplayContainerSKL._sensitivityFilter
+ OBJC_IVAR_$_CBHIDEventManager._unfilteredClients
+ _CBU_DeviceEnclosureColor
+ _CFStringGetIntValue
+ _OBJC_CLASS_$_ALSSensitivityFilter
+ _OBJC_METACLASS_$_ALSSensitivityFilter
+ __52-[CBHIDEventManager hidEventCallbackWithEvent:from:]_block_invoke
+ __DATA_ALSSensitivityFilter
+ __INSTANCE_METHODS_ALSSensitivityFilter
+ __IVARS_ALSSensitivityFilter
+ __METACLASS_DATA_ALSSensitivityFilter
+ __PROPERTIES_ALSSensitivityFilter
+ ___35-[CBHIDEventManager addHIDService:]_block_invoke_2
+ ___38-[CBHIDEventManager removeHIDService:]_block_invoke_2
+ ___41-[CBHIDEventManager addUnfilteredClient:]_block_invoke
+ ___block_descriptor_40_e8_32o_e36_v24?0"<CBHIDServiceProtocol>"8^B16l
+ _objc_msgSend$addUnfilteredClient:
+ _objc_msgSend$clearCachedALSEvents
+ _objc_msgSend$colorSensitivity
+ _objc_msgSend$crossedColorThreshold::
+ _objc_msgSend$crossedLuxThreshold::
+ _objc_msgSend$handleDisplayBrightnessFactorUpdate:
+ _objc_msgSend$handleDisplayPowerStateEvent:
+ _objc_msgSend$isEventOverThreshold:comparedTo:
+ _objc_msgSend$luxAbsoluteSensitivity
+ _objc_msgSend$luxRelativeSensitivity
+ _objc_msgSend$nitsUpdateLogType
+ _objc_msgSend$setColorSensitivity:
+ _objc_msgSend$setLuxAbsoluteSensitivity:
+ _objc_msgSend$setLuxRelativeSensitivity:
+ _objc_msgSend$shouldDiscardALSEvent:
- GCC_except_table59
CStrings:
+ "4"
+ "Add unfiltered client %@"
+ "Brightness factor = %f, clear cached ALS events"
+ "Display will wake, clear cached ALS events"
+ "DisplayIntegrated"
+ "Overriding Boot-nits: %.2f -> %.2f nits"
+ "override-boot-brightness-nits"
+ "v24@?0@\"<CBHIDServiceProtocol>\"8^B16"
```
