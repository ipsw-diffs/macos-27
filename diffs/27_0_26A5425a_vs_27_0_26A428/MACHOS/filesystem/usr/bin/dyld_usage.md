## dyld_usage

> `/usr/bin/dyld_usage`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__DATA_CONST.__const`

```diff

 27062.0.0.0.0
-  __TEXT.__text: 0xcf5c
+  __TEXT.__text: 0xca7c
   __TEXT.__auth_stubs: 0x550
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0x173b
Functions:
~ __ZL15get_screenwidthv : 112 -> 104
~ __ZN13OutputManager5flushEv : 928 -> 888
~ __ZL22setup_ktrace_callbacksv : 104 -> 92
~ __ZNSt3__16vectorINS_10shared_ptrIN15output_renderer10event_pairEEENS_9allocatorIS4_EEE16__destroy_vectorclB9fqn220106Ev : 84 -> 72
~ __ZNSt3__119__shared_weak_count16__release_sharedB9fqn220106Ev : 100 -> 88
~ __ZN15output_renderer16flushInterruptedEv : 664 -> 624
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqn220106Ev : 420 -> 380
~ __ZN15output_renderer6outputENSt3__110shared_ptrINS_10event_pairEEE : 888 -> 848
~ __ZN15output_renderer9timestampENSt3__110shared_ptrINS_10event_pairEEEb : 692 -> 652
~ __ZN15output_renderer7processENSt3__110shared_ptrINS_10event_pairEEEb : 592 -> 540
~ __ZN15output_renderer8durationENSt3__110shared_ptrINS_10event_pairEEE : 564 -> 524
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE17__assign_externalEPKc : 72 -> 60
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE25__init_copy_ctor_externalEPKcm : 68 -> 56
~ __ZN15output_renderer10outputJSONENSt3__110shared_ptrINS_10event_pairEEERNS0_19basic_ostringstreamIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE : 2128 -> 2108
~ __ZN15output_renderer13outputConsoleENSt3__110shared_ptrINS_10event_pairEEEyRNS0_19basic_ostringstreamIcNS0_11char_traitsIcEENS0_9allocatorIcEEEEy : 2776 -> 2716
~ __ZNSt3__16vectorINS_10shared_ptrIN15output_renderer10event_pairEEENS_9allocatorIS4_EEE24__emplace_back_slow_pathIJRKS4_EEEPS4_DpOT_ : 224 -> 220
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE24__emplace_back_slow_pathIJS6_EEEPS6_DpOT_ : 264 -> 260
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE16__destroy_vectorclB9fqn220106Ev : 84 -> 72
~ __ZZN15output_renderer17outputTracingJSONENSt3__110shared_ptrINS_10event_pairEEERNS0_19basic_ostringstreamIcNS0_11char_traitsIcEENS0_9allocatorIcEEEEENKUlbE_clEb : 2000 -> 1968
~ __ZN15output_renderer11recordEventEP11trace_point : 2696 -> 2504
~ ____ZL22setup_ktrace_callbacksv_block_invoke_3 : 164 -> 152
~ __ZN15output_renderer12dequeueEventINS_6dlopenEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZN15output_renderer12dequeueEventINS_16dlopen_preflightEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZN15output_renderer12dequeueEventINS_10app_launchEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZN15output_renderer12dequeueEventINS_5dlsymEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZN15output_renderer12dequeueEventINS_11static_initEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZN15output_renderer12dequeueEventINS_9map_imageEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZN15output_renderer12dequeueEventINS_12apply_fixupsEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZN15output_renderer12dequeueEventINS_16attach_signatureEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZN15output_renderer12dequeueEventINS_13build_closureEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZN15output_renderer12dequeueEventINS_16validate_closureEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZN15output_renderer12dequeueEventINS_7dlcloseEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZN15output_renderer12dequeueEventINS_6dladdrEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZN15output_renderer12dequeueEventINS_18add_image_callbackEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZN15output_renderer12dequeueEventINS_21remove_image_callbackEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZN15output_renderer12dequeueEventINS_15objc_image_initEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZN15output_renderer12dequeueEventINS_15objc_images_mapEEEvP11trace_pointNSt3__18functionIFvPT_EEE : 276 -> 256
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer6dlopenENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__16vectorINS_10shared_ptrIN15output_renderer10event_pairEEENS_9allocatorIS4_EEE24__emplace_back_slow_pathIJS4_EEEPS4_DpOT_ : 224 -> 220
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer16dlopen_preflightENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer10app_launchENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer5dlsymENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer11static_initENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer9map_imageENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer12apply_fixupsENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer16attach_signatureENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer13build_closureENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer16validate_closureENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer6dladdrENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer7dlcloseENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer18add_image_callbackENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer21remove_image_callbackENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer15objc_image_initENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN15output_renderer15objc_images_mapENS_9allocatorIS2_EEED0Ev : 84 -> 72
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ _GLOBAL__sub_I_dyld_usage.cpp : 192 -> 180
~ _ZL11stringForIDy.cold.1 : 112 -> 100
```
