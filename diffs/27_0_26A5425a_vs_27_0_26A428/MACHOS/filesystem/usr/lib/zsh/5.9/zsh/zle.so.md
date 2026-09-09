## zle.so

> `/usr/lib/zsh/5.9/zsh/zle.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 118.0.0.0.0
-  __TEXT.__text: 0x24078
+  __TEXT.__text: 0x23c2c
   __TEXT.__auth_stubs: 0x1930
   __TEXT.__cstring: 0x27cb
   __TEXT.__const: 0x210
-  __TEXT.__unwind_info: 0x5c8
+  __TEXT.__unwind_info: 0x758
   __DATA_CONST.__const: 0xb18
   __DATA_CONST.__auth_got: 0xc98
   __DATA_CONST.__got: 0x618
Functions:
~ _remember_edits : 220 -> 208
~ _viuplineorhistory : 76 -> 64
~ _vidownlineorhistory : 68 -> 56
~ _zle_setline : 160 -> 148
~ _beginningofbufferorhistory : 68 -> 56
~ sub_1ed8 -> sub_1e9c : 5068 -> 5072
~ sub_3390 -> sub_3358 : 168 -> 156
~ _vihistorysearchforward : 144 -> 132
~ _vihistorysearchbackward : 144 -> 132
~ sub_42a8 -> sub_424c : 152 -> 140
~ _deletekeymap : 100 -> 88
~ sub_474c -> sub_46d8 : 148 -> 136
~ _bin_bindkey : 732 -> 708
~ _cleanup_keymaps : 76 -> 64
~ _zlesetkeymap : 108 -> 96
~ sub_6c14 -> sub_6b64 : 80 -> 68
~ sub_6cbc -> sub_6c00 : 304 -> 292
~ sub_6dec -> sub_6d24 : 144 -> 132
~ sub_6e7c -> sub_6da8 : 436 -> 424
~ sub_71e8 -> sub_7108 : 72 -> 60
~ _getbyte : 2524 -> 2520
~ _getfullchar : 60 -> 48
~ _zlecore : 816 -> 812
~ sub_9640 -> sub_9540 : 100 -> 88
~ sub_9898 -> sub_978c : 176 -> 164
~ _resetprompt : 44 -> 32
~ _zle_resetprompt : 68 -> 56
~ _cleanup_ : 188 -> 176
~ sub_a24c -> sub_a110 : 292 -> 276
~ sub_af50 -> sub_ae04 : 112 -> 100
~ _doinsert : 484 -> 480
~ _backwarddeletechar : 104 -> 100
~ sub_baa4 -> sub_b944 : 184 -> 172
~ _transposechars : 412 -> 408
~ _regionlines : 160 -> 156
~ sub_c390 -> sub_c21c : 656 -> 632
~ _quotedinsert : 76 -> 64
~ _makesuffixstr : 516 -> 504
~ _exchangepointandmark : 100 -> 96
~ _vifindnextchar : 112 -> 100
~ _vifindprevchar : 112 -> 100
~ _vifindnextcharskip : 116 -> 104
~ _vifindprevcharskip : 116 -> 104
~ sub_fef8 -> sub_fd20 : 144 -> 132
~ sub_10118 -> sub_ff34 : 76 -> 72
~ sub_1025c -> sub_10074 : 56 -> 44
~ sub_10524 -> sub_10330 : 76 -> 64
~ sub_10748 -> sub_10548 : 44 -> 40
~ _get_region_highlight : 596 -> 584
~ _unset_region_highlight : 76 -> 64
~ sub_1157c -> sub_11360 : 232 -> 220
~ _zrefresh : 9964 -> 9952
~ _moveto : 628 -> 616
~ sub_143a0 -> sub_14160 : 76 -> 64
~ sub_14570 -> sub_14324 : 192 -> 184
~ sub_14960 -> sub_1470c : 3328 -> 3312
~ _unrefthingy : 104 -> 92
~ _freewidget : 120 -> 108
~ _deletezlefunction : 104 -> 92
~ _bin_zle : 236 -> 224
~ sub_16a24 -> sub_16790 : 76 -> 64
~ sub_1762c -> sub_1738c : 500 -> 476
~ sub_1784c -> sub_17594 : 64 -> 52
~ _completeword : 272 -> 248
~ sub_17ab8 -> sub_177dc : 12900 -> 12892
~ _menucomplete : 152 -> 128
~ _deletecharorlist : 176 -> 152
~ _expandword : 136 -> 112
~ _expandorcomplete : 272 -> 248
~ _menuexpandorcomplete : 152 -> 128
~ _acceptandmenucomplete : 100 -> 88
~ _unmetafy_line : 152 -> 140
~ _listlist : 2192 -> 2180
~ _stringaszleline : 868 -> 864
~ _zle_restore_positions : 436 -> 424
~ _zle_free_positions : 96 -> 84
~ _cuttext : 828 -> 832
~ _backkill : 168 -> 156
~ _forekill : 172 -> 160
~ _backdel : 228 -> 204
~ _foredel : 204 -> 180
~ _setline : 272 -> 260
~ _showmsg : 656 -> 652
~ _handleundo : 248 -> 236
~ _mkundoent : 564 -> 560
~ _viundochange : 116 -> 104
~ _startvichange : 384 -> 372
~ _viquotedinsert : 152 -> 140
~ _vidigitorbeginningofline : 132 -> 108
~ _upcaseword : 228 -> 224
~ _downcaseword : 228 -> 224
~ _capitalizeword : 392 -> 388
~ _transposewords : 752 -> 748
```
