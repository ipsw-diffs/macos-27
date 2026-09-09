## yara

> `/System/Library/PrivateFrameworks/yara.framework/Versions/A/yara`

```diff

 40.0.1.0.0
-  __TEXT.__text: 0x3aef0
+  __TEXT.__text: 0x3af3c
   __TEXT.__const: 0x3348
   __TEXT.__cstring: 0x8eb4
   __TEXT.__unwind_info: 0x6e0
Functions:
~ __yr_scanner_scan_mem_block : 892 -> 904
~ _yr_atoms_extract_from_re : 2236 -> 2240
~ _re_yyparse : 3008 -> 3068
~ _hex_yyparse : 2064 -> 2076
~ _yara_yyparse : 15260 -> 15272
~ _dotnet_parse_tilde_2 : 4832 -> 4796
~ _pe_rva_to_offset : 256 -> 260
~ _parse_elf_header_32_be : 2292 -> 2296
~ _parse_elf_header_64_be : 2288 -> 2292
```
