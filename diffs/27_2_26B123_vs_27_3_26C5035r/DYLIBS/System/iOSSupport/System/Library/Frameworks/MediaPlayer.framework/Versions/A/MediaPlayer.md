## MediaPlayer

> `/System/iOSSupport/System/Library/Frameworks/MediaPlayer.framework/Versions/A/MediaPlayer`

```diff

-4026.240.1.0.0
-  __TEXT.__text: 0x20db38
-  __TEXT.__objc_methlist: 0x2179c
-  __TEXT.__const: 0x4d90
-  __TEXT.__cstring: 0x29ce5
-  __TEXT.__oslogstring: 0xfe90
-  __TEXT.__gcc_except_tab: 0xa480
+4026.300.13.0.0
+  __TEXT.__text: 0x20e09c
+  __TEXT.__objc_methlist: 0x217cc
+  __TEXT.__const: 0x4da0
+  __TEXT.__cstring: 0x29e35
+  __TEXT.__oslogstring: 0xfef0
+  __TEXT.__gcc_except_tab: 0xa490
   __TEXT.__dlopen_cstrs: 0x25c
   __TEXT.__ustring: 0x1dc
   __TEXT.__constg_swiftt: 0x32c

   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x4
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__unwind_info: 0xc200
+  __TEXT.__unwind_info: 0xc220
   __TEXT.__eh_frame: 0x4a8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xae08
+  __DATA_CONST.__const: 0xae28
   __DATA_CONST.__objc_classlist: 0x1110
   __DATA_CONST.__objc_catlist: 0xa0
   __DATA_CONST.__objc_protolist: 0x368
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x10390
+  __DATA_CONST.__objc_selrefs: 0x103c8
   __DATA_CONST.__objc_protorefs: 0xa8
   __DATA_CONST.__objc_superrefs: 0xbb0
-  __DATA_CONST.__objc_arraydata: 0x828
-  __DATA_CONST.__got: 0x1ed8
-  __AUTH_CONST.__const: 0x4b80
-  __AUTH_CONST.__cfstring: 0x20600
-  __AUTH_CONST.__objc_const: 0x38288
+  __DATA_CONST.__objc_arraydata: 0x830
+  __DATA_CONST.__got: 0x1ee8
+  __AUTH_CONST.__const: 0x4bc0
+  __AUTH_CONST.__cfstring: 0x20740
+  __AUTH_CONST.__objc_const: 0x382a0
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x348
-  __AUTH_CONST.__objc_arrayobj: 0xea0
+  __AUTH_CONST.__objc_arrayobj: 0xeb8
   __AUTH_CONST.__objc_doubleobj: 0x40
   __AUTH_CONST.__auth_got: 0x1c70
   __AUTH.__objc_data: 0x6ff0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 13703
-  Symbols:   29750
-  CStrings:  5950
+  Functions: 13711
+  Symbols:   29768
+  CStrings:  5962
 
Symbols:
+ +[MPModelAlbum __MPModelPropertyAlbumHasAllTracks__MAPPING_MISSING__]
+ +[MPModelAlbum __hasAllTracks_KEY]
+ +[MPModelPodcastEpisode __MPModelPropertyPodcastEpisodeRequiresAssetToken__MAPPING_MISSING__]
+ +[MPModelPodcastEpisode __requiresAssetToken_KEY]
+ +[MPModelSong __MPModelPropertySongVisualTraits__MAPPING_MISSING__]
+ +[MPModelSong __visualTraits_KEY]
+ -[MPHomeUserMonitor _handleHomeMemberRestrictionsDidChangeNotification:]
+ _ICUserProfileStoreHomeMemberRestrictionsDidChangeNotification
+ _MPModelPropertyAlbumHasAllTracks
+ _MPModelPropertyPodcastEpisodeRequiresAssetToken
+ _MPModelPropertySongVisualTraits
+ _MPNowPlayingContentItemUserInfoKeyPodcastEpisodeRequiresAssetToken
+ _MPNowPlayingContentItemUserInfoKeySongVisualTraits
+ _OBJC_CLASS_$_ICUserProfileStore
+ ___72-[MPHomeUserMonitor _handleHomeMemberRestrictionsDidChangeNotification:]_block_invoke
+ ____MPMRInitPropertySongMap_block_invoke_9
+ ____MPMediaKitInitPropertySongMap_block_invoke_10
+ _objc_msgSend$allowsExplicitContentForHomeMemberIdentifier:
+ _objc_msgSend$setElapsedTimeTimestamp:
+ _objc_msgSend$setHasAllTracks:
+ _objc_msgSend$setVisualTraits:
+ _objc_msgSend$sharedStore
+ _objc_msgSend$visualTraits
- +[MPModelAlbum __MPModelPropertyAlbumIsFollowed__MAPPING_MISSING__]
- +[MPModelAlbum __isFollowed_KEY]
- _MPModelPropertyAlbumIsFollowed
- _objc_msgSend$isWatch
- _objc_msgSend$setIsFollowed:
CStrings:
+ "<MPHomeUserMonitor %p> ICUserProfileStore home member restrictions did change"
+ "<MPHomeUserMonitor %p> _loadAllowExplicitValueFromSetting: userID=%{private}@ source=%{public}@ cachedValue=%{BOOL}u newValue=%{BOOL}u"
+ "Fallback"
+ "HomeKit"
+ "MPModelPropertyAlbumHasAllTracks"
+ "MPModelPropertyPodcastEpisodeRequiresAssetToken"
+ "MPModelPropertySongVisualTraits"
+ "Translator was missing mapping for MPModelPropertyAlbumHasAllTracks"
+ "Translator was missing mapping for MPModelPropertyPodcastEpisodeRequiresAssetToken"
+ "Translator was missing mapping for MPModelPropertySongVisualTraits"
+ "UserProfileExplicitAllowed"
+ "UserProfiles"
+ "attributes.supportsSelfieSing"
+ "podEpReqTkn"
+ "sVisTr"
- "<MPHomeUserMonitor %p> _loadAllowExplicitValueFromSetting: userID=%{private}@ cachedValue=%{BOOL}u newValue=%{BOOL}u"
- "MPModelPropertyAlbumIsFollowed"
- "Translator was missing mapping for MPModelPropertyAlbumIsFollowed"
```
