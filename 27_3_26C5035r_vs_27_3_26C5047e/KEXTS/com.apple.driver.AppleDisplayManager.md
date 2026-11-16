## com.apple.driver.AppleDisplayManager

> `com.apple.driver.AppleDisplayManager`

```diff

-700.51.10.0.0
+700.51.12.0.0
   __TEXT.__const: 0x8
-  __TEXT.__cstring: 0x2db4
-  __TEXT_EXEC.__text: 0x9d8c
+  __TEXT.__cstring: 0x2fa1
+  __TEXT_EXEC.__text: 0x9f58
   __TEXT_EXEC.__auth_stubs: 0x1c0
   __DATA.__data: 0xc8
   __DATA.__common: 0x60

   __DATA_CONST.__got: 0x48
   Functions: 134
   Symbols:   505
-  CStrings:  254
+  CStrings:  262
 
Functions:
~ __ZN19AppleDisplayManager36display_resources_request_status_getEjP32ADMDisplayResourcesRequestStatus : 832 -> 1292
CStrings:
+ "AED %s: fb %u back on %u pipes (max %u) with no cached pipe count, checking dual-pipe re-pair (tiling mgr %s)"
+ "AED %s: fb %u crossbar kept dual pipe across replug but shim is unpaired, re-pairing"
+ "AED %s: fb %u dual-pipe re-pair after replug failed (0x%x)"
+ "AED %s: fb %u dual-pipe re-pair after replug succeeded"
+ "AED %s: fb %u is tiled/DP-split on replug, no re-pair, reporting set not happened"
+ "AED %s: fb %u skipping replug re-pair (tiling mgr %s, dual-pipe HPD already valid %d)"
+ "missing"
+ "present"
```
