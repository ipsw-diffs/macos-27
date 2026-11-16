## AuthenticationServices

> `/System/Library/Frameworks/AuthenticationServices.framework/Versions/A/AuthenticationServices`

```diff

-626.1.12.11.4
-  __TEXT.__text: 0x118344
+626.1.17.0.0
+  __TEXT.__text: 0x118604
   __TEXT.__objc_methlist: 0x80e8
   __TEXT.__const: 0x12c84
   __TEXT.__cstring: 0xb218
   __TEXT.__ustring: 0x65ac
-  __TEXT.__oslogstring: 0x3858
+  __TEXT.__oslogstring: 0x3998
   __TEXT.__gcc_except_tab: 0x11f0
   __TEXT.__dlopen_cstrs: 0x25e
   __TEXT.__swift5_typeref: 0x2e4a

   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 7667
   Symbols:   8387
-  CStrings:  1375
+  CStrings:  1378
 
Functions:
~ -[_ASPasswordManagerIconController _fetchIconWithName:domain:iconSize:shouldUseOneTimeRequest:requestID:responseHandler:] : 624 -> 724
~ -[_ASPasswordManagerIconController _requestIconWithName:domain:iconSize:options:shouldUseOneTimeRequest:requestID:responseHandler:] : 1500 -> 1596
~ ___131-[_ASPasswordManagerIconController _requestIconWithName:domain:iconSize:options:shouldUseOneTimeRequest:requestID:responseHandler:]_block_invoke : 908 -> 1004
~ -[ASAuthorizationController _convertCoreErrorToPublicError:] : 540 -> 608
~ sub_1cf728b5c -> sub_1cfb75cc4 : 112 -> 124
~ sub_1cf742c04 -> sub_1cfb8fd78 : 252 -> 276
~ sub_1cf759a0c -> sub_1cfba6b98 : 276 -> 308
~ sub_1cf759d8c -> sub_1cfba6f38 : 436 -> 480
~ sub_1cf759f40 -> sub_1cfba7118 : 260 -> 284
~ sub_1cf75a044 -> sub_1cfba7234 : 260 -> 284
~ sub_1cf76c33c -> sub_1cfbb9544 : 436 -> 480
~ sub_1cf76c4f0 -> sub_1cfbb9724 : 260 -> 284
~ sub_1cf76c5f4 -> sub_1cfbb9840 : 276 -> 312
~ sub_1cf76c708 -> sub_1cfbb9978 : 252 -> 276
~ sub_1cf77e4b0 -> sub_1cfbcb738 : 2088 -> 2104
~ sub_1cf781b78 -> sub_1cfbcee10 : 3500 -> 3528
~ sub_1cf782a08 -> sub_1cfbcfcbc : 524 -> 536
CStrings:
+ "Fetching touch icon; domain=%{sensitive, mask.hash}@; enableIconDownload=%{bool}d; enablePrivateRelay=%{bool}d; oneTimeRequest=%{bool}d"
+ "Not downloading touch icon because the domain is an IP address; domain=%{sensitive, mask.hash}@"
+ "Not fetching touch icon because network fetching isn't allowed; domain=%{sensitive, mask.hash}@"
+ "Using generated monogram for touch icon; domain=%{sensitive, mask.hash}@"
- "Fetching touch icon; domain=%{sensitive, mask.hash}@; enablePrivateRelay=%{bool}d"
```
