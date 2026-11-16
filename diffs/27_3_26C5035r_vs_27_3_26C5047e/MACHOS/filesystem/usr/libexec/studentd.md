## studentd

> `/usr/libexec/studentd`

### Sections with Same Size but Changed Content

- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_data`

```diff

-148.60.3.0.0
-  __TEXT.__text: 0xe2810
-  __TEXT.__auth_stubs: 0x1f40
-  __TEXT.__objc_stubs: 0x12e20
-  __TEXT.__objc_methlist: 0xb1b4
-  __TEXT.__objc_methname: 0x19800
+148.60.6.0.0
+  __TEXT.__text: 0xe65c4
+  __TEXT.__auth_stubs: 0x1f60
+  __TEXT.__objc_stubs: 0x13360
+  __TEXT.__objc_methlist: 0xb484
+  __TEXT.__objc_methname: 0x1a418
   __TEXT.__objc_classname: 0x2cda
-  __TEXT.__objc_methtype: 0x407b
-  __TEXT.__cstring: 0x6896
-  __TEXT.__const: 0x1ea8
-  __TEXT.__oslogstring: 0x79de
-  __TEXT.__gcc_except_tab: 0x7bc
+  __TEXT.__objc_methtype: 0x41eb
+  __TEXT.__cstring: 0x6906
+  __TEXT.__const: 0x1f38
+  __TEXT.__oslogstring: 0x7abe
+  __TEXT.__gcc_except_tab: 0x7c8
   __TEXT.__ustring: 0x818
-  __TEXT.__swift5_typeref: 0xeea
+  __TEXT.__swift5_typeref: 0xf3a
   __TEXT.__constg_swiftt: 0xa10
-  __TEXT.__swift5_reflstr: 0x813
-  __TEXT.__swift5_fieldmd: 0x6c4
+  __TEXT.__swift5_reflstr: 0x7e3
+  __TEXT.__swift5_fieldmd: 0x6b8
   __TEXT.__swift5_builtin: 0x3c
   __TEXT.__swift5_assocty: 0x18
   __TEXT.__swift5_proto: 0xb8
   __TEXT.__swift5_types: 0x84
-  __TEXT.__swift5_capture: 0xb28
-  __TEXT.__swift_as_entry: 0x1dc
-  __TEXT.__swift_as_ret: 0x264
-  __TEXT.__swift_as_cont: 0x520
+  __TEXT.__swift5_capture: 0xbb8
+  __TEXT.__swift_as_entry: 0x1e8
+  __TEXT.__swift_as_ret: 0x27c
+  __TEXT.__swift_as_cont: 0x538
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__unwind_info: 0x5758
-  __TEXT.__eh_frame: 0x6520
-  __DATA_CONST.__const: 0x5058
-  __DATA_CONST.__cfstring: 0x4940
+  __TEXT.__unwind_info: 0x5d90
+  __TEXT.__eh_frame: 0x68c8
+  __DATA_CONST.__const: 0x5238
+  __DATA_CONST.__cfstring: 0x4960
   __DATA_CONST.__objc_classlist: 0x950
   __DATA_CONST.__objc_catlist: 0x80
   __DATA_CONST.__objc_protolist: 0x2e8

   __DATA_CONST.__objc_dictobj: 0x1770
   __DATA_CONST.__objc_intobj: 0xf0
   __DATA_CONST.__objc_doubleobj: 0x50
-  __DATA_CONST.__auth_got: 0xfb0
-  __DATA_CONST.__got: 0x14a8
-  __DATA_CONST.__auth_ptr: 0x340
-  __DATA.__objc_const: 0x15da0
-  __DATA.__objc_selrefs: 0x5470
-  __DATA.__objc_ivar: 0x9dc
+  __DATA_CONST.__auth_got: 0xfc0
+  __DATA_CONST.__got: 0x14b8
+  __DATA_CONST.__auth_ptr: 0x348
+  __DATA.__objc_const: 0x16198
+  __DATA.__objc_selrefs: 0x55e8
+  __DATA.__objc_ivar: 0xa1c
   __DATA.__objc_data: 0x6368
