## CaptiveNetworkSupport

> `/System/Library/SystemConfiguration/CaptiveNetworkSupport.bundle/Contents/MacOS/CaptiveNetworkSupport`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__data`

```diff

-545.40.1.0.0
-  __TEXT.__text: 0x2551c
+545.60.2.0.0
+  __TEXT.__text: 0x259e8
   __TEXT.__auth_stubs: 0x11a0
-  __TEXT.__objc_stubs: 0x120
+  __TEXT.__objc_stubs: 0xc0
   __TEXT.__const: 0x1d0
-  __TEXT.__oslogstring: 0x47fe
-  __TEXT.__cstring: 0x1986
-  __TEXT.__objc_methname: 0x9a
-  __TEXT.__unwind_info: 0x978
-  __DATA_CONST.__const: 0xfb8
-  __DATA_CONST.__cfstring: 0x1a20
+  __TEXT.__oslogstring: 0x484b
+  __TEXT.__cstring: 0x194b
+  __TEXT.__objc_methname: 0x5b
+  __TEXT.__unwind_info: 0x9a0
+  __DATA_CONST.__const: 0xff0
+  __DATA_CONST.__cfstring: 0x1a00
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x8d8
-  __DATA_CONST.__got: 0x258
+  __DATA_CONST.__got: 0x248
   __DATA_CONST.__auth_ptr: 0x10
-  __DATA.__objc_selrefs: 0x48
+  __DATA.__objc_selrefs: 0x30
   __DATA.__data: 0x211
   __DATA.__bss: 0x210
   __DATA.__common: 0x18

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 605
-  Symbols:   1145
+  Functions: 616
+  Symbols:   1152
   CStrings:  907
 
Symbols:
+ _LaunchCaptiveNetworkAssistant
+ _UserSessionAuthorize
+ _UserSessionHandlerInit
+ _UserSessionHandlerMethods
+ _UserSessionLaunchWebSheet
+ _UserSessionProcessControl
+ _UserSessionProcessResponse
+ _UserSessionProvideCommand
+ _UserSessionQueueLaunchWebSheetCommand
+ _UserSessionRegister
+ _UserSessionRemove
+ _getHandlerWithUID
- _OBJC_CLASS_$_LSApplicationWorkspace
- _OBJC_CLASS_$_NSURL
- _objc_msgSend$defaultWorkspace
- _objc_msgSend$fileURLWithPath:
- _objc_msgSend$openURL:configuration:error:
CStrings:
+ "CaptiveNetworkSupport-545.60.2"
+ "No user session for uid %d"
+ "Queued command %@"
+ "Received response for command %@"
+ "Session uid %d pid %d DIED"
+ "Session uid %d pid %d REGISTERED"
+ "Session uid %d pid %d launching websheet"
- "/System/Library/CoreServices/Captive Network Assistant.app"
- "CaptiveNetworkSupport-545.40.1"
- "defaultWorkspace"
- "failed to launch Captive Network Assistant, Error: %@"
- "fileURLWithPath:"
- "openURL:configuration:error:"
- "successfully launched Captive Network Assistant"
```
