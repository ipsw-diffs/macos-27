## srp-mdns-proxy

> `/usr/libexec/srp-mdns-proxy`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 3111.40.45.0.0
-  __TEXT.__text: 0x8e46c
+  __TEXT.__text: 0x8e8e0
   __TEXT.__auth_stubs: 0x14f0
   __TEXT.__const: 0x2f5
-  __TEXT.__cstring: 0x91d2
-  __TEXT.__oslogstring: 0x1419c
-  __TEXT.__unwind_info: 0x848
+  __TEXT.__cstring: 0x92af
+  __TEXT.__oslogstring: 0x14402
+  __TEXT.__unwind_info: 0x858
   __TEXT.__eh_frame: 0x7c
   __DATA_CONST.__const: 0x920
   __DATA_CONST.__cfstring: 0x140

   - /usr/lib/libmrc.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 481
-  Symbols:   1120
-  CStrings:  2609
+  Functions: 485
+  Symbols:   1124
+  CStrings:  2616
 
Symbols:
+ _thread_netdata_decode_6lowpan_id_payload
+ _thread_netdata_decode_prefix_payload
+ _thread_netdata_decode_server_payload
+ _thread_netdata_decode_service_payload
CStrings:
+ "%{public}s: TLV length %zu exceeds the %d byte maximum"
+ "%{public}s: dns_concatenate_name_to_wire: called at %{public}s:%d with both prefix and labels_prefix non-NULL (labels_prefix = %p, prefix = %p, suffix = %p)"
+ "%{public}s: dns_concatenate_name_to_wire: called at %{public}s:%d with both suffix and labels_prefix including a terminal label (labels_prefix = %p, prefix = %p, suffix = %p)"
+ "%{public}s: dns_concatenate_name_to_wire: called at %{public}s:%d with no way to terminate the name (labels_prefix = %p, prefix = %p, suffix = %p)"
+ "%{public}s: service TLV value must be at least 6 bytes long (was %u bytes long)"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/mDNSResponderExtras/ServiceRegistration/wireutils.c"
+ "23:53:55"
+ "Oct  7 2026"
+ "dns_concatenate_name_to_wire_"
- "01:31:23"
- "Oct  8 2026"
```
