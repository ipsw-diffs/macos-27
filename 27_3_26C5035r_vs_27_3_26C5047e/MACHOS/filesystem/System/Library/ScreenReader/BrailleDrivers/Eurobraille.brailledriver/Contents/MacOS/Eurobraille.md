## Eurobraille

> `/System/Library/ScreenReader/BrailleDrivers/Eurobraille.brailledriver/Contents/MacOS/Eurobraille`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protorefs`

```diff

-1050.3.12.0.0
-  __TEXT.__text: 0x25cc
-  __TEXT.__auth_stubs: 0x330
-  __TEXT.__objc_stubs: 0x4e0
-  __TEXT.__objc_methlist: 0x434
-  __TEXT.__const: 0x60
-  __TEXT.__oslogstring: 0x8b3
-  __TEXT.__objc_methname: 0x8aa
-  __TEXT.__objc_classname: 0x98
-  __TEXT.__objc_methtype: 0x248
-  __TEXT.__cstring: 0x274
-  __TEXT.__unwind_info: 0xc0
-  __DATA_CONST.__const: 0xe0
+1050.3.22.0.0
+  __TEXT.__text: 0x3a80
+  __TEXT.__auth_stubs: 0x4b0
+  __TEXT.__objc_stubs: 0x840
+  __TEXT.__objc_methlist: 0x514
+  __TEXT.__const: 0x68
+  __TEXT.__oslogstring: 0xa87
+  __TEXT.__objc_methname: 0xb9a
+  __TEXT.__objc_classname: 0xc9
+  __TEXT.__objc_methtype: 0x2f7
+  __TEXT.__cstring: 0x2a6
+  __TEXT.__unwind_info: 0x120
+  __DATA_CONST.__const: 0x158
   __DATA_CONST.__cfstring: 0x200
-  __DATA_CONST.__objc_classlist: 0x8
-  __DATA_CONST.__objc_protolist: 0x30
+  __DATA_CONST.__objc_classlist: 0x10
+  __DATA_CONST.__objc_protolist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x8
-  __DATA_CONST.__auth_got: 0x1a0
-  __DATA_CONST.__got: 0x60
-  __DATA.__objc_const: 0x6e0
-  __DATA.__objc_selrefs: 0x310
-  __DATA.__objc_ivar: 0x68
-  __DATA.__objc_data: 0x50
-  __DATA.__data: 0x240
+  __DATA_CONST.__objc_superrefs: 0x10
+  __DATA_CONST.__auth_got: 0x260
+  __DATA_CONST.__got: 0x98
+  __DATA.__objc_const: 0x900
+  __DATA.__objc_selrefs: 0x400
+  __DATA.__objc_ivar: 0x90
+  __DATA.__objc_data: 0xa0
+  __DATA.__data: 0x2a0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/IOBluetooth.framework/Versions/A/IOBluetooth

   - /System/Library/PrivateFrameworks/ScreenReader.framework/Versions/A/Frameworks/ScreenReaderOutput.framework/Versions/A/ScreenReaderOutput
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 34
-  Symbols:   75
-  CStrings:  227
+  Functions: 52
+  Symbols:   102
+  CStrings:  290
 
Symbols:
+ _CFDataDeleteBytes
+ _CFDataGetBytePtr
+ _CFDataGetLength
+ _CFRunLoopAddSource
+ _IONotificationPortCreate
+ _IONotificationPortDestroy
+ _IONotificationPortGetRunLoopSource
+ _IOObjectConformsTo
+ _IOObjectRetain
+ _IORegistryEntryCreateIterator
+ _IOServiceAddInterestNotification
+ _OBJC_CLASS_$_NSFileHandle
+ _OBJC_CLASS_$_NSLock
+ _OBJC_CLASS_$_NSThread
+ _OBJC_CLASS_$_SCRDFileReader
+ _OBJC_CLASS_$_SCRDUSBDevice
+ _SCRDSerialDeviceCalloutDevicePath
+ _SCRDSerialDeviceOpenSerialPortForPath
+ ___error
+ _cfmakeraw
+ _cfsetspeed
+ _objc_alloc_init
+ _poll
+ _tcflush
+ _tcgetattr
+ _tcsetattr
+ _write
CStrings:
+ "@\"NSArray\""
+ "@\"NSLock\""
+ "@\"SCRDFileReader\""
+ "@24@0:8@16"
+ "B20@0:8B16"
+ "B32@0:8r^v16Q24"
+ "Eurobraille USB serial ports [%{public}@]"
+ "Failed to load Eurobraille braille driver because no serial port could be opened"
+ "Failed to load Eurobraille braille driver because of unexpected vendor id [%ld] product id [%ld]"
+ "Failed to load Eurobraille braille driver because we could not register for disconnect notifications"
+ "Failed to open Eurobraille serial port [%{public}@], errno [%d]"
+ "I"
+ "IOGeneralInterest"
+ "IOSerialBSDClient"
+ "IOService"
+ "Loaded Eurobraille braille driver over USB serial. Model [%{public}@], ports [%lu]"
+ "SCRDFileReaderDelegate"
+ "SCROEurobrailleSerialPort"
+ "T@\"NSString\",R,N,V_path"
+ "T^{__CFData=},R,N,V_parseBuffer"
+ "^{IONotificationPort=}"
+ "^{__CFData=}16@0:8"
+ "_fileDescriptor"
+ "_fillWriteBufferWithMainCells:length:"
+ "_notification"
+ "_notificationPort"
+ "_parseBuffer"
+ "_path"
+ "_reader"
+ "_receivedBytes"
+ "_receivedBytesLock"
+ "_serialPorts"
+ "_usbDeviceObject"
+ "_usbSerialGetInputEvents"
+ "_usbSerialLoadDriverWithIOElement:"
+ "_usbSerialRegisterForDisconnectNotifications:"
+ "_usbSerialSetMainCells:length:"
+ "_usbSerialTearDown"
+ "addObjectsFromArray:"
+ "array"
+ "close"
+ "compare:"
+ "copy"
+ "fileReader:data:length:"
+ "initWithDelegate:fileHandle:"
+ "initWithFileDescriptor:closeOnDealloc:"
+ "initWithIOObject:"
+ "initWithPath:"
+ "invalidate"
+ "lock"
+ "makeObjectsPerformSelector:"
+ "moveReceivedBytesToParseBuffer"
+ "open"
+ "parseBuffer"
+ "path"
+ "product"
+ "sleepForTimeInterval:"
+ "sortedArrayUsingSelector:"
+ "start"
+ "unlock"
+ "v40@0:8@\"SCRDFileReader\"16r^v24Q32"
+ "v40@0:8@16r^v24Q32"
+ "vendor"
+ "writeBytes:length:"
- "!\xa1"
```
