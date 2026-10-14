## ReplicatorDependencies

> `/System/Library/PrivateFrameworks/ReplicatorDependencies.framework/Versions/A/ReplicatorDependencies`

```diff

-176.2.5.0.0
-  __TEXT.__text: 0x273a4
+176.2.6.0.0
+  __TEXT.__text: 0x27540
   __TEXT.__objc_methlist: 0x314
-  __TEXT.__const: 0x1ce4
+  __TEXT.__const: 0x1d14
   __TEXT.__swift5_typeref: 0xbb4
-  __TEXT.__swift5_reflstr: 0x898
+  __TEXT.__swift5_reflstr: 0x8a8
   __TEXT.__swift5_assocty: 0x180
   __TEXT.__constg_swiftt: 0x111c
   __TEXT.__swift5_fieldmd: 0xa5c
   __TEXT.__swift5_builtin: 0x3c
   __TEXT.__swift5_proto: 0x130
   __TEXT.__swift5_types: 0xac
-  __TEXT.__oslogstring: 0x1011
+  __TEXT.__oslogstring: 0x1141
   __TEXT.__cstring: 0x531
   __TEXT.__swift5_capture: 0x48c
   __TEXT.__swift_as_entry: 0x28

   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x20f8
-  __AUTH_CONST.__objc_const: 0x12c8
+  __AUTH_CONST.__objc_const: 0x12a8
   __AUTH_CONST.__auth_got: 0x9f0
   __DATA.__data: 0x250
   __DATA.__bss: 0x1610
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0x3f0
-  __DATA_DIRTY.__data: 0x1290
+  __DATA_DIRTY.__data: 0x1280
   __DATA_DIRTY.__bss: 0x900
   __DATA_DIRTY.__common: 0x30
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
Functions:
~ sub_2a09fec08 -> sub_2a127ac08 : 152 -> 192
~ sub_2a09feca0 -> sub_2a127acc8 : 8 -> 16
~ sub_2a09feea4 -> sub_2a127aed4 : 152 -> 192
~ sub_2a0a06740 -> sub_2a1282798 : 768 -> 772
~ sub_2a0a0a8ac -> sub_2a1286908 : 1564 -> 1580
~ sub_2a0a117c4 -> sub_2a128d830 : 216 -> 224
~ sub_2a0a1317c -> sub_2a128f1f0 : 48 -> 112
~ sub_2a0a13f30 -> sub_2a128ffe4 : 1536 -> 1652
~ sub_2a0a14584 -> sub_2a12906ac : 1776 -> 1888
~ sub_2a0a14c74 -> sub_2a1290e0c : 2540 -> 2644
~ sub_2a0a15660 -> sub_2a1291860 : 800 -> 864
~ sub_2a0a15980 -> sub_2a1291bc0 : 1944 -> 2032
~ sub_2a0a161c8 -> sub_2a1292460 : 712 -> 776
~ sub_2a0a16490 -> sub_2a1292768 : 4572 -> 4796
~ sub_2a0a176d0 -> sub_2a1293a88 : 100 -> 92
~ sub_2a0a17734 -> sub_2a1293ae4 : 112 -> 104
~ sub_2a0a179bc -> sub_2a1293d64 : 52 -> 116
~ sub_2a0a17a00 -> sub_2a1293de8 : 2724 -> 2536
~ sub_2a0a184a4 -> sub_2a12947d0 : 2768 -> 2472
~ sub_2a0a199c4 -> sub_2a1295bc8 : 36 -> 28
~ sub_2a0a1bd64 -> sub_2a1297f60 : 3304 -> 3168
~ sub_2a0a23420 -> sub_2a129f594 : 380 -> 420
CStrings:
+ "%{public}llu:%{private}s: Cannot create NWConnection from nw_connection_t"
+ "%{public}llu:%{private}s: Connection cancelled"
+ "%{public}llu:%{private}s: Connection failed and entered waiting state: %{public}s"
+ "%{public}llu:%{private}s: Connection failed with no reported error"
+ "%{public}llu:%{private}s: Connection failed: %{public}s"
+ "%{public}llu:%{private}s: Connection ready"
+ "%{public}llu:%{private}s: Connection state changed; state: %{public}s"
+ "%{public}llu:%{private}s: Connection state changed; state: %{public}s; error: %{public}s"
+ "%{public}llu:%{private}s: Failed to send file %{public}s error: %{public}s"
+ "%{public}llu:%{private}s: Failed to send message data: %{public}s"
+ "%{public}llu:%{private}s: New outgoing connection created to %{public}s"
+ "%{public}llu:%{private}s: Ready to receive %{public}u bytes"
+ "%{public}llu:%{private}s: Received %{public}ld bytes"
+ "%{public}llu:%{private}s: Received error: %{public}s"
+ "%{public}llu:%{private}s: Received nil data"
+ "%{public}llu:%{private}s: Sending file %{public}s; maximumLength: %{public}ld"
+ "%{public}llu:%{private}s: Sent %{public}ld bytes"
+ "%{public}llu:%{private}s: Sent file %{public}s; maximumLength: %{public}ld; totalBytesSent: %{public}ld"
+ "%{public}llu:%{private}s: Starting connection"
+ "%{public}s: %{public}s %{private}s will be used for connection: %{public}s"
+ "%{public}s: Browser found device with ID: %{private}s; name: %{private}s; isMeDevice: %{bool,public}d"
+ "%{public}s: Monitor found remote device with ID %{private}s but it is not the 'me' device"
+ "%{public}s: Monitor found remote device with ID: %{private}s"
+ "%{public}s: Received new connection: %{public}s: DeviceID: %{private}s"
+ "%{public}s: Unable to get DeviceID from connection: %{public}s: Using uuidString %{private}s instead"
+ "Fetched IDS device: %{private}s; isCloudPaired: %{bool,public}d"
+ "Finding active paired device in devices: %{private}s"
+ "IDS PairedDevice is %{private}s"
+ "[?:%{private}s]: Creating %{public}s connection for %{public}s"
- "%{public}s: %{public}s %{public}s will be used for connection: %{public}s"
- "%{public}s: Browser found device with ID: %{public}s; name: %{public}s; isMeDevice: %{bool,public}d"
- "%{public}s: Cannot create NWConnection from nw_connection_t"
- "%{public}s: Connection cancelled"
- "%{public}s: Connection failed and entered waiting state: %{public}s"
- "%{public}s: Connection failed with no reported error"
- "%{public}s: Connection failed: %{public}s"
- "%{public}s: Connection ready"
- "%{public}s: Connection state changed; state: %{public}s"
- "%{public}s: Connection state changed; state: %{public}s; error: %{public}s"
- "%{public}s: Failed to send file %{public}s error: %{public}s"
- "%{public}s: Failed to send message data: %{public}s"
- "%{public}s: Monitor found remote device with ID %{public}s but it is not the 'me' device"
- "%{public}s: Monitor found remote device with ID: %{public}s"
- "%{public}s: New outgoing connection created to %{public}s; deviceID: %{public}s"
- "%{public}s: Ready to receive %u bytes"
- "%{public}s: Received %{public}ld bytes"
- "%{public}s: Received error: %{public}s"
- "%{public}s: Received new connection: %{public}s: DeviceID: %{public}s"
- "%{public}s: Received nil data"
- "%{public}s: Sending file %{public}s; maximumLength: %{public}ld"
- "%{public}s: Sent %ld bytes"
- "%{public}s: Sent file %{public}s; maximumLength: %{public}ld; totalBytesSent: %{public}ld"
- "%{public}s: Starting connection"
- "%{public}s: Unable to get DeviceID from connection: %{public}s: Using uuidString %{public}s instead"
- "Fetched IDS device: %{public}s; isCloudPaired: %{bool,public}d"
- "Finding active paired device in devices: %{public}s"
- "IDS PairedDevice is %{public}s"
- "[?:%s]: Creating %s connection for %{public}s"
```
