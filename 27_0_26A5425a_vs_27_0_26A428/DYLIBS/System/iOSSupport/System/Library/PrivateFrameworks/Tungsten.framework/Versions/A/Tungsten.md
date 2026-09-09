## Tungsten

> `/System/iOSSupport/System/Library/PrivateFrameworks/Tungsten.framework/Versions/A/Tungsten`

```diff

 911.0.134.0.0
-  __TEXT.__text: 0xfcc64
+  __TEXT.__text: 0xfcc9c
   __TEXT.__objc_methlist: 0x11ca8
   __TEXT.__const: 0x39d0
   __TEXT.__constg_swiftt: 0x244

   __TEXT.__gcc_except_tab: 0x3508
   __TEXT.__oslogstring: 0x25bb
   __TEXT.__ustring: 0x3c
-  __TEXT.__unwind_info: 0x43b8
+  __TEXT.__unwind_info: 0x43b0
   __TEXT.__eh_frame: 0x304
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
Functions:
~ -[PXGDisplayAssetTextureProvider requestTexturesForSpritesInRange:geometries:styles:infos:inLayout:] : 3152 -> 3144
~ ___39-[PXGCompositeLayout _updateSublayouts]_block_invoke_2 : 1220 -> 1224
~ -[PXGSublayoutDataStore enumerateSublayoutsInRange:options:usingBlock:] : 284 -> 288
~ -[PXGSublayoutDataStore enumerateSublayoutGeometriesInRange:options:usingBlock:] : 352 -> 360
~ -[PXGMetalRenderer _setupYCbCrMatrices] : 396 -> 388
~ ___101-[PXGMetalRenderer _populateEffectSprites:spriteRenderDataStore:presentationDataStore:metadataStore:]_block_invoke : 592 -> 596
~ ___87+[PXGDiagnosticsSpriteProbe shouldUseDoubleSidedAnimationForSprites:indexes:animation:]_block_invoke : 204 -> 208
~ -[PXGDecoratingLayout normalizedSizeForDecorationType:] : 72 -> 76
~ ___98-[PXGMetalTextureAtlas addSpriteWithTextureRequestID:thumbnailData:size:bytesPerRow:contentsRect:]_block_invoke_2 : 140 -> 144
~ -[PXGSpriteDataStore _mutableSpritesInRange:] : 244 -> 252
~ -[PXGSpriteDataStore spriteAtIndex:] : 136 -> 144
~ -[PXGViewRenderer renderSpritesWithTextures:dataStore:presentationDataStore:presentationMetadataStore:layout:] : 3884 -> 3888
~ ___110-[PXGViewRenderer renderSpritesWithTextures:dataStore:presentationDataStore:presentationMetadataStore:layout:]_block_invoke_5 : 1848 -> 1844
~ ___217-[PXGAnimator computeAnimationStateForTime:inputSpriteDataStore:inputChangeDetails:inputLayout:viewportShift:animationPresentationSpriteDataStore:animationTargetSpriteDataStore:animationChangeDetails:animationLayout:]_block_invoke_10 : 948 -> 952
~ ___217-[PXGAnimator computeAnimationStateForTime:inputSpriteDataStore:inputChangeDetails:inputLayout:viewportShift:animationPresentationSpriteDataStore:animationTargetSpriteDataStore:animationChangeDetails:animationLayout:]_block_invoke_11 : 216 -> 224
~ -[PXGTextureManager _lookupLock_requestTexturesForSpritesInRange:textureProvider:mediaKind:presentationType:isAppearing:layout:leafSpriteIndexRange:sprites:textureStreamInfos:loadingStatus:] : 1484 -> 1496
```
