## zsh

> `/bin/zsh`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 118.0.0.0.0
-  __TEXT.__text: 0x77e0c
+  __TEXT.__text: 0x77480
   __TEXT.__auth_stubs: 0xb80
   __TEXT.__const: 0x4f90
   __TEXT.__cstring: 0x6477
-  __TEXT.__unwind_info: 0xd28
+  __TEXT.__unwind_info: 0x1128
   __DATA_CONST.__const: 0xe70
   __DATA_CONST.__auth_got: 0x5c0
   __DATA_CONST.__got: 0x48
Functions:
~ _createbuiltintable : 256 -> 244
~ sub_10000088c -> sub_100000880 : 84 -> 72
~ sub_1000008e0 -> sub_1000008c8 : 128 -> 116
~ _init_builtins : 116 -> 104
~ _bin_enable : 1016 -> 1004
~ _set_pwd_env : 328 -> 316
~ _bin_cd : 2940 -> 2932
~ _cd_able_vars : 128 -> 116
~ _printif : 96 -> 84
~ _bin_fc : 3336 -> 3332
~ _bin_typeset : 6916 -> 6904
~ sub_100007f08 -> sub_100007e90 : 252 -> 240
~ sub_100008004 -> sub_100007f80 : 432 -> 420
~ sub_1000081b4 -> sub_100008124 : 632 -> 620
~ _bin_unset : 1572 -> 1560
~ _bin_print : 10000 -> 9948
~ _bin_break : 720 -> 716
~ _bin_read : 5176 -> 5172
~ _zopenmax : 68 -> 60
~ _zgetcwd : 148 -> 136
~ sub_100011f18 -> sub_100011e20 : 236 -> 224
~ _findcmd : 856 -> 844
~ _execstring : 168 -> 156
~ _execlist : 2320 -> 2316
~ _execsubst : 116 -> 104
~ sub_100015380 -> sub_100015254 : 180 -> 168
~ sub_10001806c -> sub_100017f34 : 1416 -> 1420
~ sub_100018bb0 -> sub_100018a7c : 104 -> 92
~ sub_100018f38 -> sub_100018df8 : 352 -> 364
~ sub_100019098 -> sub_100018f64 : 11676 -> 11664
~ sub_10001be34 -> sub_10001bcf4 : 864 -> 868
~ sub_10001c194 -> sub_10001c058 : 176 -> 164
~ sub_10001c4b4 -> sub_10001c36c : 864 -> 840
~ sub_10001d024 -> sub_10001cec4 : 412 -> 416
~ _zglob : 9272 -> 9256
~ _xpandbraces : 1828 -> 1824
~ _deletehashtable : 80 -> 68
~ _addhashnode : 72 -> 60
~ sub_100024cec -> sub_100024b64 : 168 -> 156
~ sub_1000253f8 -> sub_100025264 : 80 -> 68
~ sub_100025448 -> sub_1000252a8 : 468 -> 456
~ sub_1000258d0 -> sub_100025724 : 132 -> 108
~ sub_100025954 -> sub_100025790 : 132 -> 120
~ sub_1000259d8 -> sub_100025808 : 120 -> 108
~ sub_100025a50 -> sub_100025874 : 156 -> 144
~ sub_100025aec -> sub_100025904 : 696 -> 684
~ sub_100025fd0 -> sub_100025ddc : 128 -> 116
~ sub_1000260f8 -> sub_100025ef8 : 72 -> 60
~ sub_100026140 -> sub_100025f34 : 580 -> 568
~ _emptyhisttable : 64 -> 52
~ _addhistnode : 208 -> 196
~ _freehistnode : 64 -> 52
~ _createnameddirtable : 244 -> 232
~ sub_100026d68 -> sub_100026b20 : 52 -> 40
~ sub_100026e0c -> sub_100026bb8 : 112 -> 100
~ sub_100026eb0 -> sub_100026c50 : 72 -> 60
~ sub_100026ef8 -> sub_100026c8c : 164 -> 152
~ _strinbeg : 64 -> 52
~ _hbegin : 1032 -> 1020
~ _hwrep : 260 -> 248
~ sub_10002d4fc -> sub_10002d260 : 208 -> 184
~ _parseopts : 1500 -> 1492
~ sub_10002e6d8 -> sub_10002e41c : 220 -> 208
~ _init_io : 760 -> 748
~ _init_shout : 140 -> 128
~ _setupvals : 2180 -> 2176
~ _sourcehome : 516 -> 504
~ _init_misc : 312 -> 300
~ _shinbufrestore : 116 -> 104
~ sub_100031a4c -> sub_100031744 : 392 -> 380
~ _inungetc : 440 -> 428
~ _inpush : 404 -> 392
~ _update_job : 1924 -> 1900
~ _printjob : 2476 -> 2472
~ _deletejob : 140 -> 128
~ _addfilelist : 192 -> 180
~ _deletefilelist : 160 -> 148
~ sub_100034580 -> sub_100034214 : 124 -> 112
~ _clearjobtab : 364 -> 368
~ _spawnjob : 440 -> 444
~ _addbgstatus : 256 -> 244
~ _bin_fg : 3672 -> 3676
~ sub_100036780 -> sub_100036408 : 208 -> 196
~ _removetrapnode : 108 -> 96
~ _acquire_pgrp : 440 -> 428
~ _exalias : 976 -> 964
~ _add : 168 -> 164
~ _freelinklist : 112 -> 100
~ _selectlist : 576 -> 568
~ sub_10003dfcc -> sub_10003dc0c : 2364 -> 2348
~ sub_10003ea7c -> sub_10003e6ac : 140 -> 144
~ sub_10003eb08 -> sub_10003e73c : 1784 -> 1760
~ _hrealloc : 1472 -> 1456
~ sub_100040d60 -> sub_10004096c : 136 -> 124
~ _register_module : 152 -> 140
~ _ensurefeature : 192 -> 180
~ _runhookdef : 156 -> 144
~ _removemathfunc : 92 -> 80
~ sub_100042bc4 -> sub_100042794 : 124 -> 112
~ sub_100042d40 -> sub_100042904 : 148 -> 124
~ _bin_zmodload : 792 -> 780
~ sub_100043894 -> sub_100043434 : 1896 -> 1872
~ sub_100044090 -> sub_100043c18 : 476 -> 452
~ sub_10004426c -> sub_100043ddc : 676 -> 664
~ _setfeatureenables : 968 -> 980
~ _handlefeatures : 88 -> 76
~ sub_100045490 -> sub_100044ff4 : 112 -> 100
~ sub_100045500 -> sub_100045058 : 112 -> 100
~ sub_100045b28 -> sub_100045674 : 264 -> 252
~ sub_100045e2c -> sub_10004596c : 288 -> 272
~ sub_100046dac -> sub_1000468dc : 140 -> 128
~ _strsetfn : 128 -> 116
~ _arrsetfn : 120 -> 108
~ _arrvarsetfn : 196 -> 184
~ _colonarrsetfn : 128 -> 116
~ _freeparamnode : 116 -> 104
~ sub_100047af4 -> sub_1000475dc : 104 -> 92
~ _issetvar : 236 -> 232
~ _copyparam : 308 -> 296
~ sub_1000499a0 -> sub_10004946c : 4896 -> 4892
~ _getstrvalue : 1684 -> 1648
~ _getarrvalue : 612 -> 588
~ _getintvalue : 184 -> 160
~ _assignstrvalue : 1200 -> 1188
~ _setarrvalue : 1176 -> 1128
~ _setnumvalue : 436 -> 424
~ sub_10004cb1c -> sub_10004c548 : 616 -> 592
~ _getsparam_u : 56 -> 44
~ _uniqarray : 88 -> 76
~ _arrfixenv : 236 -> 224
~ sub_10004e870 -> sub_10004e260 : 672 -> 644
~ _usernamesetfn : 236 -> 224
~ _ifssetfn : 68 -> 56
~ _lc_allsetfn : 316 -> 304
~ _langsetfn : 60 -> 48
~ _lcsetfn : 384 -> 372
~ _errnosetfn : 92 -> 80
~ _homesetfn : 144 -> 132
~ _wordcharssetfn : 68 -> 56
~ _termsetfn : 88 -> 76
~ _terminfosetfn : 104 -> 92
~ _terminfodirssetfn : 104 -> 92
~ sub_10004ff44 -> sub_10004f894 : 592 -> 568
~ sub_1000501c0 -> sub_10004faf8 : 120 -> 108
~ _parse_event : 192 -> 180
~ _parse_list : 192 -> 180
~ sub_100051110 -> sub_100050a24 : 360 -> 348
~ _parse_cond : 116 -> 104
~ _dupeprog : 236 -> 240
~ _freeeprog : 188 -> 176
~ _decrdumpcount : 172 -> 160
~ _ecgetstr : 192 -> 184
~ _ecrawstr : 120 -> 124
~ _eccopyredirs : 420 -> 412
~ sub_100051e4c -> sub_100051728 : 224 -> 220
~ _bin_zcompile : 1824 -> 1828
~ sub_100052864 -> sub_100052140 : 108 -> 116
~ _dump_autoload : 304 -> 312
~ sub_1000567b0 -> sub_10005609c : 1984 -> 1948
~ _patcompile : 1480 -> 1472
~ sub_100057e98 -> sub_100057758 : 1436 -> 1440
~ sub_1000594f8 -> sub_100058dbc : 6648 -> 6620
~ sub_10005c150 -> sub_10005b9f8 : 92 -> 104
~ _promptexpand : 552 -> 540
~ sub_10005d624 -> sub_10005cecc : 5568 -> 5556
~ _tsetcap : 580 -> 568
~ _set_colour_attribute : 1020 -> 1008
~ _allocate_colour_buffer : 496 -> 492
~ sub_100060448 -> sub_10005fcc8 : 324 -> 312
~ _endtrapscope : 624 -> 600
~ sub_100062e88 -> sub_1000626e4 : 828 -> 824
~ _dupstring : 72 -> 60
~ _dupstring_glen : 84 -> 72
~ _ztrdup : 72 -> 60
~ _appstr : 104 -> 92
~ _globlist : 244 -> 232
~ _filesubstr : 868 -> 864
~ _equalsubstr : 212 -> 200
~ sub_100065e00 -> sub_10006560c : 200 -> 196
~ sub_100065ff4 -> sub_1000657fc : 15980 -> 15956
~ sub_10006a460 -> sub_100069c50 : 284 -> 272
~ sub_10006b104 -> sub_10006a8e8 : 296 -> 284
~ _zoutputtab : 132 -> 120
~ sub_10006b4bc -> sub_10006ac88 : 4652 -> 4640
~ sub_10006cdb8 -> sub_10006c578 : 208 -> 196
~ sub_10006ce88 -> sub_10006c63c : 220 -> 196
~ sub_10006d084 -> sub_10006c820 : 276 -> 264
~ _tulower : 116 -> 104
~ _is_wcs_nicechar : 140 -> 128
~ _findpwd : 140 -> 128
~ _fprintdir : 128 -> 116
~ _substnamedir : 136 -> 112
~ _adduserdir : 496 -> 472
~ _getnameddir : 328 -> 316
~ _addprepromptfn : 100 -> 88
~ _delprepromptfn : 112 -> 100
~ _addtimedfn : 148 -> 136
~ _deltimedfn : 112 -> 100
~ _adjustwinsize : 500 -> 488
~ _tuupper : 116 -> 104
~ _zsleep_random : 164 -> 152
~ _ztrftime : 1840 -> 1836
~ _zjoin : 288 -> 276
~ _sepjoin : 456 -> 432
~ _sepsplit : 348 -> 336
~ _freearray : 76 -> 64
~ _arrdup_max : 148 -> 144
~ _quotedzputs : 1184 -> 1172
~ _restoredir : 516 -> 504
```
