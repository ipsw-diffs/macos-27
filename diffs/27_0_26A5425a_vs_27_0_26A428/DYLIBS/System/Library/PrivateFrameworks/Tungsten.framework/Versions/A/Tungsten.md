## Tungsten

> `/System/Library/PrivateFrameworks/Tungsten.framework/Versions/A/Tungsten`

```diff

 911.0.134.0.0
-  __TEXT.__text: 0x108554
+  __TEXT.__text: 0x1085d4
   __TEXT.__objc_methlist: 0x11b8c
   __TEXT.__const: 0x39f0
   __TEXT.__constg_swiftt: 0x244

   __TEXT.__gcc_except_tab: 0x3528
   __TEXT.__oslogstring: 0x2225
   __TEXT.__ustring: 0x94
-  __TEXT.__unwind_info: 0x44a0
+  __TEXT.__unwind_info: 0x4498
   __TEXT.__eh_frame: 0x304
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
Functions:
~ -[PXGDisplayAssetTextureProvider requestTexturesForSpritesInRange:geometries:styles:infos:inLayout:] : 3256 -> 3252
~ __39-[PXGCompositeLayout _updateSublayouts]_block_invoke.71 : 1240 -> 1244
~ -[PXGSublayoutDataStore enumerateSublayoutsInRange:options:usingBlock:] : 296 -> 300
~ -[PXGSublayoutDataStore enumerateSublayoutGeometriesInRange:options:usingBlock:] : 368 -> 376
~ -[PXGMetalRenderer _setupYCbCrMatrices] : 400 -> 392
~ ___101-[PXGMetalRenderer _populateEffectSprites:spriteRenderDataStore:presentationDataStore:metadataStore:]_block_invoke : 600 -> 604
~ -[PXGMetalRenderer _parseAndSortRenderTextures:willPerformOffscreenPass:] : 2424 -> 2420
~ ___87+[PXGDiagnosticsSpriteProbe shouldUseDoubleSidedAnimationForSprites:indexes:animation:]_block_invoke : 204 -> 208
~ -[PXGDecoratingLayout normalizedSizeForDecorationType:] : 72 -> 76
~ __98-[PXGMetalTextureAtlas addSpriteWithTextureRequestID:thumbnailData:size:bytesPerRow:contentsRect:]_block_invoke.194 : 140 -> 144
~ -[PXGSpriteDataStore _mutableSpritesInRange:] : 248 -> 256
~ -[PXGSpriteDataStore spriteAtIndex:] : 136 -> 144
~ -[PXGViewRenderer renderSpritesWithTextures:dataStore:presentationDataStore:presentationMetadataStore:layout:] : 4052 -> 4084
~ __110-[PXGViewRenderer renderSpritesWithTextures:dataStore:presentationDataStore:presentationMetadataStore:layout:]_block_invoke.58 : 2060 -> 2056
~ __217-[PXGAnimator computeAnimationStateForTime:inputSpriteDataStore:inputChangeDetails:inputLayout:viewportShift:animationPresentationSpriteDataStore:animationTargetSpriteDataStore:animationChangeDetails:animationLayout:]_block_invoke.55 : 948 -> 952
~ __217-[PXGAnimator computeAnimationStateForTime:inputSpriteDataStore:inputChangeDetails:inputLayout:viewportShift:animationPresentationSpriteDataStore:animationTargetSpriteDataStore:animationChangeDetails:animationLayout:]_block_invoke.58 : 216 -> 224
~ -[PXGTextureManager _lookupLock_requestTexturesForSpritesInRange:textureProvider:mediaKind:presentationType:isAppearing:layout:leafSpriteIndexRange:sprites:textureStreamInfos:loadingStatus:] : 1552 -> 1608
```
