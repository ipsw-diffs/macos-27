## AppleIDSetupDaemon

> `/System/Library/PrivateFrameworks/AppleIDSetupDaemon.framework/Versions/A/AppleIDSetupDaemon`

```diff

-129.125.6.1.0
-  __TEXT.__text: 0x111820
+129.250.2.0.0
+  __TEXT.__text: 0x113c48
   __TEXT.__objc_methlist: 0x824
-  __TEXT.__const: 0x3a24
+  __TEXT.__const: 0x3ab4
   __TEXT.__cstring: 0x8f7
-  __TEXT.__oslogstring: 0x5e59
-  __TEXT.__constg_swiftt: 0x199c
-  __TEXT.__swift5_typeref: 0x192a
+  __TEXT.__oslogstring: 0x6199
+  __TEXT.__constg_swiftt: 0x19a4
+  __TEXT.__swift5_typeref: 0x193a
   __TEXT.__swift5_builtin: 0x8c
-  __TEXT.__swift5_reflstr: 0xd44
-  __TEXT.__swift5_fieldmd: 0xd30
+  __TEXT.__swift5_reflstr: 0xd54
+  __TEXT.__swift5_fieldmd: 0xd3c
   __TEXT.__swift5_assocty: 0x260
   __TEXT.__swift5_proto: 0x16c
   __TEXT.__swift5_types: 0xf0
-  __TEXT.__swift_as_entry: 0x3bc
-  __TEXT.__swift_as_ret: 0x6f0
-  __TEXT.__swift_as_cont: 0xd08
-  __TEXT.__swift5_capture: 0x9c0
+  __TEXT.__swift_as_entry: 0x3c0
+  __TEXT.__swift_as_ret: 0x6fc
+  __TEXT.__swift_as_cont: 0xd18
+  __TEXT.__swift5_capture: 0x9e4
   __TEXT.__swift5_protos: 0x3c
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__unwind_info: 0x4568
-  __TEXT.__eh_frame: 0xec00
+  __TEXT.__unwind_info: 0x45b8
+  __TEXT.__eh_frame: 0xedb0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0xa8
   __DATA_CONST.__objc_protolist: 0x88
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5a0
+  __DATA_CONST.__objc_selrefs: 0x5b0
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x10
-  __DATA_CONST.__got: 0xaa0
-  __AUTH_CONST.__const: 0x2480
+  __DATA_CONST.__got: 0xab8
+  __AUTH_CONST.__const: 0x24d0
   __AUTH_CONST.__cfstring: 0x20
-  __AUTH_CONST.__objc_const: 0x3248
+  __AUTH_CONST.__objc_const: 0x3268
   __AUTH_CONST.__auth_got: 0x12e8
   __AUTH.__objc_data: 0x548
-  __AUTH.__data: 0xc20
+  __AUTH.__data: 0xc30
   __DATA.__objc_ivar: 0xc
-  __DATA.__data: 0x13d0
+  __DATA.__data: 0x13c0
   __DATA.__bss: 0x28a0
   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0x220

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2822
-  Symbols:   978
-  CStrings:  497
+  Functions: 2836
+  Symbols:   985
+  CStrings:  508
 
Symbols:
+ _ACAccountTypeIdentifierIdentityServices
+ _AIDAServiceTypeFaceTime
+ _AIDAServiceTypeMessages
+ _objc_msgSend$DSIDForAccount:
+ _objc_msgSend$aa_normalizedPersonID
+ _symbolic SSSg
+ _symbolic SSSgz_Xx
CStrings:
+ "Checking for IdentityServices account"
+ "Did not find an IdentityServices account matching the primary Apple Account"
+ "Discovered eligible IdentityServices account for the primary Apple Account"
+ "Error occurred in registering aps connection: %s"
+ "Explicitly adding Messages and FaceTime to services for IdMS account, only as a temporary workaround"
+ "Failed to fetch IdentityServices accounts: %@"
+ "Failed to start proximity connector: %@"
+ "No primary AuthKit account found on device. Cannot search for IdentityServices account."
+ "Primary AuthKit account has no DSID. Cannot search for IdentityServices account."
+ "Primary AuthKit account has no altDSID. Cannot search for IdentityServices account."
+ "Proximity connector started and listening for IDS messages"
```
