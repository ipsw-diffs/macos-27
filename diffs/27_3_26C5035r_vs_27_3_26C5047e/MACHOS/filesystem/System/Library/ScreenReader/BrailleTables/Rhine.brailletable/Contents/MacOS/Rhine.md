## Rhine

> `/System/Library/ScreenReader/BrailleTables/Rhine.brailletable/Contents/MacOS/Rhine`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-22.0.0.0.0
-  __TEXT.__text: 0x1eed4
-  __TEXT.__auth_stubs: 0x1f0
+24.0.0.0.0
+  __TEXT.__text: 0x21078
+  __TEXT.__auth_stubs: 0x210
   __TEXT.__objc_stubs: 0x3e0
   __TEXT.__objc_methlist: 0x264
-  __TEXT.__const: 0x21618
-  __TEXT.__cstring: 0xa3dc
+  __TEXT.__const: 0x21f58
+  __TEXT.__cstring: 0xa499
   __TEXT.__objc_classname: 0x6a
   __TEXT.__objc_methname: 0x620
   __TEXT.__objc_methtype: 0x228
   __TEXT.__oslogstring: 0x115
-  __TEXT.__unwind_info: 0x278
-  __DATA_CONST.__const: 0x46938
+  __TEXT.__unwind_info: 0x290
+  __DATA_CONST.__const: 0x46ab8
   __DATA_CONST.__cfstring: 0x240
   __DATA_CONST.__objc_classlist: 0x10
   __DATA_CONST.__objc_protolist: 0x18

   __DATA_CONST.__objc_arraydata: 0x78
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA_CONST.__objc_dictobj: 0x28
-  __DATA_CONST.__auth_got: 0x100
+  __DATA_CONST.__auth_got: 0x110
   __DATA_CONST.__got: 0x68
   __DATA.__objc_const: 0x3c0
   __DATA.__objc_selrefs: 0x1f0

   __DATA.__objc_data: 0xa0
   __DATA.__data: 0xea0
   __DATA.__common: 0x8520
-  __DATA.__bss: 0x1e0
+  __DATA.__bss: 0x1f0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/PrivateFrameworks/ScreenReader.framework/Versions/A/Frameworks/BrailleTranslation.framework/Versions/A/BrailleTranslation
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 152
-  Symbols:   273
-  CStrings:  4219
+  Symbols:   275
+  CStrings:  4237
 
Symbols:
+ _malloc_type_calloc
+ _strndup
Functions:
~ _equals_zweiformig : 352 -> 332
~ _no_exception : 368 -> 336
~ _is_figure : 316 -> 308
~ _is_common_abbrev : 476 -> 480
~ _lowerchar_follows : 712 -> 736
~ _std_string : 52 -> 60
~ _add_char : 20 -> 96
~ _add_string : 32 -> 60
~ _add_num : 232 -> 216
~ _add_time : 116 -> 104
~ _is_lower_num : 2112 -> 2148
~ _add_basis_char : 220 -> 232
~ _open_math_passage : 188 -> 288
~ _close_math_passage : 220 -> 216
~ _add_seg : 5828 -> 6656
~ _add_whitespace : 104 -> 112
~ _skip_whitespace : 192 -> 180
~ _remove_whitespace : 168 -> 152
~ _no_abbrev : 636 -> 624
~ _no_locution : 268 -> 264
~ _is_supersub : 152 -> 160
~ _process_dash : 688 -> 664
~ _process_quotes : 724 -> 696
~ _process_supersub : 1260 -> 1228
~ _wh_forward_translate : 44640 -> 44184
~ _bwd_fetch_char : 884 -> 868
~ _bwd_fetch_ueb_char : 116 -> 120
~ _bwd_add_char : 20 -> 68
~ _bwd_add_string : 44 -> 124
~ _bwd_add_space : 40 -> 128
~ _bwd_add_seg : 4016 -> 4228
~ _bwd_resolve_nospace : 316 -> 288
~ _bwd_add_rightchars : 676 -> 812
~ _bwd_no_locution : 852 -> 764
~ _bwd_add_abbrev_char : 252 -> 444
~ _bwd_generic_abbrev : 84 -> 180
~ _bwd_terminate_abbrev : 92 -> 104
~ _bwd_no_abbrev : 704 -> 688
~ _wh_backward_translate : 33016 -> 40008
~ sub_1f390 -> sub_21378 : 976 -> 1424
~ sub_1f760 -> sub_21908 : 532 -> 528
CStrings:
+ "\"#."
+ "\"#="
+ "\"."
+ "\"="
+ "&n."
+ "(){}[]1|03="
+ "({[<\x8b"
+ "*#"
+ "-."
+ ".s"
+ "/cort"
+ "7.0.26.1022"
+ "<<"
+ "<<<"
+ "<m*"
+ "=){~!?.\"`123456789>"
+ "Ch"
+ "Pro"
+ "SDG"
+ "["
+ "]"
+ "no/"
+ "\xab"
+ "\xbb"
- "&RIN"
- "(){}[]1|03"
- "({[<\x91"
- "123"
- "7.0.26.400"
- "GERIN"
```