-  __DATA.__data: 0x2f20
-  __DATA.__bss: 0x1ea0
+  __DATA.__data: 0x2f40
+  __DATA.__bss: 0x1e90
   __DATA.__common: 0x78
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/AVRouting.framework/Versions/A/AVRouting

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5521
-  Symbols:   1277
-  CStrings:  5876
+  Functions: 5629
+  Symbols:   1280
+  CStrings:  5975
 
Symbols:
+ _CRKItemNotFoundError
+ _OBJC_CLASS_$_CRKAppLockToMultipleAppsMarkerFile
+ _swift_getAtKeyPath
CStrings:
+ "@\"<CRKMarker>\""
+ "@\"<CRKMarker>\"16@0:8"
+ "@\"<STUApplicationRestrictionMonitoringPrimitives>\""
+ "@\"<STUApplicationRestrictionMonitoringPrimitives>\"16@0:8"
+ "@\"<STUHomeScreenConfigurationPrimitives>\""
+ "@\"<STUHomeScreenConfigurationPrimitives>\"16@0:8"
+ "@\"<STUSiriPrimitives>\""
+ "@\"<STUSiriPrimitives>\"16@0:8"
+ "@\"STUWhiteboard\"8@?0"
+ "@40@0:8@?16@?24@?32"
+ "B36@?0@\"NSArray\"8@\"NSString\"16B24^@28"
+ "B48@0:8@16@24@32@40"
+ "B48@0:8@16@24^@32@?40"
+ "Bringing primary app %{public}s to the front"
+ "Failed to apply the new Guided Browser web clip to the app whitelist: %{public}@"
+ "Failed to bring %{public}s to the front: %{public}@"
+ "Failed to update Guided Browsing session after the intent to app lock to Guided Browser changed to %{bool,public}d: %{public}@"
+ "Intent to app lock to Guided Browser with quit prevented changed to %{bool,public}d"
+ "Not starting Guided Browser foreground enforcer — intendsToAppLockOnlyToGuidedBrowser=%{bool,public}d, hasConfiguration=%{bool,public}d"
+ "T@\"<CRKMarker>\",R,N"
+ "T@\"<CRKMarker>\",R,N,V_appLockToMultipleAppsMarker"
+ "T@\"<STUApplicationRestrictionMonitoringPrimitives>\",R,N"
+ "T@\"<STUApplicationRestrictionMonitoringPrimitives>\",R,N,V_applicationRestrictionMonitoringPrimitives"
+ "T@\"<STUHomeScreenConfigurationPrimitives>\",R,N"
+ "T@\"<STUHomeScreenConfigurationPrimitives>\",R,N,V_homeScreenConfigurationPrimitives"
+ "T@\"<STUSiriPrimitives>\",R,N"
+ "T@\"<STUSiriPrimitives>\",R,N,V_siriPrimitives"
+ "T@\"NSString\",C,N,V_appliedGuidedBrowserBundleIdentifier"
+ "T@\"NSString\",C,N,V_guidedBrowserWebClipIdentifier"
+ "T@\"NSString\",R,C,N,V_guidedBrowserWebClipIdentifier"
+ "T@\"STUWhiteboard\",&,N,V_observedWhiteboard"
+ "T@?,C,N,V_applier"
+ "T@?,C,N,V_guidedAccessProvider"
+ "T@?,C,N,V_whiteboardProvider"
+ "TB,N,V_hasAppliedSingleAppAllowlistSinceLastClear"
+ "TB,N,V_hasSeenLockedState"
+ "TB,N,V_intendsToAppLockOnlyToGuidedBrowser"
+ "TB,N,V_isOpening"
+ "TB,R,N,V_postsProfileListChanged"
+ "_appLockToMultipleAppsMarker"
+ "_applicationRestrictionMonitoringPrimitives"
+ "_appliedGuidedBrowserBundleIdentifier"
+ "_applier"
+ "_guidedAccessProvider"
+ "_guidedBrowserWebClipIdentifier"
+ "_hasAppliedSingleAppAllowlistSinceLastClear"
+ "_hasSeenLockedState"
+ "_homeScreenConfigurationPrimitives"
+ "_intendsToAppLockOnlyToGuidedBrowser"
+ "_isOpening"
+ "_observedWhiteboard"
+ "_postsProfileListChanged"
+ "_siriPrimitives"
+ "_whiteboardProvider"
+ "allowlistBundleIdentifiersForBundleIdentifiers:"
+ "appLockOperation:didApplyLockWithError:"
+ "appLockToMultipleAppsMarker"
+ "applicationRestrictionMonitoringPrimitives"
+ "appliedGuidedBrowserBundleIdentifier"
+ "applier"
+ "bundleIdentifiersForRequest:"
+ "effectiveBundleIdentifiers"
+ "forceSetBundleIdentifiers:guidedBrowserBundleIdentifier:error:"
+ "guidedAccessProvider"
+ "guidedBrowserBundleIdentifierForBundleIdentifiers:"
+ "guidedBrowserWebClipIdentifier"
+ "hasAppliedSingleAppAllowlistSinceLastClear"
+ "hasSeenLockedState"
+ "homeScreenConfigurationPrimitives"
+ "initWithApplier:whiteboardProvider:guidedAccessProvider:"
+ "initWithBundleIdentifiers:guidedBrowserWebClipIdentifier:"
+ "initWithBundleIdentifiers:guidedBrowserWebClipIdentifier:postsProfileListChanged:"
+ "initialLockContinuation"
+ "initialLockPromise"
+ "intendsToAppLockOnlyToGuidedBrowser"
+ "isGuidedBrowserInMultiAppLockWithBundleIdentifiers:"
+ "isGuidedBrowserOnlyRequest"
+ "isOpening"
+ "isSingleAppLockForBundleIdentifiers:"
+ "observeWhiteboard:"
+ "observedWhiteboard"
+ "openAppAgainAfterUnlock"
+ "postsProfileListChanged"
+ "primaryBundleIdentifier"
+ "primaryBundleIdentifierForRequest:"
+ "productionApplier"
+ "reapplyForGuidedBrowserBundleIdentifierChange"
+ "recoverStaleSuppression"
+ "setAppliedGuidedBrowserBundleIdentifier:"
+ "setApplier:"
+ "setGuidedAccessProvider:"
+ "setGuidedBrowserWebClipIdentifier:"
+ "setHasAppliedSingleAppAllowlistSinceLastClear:"
+ "setHasSeenLockedState:"
+ "setIntendsToAppLockOnlyToGuidedBrowser:"
+ "setIsOpening:"
+ "setObservedWhiteboard:"
+ "setWhiteboardProvider:"
+ "shouldApplyBundleIdentifiers:guidedBrowserBundleIdentifier:appliedBundleIdentifiers:appliedGuidedBrowserBundleIdentifier:"
+ "shouldReapplyBundleIdentifiers:appliedGuidedBrowserBundleIdentifier:forChangedGuidedBrowserBundleIdentifier:"
+ "siriPrimitives"
+ "transferLockToBundleIdentifiers:primaryBundleIdentifier:error:completion:"
+ "updateIntendsToAppLockOnlyToGuidedBrowser:"
+ "waitForInitialLockWithCompletion:"
+ "webClipIdentifierForGuidedBrowserBundleIdentifier:"
+ "whiteboardProvider"
- "Failed to update Guided Browsing session after intendsToAppLockToGuidedBrowser changed to %{bool,public}d: %{public}@"
- "Not starting Guided Browser foreground enforcer — intendsToAppLockToGuidedBrowser=%{bool,public}d, hasConfiguration=%{bool,public}d"
- "forceSetBundleIdentifiers:error:"
- "intendsToAppLockToGuidedBrowser changed to %{bool,public}d"
- "lockStateDidChange"
- "mBundleIdentifier"
- "transferLockToBundleIdentifier:error:"
```
