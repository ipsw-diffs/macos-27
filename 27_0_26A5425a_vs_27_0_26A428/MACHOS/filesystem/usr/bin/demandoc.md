## demandoc

> `/usr/bin/demandoc`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 17.0.0.0.0
-  __TEXT.__text: 0x1b4d4
+  __TEXT.__text: 0x1b0a8
   __TEXT.__auth_stubs: 0x3f0
   __TEXT.__cstring: 0x5fcc
   __TEXT.__const: 0x230
-  __TEXT.__unwind_info: 0x450
+  __TEXT.__unwind_info: 0x720
   __DATA_CONST.__const: 0x4d38
   __DATA_CONST.__auth_got: 0x1f8
   __DATA_CONST.__got: 0x20
Functions:
~ _pmandoc : 172 -> 160
~ _ohash_qlookup : 92 -> 80
~ _ohash_qlookupi : 92 -> 80
~ _reallocarray : 88 -> 76
~ _recallocarray : 328 -> 316
~ _man_parseln : 1144 -> 1152
~ _rew_scope : 280 -> 268
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ _man_validate : 560 -> 536
~ _post_TH : 828 -> 816
~ _post_SH : 544 -> 532
~ _check_par : 348 -> 336
~ _post_IP : 200 -> 176
~ _post_OP : 120 -> 108
~ _post_MR : 264 -> 252
~ _mdoc_parseln : 1652 -> 1656
~ _mdoc_argv_free : 296 -> 284
~ _mdoc_endparse : 208 -> 196
~ _blk_full : 2180 -> 2168
~ _ctx_synopsis : 96 -> 60
~ _phrase_ta : 272 -> 248
~ _rew_elem : 92 -> 80
~ _dword : 312 -> 300
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ _mdoc_state : 152 -> 140
~ _mdoc_validate : 2044 -> 2008
~ _post_dt : 728 -> 716
~ _post_sh : 1768 -> 1756
~ _post_section : 480 -> 456
~ _post_display : 908 -> 884
~ _post_bl : 2184 -> 2172
~ _post_it : 672 -> 648
~ _post_an : 360 -> 336
~ _post_defaults : 208 -> 196
~ _post_tag : 164 -> 152
~ _post_er : 124 -> 112
~ _post_fa : 188 -> 176
~ _post_fn : 56 -> 44
~ _post_nd : 152 -> 140
~ _post_st : 212 -> 200
~ _post_xr : 176 -> 164
~ _post_bf : 408 -> 396
~ _post_em : 64 -> 52
~ _post_rs : 440 -> 428
~ _post_sm : 256 -> 244
~ _post_sx : 56 -> 44
~ _post_fo : 224 -> 200
~ _post_bk : 116 -> 104
~ _post_tg : 772 -> 748
~ _post_prevpar : 252 -> 240
~ _post_fname : 224 -> 212
~ _eqn_box_free : 124 -> 112
~ _eqn_free : 140 -> 128
~ _roff_free : 120 -> 108
~ _roff_setreg : 100 -> 88
~ _roff_man_reset : 140 -> 128
~ _roff_man_free1 : 124 -> 112
~ _roff_man_free : 64 -> 52
~ _roff_strdup : 572 -> 560
~ _roff_node_relink : 68 -> 56
~ _roff_node_free : 112 -> 100
~ _roff_node_delete : 92 -> 80
~ _roff_getarg : 640 -> 628
~ _roff_parseln : 2216 -> 2192
~ _roff_req_or_macro : 436 -> 424
~ _roff_getreg : 76 -> 64
~ _roff_cond : 1240 -> 1244
~ _roff_setstr : 160 -> 148
~ _roff_validate : 84 -> 72
~ _roff_valid_br : 208 -> 196
~ _roff_valid_ft : 192 -> 180
~ _roff_valid_sp : 152 -> 140
~ _getdata : 1072 -> 1068
~ _mandoc_normdate : 660 -> 636
~ _mandoc_strntoi : 220 -> 212
~ _OUTLINED_FUNCTION_0 : 24 -> 12
~ _mparse_readfd : 1216 -> 1204
~ _mparse_reset : 84 -> 72
~ _mparse_free : 104 -> 92
~ _tag_put : 748 -> 744
```
