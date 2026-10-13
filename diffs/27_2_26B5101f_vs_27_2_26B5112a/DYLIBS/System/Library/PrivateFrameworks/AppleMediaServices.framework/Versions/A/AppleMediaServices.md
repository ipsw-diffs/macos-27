## AppleMediaServices

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/Versions/A/AppleMediaServices`

```diff

-10.1.17.0.0
-  __TEXT.__text: 0x8e6be8
+10.1.18.0.0
+  __TEXT.__text: 0x8e6ed0
   __TEXT.__lazy_helpers: 0x2e98
-  __TEXT.__objc_methlist: 0x24704
+  __TEXT.__objc_methlist: 0x2474c
   __TEXT.__const: 0xbb080
   __TEXT.__dlopen_cstrs: 0x834
-  __TEXT.__cstring: 0x2cd60
+  __TEXT.__cstring: 0x2cd4b
   __TEXT.__swift5_typeref: 0x7aa7
   __TEXT.__swift5_reflstr: 0x42be
   __TEXT.__swift5_assocty: 0xfc0

   __TEXT.__oslogstring: 0x317bf
   __TEXT.__gcc_except_tab: 0x53a0
   __TEXT.__ustring: 0x262
-  __TEXT.__unwind_info: 0x173d8
+  __TEXT.__unwind_info: 0x173f0
   __TEXT.__eh_frame: 0x18634
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0xe8
   __DATA_CONST.__objc_protolist: 0x4b0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xff30
+  __DATA_CONST.__objc_selrefs: 0xff50
   __DATA_CONST.__objc_protorefs: 0x278
   __DATA_CONST.__objc_superrefs: 0xcf8
   __DATA_CONST.__objc_arraydata: 0x498
   __DATA_CONST.__got: 0x1a48
   __AUTH_CONST.__const: 0x45830
   __AUTH_CONST.__cfstring: 0x237a0
-  __AUTH_CONST.__objc_const: 0x3ff48
+  __AUTH_CONST.__objc_const: 0x3ff78
   __AUTH_CONST.__lazy_load_got: 0x460
   __AUTH_CONST.__objc_intobj: 0xc60
   __AUTH_CONST.__objc_arrayobj: 0x180

   __AUTH_CONST.__auth_got: 0x2460
   __AUTH.__objc_data: 0x99f8
   __AUTH.__data: 0x2c80
-  __DATA.__objc_ivar: 0x1a60
+  __DATA.__objc_ivar: 0x1a64
   __DATA.__data: 0x7e40
   __DATA.__bss: 0x1c958
   __DATA.__common: 0x1520

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 30014
-  Symbols:   32559
-  CStrings:  8978
+  Functions: 30020
+  Symbols:   32570
+  CStrings:  8977
 
Symbols:
+ +[AMSPurchaseRequestEncoder shouldCompressRequestBodyWithCallerDisabled:bag:]
+ -[AMSPurchaseRequestEncoder requestByEncodingRequestAndReturnSigningErrors:parameters:]
+ -[AMSPurchaseRequestEncoder shouldCompressRequestBodyForRequest:]
+ -[AMSURLRequestEncoder shouldCompressRequestBodyForRequest:]
+ -[AMSURLRequestProperties disableRequestBodyCompression]
+ -[AMSURLRequestProperties setDisableRequestBodyCompression:]
+ OBJC_IVAR_$_AMSURLRequestProperties._disableRequestBodyCompression
+ ___82-[AMSURLRequestEncoder requestByEncodingRequestAndReturnSigningErrors:parameters:]_block_invoke_3
+ ___block_descriptor_56_e8_32s40s48s_e44_"AMSPromise"24?0"AMSBoolean"8"NSError"16l
+ ___block_descriptor_74_e8_32s40s48s56s64bs_e20_v20?0B8"NSError"12l
+ _objc_msgSend$disableRequestBodyCompression
+ _objc_msgSend$setDisableRequestBodyCompression:
+ _objc_msgSend$shouldCompressRequestBodyForRequest:
+ _objc_msgSend$shouldCompressRequestBodyWithCallerDisabled:bag:
- ___54-[AMSPurchaseRequestEncoder initWithPurchaseInfo:bag:]_block_invoke
- ___block_descriptor_40_e8_32s_e20_v16?0"AMSBoolean"8l
- ___block_descriptor_73_e8_32s40s48s56s64bs_e20_v20?0B8"NSError"12l
CStrings:
- "v16@?0@\"AMSBoolean\"8"
```
