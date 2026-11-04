## SiriActivationFoundation

> `/System/Library/PrivateFrameworks/SiriActivationFoundation.framework/Versions/A/SiriActivationFoundation`

```diff

-3605.31.1.14.1
-  __TEXT.__text: 0x399cc
-  __TEXT.__objc_methlist: 0x28f4
+3610.10.1.0.0
+  __TEXT.__text: 0x39a1c
+  __TEXT.__objc_methlist: 0x290c
   __TEXT.__const: 0x205c
-  __TEXT.__cstring: 0x468b
+  __TEXT.__cstring: 0x46cb
   __TEXT.__oslogstring: 0xb5a
   __TEXT.__constg_swiftt: 0xc58
   __TEXT.__swift5_typeref: 0x15f4

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x130
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1110
+  __DATA_CONST.__objc_selrefs: 0x1120
   __DATA_CONST.__objc_protorefs: 0x68
   __DATA_CONST.__objc_superrefs: 0x128
   __DATA_CONST.__objc_arraydata: 0x560
   __DATA_CONST.__got: 0x3d0
   __AUTH_CONST.__const: 0x2b98
-  __AUTH_CONST.__cfstring: 0x3cc0
-  __AUTH_CONST.__objc_const: 0x5bc0
+  __AUTH_CONST.__cfstring: 0x3ce0
+  __AUTH_CONST.__objc_const: 0x5bf0
   __AUTH_CONST.__objc_intobj: 0x810
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__auth_got: 0x7a0
   __AUTH.__objc_data: 0x1f8
   __AUTH.__data: 0x138
-  __DATA.__objc_ivar: 0x37c
+  __DATA.__objc_ivar: 0x380
   __DATA.__data: 0xe30
   __DATA.__bss: 0x1220
   __DATA_DIRTY.__objc_data: 0xfa0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1913
-  Symbols:   2468
-  CStrings:  612
+  Functions: 1915
+  Symbols:   2472
+  CStrings:  613
 
Symbols:
+ -[SAFRequestOptions carOwnsCommunication]
+ -[SAFRequestOptions setCarOwnsCommunication:]
+ _OBJC_IVAR_$_SAFRequestOptions._carOwnsCommunication
+ _objc_msgSend$carOwnsCommunication
Functions:
~ -[SAFRequestOptions initWithCoder:] : 2512 -> 2532
~ -[SAFRequestOptions encodeWithCoder:] : 2244 -> 2272
~ -[SAFRequestOptions description] : 2492 -> 2508
- -[SAFRequestOptions setHomeButtonUpFromBeep:]
+ -[SAFRequestOptions setHomeButtonUpFromBeep:]
- -[SAFRequestOptions setRequestInfo:]
+ -[SAFRequestOptions requestInfo]
+ -[SAFRequestOptions setSpeechRequestOptions:]
+ -[SAFRequestOptions uiPresentationIdentifier]
CStrings:
+ ";is(speech=%i; textInput=%i;stark=%i;CPconnected=%i;dnd=%i;rightHandDrive=%i;isForBluetoothCar=%i);carDNDStatus=%@;remotePresentationBringUp=%i;supportsCarPlayVehicleData=%i;carOwnsMainAudio=%i;carOwnsCommunication=%i"
+ "SAFRequestOptionsCarOwnsCommunicationCodingKey"
- ";is(speech=%i; textInput=%i;stark=%i;CPconnected=%i;dnd=%i;rightHandDrive=%i;isForBluetoothCar=%i);carDNDStatus=%@;remotePresentationBringUp=%i;supportsCarPlayVehicleData=%i;carOwnsMainAudio=%i"
```
