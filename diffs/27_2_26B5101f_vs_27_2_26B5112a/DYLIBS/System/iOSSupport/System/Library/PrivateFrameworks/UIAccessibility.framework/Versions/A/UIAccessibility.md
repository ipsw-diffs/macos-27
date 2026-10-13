## UIAccessibility

> `/System/iOSSupport/System/Library/PrivateFrameworks/UIAccessibility.framework/Versions/A/UIAccessibility`

```diff

-3245.8.4.0.0
-  __TEXT.__text: 0x66d50
-  __TEXT.__objc_methlist: 0x67e4
-  __TEXT.__const: 0x218
+3245.8.6.2.0
+  __TEXT.__text: 0x67074
+  __TEXT.__objc_methlist: 0x6804
+  __TEXT.__const: 0x228
   __TEXT.__dlopen_cstrs: 0x162
   __TEXT.__gcc_except_tab: 0xbf8
   __TEXT.__cstring: 0x6ab9
-  __TEXT.__oslogstring: 0x2c8f
+  __TEXT.__oslogstring: 0x2d23
   __TEXT.__ustring: 0x14
-  __TEXT.__unwind_info: 0x1e88
+  __TEXT.__unwind_info: 0x1e98
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1490
+  __DATA_CONST.__const: 0x14b8
   __DATA_CONST.__objc_classlist: 0x1b8
   __DATA_CONST.__objc_catlist: 0xa8
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5370
+  __DATA_CONST.__objc_selrefs: 0x5388
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0xe8
   __DATA_CONST.__objc_arraydata: 0x128

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2547
-  Symbols:   6463
-  CStrings:  1135
+  Functions: 2551
+  Symbols:   6471
+  CStrings:  1137
 
Symbols:
+ -[NSObject(AXAutoscrolling) _accessibilityShouldRetryScrollToBottom]
+ -[UIAccessibilityAutoscrollManager _bottomContentOffset]
+ -[UIAccessibilityAutoscrollManager _scrollToBottomWithRetriesRemaining:]
+ GCC_except_table1841
+ GCC_except_table1934
+ GCC_except_table1952
+ GCC_except_table2106
+ GCC_except_table2153
+ GCC_except_table2159
+ GCC_except_table2168
+ GCC_except_table2385
+ GCC_except_table2404
+ GCC_except_table2487
+ ___72-[UIAccessibilityAutoscrollManager _scrollToBottomWithRetriesRemaining:]_block_invoke
+ ___block_descriptor_72_e8_32s40s_e5_v8?0ls32l8s40l8
+ _objc_msgSend$_accessibilityShouldRetryScrollToBottom
+ _objc_msgSend$_bottomContentOffset
+ _objc_msgSend$_scrollToBottomWithRetriesRemaining:
- GCC_except_table1840
- GCC_except_table1933
- GCC_except_table1951
- GCC_except_table2105
- GCC_except_table2152
- GCC_except_table2158
- GCC_except_table2166
- GCC_except_table2381
- GCC_except_table2400
- GCC_except_table2483
CStrings:
+ "cannot scroll to bottom, no autoscroll target was set"
+ "scrolling to bottom %{public}@ from %{public}@, content size %{public}@, %ld retries left: %@"
```
