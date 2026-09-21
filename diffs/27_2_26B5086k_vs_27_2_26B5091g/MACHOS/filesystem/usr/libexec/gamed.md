## gamed

> `/usr/libexec/gamed`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`

```diff

-821.1.8.0.0
-  __TEXT.__text: 0x35d594
-  __TEXT.__auth_stubs: 0x45c0
-  __TEXT.__objc_stubs: 0x1b580
-  __TEXT.__objc_methlist: 0xe1b4
-  __TEXT.__const: 0x6d960
-  __TEXT.__objc_classname: 0x29b7
-  __TEXT.__oslogstring: 0x185e9
-  __TEXT.__cstring: 0x19a01
-  __TEXT.__objc_methname: 0x23837
-  __TEXT.__objc_methtype: 0x71ed
-  __TEXT.__gcc_except_tab: 0x2f64
-  __TEXT.__swift5_typeref: 0x2b46
-  __TEXT.__constg_swiftt: 0x1bbc
+821.1.11.0.0
+  __TEXT.__text: 0x35eb50
+  __TEXT.__auth_stubs: 0x45d0
+  __TEXT.__objc_stubs: 0x1b700
+  __TEXT.__objc_methlist: 0xe2b4
+  __TEXT.__const: 0x6d9d0
+  __TEXT.__objc_classname: 0x29d7
+  __TEXT.__oslogstring: 0x186f9
+  __TEXT.__cstring: 0x19b01
+  __TEXT.__objc_methname: 0x23bc7
+  __TEXT.__objc_methtype: 0x722d
+  __TEXT.__gcc_except_tab: 0x3008
+  __TEXT.__swift5_typeref: 0x2b4c
+  __TEXT.__constg_swiftt: 0x1bd8
   __TEXT.__swift5_reflstr: 0x1299
-  __TEXT.__swift5_fieldmd: 0x1764
+  __TEXT.__swift5_fieldmd: 0x1774
   __TEXT.__swift5_builtin: 0xa0
   __TEXT.__swift5_assocty: 0x138
   __TEXT.__swift5_proto: 0x2a8
-  __TEXT.__swift5_types: 0x1e8
+  __TEXT.__swift5_types: 0x1ec
   __TEXT.__swift5_capture: 0x1a08
   __TEXT.__swift_as_entry: 0x514
   __TEXT.__swift_as_ret: 0x610
   __TEXT.__swift_as_cont: 0x8c0
   __TEXT.__swift5_protos: 0x1c
   __TEXT.__swift5_mpenum: 0x1c
-  __TEXT.__unwind_info: 0xac28
-  __TEXT.__eh_frame: 0xb998
-  __DATA_CONST.__const: 0x1b3d0
-  __DATA_CONST.__cfstring: 0xbfc0
-  __DATA_CONST.__objc_classlist: 0x968
+  __TEXT.__unwind_info: 0xac78
+  __TEXT.__eh_frame: 0xb9e8
+  __DATA_CONST.__const: 0x1b4d0
+  __DATA_CONST.__cfstring: 0xc0a0
+  __DATA_CONST.__objc_classlist: 0x970
   __DATA_CONST.__objc_catlist: 0x158
   __DATA_CONST.__objc_protolist: 0x240
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arraydata: 0x378
   __DATA_CONST.__objc_dictobj: 0x280
   __DATA_CONST.__objc_arrayobj: 0x138
-  __DATA_CONST.__auth_got: 0x22f8
-  __DATA_CONST.__got: 0x20c8
+  __DATA_CONST.__auth_got: 0x2300
+  __DATA_CONST.__got: 0x20c0
   __DATA_CONST.__auth_ptr: 0xd08
-  __DATA.__objc_const: 0x203d8
-  __DATA.__objc_selrefs: 0x8128
-  __DATA.__objc_ivar: 0x708
-  __DATA.__objc_data: 0x7198
+  __DATA.__objc_const: 0x205a8
+  __DATA.__objc_selrefs: 0x81a8
+  __DATA.__objc_ivar: 0x720
+  __DATA.__objc_data: 0x71e8
   __DATA.__data: 0x4c90
   __DATA.__bss: 0x55c0
   __DATA.__common: 0xb10

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12406
-  Symbols:   2428
-  CStrings:  10475
+  Functions: 12458
+  Symbols:   2427
+  CStrings:  10512
 
