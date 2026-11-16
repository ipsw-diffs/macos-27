## DADaemonSupport

> `/System/Library/PrivateFrameworks/DataAccess.framework/Frameworks/DADaemonSupport.framework/Versions/A/DADaemonSupport`

```diff

-2708.2.3.0.0
-  __TEXT.__text: 0x36fbc
-  __TEXT.__objc_methlist: 0x25f8
+2708.3.2.0.0
+  __TEXT.__text: 0x375b0
+  __TEXT.__objc_methlist: 0x2600
   __TEXT.__const: 0x142
   __TEXT.__gcc_except_tab: 0x694
-  __TEXT.__oslogstring: 0x6129
-  __TEXT.__cstring: 0x1277
-  __TEXT.__unwind_info: 0xd80
+  __TEXT.__oslogstring: 0x624e
+  __TEXT.__cstring: 0x1294
+  __TEXT.__unwind_info: 0xd88
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0xc8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1fd0
+  __DATA_CONST.__objc_selrefs: 0x1ff0
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0xc8
   __DATA_CONST.__objc_arraydata: 0x18
-  __DATA_CONST.__got: 0xb48
+  __DATA_CONST.__got: 0xb90
   __AUTH_CONST.__const: 0xa80
-  __AUTH_CONST.__cfstring: 0xd80
+  __AUTH_CONST.__cfstring: 0xda0
   __AUTH_CONST.__objc_const: 0x65e0
   __AUTH_CONST.__objc_intobj: 0xd8
   __AUTH_CONST.__objc_arrayobj: 0x18

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 952
-  Symbols:   2921
-  CStrings:  511
+  Functions: 953
+  Symbols:   2933
+  CStrings:  516
 
Symbols:
+ -[DADClient _handleCalDAVServerSimulatorResourceRequest:eventDict:]
+ _OBJC_CLASS_$_NSData
+ _kDAEServerSimulatorActionFetchResource
+ _kDAEServerSimulatorActionPutResource
+ _kDAEServerSimulatorCollectionDefaultCalendar
+ _kDAEServerSimulatorCollectionInbox
+ _kDAEServerSimulatorCollectionKey
+ _kDAEServerSimulatorResourceContentsKey
+ _kDAEServerSimulatorResourceNameKey
+ _kDAEServerSimulatorUsernameKey
+ _objc_msgSend$_handleCalDAVServerSimulatorResourceRequest:eventDict:
+ _objc_msgSend$contentsOfResourceNamed:inCollection:forUsername:
+ _objc_msgSend$putICSResourceNamed:contents:inCollection:forUsername:
+ _objc_msgSend$simulatorForHostname:
+ _xpc_dictionary_set_data
- ___30-[DADClient _dispatchMessage:]_block_invoke_22
- ___30-[DADClient _dispatchMessage:]_block_invoke_23
- ___30-[DADClient _dispatchMessage:]_block_invoke_24
Functions:
~ -[DADClient _manageCalDAVServerSimulatorWithHostname:action:] : 520 -> 564
+ -[DADClient _handleCalDAVServerSimulatorResourceRequest:eventDict:]
~ -[DADClient _dispatchMessage:] : 8524 -> 8544
~ ___30-[DADClient _dispatchMessage:]_block_invoke_21 : 128 -> 348
~ ___35+[DADClient permissionsForMessage:]_block_invoke : 1112 -> 1128
CStrings:
+ "CalDAV server simulator message with unrecognized action: %@"
+ "CalDAV server simulator request for a hostname this client didn't begin: %@"
+ "CalDAV server simulator resource request was sent without a reply"
+ "Malformed CalDAV server simulator request: action %@, collection %@"
+ "_manageCalDAVServerSimulatorWithHostname called with a missing or invalid hostname"
+ "_manageCalDAVServerSimulatorWithHostname called with a non-simulated hostname: %@"
+ "simulated.calendar.apple.com"
- "_manageCalDAVServerSimulatorWithHostname called with nil hostname"
- "_manageCalDAVServerSimulatorWithHostname called with unrecognized action: %@"
```
