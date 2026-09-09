## mandoc

> `/usr/bin/mandoc`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 17.0.0.0.0
-  __TEXT.__text: 0x3ea0c
+  __TEXT.__text: 0x3e050
   __TEXT.__auth_stubs: 0x870
   __TEXT.__cstring: 0x8b8c
   __TEXT.__const: 0x6d0
-  __TEXT.__unwind_info: 0xac0
+  __TEXT.__unwind_info: 0x1200
   __DATA_CONST.__const: 0xadc0
   __DATA_CONST.__auth_got: 0x438
   __DATA_CONST.__got: 0x38
Functions:
~ _print_eqn : 156 -> 144
~ _html_reset : 56 -> 44
~ _html_free : 56 -> 44
~ _print_gen_head : 540 -> 528
~ _print_tagq : 116 -> 104
~ _print_ctag : 316 -> 304
~ _print_endword : 172 -> 160
~ _print_gen_decls : 108 -> 96
~ _print_metaf : 384 -> 372
~ _print_man_node : 796 -> 748
~ _mdoc_quote_post : 388 -> 376
~ _mdoc__x_post : 284 -> 272
~ _mdoc_fo_post : 116 -> 104
~ _synopsis_pre : 256 -> 244
~ _roff_html_pre : 80 -> 68
~ _roff_html_pre_ce : 164 -> 152
~ _roff_html_pre_fi : 92 -> 80
~ _roff_html_pre_ft : 84 -> 72
~ _roff_html_pre_nf : 92 -> 80
~ _roff_html_pre_sp : 144 -> 132
~ _print_man_node : 844 -> 796
~ _post_SH : 60 -> 48
~ _post_TP : 120 -> 108
~ _post_UR : 160 -> 148
~ _terminal_mdoc : 432 -> 408
~ _termp_sh_post : 100 -> 88
~ _termp_bl_post : 148 -> 136
~ _termp_in_post : 124 -> 112
~ _termp_nm_post : 164 -> 152
~ _termp_quote_post : 488 -> 380
~ _termp____post : 228 -> 216
~ _termp__t_post : 104 -> 92
~ _termp_fo_post : 140 -> 128
~ _print_bvspace : 312 -> 300
~ _synopsis_pre : 224 -> 200
~ _roff_term_pre : 56 -> 44
~ _roff_term_pre_ft : 240 -> 216
~ _roff_term_pre_ti : 244 -> 236
~ _term_free : 132 -> 120
~ _term_flushln : 1560 -> 1540
~ _endline : 172 -> 160
~ _term_vspace : 96 -> 84
~ _bufferc : 164 -> 152
~ _encode1 : 456 -> 444
~ _terminal_sepline : 120 -> 108
~ _ascii_uc2str : 60 -> 48
~ _pspdf_free : 84 -> 72
~ _ps_begin : 1136 -> 1124
~ _ps_end : 792 -> 780
~ _term_tbl : 4252 -> 4236
~ _tbl_word : 188 -> 176
~ _dbm_page_byname : 44 -> 32
~ _dbm_page_bysect : 44 -> 32
~ _dbm_page_bydesc : 44 -> 32
~ _dbm_page_bymacro : 64 -> 52
~ _dbm_page_next : 336 -> 312
~ _dbm_macro_bypage : 64 -> 52
~ _macro_bypage : 332 -> 320
~ _manpage_compare : 248 -> 232
~ _exprfree : 76 -> 64
~ _mansearch_free : 116 -> 104
~ _dba_page_add : 236 -> 212
~ _dba_page_alias : 164 -> 152
~ _dba_macro_add : 88 -> 76
~ _dba_array_free : 128 -> 116
~ _dba_array_add : 144 -> 132
~ _dba_array_sort : 60 -> 48
~ _dba_array_writelen : 76 -> 64
~ _dba_array_writelst : 80 -> 68
~ _dba_str_write : 64 -> 52
~ _mandocdb : 2820 -> 2840
~ _dbwrite : 1084 -> 1060
~ _mlink_free : 84 -> 72
~ _dbadd_mlink : 148 -> 136
~ _parse_mdoc_fname : 188 -> 176
~ _main : 7320 -> 7316
~ _manconf_free : 124 -> 112
~ _man_mdoc : 292 -> 280
~ _print_node : 736 -> 724
~ _post_dl : 112 -> 100
~ _post_bd : 276 -> 264
~ _post_bl : 244 -> 232
~ _post_it : 340 -> 328
~ _post_fa : 76 -> 64
~ _post_in : 136 -> 124
~ _post_enc : 104 -> 92
~ _post_percent : 332 -> 320
~ _post__t : 116 -> 104
~ _font_pop : 124 -> 112
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ _markdown_mdoc : 344 -> 332
~ _md_post_Fa : 72 -> 60
~ _md_post_In : 112 -> 100
~ _md_post_word : 104 -> 92
~ _md_post_pc : 188 -> 176
~ _md_post__T : 124 -> 112
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ _tblcalc : 2388 -> 2364
~ _tree_mdoc : 76 -> 64
~ _tree_man : 96 -> 84
~ _print_attr : 360 -> 348
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