Symbols:
+ _GKOverlayBundleIDs
- _GKGameOverlayUIIdentifier
- _GKGameOverlayViewServiceIdentifier
CStrings:
+ "-[GKProfileService _fetchProfilesForPlayerIDs:familiarity:responseKind:deferNonEssentialData:context:handler:]"
+ "-[GKProfileService _getProfilesForPlayerIDs:discardingStaleData:deferNonEssentialData:familiarity:context:handler:]"
+ "-[GKProfileService _getProfilesForPlayerIDs:discardingStaleData:deferNonEssentialData:familiarity:context:handler:]_block_invoke"
+ "-[GKProfileService _getProfilesForPlayerIDs:discardingStaleData:deferNonEssentialData:handler:]"
+ "-[GKProfileService _loadProfilesForPlayerIDs:familiarity:responseComplete:deferNonEssentialData:context:handler:]"
+ "@\"GKFriendSuggestionContext\""
+ "@64@0:8@16@24@32@40@?48@?56"
+ "@68@0:8@16@24B32@36@44@52@?60"
+ "Background game metadata warm completed for %lu bundle id(s)"
+ "Background game metadata warm failed: %@"
+ "Background scoped id warm completed"
+ "Failed to warm scoped ids for profiles in the background, error: %@"
+ "GKFriendSuggestionContext"
+ "GKProfileService: warmGameMetadataInBackgroundForBundleIDs:"
+ "T@\"GKFriendSuggestionContext\",&,N,V_context"
+ "T@\"NSArray\",C,N,V_recentGamesInCommon"
+ "T@\"NSDictionary\",&,N,V_cachedCaidsMetadata"
+ "T@\"NSNumber\",C,N,V_hasFriendsInCommon"
+ "T@\"NSNumber\",C,N,V_numRecentGamesInCommon"
+ "_cachedCaidsMetadata"
+ "_fetchProfilesForPlayerIDs:familiarity:responseKind:deferNonEssentialData:context:handler:"
+ "_getProfilesForPlayerIDs:discardingStaleData:deferNonEssentialData:familiarity:context:handler:"
+ "_getProfilesForPlayerIDs:discardingStaleData:deferNonEssentialData:handler:"
+ "_hasFriendsInCommon"
+ "_loadProfilesForPlayerIDs:familiarity:responseComplete:deferNonEssentialData:context:handler:"
+ "_numRecentGamesInCommon"
+ "_recentGamesInCommon"
+ "cachedCaidsMetadata"
+ "cachedSuggestedFriendsWithContext:"
+ "caids-with-metadata"
+ "caidsMetadata"
+ "contactAssociationIDsFromServerArray:"
+ "contextFromServerDictionary:"
+ "contextMapFromServerArray:"
+ "getProfilesForPlayerIDs:discardingStaleData:deferNonEssentialData:handler:"
+ "has-friends-in-common"
+ "hasFriendsInCommon"
+ "initWithSettings:networkRequester:cachedSortedAssociationIDs:cachedCaidsMetadata:transactionGroupProvider:featureEnabledBlock:"
+ "modifiersWithSettings:contactsIntegrationController:hasCachedSuggestions:cachedSortedAssociationIDs:cachedCaidsMetadata:rerankRequester:transactionGroupProvider:"
+ "num-recent-games-in-common"
+ "numRecentGamesInCommon"
+ "recent-games-in-common"
+ "recentGamesInCommon"
+ "setCachedCaidsMetadata:"
+ "setCaidsMetadata:"
+ "setHasFriendsInCommon:"
+ "setNumRecentGamesInCommon:"
+ "setRecentGamesInCommon:"
+ "v52@0:8@16B24B28i32@36@?44"
+ "v52@0:8@16i24B28B32@36@?44"
+ "v52@0:8@16i24i28B32@36@?44"
+ "warmGameMetadataInBackgroundForBundleIDs:"
- "-[GKProfileService _fetchProfilesForPlayerIDs:familiarity:responseKind:context:handler:]"
- "-[GKProfileService _getProfilesForPlayerIDs:discardingStaleData:familiarity:context:handler:]"
- "-[GKProfileService _getProfilesForPlayerIDs:discardingStaleData:familiarity:context:handler:]_block_invoke"
- "-[GKProfileService _getProfilesForPlayerIDs:discardingStaleData:handler:]"
- "-[GKProfileService _loadProfilesForPlayerIDs:familiarity:responseComplete:context:handler:]"
- "@56@0:8@16@24@32@?40@?48"
- "@60@0:8@16@24B32@36@44@?52"
- "_fetchProfilesForPlayerIDs:familiarity:responseKind:context:handler:"
- "_getProfilesForPlayerIDs:discardingStaleData:familiarity:context:handler:"
- "_getProfilesForPlayerIDs:discardingStaleData:handler:"
- "_loadProfilesForPlayerIDs:familiarity:responseComplete:context:handler:"
- "initWithSettings:networkRequester:cachedSortedAssociationIDs:transactionGroupProvider:featureEnabledBlock:"
- "modifiersWithSettings:contactsIntegrationController:hasCachedSuggestions:cachedSortedAssociationIDs:rerankRequester:transactionGroupProvider:"
- "v48@0:8@16i24B28@32@?40"
- "v48@0:8@16i24i28@32@?40"
```
