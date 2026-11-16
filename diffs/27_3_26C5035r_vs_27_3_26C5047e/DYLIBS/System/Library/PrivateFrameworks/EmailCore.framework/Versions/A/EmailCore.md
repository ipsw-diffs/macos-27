## EmailCore

> `/System/Library/PrivateFrameworks/EmailCore.framework/Versions/A/EmailCore`

```diff

-3901.300.31.0.0
-  __TEXT.__text: 0x66ab4
-  __TEXT.__objc_methlist: 0x5118
-  __TEXT.__gcc_except_tab: 0x7440
+3901.300.60.0.0
+  __TEXT.__text: 0x67448
+  __TEXT.__objc_methlist: 0x5178
+  __TEXT.__gcc_except_tab: 0x756c
   __TEXT.__const: 0x15d0
-  __TEXT.__cstring: 0x8826
+  __TEXT.__cstring: 0x8896
   __TEXT.__oslogstring: 0xcc5
   __TEXT.__ustring: 0x90
   __TEXT.__constg_swiftt: 0x148

   __TEXT.__swift5_fieldmd: 0x49c
   __TEXT.__swift5_proto: 0x24
   __TEXT.__swift5_assocty: 0x18
-  __TEXT.__unwind_info: 0x2fa8
+  __TEXT.__unwind_info: 0x3000
   __TEXT.__eh_frame: 0x1f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1ba8
+  __DATA_CONST.__const: 0x1bb0
   __DATA_CONST.__objc_classlist: 0x358
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x120
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2a80
+  __DATA_CONST.__objc_selrefs: 0x2ac8
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x278
   __DATA_CONST.__objc_arraydata: 0x80
   __DATA_CONST.__got: 0x788
   __AUTH_CONST.__const: 0x2db0
-  __AUTH_CONST.__cfstring: 0x5480
+  __AUTH_CONST.__cfstring: 0x5580
   __AUTH_CONST.__objc_const: 0xaab0
   __AUTH_CONST.__objc_arrayobj: 0xf0
   __AUTH_CONST.__objc_intobj: 0x198

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2178
-  Symbols:   5191
-  CStrings:  1544
+  Functions: 2186
+  Symbols:   5207
+  CStrings:  1552
 
Symbols:
+ +[ECMessageBodyParsingUtils _blockquoteDepthAtLocation:inHTML:]
+ +[ECMessageBodyParsingUtils _html:hasTag:atLocation:]
+ +[ECMessageBodyParsingUtils _locationOfOpenTag:enclosingLocation:inHTML:]
+ +[ECMessageBodyParsingUtils _rangeOfDivStartingAtLocation:inHTML:]
+ +[ECMessageBodyParsingUtils _rangeOfManagedSignatureInHTML:fromLocation:aboveQuotedContentOnly:]
+ +[ECMessageBodyParsingUtils rangeOfManagedSignatureAboveQuotedContentInHTMLBody:]
+ +[ECMessageBodyParsingUtils strippedManagedSignatureFromHTMLBody:]
+ +[ECSecureMIMETrustEvaluation configureTrust:withOptions:]
+ _ECHTMLIDSignatureAttribute
+ _objc_msgSend$_blockquoteDepthAtLocation:inHTML:
+ _objc_msgSend$_html:hasTag:atLocation:
+ _objc_msgSend$_locationOfOpenTag:enclosingLocation:inHTML:
+ _objc_msgSend$_rangeOfDivStartingAtLocation:inHTML:
+ _objc_msgSend$_rangeOfManagedSignatureInHTML:fromLocation:aboveQuotedContentOnly:
+ _objc_msgSend$configureTrust:withOptions:
+ _objc_msgSend$rangeOfString:options:
CStrings:
+ "<!--"
+ "</blockquote"
+ "</div"
+ "<blockquote"
+ "<br><br><br/><br/>"
+ "<div"
+ "<div data-siri-quote-preamble"
+ "id=\"AppleMailSignature\""
```
