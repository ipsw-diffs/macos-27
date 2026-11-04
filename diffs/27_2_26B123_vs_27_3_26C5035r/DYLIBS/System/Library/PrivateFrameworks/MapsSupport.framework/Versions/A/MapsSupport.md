## MapsSupport

> `/System/Library/PrivateFrameworks/MapsSupport.framework/Versions/A/MapsSupport`

```diff

-2972.21.6.17.31
-  __TEXT.__text: 0x77174
+2972.22.9.10.6
+  __TEXT.__text: 0x77270
   __TEXT.__objc_methlist: 0x7e88
   __TEXT.__const: 0x29a
   __TEXT.__cstring: 0x5d97
-  __TEXT.__oslogstring: 0x7fa7
+  __TEXT.__oslogstring: 0x7fd7
   __TEXT.__gcc_except_tab: 0xd10
   __TEXT.__ustring: 0x2b2
   __TEXT.__constg_swiftt: 0x38

   - /usr/lib/swift/libswiftos.dylib
   Functions: 2791
   Symbols:   6718
-  CStrings:  1333
+  CStrings:  1334
 
Symbols:
+ _objc_msgSend$hasChargingTime
- _objc_msgSend$hasChargingStationInfo
Functions:
~ -[MSPSharedTripNotificationRules currentlyNecessaryNotificationTypeForState:] : 856 -> 876
~ -[GEOSharedNavState(MSPExtras) updateWaypointsFromComposedRoute:] : 1124 -> 1256
~ -[GEOSharedNavWaypointInfo(MSPExtras) name] : 140 -> 240
CStrings:
+ "No chargingInfo or geoMapItem for leg %lu"
```
