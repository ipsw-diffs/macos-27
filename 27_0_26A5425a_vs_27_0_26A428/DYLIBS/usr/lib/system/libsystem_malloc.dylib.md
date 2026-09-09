## libsystem_malloc.dylib

> `/usr/lib/system/libsystem_malloc.dylib`

```diff

 886.0.8.0.0
-  __TEXT.__text: 0x47020
+  __TEXT.__text: 0x47270
   __TEXT.__const: 0x6ff
   __TEXT.__cstring: 0xb9d1
   __TEXT.__dof_magmalloc: 0xa96
-  __TEXT.__unwind_info: 0x998
+  __TEXT.__unwind_info: 0x9a0
   __TEXT.__eh_frame: 0x48
   __TEXT.__auth_stubs: 0x7b0
   __DATA_CONST.__const: 0xa28
Functions:
~ _nanov2_malloc : 572 -> 580
~ _nanov2_find_block_and_allocate : 1548 -> 1568
~ _nanov2_allocate_from_block : 352 -> 356
~ _nanov2_size : 384 -> 388
~ _nanov2_pointer_size : 396 -> 400
~ _nanov2_calloc : 696 -> 704
~ _tiny_malloc_from_free_list : 1852 -> 1856
~ _tiny_size : 452 -> 456
~ _small_size : 244 -> 252
~ _free_small : 1804 -> 1808
~ _tiny_try_realloc_in_place : 1484 -> 1488
~ _free_tiny : 844 -> 848
~ _tiny_free_no_lock : 2060 -> 2072
~ _tiny_free_list_add_ptr : 620 -> 624
~ _small_try_realloc_in_place : 756 -> 760
~ _small_memalign : 788 -> 796
~ _medium_size : 236 -> 244
~ _free_medium : 3324 -> 3348
~ _tiny_memalign : 760 -> 768
~ _tiny_try_shrink_in_place : 332 -> 336
~ _small_try_shrink_in_place : 380 -> 384
~ _nanov2_madvise_block : 220 -> 224
~ _rack_init : 332 -> 336
~ _tiny_finalize_region : 456 -> 460
~ _medium_memalign : 892 -> 900
~ _nanov2_create_zone : 1056 -> 1064
~ _szone_force_lock : 676 -> 688
~ _szone_force_unlock : 396 -> 408
~ _szone_statistics_task : 720 -> 732
~ _xzm_segment_group_free_chunk : 1912 -> 1916
~ __xzm_segment_group_span_mark_smaller : 448 -> 432
~ _xzm_segment_group_try_realloc_huge_chunk : 984 -> 988
~ _scalable_zone_info_task : 604 -> 612
~ _scalable_zone_statistics : 516 -> 528
~ _szone_locked : 576 -> 588
~ _szone_reinit_lock : 156 -> 168
~ _szone_check_all : 796 -> 804
~ _szone_print : 1780 -> 1792
~ _small_madvise_pressure_relief : 908 -> 912
~ _small_check_region : 948 -> 968
~ _small_in_use_enumerator : 868 -> 884
~ _print_small_free_list : 800 -> 804
~ _small_free_list_check : 720 -> 724
~ _mfm_alloc : 1092 -> 1100
~ _mfm_free : 1632 -> 1640
~ _mfmi_enumerator : 584 -> 580
~ _print_mfm_arena : 1008 -> 1012
~ _check_slots : 220 -> 232
~ _check_metadata : 112 -> 116
~ _nanov2_malloc_type : 580 -> 588
~ __nanov2_free : 868 -> 872
~ _nanov2_calloc_type : 704 -> 712
~ _nanov2_malloc_zero_on_alloc : 616 -> 624
~ _nanov2_malloc_type_zero_on_alloc : 628 -> 636
~ _nanov2_pressure_relief : 684 -> 692
~ _nanov2_ptr_in_use_enumerator : 1472 -> 1488
~ _nanov2_print : 1496 -> 1528
~ _nanov2_statistics : 724 -> 728
~ __xzm_initialize_const_zone_data : 1296 -> 1300
~ _xzm_malloc_zone_malloc_type_realloc_slow : 4152 -> 4176
~ __xzm_xzone_malloc_small_freelist : 1208 -> 1228
~ __xzm_xzone_malloc_from_freelist_chunk : 984 -> 992
~ __xzm_xzone_chunk_madvise_free_slices : 324 -> 328
~ _malloc_sanitizer_fallback_allocate_poison : 292 -> 276
~ _medium_madvise_pressure_relief : 904 -> 908
~ _medium_try_shrink_in_place : 428 -> 432
~ _medium_check_region : 908 -> 920
~ _medium_in_use_enumerator : 856 -> 872
~ _print_medium_free_list : 800 -> 804
~ _print_medium_region_vis : 784 -> 788
~ _medium_free_list_check : 708 -> 712
~ _malloc_freezedry : 212 -> 220
~ _malloc_jumpstart : 272 -> 276
~ _tiny_madvise_pressure_relief : 908 -> 912
~ _tiny_check_region : 1324 -> 1332
~ _tiny_in_use_enumerator : 1040 -> 1056
~ _print_tiny_free_list : 576 -> 580
~ _tiny_free_list_check : 668 -> 672
~ _tiny_check : 380 -> 384
```
