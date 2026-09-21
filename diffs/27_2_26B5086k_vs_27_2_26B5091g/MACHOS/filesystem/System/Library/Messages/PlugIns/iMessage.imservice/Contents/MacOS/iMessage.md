## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/Contents/MacOS/iMessage`

### Sections with Same Size but Changed Content

- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`

```diff

-1491.200.63.0.0
-  __TEXT.__text: 0x11ac74
-  __TEXT.__auth_stubs: 0x2200
-  __TEXT.__objc_stubs: 0xee00
-  __TEXT.__objc_methlist: 0x33d4
-  __TEXT.__const: 0x15b8
-  __TEXT.__gcc_except_tab: 0x9630
-  __TEXT.__cstring: 0x3efd
-  __TEXT.__oslogstring: 0x1c13b
-  __TEXT.__objc_classname: 0x83f
-  __TEXT.__objc_methname: 0x1593a
-  __TEXT.__objc_methtype: 0x360b
+1491.200.73.0.0
+  __TEXT.__text: 0x12105c
+  __TEXT.__auth_stubs: 0x2290
+  __TEXT.__objc_stubs: 0xf000
+  __TEXT.__objc_methlist: 0x3444
+  __TEXT.__const: 0x15a8
+  __TEXT.__gcc_except_tab: 0x9658
+  __TEXT.__cstring: 0x410d
+  __TEXT.__oslogstring: 0x1c75b
+  __TEXT.__objc_classname: 0x87f
+  __TEXT.__objc_methname: 0x15c7a
+  __TEXT.__objc_methtype: 0x362b
   __TEXT.__ustring: 0x4
-  __TEXT.__swift5_typeref: 0xe6e
+  __TEXT.__swift5_typeref: 0xed4
   __TEXT.__constg_swiftt: 0x654
   __TEXT.__swift5_reflstr: 0x563
   __TEXT.__swift5_fieldmd: 0x5d4

   __TEXT.__swift_as_entry: 0x9c
   __TEXT.__swift_as_ret: 0xc0
   __TEXT.__swift_as_cont: 0x13c
-  __TEXT.__swift5_capture: 0x9d4
+  __TEXT.__swift5_capture: 0x9f8
   __TEXT.__swift5_assocty: 0x60
   __TEXT.__swift5_builtin: 0x78
   __TEXT.__swift5_mpenum: 0x38
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x34e0
+  __TEXT.__unwind_info: 0x3570
   __TEXT.__eh_frame: 0x1a80
-  __DATA_CONST.__const: 0x5a78
-  __DATA_CONST.__cfstring: 0x3ce0
+  __DATA_CONST.__const: 0x5b40
+  __DATA_CONST.__cfstring: 0x3d40
   __DATA_CONST.__objc_classlist: 0x138
   __DATA_CONST.__objc_catlist: 0x48
-  __DATA_CONST.__objc_protolist: 0x88
+  __DATA_CONST.__objc_protolist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_protorefs: 0x18
+  __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0xb8
   __DATA_CONST.__objc_intobj: 0x3c0
   __DATA_CONST.__objc_arraydata: 0x28
   __DATA_CONST.__objc_arrayobj: 0x60
   __DATA_CONST.__objc_doubleobj: 0x20
-  __DATA_CONST.__auth_got: 0x1110
-  __DATA_CONST.__got: 0x1320
+  __DATA_CONST.__auth_got: 0x1158
+  __DATA_CONST.__got: 0x1370
   __DATA_CONST.__auth_ptr: 0x338
-  __DATA.__objc_const: 0x4110
-  __DATA.__objc_selrefs: 0x4290
+  __DATA.__objc_const: 0x4168
+  __DATA.__objc_selrefs: 0x4318
   __DATA.__objc_ivar: 0x28c
   __DATA.__objc_data: 0xf30
-  __DATA.__data: 0xef8
-  __DATA.__bss: 0x1070
+  __DATA.__data: 0xff8
+  __DATA.__bss: 0x1090
   __DATA.__common: 0x38
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2710
-  Symbols:   923
-  CStrings:  5366
+  Functions: 2742
+  Symbols:   929
+  CStrings:  5424
 
