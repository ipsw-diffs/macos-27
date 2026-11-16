## BackgroundShortcutRunner

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/XPCServices/BackgroundShortcutRunner.xpc/Contents/MacOS/BackgroundShortcutRunner`

### Sections with Same Size but Changed Content

- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-5203.0.1.0.0
-  __TEXT.__text: 0x84ddc
-  __TEXT.__auth_stubs: 0x3120
-  __TEXT.__objc_stubs: 0x2040
-  __TEXT.__objc_methlist: 0x644
-  __TEXT.__const: 0x19c0
+5206.0.5.0.0
+  __TEXT.__text: 0x86528
+  __TEXT.__auth_stubs: 0x31a0
+  __TEXT.__objc_stubs: 0x2060
+  __TEXT.__objc_methlist: 0x654
+  __TEXT.__const: 0x19d0
   __TEXT.__constg_swiftt: 0x4f0
-  __TEXT.__swift5_typeref: 0xfcc
+  __TEXT.__swift5_typeref: 0xfde
   __TEXT.__swift5_builtin: 0xa0
   __TEXT.__swift5_reflstr: 0x48c
   __TEXT.__swift5_fieldmd: 0x4e0
   __TEXT.__swift5_assocty: 0x108
-  __TEXT.__cstring: 0x1909
-  __TEXT.__swift5_capture: 0xb9c
-  __TEXT.__oslogstring: 0x14cb
+  __TEXT.__cstring: 0x1910
+  __TEXT.__swift5_capture: 0xbb0
+  __TEXT.__oslogstring: 0x161b
   __TEXT.__swift5_proto: 0xc0
   __TEXT.__swift5_types: 0x70
   __TEXT.__objc_classname: 0x214
-  __TEXT.__objc_methname: 0x26cf
-  __TEXT.__objc_methtype: 0x9bf
+  __TEXT.__objc_methname: 0x26af
+  __TEXT.__objc_methtype: 0x9c0
   __TEXT.__swift_as_entry: 0xf0
-  __TEXT.__swift_as_ret: 0x180
-  __TEXT.__swift_as_cont: 0x310
+  __TEXT.__swift_as_ret: 0x184
+  __TEXT.__swift_as_cont: 0x318
   __TEXT.__swift5_mpenum: 0x10
   __TEXT.__gcc_except_tab: 0x20
-  __TEXT.__unwind_info: 0x1820
-  __TEXT.__eh_frame: 0x4898
-  __DATA_CONST.__const: 0x2700
-  __DATA_CONST.__cfstring: 0x3c0
+  __TEXT.__unwind_info: 0x1840
+  __TEXT.__eh_frame: 0x4960
+  __DATA_CONST.__const: 0x26f8
+  __DATA_CONST.__cfstring: 0x3e0
   __DATA_CONST.__objc_classlist: 0x40
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x88
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x8
-  __DATA_CONST.__auth_got: 0x18a0
-  __DATA_CONST.__got: 0xdf0
-  __DATA_CONST.__auth_ptr: 0x400
+  __DATA_CONST.__auth_got: 0x18e0
+  __DATA_CONST.__got: 0xe00
+  __DATA_CONST.__auth_ptr: 0x408
   __DATA.__objc_const: 0x8c0
-  __DATA.__objc_selrefs: 0xa58
+  __DATA.__objc_selrefs: 0xa60
   __DATA.__objc_ivar: 0xc
   __DATA.__objc_data: 0x3b0
-  __DATA.__data: 0x1328
+  __DATA.__data: 0x1308
   __DATA.__bss: 0x1830
   __DATA.__common: 0x8
   - /System/Library/Frameworks/CoreData.framework/Versions/A/CoreData

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2713
+  Functions: 2728
   Symbols:   314
-  CStrings:  722
+  CStrings:  726
 
Symbols:
+ _NSStringFromSelector
- _WFEncodableError
CStrings:
+ "%s client called %{public}@ without stepwise-execution entitlement"
+ "%s: dropping %ld earlier copy sourced from %s before indexing under %s"
+ "%s: replacing %ld earlier copy sourced from %s"
+ "-[WFIsolatedShortcutRunner checkToolKitAccessForMethod:]"
+ "Client is not entitled to perform this operation."
+ "Preserving %ld existing FlowTool(s): this pass regenerated only %ld (incompleteMetadata=%{bool}d). Skipping destructive FlowTool replacement so a later reindex can regenerate once App Intents indexing is complete."
+ "Vv36@0:8@16B24@?28"
+ "beginToolStepOrReplyIfNotRunning"
+ "checkToolKitAccessForMethod:"
+ "failToolStep:withError:"
+ "runLinkQuery:valueSet:toolInvocation:encodedOptions:completionBlock:"
+ "stepWithAction:forToolStep:"
+ "v56@0:8@\"NSData\"16@\"NSData\"24@\"NSData\"32@\"NSData\"40@?<v@?@\"NSData\"@\"NSError\">48"
- "%s runToolWithInvocation: called without stepwise-execution entitlement, rejecting"
- "-[WFIsolatedShortcutRunner runToolWithInvocation:]"
- "actionWithUUID:didFinishRunningWithError:result:executionResultMetadata:"
- "performWithHost:"
- "runLinkQuery:valueSet:encodedOptions:completionBlock:"
- "stepWithAction:"
- "v16@?0@\"<WFOutOfProcessWorkflowControllerHost>\"8"
- "v36@0:8@16B24@?28"
- "v48@0:8@\"NSData\"16@\"NSData\"24@\"NSData\"32@?<v@?@\"NSData\"@\"NSError\">40"
```
