## libFontValidation.dylib

> `/System/Library/Frameworks/ApplicationServices.framework/Versions/A/Frameworks/ATS.framework/Versions/A/Resources/libFontValidation.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH.__thread_vars`
- `__DATA.__data`

```diff

-604.0.0.0.0
-  __TEXT.__text: 0x45b58
+605.0.0.0.0
+  __TEXT.__text: 0x46aa0
   __TEXT.__init_offsets: 0x4
-  __TEXT.__gcc_except_tab: 0x2390
-  __TEXT.__cstring: 0x1345d
-  __TEXT.__const: 0x1496
-  __TEXT.__ustring: 0x4cbe
-  __TEXT.__unwind_info: 0x1cc8
+  __TEXT.__gcc_except_tab: 0x2540
+  __TEXT.__cstring: 0x13522
+  __TEXT.__const: 0x14c0
+  __TEXT.__ustring: 0x4f34
+  __TEXT.__unwind_info: 0x1ce8
   __TEXT.__objc_stubs: 0x140
-  __TEXT.__auth_stubs: 0xb10
+  __TEXT.__auth_stubs: 0xb20
   __TEXT.__objc_methname: 0xe6
   __DATA_CONST.__const: 0x738
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_selrefs: 0x50
   __DATA_CONST.__got: 0xe0
   __AUTH_CONST.__const: 0x5c38
-  __AUTH_CONST.__cfstring: 0x9060
+  __AUTH_CONST.__cfstring: 0x9140
   __AUTH_CONST.__weak_auth_got: 0x30
-  __AUTH_CONST.__auth_got: 0x568
+  __AUTH_CONST.__auth_got: 0x570
   __AUTH.__thread_vars: 0x48
   __AUTH.__thread_bss: 0x18
   __DATA.__data: 0x920

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1597
-  Symbols:   2716
-  CStrings:  1977
+  Functions: 1601
+  Symbols:   2724
+  CStrings:  1981
 
Symbols:
+ GCC_except_table43
+ GCC_except_table51
+ GCC_except_table61
+ __ZNK11FTFont_sfnt22GetDroppedTableEntriesEv
+ __ZNK18ATSFontTester_sfnt18CheckDroppedTablesEv
+ __ZNK27ATSFontTesterStructure_kern15TestSimpleArrayEPKhRK21KernSimpleArrayHeaderm
+ __ZNSt3__119__allocate_at_leastB9nqe220106INS_9allocatorIN11FTFont_sfnt17DroppedTableEntryEEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
+ __ZNSt3__16vectorIN11FTFont_sfnt17DroppedTableEntryENS_9allocatorIS2_EEE20__throw_length_errorB9nqe220106Ev
+ __ZNSt3__16vectorIN11FTFont_sfnt17DroppedTableEntryENS_9allocatorIS2_EEE24__emplace_back_slow_pathIJS2_EEEPS2_DpOT_
+ __ZZL19TableIsNeededToDrawjE19kTablesNeededToDraw
+ ___cxa_rethrow
- GCC_except_table42
- GCC_except_table50
- __ZNK27ATSFontTesterStructure_kern15TestSimpleArrayERK18KernSubtableHeaderm
CStrings:
+ "%d font tables extend beyond the end of the font; more than %d means the font's directory cannot be trusted."
+ "Font table ‘%s’ (offset %u, length %u) extends beyond the end of the font (%u bytes), and the font cannot be drawn without it."
+ "Font table ‘%s’ (offset %u, length %u) extends beyond the end of the font (%u bytes), so it is ignored."
+ "Font table ‘%s’ has a directory entry with offset 0 and length 0, so it is ignored."
+ "Glyph %d: %@"
+ "Simple array left class table (at subtable offset %d) runs past the end of the table."
+ "Simple array right class table (at subtable offset %d) runs past the end of the table."
+ "The 'loca' table is not long enough for the declared glyph count"
+ "tData8 >= tTableLimit"
+ "tGlyphOffset > GetUnswappedDataLength()"
+ "tLongOffsetData + 1 <= (const uint32_t *) tTableLimit"
- "The font's directory contains an invalid table length"
- "tData8 < tTableLimit"
- "tLength < tRawFontSize"
- "tLongOffsets + 1 <= (const uint32_t *) tTableLimit"
- "tTableEnd <= tRawFontSize"
- "tTableStart <= tRawFontSize"
- "tTable_loca->GetGlyphOffset( (uint16_t) tIndex ) > GetUnswappedDataLength()"
```
