## BTLEServer

> `/usr/sbin/BTLEServer`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2701.2.0.0.0
-  __TEXT.__text: 0x48aa8
+2701.3.0.0.0
+  __TEXT.__text: 0x48de0
   __TEXT.__auth_stubs: 0xc70
-  __TEXT.__objc_stubs: 0x7180
-  __TEXT.__objc_methlist: 0x489c
+  __TEXT.__objc_stubs: 0x71e0
+  __TEXT.__objc_methlist: 0x48ac
   __TEXT.__objc_classname: 0x524
   __TEXT.__objc_methtype: 0x1b55
-  __TEXT.__cstring: 0x1f82
+  __TEXT.__cstring: 0x1f8d
   __TEXT.__const: 0x680
-  __TEXT.__objc_methname: 0xaf11
-  __TEXT.__oslogstring: 0x70ae
+  __TEXT.__objc_methname: 0xaf62
+  __TEXT.__oslogstring: 0x7198
   __TEXT.__gcc_except_tab: 0x10a8
   __TEXT.__ustring: 0xbe
-  __TEXT.__unwind_info: 0x1760
+  __TEXT.__unwind_info: 0x1768
   __DATA_CONST.__const: 0xe98
-  __DATA_CONST.__cfstring: 0x25a0
+  __DATA_CONST.__cfstring: 0x25e0
   __DATA_CONST.__objc_classlist: 0x190
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x88
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x160
-  __DATA_CONST.__objc_intobj: 0x570
+  __DATA_CONST.__objc_intobj: 0x5b8
   __DATA_CONST.__objc_arraydata: 0x1b8
   __DATA_CONST.__objc_arrayobj: 0xc0
   __DATA_CONST.__objc_doubleobj: 0x10
   __DATA_CONST.__auth_got: 0x650
-  __DATA_CONST.__got: 0x510
+  __DATA_CONST.__got: 0x518
   __DATA_CONST.__auth_ptr: 0x20
   __DATA.__objc_const: 0x9a88
-  __DATA.__objc_selrefs: 0x26b0
+  __DATA.__objc_selrefs: 0x26c8
   __DATA.__objc_ivar: 0x4f0
   __DATA.__objc_data: 0xfa0
   __DATA.__data: 0x660

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1802
-  Symbols:   366
-  CStrings:  3075
+  Functions: 1803
+  Symbols:   367
+  CStrings:  3083
 
Symbols:
+ _OBJC_CLASS_$_UARPDeviceProperties
CStrings:
+ "Classic"
+ "LE"
+ "decOpportunisticConnection only supported for LE peripherals (%u)"
+ "decOpportunisticConnection refCount:%ld %@ (%@)"
+ "deviceInactivityTimeout for device %@"
+ "didUpdateNotificationStateForCharacteristic - peripheral:%@ characteristic:%@ error:%@ transport:%@"
+ "incOpportunisticConnection only supported for LE peripherals. Current peripheral is connected over %@ (%@)"
+ "incOpportunisticConnection refCount:%ld %@ (%@)"
+ "initWithUUID:delegate:delegateQueue:deviceProperties:"
+ "setNumPacketRetries:"
+ "setTimeoutActivity:"
+ "setTimeoutPacketRetry:"
- "decOpportunisticConnection refCount:%ld %@"
- "didUpdateNotificationStateForCharacteristic - peripheral:%@ characteristic:%@ error:%@"
- "incOpportunisticConnection refCount:%ld %@"
- "initWithUUID:delegate:delegateQueue:"
```
