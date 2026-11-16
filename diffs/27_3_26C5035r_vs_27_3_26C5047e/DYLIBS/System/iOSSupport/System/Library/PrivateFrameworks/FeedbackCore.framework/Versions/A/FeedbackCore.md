## FeedbackCore

> `/System/iOSSupport/System/Library/PrivateFrameworks/FeedbackCore.framework/Versions/A/FeedbackCore`

```diff

-243.3.0.0.0
-  __TEXT.__text: 0x143170
+243.4.0.0.0
+  __TEXT.__text: 0x1449bc
   __TEXT.__lazy_helpers: 0x2a0
-  __TEXT.__objc_methlist: 0xb96c
-  __TEXT.__const: 0x3bd4
-  __TEXT.__cstring: 0xa51c
-  __TEXT.__oslogstring: 0xb086
+  __TEXT.__objc_methlist: 0xb9a4
+  __TEXT.__const: 0x3c84
+  __TEXT.__cstring: 0xa630
+  __TEXT.__oslogstring: 0xb24e
   __TEXT.__gcc_except_tab: 0x15d0
   __TEXT.__ustring: 0xe6
-  __TEXT.__constg_swiftt: 0x2044
-  __TEXT.__swift5_typeref: 0x3dc2
+  __TEXT.__constg_swiftt: 0x2060
+  __TEXT.__swift5_typeref: 0x3dee
   __TEXT.__swift5_builtin: 0xdc
-  __TEXT.__swift5_reflstr: 0xd6b
-  __TEXT.__swift5_fieldmd: 0xf04
+  __TEXT.__swift5_reflstr: 0xd72
+  __TEXT.__swift5_fieldmd: 0xf20
   __TEXT.__swift5_assocty: 0x2b8
-  __TEXT.__swift5_proto: 0x180
-  __TEXT.__swift5_types: 0x158
+  __TEXT.__swift5_proto: 0x188
+  __TEXT.__swift5_types: 0x15c
   __TEXT.__swift5_capture: 0xd5c
   __TEXT.__swift_as_entry: 0xc
   __TEXT.__swift_as_ret: 0xc
   __TEXT.__swift_as_cont: 0x24
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__unwind_info: 0x6548
-  __TEXT.__eh_frame: 0x1450
+  __TEXT.__unwind_info: 0x6580
+  __TEXT.__eh_frame: 0x1498
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0xc0
   __DATA_CONST.__objc_protolist: 0x238
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7828
+  __DATA_CONST.__objc_selrefs: 0x7848
   __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0x280
   __DATA_CONST.__objc_arraydata: 0x580
-  __DATA_CONST.__got: 0x12a8
-  __AUTH_CONST.__const: 0x49d8
-  __AUTH_CONST.__cfstring: 0x9140
-  __AUTH_CONST.__objc_const: 0x1dc60
+  __DATA_CONST.__got: 0x12b8
+  __AUTH_CONST.__const: 0x4a58
+  __AUTH_CONST.__cfstring: 0x9160
+  __AUTH_CONST.__objc_const: 0x1dcb8
   __AUTH_CONST.__lazy_load_got: 0x40
   __AUTH_CONST.__objc_intobj: 0x2e8
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_arrayobj: 0x4c8
-  __AUTH_CONST.__auth_got: 0x18a8
+  __AUTH_CONST.__auth_got: 0x1900
   __AUTH.__objc_data: 0x5178
   __AUTH.__data: 0xf70
-  __DATA.__objc_ivar: 0x73c
-  __DATA.__data: 0x2ff4
+  __DATA.__objc_ivar: 0x740
+  __DATA.__data: 0x302c
   __DATA.__objc_stublist: 0x8
-  __DATA.__bss: 0x34e8
+  __DATA.__bss: 0x35e8
   __DATA.__common: 0x160
   __DATA_DIRTY.__objc_data: 0x50
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7764
-  Symbols:   10417
-  CStrings:  2623
+  Functions: 7780
+  Symbols:   10435
+  CStrings:  2638
 
Symbols:
+ -[FBKLoginManager isLoggingOut]
+ -[FBKLoginManager setIsLoggingOut:]
+ _OBJC_IVAR_$_FBKLoginManager._isLoggingOut
+ __CLASS_METHODS__TtC12FeedbackCore16FBKOSEligibility
+ __CLASS_PROPERTIES__TtC12FeedbackCore16FBKOSEligibility
+ _objc_msgSend$countryPolicyHTTPHeaderValue
+ _objc_msgSend$isLoggingOut
+ _objc_msgSend$setIsLoggingOut:
+ _os_eligibility_get_domain_answer
+ _symbolic So8NSNumberCSg
+ _symbolic _____ 12FeedbackCore16FBKOSEligibilityC3ErrV
+ _symbolic _____ySo8NSNumberCSgG s23_ContiguousArrayStorageC
+ _type_layout_string 12FeedbackCore16FBKOSEligibilityC3ErrV
+ _xpc_array_get_count
+ _xpc_array_get_string
+ _xpc_dictionary_get_string
+ _xpc_dictionary_get_value
+ _xpc_get_type
CStrings:
+ "AI not available. Cannot get country policy"
+ "Already logging out; ignoring redundant logOut call."
+ "Context does not contain country policy"
+ "Failed to get country policy at index [%ld]"
+ "Found country policy [%{public}s] as a string"
+ "Invalid context type (Not a dictionary): "
+ "Invalid country policy type. Not an array or string: "
+ "Invalid country policy. Array is empty"
+ "No context found with country policy"
+ "No country policy found in eligibility context: %{public}s"
+ "OS_ELIGIBILITY_CONTEXT_COUNTRY_POLICY"
+ "Unable to read country policy, status: %{public}d"
+ "Using country policy: [%{public}@]"
+ "Using override for country policy [%{public}s]"
+ "X-AI-Country-Policy"
```
