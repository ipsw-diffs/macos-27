## AuthenticationServices

> `/System/iOSSupport/System/Library/Frameworks/AuthenticationServices.framework/Versions/A/AuthenticationServices`

```diff

-626.1.12.11.4
-  __TEXT.__text: 0x101044
+626.1.17.0.0
+  __TEXT.__text: 0x101420
   __TEXT.__objc_methlist: 0x5f60
   __TEXT.__const: 0x12994
   __TEXT.__gcc_except_tab: 0x101c
   __TEXT.__cstring: 0x67bb
-  __TEXT.__oslogstring: 0x2f1b
+  __TEXT.__oslogstring: 0x30ab
   __TEXT.__dlopen_cstrs: 0x202
   __TEXT.__ustring: 0x4f9a
   __TEXT.__swift5_typeref: 0x2de4

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 7053
-  Symbols:   6503
-  CStrings:  1023
+  Symbols:   6501
+  CStrings:  1027
 
Symbols:
- ___87-[_ASPasswordManagerIconController _fetchTouchIconForDomain:requestID:responseHandler:]_block_invoke_3
- ___97-[_ASPasswordManagerIconController _requestTouchIconForDomain:options:requestID:responseHandler:]_block_invoke_3
Functions:
~ ___87-[_ASPasswordManagerIconController _fetchTouchIconForDomain:requestID:responseHandler:]_block_invoke : 208 -> 200
~ ___87-[_ASPasswordManagerIconController _fetchTouchIconForDomain:requestID:responseHandler:]_block_invoke_2 : 32 -> 188
~ ___97-[_ASPasswordManagerIconController _requestTouchIconForDomain:options:requestID:responseHandler:]_block_invoke : 920 -> 1028
~ ___97-[_ASPasswordManagerIconController _requestTouchIconForDomain:options:requestID:responseHandler:]_block_invoke_3 -> ___97-[_ASPasswordManagerIconController _requestTouchIconForDomain:options:requestID:responseHandler:]_block_invoke_2 : 740 -> 1020
~ -[ASAuthorizationController _convertCoreErrorToPublicError:] : 528 -> 596
~ sub_2ba695f6c -> sub_2bb85e1c8 : 112 -> 124
~ sub_2ba6c3248 -> sub_2bb88b4b0 : 276 -> 308
~ sub_2ba6c35c8 -> sub_2bb88b850 : 436 -> 480
~ sub_2ba6c377c -> sub_2bb88ba30 : 260 -> 284
~ sub_2ba6c3880 -> sub_2bb88bb4c : 260 -> 284
~ sub_2ba6c3984 -> sub_2bb88bc68 : 260 -> 276
~ sub_2ba6cf368 -> sub_2bb89765c : 432 -> 476
~ sub_2ba6cf518 -> sub_2bb897838 : 256 -> 280
~ sub_2ba6cf618 -> sub_2bb897950 : 272 -> 308
~ sub_2ba6cf728 -> sub_2bb897a84 : 248 -> 272
~ sub_2ba6cf820 -> sub_2bb897b94 : 256 -> 272
~ sub_2ba6cf920 -> sub_2bb897ca4 : 272 -> 308
~ sub_2ba6de0a8 -> sub_2bb8a6450 : 2052 -> 2064
~ sub_2ba6e1960 -> sub_2bb8a9d14 : 3436 -> 3464
~ sub_2ba6e27a4 -> sub_2bb8aab74 : 524 -> 536
CStrings:
+ "Checked for a local visit before fetching touch icon; domain=%{sensitive, mask.hash}@; foundLocalVisit=%{bool}d"
+ "Finished fetching touch icon; domain=%{sensitive, mask.hash}@; isGenerated=%{bool}d"
+ "Received generated touch icon; domain=%{sensitive, mask.hash}@"
+ "Skipping touch icon fetch until the retry date; domain=%{sensitive, mask.hash}@; retryDate=%{public}@"
+ "Will not retry touch icon fetch until the retry date; domain=%{sensitive, mask.hash}@; retryDate=%{public}@"
- "Finished fetching touch icon; domain=%{sensitive, mask.hash}@"
```
