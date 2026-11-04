## libquic.dylib

> `/usr/lib/libquic.dylib`

```diff

-6681.41.1.0.0
-  __TEXT.__text: 0xd0174
+6681.60.32.0.0
+  __TEXT.__text: 0xd059c
   __TEXT.__objc_methlist: 0x244
   __TEXT.__const: 0x3a5
   __TEXT.__cstring: 0x8907
-  __TEXT.__oslogstring: 0x12684
-  __TEXT.__unwind_info: 0x12e0
+  __TEXT.__oslogstring: 0x1271c
+  __TEXT.__unwind_info: 0x12e8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __AUTH_CONST.__const: 0x1870
   __AUTH_CONST.__cfstring: 0x1320
   __AUTH_CONST.__objc_const: 0xf8
-  __AUTH_CONST.__auth_got: 0xd48
+  __AUTH_CONST.__auth_got: 0xd50
   __AUTH.__objc_data: 0x28
   __AUTH.__data: 0x118
   __DATA.__objc_ivar: 0xc

   - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1172
-  Symbols:   1700
-  CStrings:  2623
+  Functions: 1173
+  Symbols:   1702
+  CStrings:  2625
 
Symbols:
+ _nw_quic_connection_add_derived_tls_epsk
+ _quic_packet_insert_frame
Functions:
+ _quic_packet_insert_frame
~ ___quic_crypto_tls_start_block_invoke : 1192 -> 1208
~ _quic_crypto_setup_flow_control : 1576 -> 1604
~ _quic_fc_setup_stream : 1964 -> 1992
~ _quic_stream_send_create : 3120 -> 3308
~ _quic_conn_can_send_frames : 1332 -> 1548
~ _quic_conn_send_internal : 908 -> 936
~ __quic_packet_builder_calculate_size : 2052 -> 2204
~ __quic_packet_builder_assemble : 6836 -> 7016
CStrings:
+ "%{public}s deferring DATAGRAM flow: real transport parameters not yet available"
+ "%{public}s outbound data is pending, but in 0-RTT phase, sending anyway"
```
