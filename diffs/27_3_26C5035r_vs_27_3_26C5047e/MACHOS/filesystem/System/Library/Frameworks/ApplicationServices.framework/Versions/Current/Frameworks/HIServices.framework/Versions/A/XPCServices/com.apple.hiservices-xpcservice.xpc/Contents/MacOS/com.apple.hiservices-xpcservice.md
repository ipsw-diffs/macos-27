## com.apple.hiservices-xpcservice

> `/System/Library/Frameworks/ApplicationServices.framework/Versions/Current/Frameworks/HIServices.framework/Versions/A/XPCServices/com.apple.hiservices-xpcservice.xpc/Contents/MacOS/com.apple.hiservices-xpcservice`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-835.6.0.0.0
-  __TEXT.__text: 0x46d0
-  __TEXT.__auth_stubs: 0x810
-  __TEXT.__objc_stubs: 0x6e0
-  __TEXT.__objc_methlist: 0x284
-  __TEXT.__const: 0x9c
-  __TEXT.__cstring: 0x105d
-  __TEXT.__gcc_except_tab: 0x108
-  __TEXT.__objc_methname: 0x9c8
-  __TEXT.__oslogstring: 0x350
+835.10.0.0.0
+  __TEXT.__text: 0x7e54
+  __TEXT.__auth_stubs: 0xbf0
+  __TEXT.__objc_stubs: 0x9a0
+  __TEXT.__objc_methlist: 0x29c
+  __TEXT.__const: 0xf0
+  __TEXT.__cstring: 0x190d
+  __TEXT.__gcc_except_tab: 0x11c
+  __TEXT.__objc_methname: 0xb89
+  __TEXT.__oslogstring: 0x636
   __TEXT.__ustring: 0x34
   __TEXT.__objc_classname: 0x12
-  __TEXT.__objc_methtype: 0x1ba
-  __TEXT.__unwind_info: 0x258
-  __DATA_CONST.__const: 0x310
-  __DATA_CONST.__cfstring: 0x1340
+  __TEXT.__objc_methtype: 0x1e9
+  __TEXT.__dlopen_cstrs: 0x44
+  __TEXT.__unwind_info: 0x378
+  __DATA_CONST.__const: 0x938
+  __DATA_CONST.__cfstring: 0x1240
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x8

   __DATA_CONST.__objc_arrayobj: 0xa8
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA_CONST.__objc_intobj: 0x48
-  __DATA_CONST.__auth_got: 0x418
-  __DATA_CONST.__got: 0x110
+  __DATA_CONST.__auth_got: 0x608
+  __DATA_CONST.__got: 0x178
   __DATA.__objc_const: 0x2e0
-  __DATA.__objc_selrefs: 0x270
+  __DATA.__objc_selrefs: 0x320
   __DATA.__objc_ivar: 0x34
   __DATA.__objc_data: 0x50
-  __DATA.__data: 0x4
-  __DATA.__bss: 0x58
+  __DATA.__data: 0x23f8
+  __DATA.__bss: 0x240
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
+  - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
+  - /System/Library/PrivateFrameworks/TCC.framework/Versions/A/TCC
   - /System/Library/PrivateFrameworks/login.framework/Versions/A/login
   - /usr/lib/libSystem.B.dylib
+  - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 120
-  Symbols:   175
-  CStrings:  297
+  Functions: 231
+  Symbols:   250
+  CStrings:  481
 
