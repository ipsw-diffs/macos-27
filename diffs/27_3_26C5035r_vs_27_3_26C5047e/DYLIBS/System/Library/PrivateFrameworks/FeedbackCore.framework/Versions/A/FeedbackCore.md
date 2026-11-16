## FeedbackCore

> `/System/Library/PrivateFrameworks/FeedbackCore.framework/Versions/A/FeedbackCore`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_reflstr`

```diff

-243.3.0.0.0
-  __TEXT.__text: 0xfd8b4
+243.4.0.0.0
+  __TEXT.__text: 0xff170
   __TEXT.__lazy_helpers: 0x2a0
-  __TEXT.__objc_methlist: 0x7144
-  __TEXT.__const: 0x1c74
-  __TEXT.__cstring: 0x863e
-  __TEXT.__oslogstring: 0x9552
+  __TEXT.__objc_methlist: 0x717c
+  __TEXT.__const: 0x1d24
+  __TEXT.__cstring: 0x874e
+  __TEXT.__oslogstring: 0x9712
   __TEXT.__gcc_except_tab: 0x121c
   __TEXT.__ustring: 0xdc
   __TEXT.__dlopen_cstrs: 0x62
-  __TEXT.__constg_swiftt: 0x84c
-  __TEXT.__swift5_typeref: 0x150a
+  __TEXT.__constg_swiftt: 0x868
+  __TEXT.__swift5_typeref: 0x1536
   __TEXT.__swift5_builtin: 0x8c
   __TEXT.__swift5_reflstr: 0x4c8
   __TEXT.__swift5_assocty: 0xf0
   __TEXT.__swift5_capture: 0xa14
-  __TEXT.__swift5_fieldmd: 0x598
-  __TEXT.__swift5_proto: 0xd4
-  __TEXT.__swift5_types: 0x88
+  __TEXT.__swift5_fieldmd: 0x5b4
+  __TEXT.__swift5_proto: 0xdc
+  __TEXT.__swift5_types: 0x8c
   __TEXT.__swift_as_entry: 0xc
   __TEXT.__swift_as_ret: 0xc
   __TEXT.__swift_as_cont: 0x24
-  __TEXT.__unwind_info: 0x45d0
-  __TEXT.__eh_frame: 0x1348
+  __TEXT.__unwind_info: 0x4600
+  __TEXT.__eh_frame: 0x1390
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x68
   __DATA_CONST.__objc_protolist: 0x100
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4f08
+  __DATA_CONST.__objc_selrefs: 0x4f28
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x1b8
   __DATA_CONST.__objc_arraydata: 0x4c8
-  __DATA_CONST.__got: 0xc78
-  __AUTH_CONST.__const: 0x6018
-  __AUTH_CONST.__cfstring: 0x8760
-  __AUTH_CONST.__objc_const: 0xe598
+  __DATA_CONST.__got: 0xc88
+  __AUTH_CONST.__const: 0x6098
+  __AUTH_CONST.__cfstring: 0x8780
+  __AUTH_CONST.__objc_const: 0xe5f0
   __AUTH_CONST.__lazy_load_got: 0x40
   __AUTH_CONST.__objc_intobj: 0x318
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_arrayobj: 0x468
-  __AUTH_CONST.__auth_got: 0xee0
+  __AUTH_CONST.__auth_got: 0xf28
   __AUTH.__objc_data: 0x2700
   __AUTH.__data: 0x5a8
-  __DATA.__objc_ivar: 0x458
-  __DATA.__data: 0x1664
-  __DATA.__bss: 0x1f68
+  __DATA.__objc_ivar: 0x45c
+  __DATA.__data: 0x16a4
+  __DATA.__bss: 0x2068
   __DATA.__common: 0x120
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5158
-  Symbols:   7135
-  CStrings:  2251
+  Functions: 5172
+  Symbols:   7153
+  CStrings:  2266
 
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
