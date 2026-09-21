## com.apple.AppleSunriseWLAN

> `/System/Library/DriverExtensions/com.apple.AppleSunriseWLAN.dext/com.apple.AppleSunriseWLAN`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-342.6.0.0.0
-  __TEXT.__text: 0x398880
+342.7.0.0.0
+  __TEXT.__text: 0x3988d0
   __TEXT.__auth_stubs: 0x1410
-  __TEXT.__cstring: 0xe7b4a
+  __TEXT.__cstring: 0xe7bae
   __TEXT.__const: 0xd380
   __TEXT.__unwind_info: 0x6b10
   __TEXT.__oslogstring: 0x18f

   - /System/DriverKit/usr/lib/libc++.dylib
   Functions: 8054
   Symbols:   10157
-  CStrings:  20364
+  CStrings:  20366
 
Functions:
~ __ZN28AppleSunriseWLANNANInterface10RestoreNANEv : 388 -> 460
~ _glRegisterNAN : 1524 -> 1532
CStrings:
+ "\"AppleSunriseWLAN_driverkit-342.7\""
+ "AppleSunrise-user: [NAN][%s]: Error: NAN net device not ready"
+ "AppleSunrise-user: [NAN][%s]: dev: %p"
+ "AppleSunriseWLAN_driverkit-342.7"
+ "Sep 13 2026 19:15:31"
- "\"AppleSunriseWLAN_driverkit-342.6\""
- "AppleSunriseWLAN_driverkit-342.6"
- "Sep  4 2026 23:24:16"
```
