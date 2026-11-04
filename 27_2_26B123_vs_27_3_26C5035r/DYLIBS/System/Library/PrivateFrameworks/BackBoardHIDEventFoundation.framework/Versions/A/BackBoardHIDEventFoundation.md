## BackBoardHIDEventFoundation

> `/System/Library/PrivateFrameworks/BackBoardHIDEventFoundation.framework/Versions/A/BackBoardHIDEventFoundation`

```diff

-877.2.2.101.0
-  __TEXT.__text: 0x438e4
-  __TEXT.__objc_methlist: 0x23c0
+877.3.5.0.0
+  __TEXT.__text: 0x44050
+  __TEXT.__objc_methlist: 0x23d0
   __TEXT.__const: 0x68c
   __TEXT.__constg_swiftt: 0x1b0
   __TEXT.__swift5_typeref: 0x225

   __TEXT.__swift5_proto: 0x24
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_assocty: 0x18
-  __TEXT.__gcc_except_tab: 0x568
-  __TEXT.__oslogstring: 0x34e8
-  __TEXT.__unwind_info: 0xfc0
+  __TEXT.__gcc_except_tab: 0x570
+  __TEXT.__oslogstring: 0x3550
+  __TEXT.__unwind_info: 0xfd0
   __TEXT.__eh_frame: 0x158
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x108
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1560
+  __DATA_CONST.__objc_selrefs: 0x1568
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x120
   __DATA_CONST.__objc_arraydata: 0x290

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1155
-  Symbols:   2943
-  CStrings:  708
+  Functions: 1159
+  Symbols:   2947
+  CStrings:  709
 
Symbols:
+ -[BKEventDeferringEnvironmentGraph _derivedPathForTreeContainingNode:selectionPath:]
+ -[BKEventDeferringEnvironmentGraph _grantAuthorizesSelectionForPID:toNode:onSelectionPath:derivedTargets:coveringGrantor:]
+ -[BKEventDeferringEnvironmentGraph _latestConstrainedSiblingTargetForTarget:siblingTargets:siblingNodes:predicateTargets:selectionPath:]
+ -[BKEventDeferringEnvironmentGraph _targetIsEffectivelySelected:selectionPath:pathIdentifier:derivedTargets:visited:]
+ -[BKEventDeferringEnvironmentGraph _targetsOnPath:]
+ -[BKEventDeferringSelectionPathContainer _assertion:isFromSourcePIDs:]
+ -[BKEventDeferringSelectionPathContainer recordSelectionHistoryForTarget:parentTarget:]
+ GCC_except_table875
+ GCC_except_table891
+ GCC_except_table923
- -[BKEventDeferringEnvironmentGraph _grantAuthorizesSelectionForPID:toNode:onSelectionPath:]
- -[BKEventDeferringEnvironmentGraph _targetIsEffectivelySelected:selectionPath:pathIdentifier:visited:]
- -[BKEventDeferringSelectionPathContainer latestConstrainedSiblingTargetForTarget:siblingTargets:]
- GCC_except_table874
- GCC_except_table887
- GCC_except_table919
CStrings:
+ "[%{public}@ %p] changeSelectionPath(%{public}@) recorded intent below grantor %{public}@ for %{public}@"
```
