## TextInput_vi

> `/System/Library/TextInput/TextInput_vi.bundle/Versions/A/TextInput_vi`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`

```diff

 3567.400.0.0.0
-  __TEXT.__text: 0x417c
+  __TEXT.__text: 0x3fec
   __TEXT.__init_offsets: 0xc
   __TEXT.__objc_methlist: 0x250
   __TEXT.__cstring: 0x1ac
   __TEXT.__const: 0x10
-  __TEXT.__unwind_info: 0x2b0
+  __TEXT.__unwind_info: 0x2d0
   __TEXT.__objc_stubs: 0x7a0
   __TEXT.__auth_stubs: 0x540
   __TEXT.__objc_classname: 0x8e
Functions:
~ +[NSCharacterSet(VietnameseAdditions) TI_vietnameseBaseCharacterSet] : 68 -> 56
~ ___68+[NSCharacterSet(VietnameseAdditions) TI_vietnameseBaseCharacterSet]_block_invoke : 76 -> 64
~ +[NSCharacterSet(VietnameseAdditions) TI_vietnameseTelexSpecialsCharacterSet] : 68 -> 56
~ ___77+[NSCharacterSet(VietnameseAdditions) TI_vietnameseTelexSpecialsCharacterSet]_block_invoke : 76 -> 64
~ +[NSCharacterSet(VietnameseAdditions) TI_vietnameseVIQRSpecialsCharacterSet] : 68 -> 56
~ ___76+[NSCharacterSet(VietnameseAdditions) TI_vietnameseVIQRSpecialsCharacterSet]_block_invoke : 76 -> 64
~ +[NSCharacterSet(VietnameseAdditions) TI_vietnameseVNISpecialsCharacterSet] : 68 -> 56
~ ___75+[NSCharacterSet(VietnameseAdditions) TI_vietnameseVNISpecialsCharacterSet]_block_invoke : 76 -> 64
~ -[TIKeyboardInputManager_vi lexiconID] : 204 -> 192
~ +[TIKeyboardInputManager_vi cleanupUnikey] : 96 -> 84
~ -[TIKeyboardInputManager_vi decomposeString:] : 340 -> 328
~ -[TIKeyboardInputManager_vi addInput:flags:point:firstDelete:] : 528 -> 516
~ -[TIKeyboardInputManager_vi externalStringToInternal:ignoreCompositionDisabled:useReverseMap:] : 152 -> 140
~ -[TIKeyboardInputManager_vi internalStringToExternal:ignoreCompositionDisabled:] : 556 -> 544
~ -[TIKeyboardInputManager_vi deleteFromInput:] : 700 -> 688
~ -[TIKeyboardInputManager_vi_VIQR wordCharacters] : 132 -> 120
~ __ZNSt3__120__shared_ptr_emplaceIN2KB18CandidateFilter_viENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__119__shared_weak_count16__release_sharedB9nqn220106Ev : 100 -> 88
~ __ZNSt3__120__shared_ptr_emplaceIN2KB29InputManagerSpecialization_viENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZN2KB29InputManagerSpecialization_viD0Ev : 56 -> 44
~ __ZNK3WTF10RefCountedIN2TI8Favonius3KeyEE5derefEv : 148 -> 136
~ __ZNSt3__16vectorIN3WTF6RefPtrIN2TI8Favonius9LayoutKeyEEENS_9allocatorIS6_EEE16__destroy_vectorclB9nqn220106Ev : 84 -> 72
~ __ZNSt3__110__function6__funcIZ47-[TIKeyboardInputManager_vi initImplementation]E3$_0FN2KB6StringERKS4_EED0Ev : 76 -> 64
~ __ZNSt3__110__function6__funcIZ47-[TIKeyboardInputManager_vi initImplementation]E3$_0FN2KB6StringERKS4_EEclES6_ : 140 -> 128
~ _GLOBAL__sub_I_TIKeyboardInputManager_vi.mm : 92 -> 80
~ __ZNK2KB18CandidateFilter_vi17filter_candidatesERNS_19CandidateCollectionERKNS_28CandidateFilterLookupContextERKNS_24CandidateFilterResourcesE : 96 -> 84
~ __ZNSt3__16vectorIN2KB6StringENS_9allocatorIS2_EEE16__destroy_vectorclB9nqn220106Ev : 132 -> 120
~ __ZNK17TIInputManager_vi44should_accept_candidate_for_mixed_case_inputERKN2KB9CandidateERKNS0_4WordERKNS0_6StringERKNSt3__16vectorIjNSA_9allocatorIjEEEEb : 240 -> 228
~ __ZN17TIInputManager_viD0Ev : 56 -> 44
~ __ZNSt3__16vectorINS_10shared_ptrIN2KB15CandidateFilterEEENS_9allocatorIS4_EEE24__emplace_back_slow_pathIJRKS4_EEEPS4_DpOT_ : 224 -> 220
~ __ZNSt3__120__shared_ptr_emplaceIN2KB24CompositeCandidateFilterENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__16vectorINS_10shared_ptrIN2KB15CandidateFilterEEENS_9allocatorIS4_EEE16__destroy_vectorclB9nqn220106Ev : 84 -> 72
~ __ZN17TIInputManager_viD2Ev : 100 -> 88
~ ____ZNK2KB29InputManagerSpecialization_vi27create_input_segment_filterEN3WTF10PassRefPtrIN2TI8Favonius14KeyboardLayoutEEE_block_invoke : 176 -> 164
```