Symbols:
+ _CFAbsoluteTimeGetCurrent
+ _CFDataGetBytes
+ _CFDataGetLength
+ _CFDictionaryApplyFunction
+ _CFDictionaryContainsKey
+ _CFDictionaryGetCount
+ _CFDictionaryRemoveAllValues
+ _CFDictionaryRemoveValue
+ _CFDictionarySetValue
+ _CFPropertyListCreateData
+ _CFStringCreateWithCString
+ _CFStringCreateWithCStringNoCopy
+ _OBJC_CLASS_$_NSBundle
+ _OBJC_CLASS_$_NSData
+ _OBJC_CLASS_$_NSMutableArray
+ _SANDBOX_CHECK_NO_REPORT
+ ___error
+ ___strlcpy_chk
+ __os_feature_enabled_impl
+ __os_log_error_impl
+ __sl_dlopen
+ __xpc_error_connection_interrupted
+ __xpc_type_array
+ __xpc_type_data
+ __xpc_type_date
+ __xpc_type_double
+ __xpc_type_int64
+ __xpc_type_uuid
+ _abort_report_np
+ _arc4random_buf
+ _audit_token_to_asid
+ _audit_token_to_auid
+ _audit_token_to_egid
+ _audit_token_to_euid
+ _audit_token_to_pid
+ _audit_token_to_pidversion
+ _audit_token_to_rgid
+ _audit_token_to_ruid
+ _bzero
+ _clock_gettime_nsec_np
+ _dispatch_assert_queue$V2
+ _dispatch_async
+ _dispatch_queue_attr_make_with_autorelease_frequency
+ _dispatch_queue_attr_make_with_qos_class
+ _dlsym
+ _getpid
+ _kCFAllocatorNull
+ _kCFBundleVersionKey
+ _malloc_type_calloc
+ _notify_register_dispatch
+ _objc_enumerationMutation
+ _objc_sync_enter
+ _objc_sync_exit
+ _os_state_add_handler
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _responsibility_get_responsible_audit_token_for_audit_token
+ _responsibility_get_responsible_for_pid
+ _sandbox_check
+ _snprintf
+ _strcmp
+ _tcc_events_filter_create_with_criteria
+ _tcc_events_subscribe
+ _tcc_release
+ _xpc_array_apply
+ _xpc_array_get_count
+ _xpc_connection_create_mach_service
+ _xpc_connection_send_barrier
+ _xpc_connection_set_target_uid
+ _xpc_dictionary_create
+ _xpc_dictionary_get_audit_token
+ _xpc_dictionary_get_data
+ _xpc_dictionary_set_bool
+ _xpc_dictionary_set_data
+ _xpc_dictionary_set_int64
+ _xpc_dictionary_set_string
- _strncmp
CStrings:
+ " "
+ "%d"
+ "%d.%d"
+ "%d.%llu:%d.%d:%lld"
+ "%ld"
+ "%s"
+ "-"
+ "/System/Library/PrivateFrameworks/TCC.framework/Contents/MacOS/TCC"
+ "0"
+ "0123456789abcdef"
+ "1"
+ "AX_PER_APP_PERMISSIONS"
+ "AX_TRANSPARENCY_INDICATOR"
+ "B24@?0Q8^v16"
+ "B24@?0r*8^v16"
+ "B32@0:8@16^I24"
+ "Could not create the TCC events filter for accessibility services"
+ "Could not observe %{public}s: %u"
+ "HIS_XPC_AXDisplayInUseReport:"
+ "HIS_XPC_AXDisplayInUseReport: agent connection invalidated"
+ "HIS_XPC_AXDisplayInUseReportFromRequest:"
+ "HIS_XPC_RegisterControlComputerAccessFromSource:"
+ "TCC"
+ "UTF8String"
+ "VerifyXPCDictionary:validity:"
+ "^{os_state_data_s=I(?=b32I){os_state_data_decoder_s=[64c][64c]}[64c][0C]}16@?0^{os_state_hints_s=I*II}8"
+ "accessType"
+ "accessibility"
+ "addModifyAdded"
+ "addObject:"
+ "adhoc"
+ "allKeys"
+ "allocFailed"
+ "allowed"
+ "allowedForSession"
+ "allowedForSessionTime"
+ "allowedForThisApp"
+ "allowedForThisAppSession"
+ "alreadyNotified"
+ "array"
+ "ask"
+ "askEveryTime"
+ "auto"
+ "badLength"
+ "badParams"
+ "badPids"
+ "cacheClears"
+ "cacheFailed"
+ "cached"
+ "canReachTCCD"
+ "client"
+ "clientAuditToken"
+ "com.apple.HISXPC.DisplayInUse"
+ "com.apple.HIServices.accessibility"
+ "com.apple.HIServices.tcc-changes"
+ "com.apple.TCC.%s.authorization.changed"
+ "com.apple.accessibility.AXVisualSupportAgent"
+ "com.apple.accessibility.per-app-access"
+ "com.apple.tcc.access.changed"
+ "com.apple.tccd"
+ "com.apple.universalaccessAuthWarn"
+ "command"
+ "countByEnumeratingWithState:objects:count:"
+ "dataWithBytes:length:"
+ "decisions.%s.%s"
+ "decisions.ceilingDropped"
+ "dedupe"
+ "denied"
+ "destInvalid"
+ "destLookup"
+ "destination"
+ "destinationAuditToken"
+ "destinationPath"
+ "destinationPid"
+ "direct"
+ "displayType"
+ "diu.slots"
+ "dropped"
+ "dropped:agentGone"
+ "dropped:badParams"
+ "dropped:badToken"
+ "dropped:evicted"
+ "dropped:inFlight"
+ "dropped:rateLimited"
+ "event=diu v=1 side=%{public}s result=%{public}s client=%{public}s reporter=%{public}s approval=- activity=%{public}s | team=%{private}s"
+ "event=env v=1 component=%{public}s schema=1 perApp=%{public}s diu=%{public}s tccSPI=%{public}s ver=%{public}s debugOverride=- canReachTCCD=%{public}s relayReachable=%{public}s"
+ "event=observer v=1 canReachTCCD=%d darwin=%u/%u tccEvents=%{public}s observing=%d"
+ "event=relay v=1 req=%{public}s src=%{public}s dst=%{public}s result=%{public}s reason=%{public}s"
+ "exempt"
+ "fail"
+ "flagOff"
+ "forceShow"
+ "forwarded"
+ "generation"
+ "getBytes:length:"
+ "global"
+ "globalAllowed"
+ "hostAuth"
+ "hostDecision"
+ "identityMismatch"
+ "indirectObjectFailed"
+ "interacting"
+ "invalid"
+ "kTCCServiceAccessibility"
+ "kTCCServiceAccessibilityPerTarget"
+ "kTCCServiceListenEvent"
+ "kTCCServicePostEvent"
+ "lastObject"
+ "learnMore"
+ "legacy"
+ "length"
+ "limited"
+ "linker"
+ "listenEvent"
+ "listening"
+ "longLongValue"
+ "lookupFailed"
+ "mach-lookup"
+ "mainBundle"
+ "malformedRequest"
+ "noConnection"
+ "noOwnToken"
+ "noShow"
+ "noTCCSymbols"
+ "none"
+ "notAccessibility"
+ "notResponsible"
+ "numberWithDouble:"
+ "numberWithUnsignedLongLong:"
+ "objectAtIndex:"
+ "objectForInfoDictionaryKey:"
+ "observer"
+ "observing"
+ "ok"
+ "otherApp"
+ "per-app-access"
+ "perApp"
+ "pid"
+ "platform"
+ "postEvent"
+ "r%lld"
+ "rangeOfString:"
+ "relay"
+ "relay destinationAuditToken not forwarded: pid=%{public}d reason=%{public}s errno=%{public}d"
+ "relayControlComputerAccessFromSource:peerAuditToken:"
+ "remoteDesktop"
+ "removeObjectAtIndex:"
+ "removeObjectForKey:"
+ "replaced"
+ "reporterAuditToken"
+ "requestID"
+ "requestedByDestination"
+ "requests.sent.direct"
+ "requests.sent.relay"
+ "requests.suppressed.%s"
+ "responsiblePid"
+ "responsiblePidPath"
+ "root"
+ "sameApp"
+ "schema"
+ "screenCapture"
+ "selectorRejected"
+ "server"
+ "serverNotThisApp"
+ "sessionPid"
+ "shield.report"
+ "skipped"
+ "softlink:o:path:/System/Library/PrivateFrameworks/TCC.framework/TCC"
+ "source"
+ "sourceLookup"
+ "sourceTrusted"
+ "spi"
+ "stringWithFormat:"
+ "teamSigned"
+ "timeout"
+ "tracked"
+ "uncached"
+ "undecided"
+ "unknown"
+ "unsignedLongLongValue"
+ "v12@?0i8"
+ "v24@0:8@16"
+ "v24@?0Q8^{tcc_authorization_record_s=}16"
+ "v56@0:8@16{?=[8I]}24"
+ "wasAuthorized"
- "VerifyXPCDictionary:"
```
