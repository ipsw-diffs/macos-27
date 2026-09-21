## com.apple.driver.usb.cdc.ncm

> `com.apple.driver.usb.cdc.ncm`

```diff

-404.0.0.0.0
-  __TEXT.__cstring: 0x240c
+404.40.2.0.0
+  __TEXT.__cstring: 0x2483
   __TEXT.__const: 0xca
-  __TEXT_EXEC.__text: 0xcc14
+  __TEXT_EXEC.__text: 0xccf8
   __TEXT_EXEC.__auth_stubs: 0x5b0
   __DATA.__data: 0xc8
   __DATA.__common: 0x100

   __DATA_CONST.__got: 0x88
   Functions: 354
   Symbols:   972
-  CStrings:  238
+  CStrings:  240
 
Functions:
~ __ZN17AppleUSBNCM11Data15selectNTBFormatEv : 156 -> 252
~ __ZN15AppleUSBNCMData7armReadEP15InputPipeRecord : 404 -> 536
CStrings:
+ "Patching invalid NCM 1.1 NTB parameter wNdpInAlignment %d\n"
+ "Patching invalid NCM 1.1 NTB parameter wNdpOutAlignment %d\n"
```
