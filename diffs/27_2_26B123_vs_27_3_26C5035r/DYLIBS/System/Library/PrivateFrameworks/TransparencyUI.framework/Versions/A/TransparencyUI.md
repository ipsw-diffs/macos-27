## TransparencyUI

> `/System/Library/PrivateFrameworks/TransparencyUI.framework/Versions/A/TransparencyUI`

```diff

-1766.40.58.0.0
-  __TEXT.__text: 0x3ef90
-  __TEXT.__objc_methlist: 0x2c0c
-  __TEXT.__const: 0x60a
-  __TEXT.__cstring: 0x5096
-  __TEXT.__oslogstring: 0x2573
-  __TEXT.__gcc_except_tab: 0x428
+1766.60.7.0.0
+  __TEXT.__text: 0x3f894
+  __TEXT.__objc_methlist: 0x2c2c
+  __TEXT.__const: 0x61a
+  __TEXT.__cstring: 0x51e6
+  __TEXT.__oslogstring: 0x2632
+  __TEXT.__gcc_except_tab: 0x49c
   __TEXT.__dlopen_cstrs: 0xb0
   __TEXT.__ustring: 0x8
   __TEXT.__swift5_typeref: 0x585

   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_proto: 0x20
   __TEXT.__swift5_types: 0x1c
-  __TEXT.__unwind_info: 0x1988
+  __TEXT.__unwind_info: 0x19d0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x128
   __DATA_CONST.__objc_protolist: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1fc8
+  __DATA_CONST.__objc_selrefs: 0x1fe8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x100
   __DATA_CONST.__objc_arraydata: 0x20
   __DATA_CONST.__got: 0x600
-  __AUTH_CONST.__const: 0x3cd0
-  __AUTH_CONST.__cfstring: 0x1980
-  __AUTH_CONST.__objc_const: 0x7428
+  __AUTH_CONST.__const: 0x3e00
+  __AUTH_CONST.__cfstring: 0x19a0
+  __AUTH_CONST.__objc_const: 0x74a8
   __AUTH_CONST.__objc_floatobj: 0x10
   __AUTH_CONST.__objc_intobj: 0x30
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x488
+  __AUTH_CONST.__auth_got: 0x498
   __AUTH.__objc_data: 0xaf0
   __AUTH.__data: 0xb0
-  __DATA.__objc_ivar: 0x380
+  __DATA.__objc_ivar: 0x390
   __DATA.__data: 0x928
   __DATA.__bss: 0x440
   __DATA_DIRTY.__objc_data: 0x50

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2032
-  Symbols:   2777
-  CStrings:  665
+  Functions: 2050
+  Symbols:   2799
+  CStrings:  675
 
Symbols:
+ -[TUIKTStateManager _computeState]
+ -[TUIKTStateManager fetchServerOptInIfNeeded:completion:]
+ -[TUIKTStateManager needsServerOptIn]
+ GCC_except_table12
+ GCC_except_table14
+ GCC_except_table27
+ GCC_except_table29
+ GCC_except_table48
+ GCC_except_table68
+ GCC_except_table8
+ _KTAccountStatusGetString
+ _KTOptInGetString
+ _OBJC_IVAR_$_TUIKTStateManager._effectiveAccountStatus
+ _OBJC_IVAR_$_TUIKTStateManager._effectiveOptIn
+ _OBJC_IVAR_$_TUIKTStateManager._serverOptIn
+ _OBJC_IVAR_$_TUIKTStateManager._serverOptInFetched
+ ___34-[TUIKTStateManager _computeState]_block_invoke
+ ___55-[TUIAIDPPOptInSpecifierViewController _checkKTStatus:]_block_invoke_3
+ ___57-[TUIKTStateManager fetchServerOptInIfNeeded:completion:]_block_invoke
+ ___57-[TUIKTStateManager fetchServerOptInIfNeeded:completion:]_block_invoke_2
+ ___block_descriptor_40_e8_32w_e8_v12?0B8l
+ ___block_descriptor_48_e8_32bs40w_e20_v24?0Q8"NSError"16l
+ ___block_descriptor_57_e8_32s40s48w_e5_v8?0l
+ _objc_msgSend$_computeState
+ _objc_msgSend$fetchServerOptIn:
+ _objc_msgSend$fetchServerOptInIfNeeded:completion:
+ _objc_msgSend$forcedAccountStatus
+ _objc_msgSend$needsServerOptIn
- GCC_except_table19
- GCC_except_table21
- GCC_except_table23
- GCC_except_table3
- GCC_except_table65
- _objc_msgSend$serverOptIn
CStrings:
+ " (fetched)"
+ "%s asking KT server for opt-in state on %{public}@"
+ "%s forced account status %{public}@ on %{public}@"
+ "%s new %{public}@, serverOptIn %{public}@%{public}@ on %{public}@"
+ "%s server opt-in fetch failed: %{public}@ on %{public}@"
+ "-[TUIAIDPPOptInSpecifierViewController _checkKTStatus:]_block_invoke_2"
+ "-[TUIKTStateManager _computeState]"
+ "-[TUIKTStateManager fetchServerOptInIfNeeded:completion:]"
+ "-[TUIKTStateManager fetchServerOptInIfNeeded:completion:]_block_invoke"
+ "-[TUIKTStateManager fetchServerOptInIfNeeded:completion:]_block_invoke_2"
+ "v24@?0Q8@\"NSError\"16"
- "%s new %{public}@ on %{public}@"
```
