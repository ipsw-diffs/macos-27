## geoanalyticsd

> `/System/Library/PrivateFrameworks/GeoAnalytics.framework/geoanalyticsd`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

```diff

-2076.22.9.18.5
-  __TEXT.__text: 0x2ce04
+2076.22.9.18.10
+  __TEXT.__text: 0x2cc38
   __TEXT.__auth_stubs: 0x750
-  __TEXT.__objc_stubs: 0x4180
-  __TEXT.__objc_methlist: 0x1624
-  __TEXT.__const: 0x178
+  __TEXT.__objc_stubs: 0x4160
+  __TEXT.__objc_methlist: 0x1594
+  __TEXT.__const: 0x180
   __TEXT.__gcc_except_tab: 0x69c
-  __TEXT.__cstring: 0xe851
-  __TEXT.__objc_methname: 0x3bec
-  __TEXT.__objc_classname: 0x642
-  __TEXT.__objc_methtype: 0x1097
-  __TEXT.__oslogstring: 0x2055
-  __TEXT.__unwind_info: 0xb48
+  __TEXT.__cstring: 0xe853
+  __TEXT.__objc_methname: 0x3c3e
+  __TEXT.__objc_classname: 0x68b
+  __TEXT.__objc_methtype: 0x10a0
+  __TEXT.__oslogstring: 0x1f3f
+  __TEXT.__unwind_info: 0xb38
   __DATA_CONST.__const: 0x17b8
   __DATA_CONST.__cfstring: 0x12e20
-  __DATA_CONST.__objc_classlist: 0x130
-  __DATA_CONST.__objc_protolist: 0x90
+  __DATA_CONST.__objc_classlist: 0x138
+  __DATA_CONST.__objc_protolist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0xc0
   __DATA_CONST.__auth_got: 0x3b8
-  __DATA_CONST.__got: 0x378
-  __DATA.__objc_const: 0x33c8
-  __DATA.__objc_selrefs: 0x1200
-  __DATA.__objc_ivar: 0x184
-  __DATA.__objc_data: 0xbe0
-  __DATA.__data: 0x6c0
+  __DATA_CONST.__got: 0x368
+  __DATA.__objc_const: 0x34e0
+  __DATA.__objc_selrefs: 0x1208
+  __DATA.__objc_ivar: 0x190
+  __DATA.__objc_data: 0xc30
+  __DATA.__data: 0x720
   __DATA.__bss: 0x1b0
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 610
+  Functions: 603
   Symbols:   249
-  CStrings:  3692
+  CStrings:  3694
 
Symbols:
+ _OBJC_CLASS_$_GEOAPSessionCountsGatingConfig
+ _OBJC_METACLASS_$_GEOAPSessionCountsGatingConfig
- _GeoAnalyticsConfig_ShortSessionCountsDisabled
- _GeoAnalyticsConfig_ShortSessionOSVersionDenyList
CStrings:
+ "@\"NSSet\""
+ "GEOAPSessionCountsGating"
+ "GEOAPSessionSignalsHarvesterUserSessionProvider"
+ "_allowListTooLong"
+ "_allowedMetrics"
+ "allowed metrics has %lu entries; exceeds %lu, reporting an empty set"
+ "empty signal set for today; capturing an empty dynamic daily use summary"
+ "initWithAllowedMetrics:"
+ "initWithResolver:db:timeProvider:configProvider:userSessionProvider:"
+ "metric %u dropped; count %u is at or below min %u"
+ "metric %u used %u bits"
+ "session signal aggregation is not allowed (%{public}@); skipping"
+ "session signal harvesting is not allowed (%{public}@); skipping"
+ "sessionCountsDisabledReasonForConfig:"
+ "setIsInternalTool:"
+ "v32@0:8I16I20@24"
- "AllowedAggregatorMetrics has %lu entries; truncating to 16"
- "B32@0:8I16I20@24"
- "OS version %{public}@ is denylisted; skipping session signal aggregation"
- "OS version %{public}@ is denylisted; skipping session signal harvesting"
- "empty signal set for today; dynamic daily use summary will not be captured"
- "initWithResolver:db:timeProvider:configProvider:"
- "isSessionCountsDisabledInCountry:"
- "metric %u dropped; count %u is below min %u"
- "metric %u final count %u; used %u bits"
- "session signal aggregation is disabled by config; skipping"
- "session signal aggregation is disabled in country %{private}@; skipping"
- "session signal harvesting is disabled by config; skipping"
- "session signal harvesting is disabled in country %{private}@; skipping"
- "subarrayWithRange:"
```
