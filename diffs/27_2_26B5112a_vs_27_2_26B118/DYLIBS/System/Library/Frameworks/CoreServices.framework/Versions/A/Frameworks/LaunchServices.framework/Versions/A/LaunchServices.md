## LaunchServices

> `/System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/LaunchServices.framework/Versions/A/LaunchServices`

```diff

 1517.1.12.0.0
-  __TEXT.__text: 0x24fbc4
+  __TEXT.__text: 0x24ff90
   __TEXT.__lazy_helpers: 0xa8
   __TEXT.__objc_methlist: 0xee6c
   __TEXT.__const: 0xad8
-  __TEXT.__cstring: 0x33d7d
-  __TEXT.__oslogstring: 0x229f4
-  __TEXT.__gcc_except_tab: 0x34cc0
+  __TEXT.__cstring: 0x33db0
+  __TEXT.__oslogstring: 0x22b2a
+  __TEXT.__gcc_except_tab: 0x34d60
   __TEXT.__ustring: 0x1be
   __TEXT.__dof_LSFSNode: 0x2b6
   __TEXT.__unwind_info: 0x102d8

   - /usr/lib/system/libxpc.dylib
   Functions: 11222
   Symbols:   19608
-  CStrings:  7991
+  CStrings:  7996
 
Functions:
~ __LSOpenStuffCallLocal : 13040 -> 14012
CStrings:
+ "LSQInternetLocatorPath"
+ "LSQInternetLocatorTargetURL"
+ "QUARANTINE: Unable to reach CSUIA to approve quarantined Internet Locator %{private}@, refusing to open %{private}@"
+ "QUARANTINE: User declined to open quarantined Internet Locator %{private}@ (target %{private}@), status=%{public}d"
+ "QUARANTINE: XPC error talking to CSUIA to approve Internet Locator: %{public}s"
```
