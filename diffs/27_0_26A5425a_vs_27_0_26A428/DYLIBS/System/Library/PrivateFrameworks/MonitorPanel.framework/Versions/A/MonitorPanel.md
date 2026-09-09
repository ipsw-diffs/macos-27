## MonitorPanel

> `/System/Library/PrivateFrameworks/MonitorPanel.framework/Versions/A/MonitorPanel`

```diff

 2027.0.1.0.0
-  __TEXT.__text: 0x10450
-  __TEXT.__objc_methlist: 0xdc8
-  __TEXT.__cstring: 0x127c
+  __TEXT.__text: 0x106f8
+  __TEXT.__objc_methlist: 0xe30
+  __TEXT.__cstring: 0x12c0
   __TEXT.__oslogstring: 0x1167
   __TEXT.__const: 0xac
   __TEXT.__gcc_except_tab: 0x10

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x170
-  __DATA_CONST.__objc_classlist: 0x40
+  __DATA_CONST.__const: 0x180
+  __DATA_CONST.__objc_classlist: 0x48
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb58
-  __DATA_CONST.__objc_superrefs: 0x40
+  __DATA_CONST.__objc_selrefs: 0xb88
+  __DATA_CONST.__objc_superrefs: 0x48
   __DATA_CONST.__objc_arraydata: 0xe0
-  __DATA_CONST.__got: 0x160
+  __DATA_CONST.__got: 0x168
   __AUTH_CONST.__const: 0x2a0
-  __AUTH_CONST.__cfstring: 0x1820
-  __AUTH_CONST.__objc_const: 0x1920
+  __AUTH_CONST.__cfstring: 0x18c0
+  __AUTH_CONST.__objc_const: 0x1a50
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0xa0
-  __DATA.__objc_ivar: 0x1a8
+  __AUTH.__objc_data: 0xf0
+  __DATA.__objc_ivar: 0x1b4
   __DATA.__data: 0x40
   __DATA.__bss: 0x88
   __DATA_DIRTY.__objc_data: 0x1e0

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 441
-  Symbols:   1034
-  CStrings:  335
+  Functions: 448
+  Symbols:   1062
+  CStrings:  340
 
Symbols:
+ +[MPDisplayModeGenlockInfo genlockInfoWithIsGenlock:genlockMultiplier:]
+ -[MPDisplay genlockInfoForModeAtIndex:modeNumber:]
+ -[MPDisplayHW genlockInfoForModeAtIndex:modeNumber:]
+ -[MPDisplayMode genlockInfo]
+ -[MPDisplayMode initWithModeDescription:isProMotion:isVRR:genlockInfo:minRefreshRate:forDisplay:]
+ -[MPDisplayModeGenlockInfo genlockMultiplier]
+ -[MPDisplayModeGenlockInfo initWithIsGenlock:genlockMultiplier:]
+ -[MPDisplayModeGenlockInfo isGenlock]
+ GCC_except_table55
+ OBJC_IVAR_$_MPDisplayMode._genlockInfo
+ OBJC_IVAR_$_MPDisplayModeGenlockInfo._genlockMultiplier
+ OBJC_IVAR_$_MPDisplayModeGenlockInfo._isGenlock
+ _OBJC_CLASS_$_MPDisplayModeGenlockInfo
+ _OBJC_METACLASS_$_MPDisplayModeGenlockInfo
+ _SLSGetDisplayModeGenlockClockMultiplier
+ _SLSIsDisplayModeGenlock
+ __OBJC_$_CLASS_METHODS_MPDisplayModeGenlockInfo
+ __OBJC_$_INSTANCE_METHODS_MPDisplayModeGenlockInfo
+ __OBJC_$_INSTANCE_VARIABLES_MPDisplayModeGenlockInfo
+ __OBJC_$_PROP_LIST_MPDisplayModeGenlockInfo
+ __OBJC_CLASS_RO_$_MPDisplayModeGenlockInfo
+ __OBJC_METACLASS_RO_$_MPDisplayModeGenlockInfo
+ _kDisplayInfoGenlockMultiplierKey
+ _kDisplayInfoIsGenlockKey
+ _objc_msgSend$genlockInfo
+ _objc_msgSend$genlockInfoForModeAtIndex:modeNumber:
+ _objc_msgSend$genlockInfoWithIsGenlock:genlockMultiplier:
+ _objc_msgSend$genlockMultiplier
+ _objc_msgSend$initWithIsGenlock:genlockMultiplier:
+ _objc_msgSend$initWithModeDescription:isProMotion:isVRR:genlockInfo:minRefreshRate:forDisplay:
+ _objc_msgSend$isGenlock
- -[MPDisplayMode initWithModeDescription:isProMotion:isVRR:minRefreshRate:forDisplay:]
- GCC_except_table50
- _objc_msgSend$initWithModeDescription:isProMotion:isVRR:minRefreshRate:forDisplay:
CStrings:
+ "-genlock%.0f"
+ "Genlock"
+ "GenlockLocalizable"
+ "genlockMultiplier"
+ "isGenlock"
```
