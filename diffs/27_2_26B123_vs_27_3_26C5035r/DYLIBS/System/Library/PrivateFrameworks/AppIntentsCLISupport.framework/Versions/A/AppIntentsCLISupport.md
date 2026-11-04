## AppIntentsCLISupport

> `/System/Library/PrivateFrameworks/AppIntentsCLISupport.framework/Versions/A/AppIntentsCLISupport`

```diff

-301.1.16.0.0
-  __TEXT.__text: 0x11698
-  __TEXT.__const: 0x480
-  __TEXT.__cstring: 0x59e
-  __TEXT.__swift5_typeref: 0x229
+301.2.7.2.0
+  __TEXT.__text: 0x125cc
+  __TEXT.__const: 0x488
+  __TEXT.__cstring: 0x76e
+  __TEXT.__swift5_typeref: 0x231
   __TEXT.__constg_swiftt: 0x80
   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_reflstr: 0x2b

   __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_proto: 0x20
   __TEXT.__swift5_types: 0xc
-  __TEXT.__unwind_info: 0x430
-  __TEXT.__eh_frame: 0x730
+  __TEXT.__unwind_info: 0x450
+  __TEXT.__eh_frame: 0x7a8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_methname: 0x0
   __DATA_CONST.__const: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x590
+  __DATA_CONST.__objc_selrefs: 0x5b0
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0xc8
-  __AUTH_CONST.__auth_got: 0x5b8
-  __DATA.__data: 0x278
+  __AUTH_CONST.__auth_got: 0x5c0
+  __DATA.__data: 0x288
   __DATA.__bss: 0x418
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/Intents.framework/Versions/A/Intents
   - /System/Library/PrivateFrameworks/LinkMetadata.framework/Versions/A/LinkMetadata
-  - /System/Library/PrivateFrameworks/LinkServices.framework/Versions/A/LinkServices
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftAccelerate.dylib

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 369
-  Symbols:   464
-  CStrings:  34
+  Functions: 379
+  Symbols:   472
+  CStrings:  43
 
Symbols:
+ _OBJC_CLASS_$_INPerson
+ _OBJC_CLASS_$_INPersonHandle
+ _OUTLINED_FUNCTION_95
+ _objc_msgSend$initWithPersonHandle:nameComponents:displayName:image:contactIdentifier:customIdentifier:
+ _objc_msgSend$initWithValue:type:
+ _objc_msgSend$personValueType
+ _objc_msgSend$setIsMe:
+ _symbolic _____Sg 10Foundation20PersonNameComponentsV
CStrings:
+ "' must be a quoted string."
+ "'. Supported: name, phone, email, handle, contactIdentifier, customIdentifier, isMe."
+ "IntentPerson accepts only one of contactIdentifier or customIdentifier."
+ "IntentPerson accepts only one of phone, email, or handle."
+ "IntentPerson property '"
+ "IntentPerson property 'isMe' must be true or false."
+ "Unknown IntentPerson property '"
+ "contactIdentifier"
+ "customIdentifier"
```
