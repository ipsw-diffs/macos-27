## com.apple.AppleUserHIDDrivers

> `/System/Library/DriverExtensions/com.apple.AppleUserHIDDrivers.dext/com.apple.AppleUserHIDDrivers`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`

```diff

 2360.1.2.0.0
-  __TEXT.__text: 0x257c
+  __TEXT.__text: 0x2514
   __TEXT.__auth_stubs: 0x280
   __TEXT.__const: 0x2b0
   __TEXT.__cstring: 0x2e1
   __TEXT.__oslogstring: 0x2f4
-  __DATA_CONST.__const: 0x8f0
+  __DATA_CONST.__const: 0x910
   __DATA_CONST.__osclassinfo: 0x10
   __DATA_CONST.__auth_got: 0x140
   __DATA_CONST.__got: 0x38

   - /System/DriverKit/System/Library/Frameworks/USBDriverKit.framework/USBDriverKit
   - /System/DriverKit/usr/lib/libc++.dylib
   Functions: 62
-  Symbols:   215
+  Symbols:   219
   CStrings:  33
 
Symbols:
+ __ZN24AppleUserHIDEventService22handleHingeAngleReportEyj
+ __ZN24AppleUserHIDEventService22parseHingeAngleElementEP12IOHIDElement
+ __ZThn96_N24AppleUserHIDEventService22handleHingeAngleReportEyj
+ __ZThn96_N24AppleUserHIDEventService22parseHingeAngleElementEP12IOHIDElement
Functions:
~ __ZN23AppleUserHIDEventDriver4freeEv : 180 -> 168
~ __ZN23AppleUserHIDEventDriver26parseGameControllerElementEP12IOHIDElement : 264 -> 252
~ sub_1000054f4 -> sub_1000054dc : 28 -> 16
~ sub_10000552c -> sub_100005508 : 36 -> 24
~ __ZN23AppleUserHIDEventDriver16setLEDPropertiesEP12OSDictionary : 448 -> 416
~ __ZN23AppleUserHIDEventDriver11handleStartEP9IOService : 80 -> 68
~ __ZThn64_N23AppleUserHIDEventDriver11handleStartEP9IOService : 84 -> 72
```
