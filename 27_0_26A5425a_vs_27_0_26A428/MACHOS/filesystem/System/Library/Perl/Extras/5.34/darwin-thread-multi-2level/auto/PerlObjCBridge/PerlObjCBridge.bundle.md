## PerlObjCBridge.bundle

> `/System/Library/Perl/Extras/5.34/darwin-thread-multi-2level/auto/PerlObjCBridge/PerlObjCBridge.bundle`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 85.0.0.0.0
-  __TEXT.__text: 0x4288
+  __TEXT.__text: 0x4270
   __TEXT.__auth_stubs: 0x490
   __TEXT.__objc_stubs: 0x460
   __TEXT.__objc_methlist: 0x68

   __TEXT.__cstring: 0x202e
   __TEXT.__objc_classname: 0xa
   __TEXT.__objc_methtype: 0xdd
-  __TEXT.__unwind_info: 0xf0
+  __TEXT.__unwind_info: 0x148
   __DATA_CONST.__cfstring: 0x6c0
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ -[PerlProxy respondsToSelector:] : 132 -> 120
~ -[PerlProxy forwardInvocation:] : 132 -> 120
~ _XS_PerlObjCBridge_sendObjcMessage : 3368 -> 3404
~ _addSelectorToCache : 292 -> 268
~ _pocb_bless : 412 -> 400
```