Symbols:
+ _OBJC_CLASS_$_ABCRemoteDebuggingRequest
+ _OBJC_CLASS_$_EndpointRemoteDebuggingDestination
+ _OBJC_CLASS_$_ExistingRadarRemoteDebuggingRequest
+ _OBJC_CLASS_$_IDSHandle
+ _OBJC_CLASS_$_IMTapToRadarDraft
+ _OBJC_CLASS_$_NewRadarRemoteDebuggingRequest
CStrings:
+ " hit a bug in your conversation and is asking you to add to a radar from this device."
+ " hit a bug in your conversation and is asking you to file a radar from this device."
+ "@\"NSSet\"16@0:8"
+ "CKV failure"
+ "Discarding a TTR request identifier, it has characters outside [A-Za-z0-9-_.]"
+ "Discarding a TTR request identifier, it is longer than %ld characters"
+ "Discarding a TTR request radar number, it is not a plain number"
+ "Failed sending TTR request %s to %s, error: %u"
+ "Finished sending TTR request %s to %s"
+ "Ignoring a TTR request from %s, could not decode its payload"
+ "Ignoring a TTR request from %s, disabled by %s"
+ "Ignoring a TTR request from %s, no known debug request included"
+ "Ignoring a TTR request from %s, not an internal install"
+ "Ignoring a TTR request, disabled by the %s server bag"
+ "No known remote debugging request type, not sending request"
+ "Not sending CKV failure remote debugging request, could not build a prefixed URI from %@"
+ "Not sending a TTR request %s, could not encode %s"
+ "Not sending a TTR request %s, device is not registered for account %s"
+ "Not sending a TTR request %s, disabled by the %s server bag"
+ "Not sending a TTR request %s, no destination"
+ "Not sending a TTR request %s, not an internal install"
+ "Please describe what you saw on this device."
+ "Received a TTR request from %s for a new radar, asking whether to file"
+ "Received a TTR request from %s for radar %s, asking whether to file"
+ "Received an ABC request from %s"
+ "Received an invalid existing radar number in a TTR request from %s"
+ "Received generic command for remote debugging"
+ "RemoteDebugging"
+ "RemoteDebuggingDestination"
+ "RemoteDebuggingReceiveEnabled"
+ "RemoteDebuggingRequest"
+ "Sending TTR request %s to %s for %s"
+ "T@\"NSSet\",R,N"
+ "[Messages] Remote TTR Request"
+ "_requestRemoteDebuggingIfNeededForPolicyResult:account:fromIdentifier:messageIdentifier:"
+ "ckv-failure"
+ "com.apple.Messages.RemoteDebuggingRequest."
+ "com.apple.MobileSMS"
+ "defaults"
+ "existingRadarNumber"
+ "extractCKVFailedEndpointsExcluding:"
+ "handler:remoteDebuggingRequest:fromIdentifier:fromIDSID:"
+ "handles"
+ "iMessageServerBag"
+ "initWithEndpoints:"
+ "initWithReason:relatedGUID:relatedGUIDType:identifier:version:"
+ "initWithUnprefixedURI:"
+ "invalid payload, no usable identifier or debuggingRequestVersion in remote debugging request"
+ "lockdownManager"
+ "openExistingRadarNumber:notificationIdentifier:notificationTitle:notificationBody:rateLimitInterval:rateLimitKeySuffix:version:"
+ "receivedRemoteDebuggingRequest:fromIdentifier:fromIDSID:"
+ "relatedGUID"
+ "relatedGUIDType"
+ "remote-debugging-receive-enabled"
+ "remote-debugging-send-enabled"
+ "remoteDebugging-allowAll-v1"
+ "sendRemoteDebuggingRequest:destination:fromIdentifier:idsAccount:"
+ "skippedAllDestinationsCache"
+ "submitAndOpenTapToRadarWithNotificationIdentifier:notificationTitle:notificationBody:draftTitle:problemDescription:attachments:deviceClasses:classification:reproducibility:rateLimitInterval:rateLimitKeySuffix:version:"
+ "toURIs"
- "noEligibleDestinationsCache"
- "setHadNoEligibleDestinations:forMessageGUID:"
```
