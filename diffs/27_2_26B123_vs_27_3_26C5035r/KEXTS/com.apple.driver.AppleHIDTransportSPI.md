## com.apple.driver.AppleHIDTransportSPI

> `com.apple.driver.AppleHIDTransportSPI`

```diff

-10410.3.0.0.0
+10420.1.0.0.0
   __TEXT.__const: 0x338
-  __TEXT.__cstring: 0x7d4e
-  __TEXT_EXEC.__text: 0x39ec8
+  __TEXT.__cstring: 0x7da3
+  __TEXT_EXEC.__text: 0x39fa0
   __TEXT_EXEC.__auth_stubs: 0x620
   __DATA.__data: 0xc8
   __DATA.__common: 0xd8

   __DATA_CONST.__kalloc_var: 0x320
   __DATA_CONST.__auth_got: 0x310
   __DATA_CONST.__got: 0x188
-  Functions: 1075
+  Functions: 1076
   Symbols:   1422
-  CStrings:  853
+  CStrings:  854
 
Symbols:
+ __ZN26AppleHIDTransportDeviceSPI18disableAccessGatedEb
- __ZN23AppleHIDTransportDevice18disableAccessGatedEb
Functions:
~ __ZN26AppleHIDTransportDeviceSPI15enableInterruptEv : 460 -> 464
~ __ZN26AppleHIDTransportDeviceSPI16disableInterruptEv : 472 -> 492
~ __ZN26AppleHIDTransportDeviceSPI7powerOnEv : 680 -> 800
+ __ZN26AppleHIDTransportDeviceSPI18disableAccessGatedEb
~ __ZN26AppleHIDTransportDeviceSPI22createEnumerationCacheEv : 248 -> 160
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/hidspi/HSMDevice.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/hidspi/HSMDeviceInterface.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/hidspi/HSMDeviceTest.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/hidspi/HSMHIDInterface.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/hidspi/HSMParserTest.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/hidspi/HSMSPITest.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/hidspi/HSMTransferDevice.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/hidspi/HSMTransferTest.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/hidspi/HSParserDevice.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/hidspi/HSParserTest.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/hidspi/HSTransferTest.h"
+ "[0x%llx][%llx][%s::%s]: Ignoring power on because there is no interrupt event source"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/hidspi/HSMDevice.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/hidspi/HSMDeviceInterface.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/hidspi/HSMDeviceTest.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/hidspi/HSMHIDInterface.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/hidspi/HSMParserTest.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/hidspi/HSMSPITest.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/hidspi/HSMTransferDevice.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/hidspi/HSMTransferTest.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/hidspi/HSParserDevice.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/hidspi/HSParserTest.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/hidspi/HSTransferTest.h"
```
