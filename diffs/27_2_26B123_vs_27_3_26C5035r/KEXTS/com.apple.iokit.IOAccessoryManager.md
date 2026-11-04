## com.apple.iokit.IOAccessoryManager

> `com.apple.iokit.IOAccessoryManager`

```diff

-1068.40.6.0.0
+1068.60.2.0.0
   __TEXT.__const: 0x2b8
-  __TEXT.__cstring: 0x110ec
-  __TEXT.__os_log: 0x12155
-  __TEXT_EXEC.__text: 0xe4fe0
+  __TEXT.__cstring: 0x11239
+  __TEXT.__os_log: 0x12360
+  __TEXT_EXEC.__text: 0xe5818
   __TEXT_EXEC.__auth_stubs: 0xbc0
   __DATA.__data: 0x7e8
   __DATA.__common: 0x16b8
   __DATA.__bss: 0x142
   __DATA_CONST.__mod_init_func: 0x348
   __DATA_CONST.__mod_term_func: 0x340
-  __DATA_CONST.__const: 0x43268
+  __DATA_CONST.__const: 0x432a8
   __DATA_CONST.__kalloc_type: 0x2500
   __DATA_CONST.__auth_got: 0x5e0
   __DATA_CONST.__got: 0x1e8
   __DATA_CONST.__auth_ptr: 0x20
-  Functions: 5013
-  Symbols:   7296
-  CStrings:  2963
+  Functions: 5019
+  Symbols:   7308
+  CStrings:  2975
 
Symbols:
+ __ZN29IOAccessoryHIDDeviceInterface22_publishEndpointsGatedEb
+ __ZN29IOAccessoryHIDDeviceInterface24_armEndpointPublishGatedEv
+ __ZN32IOAccessoryConfigStreamInterface28_signalAccessoryInfoCompleteEv
+ __ZNK29IOAccessoryHIDDeviceInterface32_configStreamEnumerationCompleteEv
+ __ZZN29IOAccessoryHIDDeviceInterface22_publishEndpointsGatedEbE11_os_log_fmt
+ __ZZN29IOAccessoryHIDDeviceInterface24_armEndpointPublishGatedEvE11_os_log_fmt
+ __ZZN29IOAccessoryHIDDeviceInterface5startEP9IOServiceE11_os_log_fmt
+ __ZZN32IOAccessoryConfigStreamInterface28_signalAccessoryInfoCompleteEvE11_os_log_fmt
+ __ZZZN29IOAccessoryHIDDeviceInterface5startEP9IOServiceEUb0_E11_os_log_fmt
+ __ZZZN29IOAccessoryHIDDeviceInterface5startEP9IOServiceEUb1_E11_os_log_fmt
+ __ZZZN29IOAccessoryHIDDeviceInterface5startEP9IOServiceEUb1_E11_os_log_fmt_0
+ __ZZZN29IOAccessoryHIDDeviceInterface5startEP9IOServiceEUb1_E11_os_log_fmt_1
+ ____ZN29IOAccessoryHIDDeviceInterface5startEP9IOService_block_invoke_2
+ ____ZN29IOAccessoryHIDDeviceInterface5startEP9IOService_block_invoke_3
+ ____ZN29IOAccessoryHIDDeviceInterface5startEP9IOService_block_invoke_4
- __ZZZN29IOAccessoryHIDDeviceInterface5startEP9IOServiceEUb_E11_os_log_fmt_0
- __ZZZN29IOAccessoryHIDDeviceInterface5startEP9IOServiceEUb_E11_os_log_fmt_1
- ____ZN29IOAccessoryHIDDeviceInterface17_handleStartGatedEv_block_invoke_2
CStrings:
+ "%s::%s(): ConfigStream info changed\n"
+ "%s:IOAccessoryConfigStreamInterface::%s accessory info strings are final \n"
+ "%s:IOAccessoryHIDDeviceInterface::%s deferring endpoint publication, ConfigStream enumerating (deadline %d s) \n"
+ "%s:IOAccessoryHIDDeviceInterface::%s publishing %u endpoint(s), ConfigStream complete=%d, deadlineReached=%d \n"
+ "12111112122212121121211122111211112"
+ "IOAccessoryConfigStreamEnumerationComplete"
+ "[ERROR] %s:IOAccessoryHIDDeviceInterface::%s could not arm ConfigStream deadline, publishing now \n"
+ "[ERROR] %s:IOAccessoryHIDDeviceInterface::%s could not create ConfigStream deadline timer \n"
+ "[ERROR] %s:IOAccessoryHIDDeviceInterface::%s failed to publish endpoints! ret %#x \n"
+ "[ERROR] %s:IOAccessoryHIDDeviceInterface::configStreamDeadline ConfigStream did not finish enumerating within %d s, publishing anyway \n"
+ "_armEndpointPublishGated"
+ "_publishEndpointsGated"
+ "_signalAccessoryInfoComplete"
+ "start_block_invoke_2"
- "121111121222121211212111221112112"
- "_handleStartGated_block_invoke_2"
```
