## CoreMediaIO

> `/System/Library/Frameworks/CoreMediaIO.framework/Versions/A/CoreMediaIO`

```diff

 5634.0.0.0.0
-  __TEXT.__text: 0xbfab4
+  __TEXT.__text: 0xbfc7c
   __TEXT.__objc_methlist: 0x224c
   __TEXT.__const: 0x95f
   __TEXT.__cstring: 0x10393
-  __TEXT.__oslogstring: 0xfc1b
+  __TEXT.__oslogstring: 0xfc35
   __TEXT.__gcc_except_tab: 0x6380
   __TEXT.__dlopen_cstrs: 0x10e
   __TEXT.__unwind_info: 0x2770

   __DATA_CONST.__objc_superrefs: 0xe8
   __DATA_CONST.__objc_arraydata: 0x1c8
   __DATA_CONST.__got: 0x3d0
-  __AUTH_CONST.__const: 0x2620
+  __AUTH_CONST.__const: 0x2628
   __AUTH_CONST.__cfstring: 0x4aa0
   __AUTH_CONST.__objc_const: 0x40d0
   __AUTH_CONST.__weak_auth_got: 0x28

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3700
+  Functions: 3699
   Symbols:   4650
-  CStrings:  2609
+  CStrings:  2610
 
Functions:
~ __ZN4CMIO3DAL6Object17PropertiesChangedEjPK25CMIOObjectPropertyAddress : 1180 -> 1176
~ __ZNSt3__16vectorIN4CMIO15PropertyAddressENS_9allocatorIS2_EEE24__emplace_back_slow_pathIJS2_EEEPS2_DpOT_ : 252 -> 248
~ __ZNSt3__15dequeIjNS_9allocatorIjEEE19__add_back_capacityEv : 468 -> 472
~ __ZNSt3__114__split_bufferIPjNS_9allocatorIS1_EEE12emplace_backIJRS1_EEEvDpOT_ : 256 -> 260
~ __ZNSt3__114__split_bufferIPjRNS_9allocatorIS1_EEE12emplace_backIJS1_EEEvDpOT_ : 256 -> 260
~ -[CMIOExtensionProviderHostContext setStreamPropertyValuesWithStreamID:propertyValues:reply:] : 704 -> 1164
~ __ZN4CMIO25callbackDrivenClockHelper15PostTimingEventE6CMTimeyb : 3716 -> 3720
- _OUTLINED_FUNCTION_3
~ -[CMIOExtensionProviderServer init].cold.1 : 84 -> 96
~ -[CMIOExtensionProviderServer init].cold.2 : 84 -> 96
~ -[CMIOExtensionProviderServer init].cold.3 : 88 -> 84
~ -[CMIOExtensionProviderServer start].cold.1 : 108 -> 104
~ -[CMIOExtensionProviderServer addConnection:].cold.1 : 108 -> 104
CStrings:
+ "%s:%d:%s SetProperty - %@"
```
