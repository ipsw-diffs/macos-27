## NeuralNetworks

> `/System/Library/PrivateFrameworks/NeuralNetworks.framework/Versions/A/NeuralNetworks`

```diff

 150.0.0.0.0
-  __TEXT.__text: 0x1f8e50
+  __TEXT.__text: 0x1f9eb8
   __TEXT.__objc_methlist: 0x1594
-  __TEXT.__const: 0x1dbb8
-  __TEXT.__cstring: 0xf193
+  __TEXT.__const: 0x1dce8
+  __TEXT.__cstring: 0xf3c3
   __TEXT.__oslogstring: 0x24a
   __TEXT.__gcc_except_tab: 0x19a0
-  __TEXT.__constg_swiftt: 0x7ae0
-  __TEXT.__swift5_typeref: 0x8603
-  __TEXT.__swift5_reflstr: 0x418c
-  __TEXT.__swift5_fieldmd: 0x6f20
-  __TEXT.__swift5_builtin: 0x3ac
+  __TEXT.__constg_swiftt: 0x7afc
+  __TEXT.__swift5_typeref: 0x8623
+  __TEXT.__swift5_reflstr: 0x41dc
+  __TEXT.__swift5_fieldmd: 0x6f54
+  __TEXT.__swift5_builtin: 0x3c0
   __TEXT.__swift5_assocty: 0x1ce0
-  __TEXT.__swift5_proto: 0x1d34
-  __TEXT.__swift5_types: 0x830
+  __TEXT.__swift5_proto: 0x1d40
+  __TEXT.__swift5_types: 0x834
   __TEXT.__swift5_protos: 0xd8
   __TEXT.__swift5_capture: 0xc94
-  __TEXT.__swift5_mpenum: 0x1d4
+  __TEXT.__swift5_mpenum: 0x1dc
   __TEXT.__swift_as_entry: 0x14
   __TEXT.__swift_as_ret: 0x14
   __TEXT.__swift_as_cont: 0x30
-  __TEXT.__unwind_info: 0xb438
+  __TEXT.__unwind_info: 0xb448
   __TEXT.__eh_frame: 0xc7b8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x90
   __DATA_CONST.__got: 0xd00
-  __AUTH_CONST.__const: 0x16128
+  __AUTH_CONST.__const: 0x161d8
   __AUTH_CONST.__cfstring: 0x300
   __AUTH_CONST.__objc_const: 0xbe08
   __AUTH_CONST.__weak_auth_got: 0x18

   __AUTH.__objc_data: 0x280
   __AUTH.__data: 0x6260
   __DATA.__objc_ivar: 0xd8
-  __DATA.__data: 0x4ad8
-  __DATA.__bss: 0x23110
+  __DATA.__data: 0x4ae8
+  __DATA.__bss: 0x23290
   __DATA.__common: 0xa8
   __DATA_DIRTY.__objc_data: 0x4b0
   __DATA_DIRTY.__data: 0x4b68

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 16441
-  Symbols:   4921
-  CStrings:  1070
+  Functions: 16458
+  Symbols:   4925
+  CStrings:  1076
 
Symbols:
+ _get_enum_tag_for_layout_string 14NeuralNetworks20BackpropagationErrorO
+ _symbolic SS13operationName_t
+ _symbolic _____ 14NeuralNetworks20BackpropagationErrorO
+ _type_layout_string 14NeuralNetworks20BackpropagationErrorO
CStrings:
+ "Encountered the operation `"
+ "Failed to differentiate through an operand of `"
+ "Failed to find gradients for the operation `"
+ "` that is using a non-differentiable scalar type. Ensure all differentiate paths are using floating point scalar types."
+ "` with no derivative. Ensure the values you are differentiating against are used in the computation, also ensure the layers being propagated through all have their `learningPhase` set to `training`."
+ "`. Ensure the values you are differentiating against are used in the computation."
```
