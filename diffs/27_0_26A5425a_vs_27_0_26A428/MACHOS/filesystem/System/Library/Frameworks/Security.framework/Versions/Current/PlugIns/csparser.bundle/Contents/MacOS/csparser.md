## csparser

> `/System/Library/Frameworks/Security.framework/Versions/Current/PlugIns/csparser.bundle/Contents/MacOS/csparser`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__dof_security_`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-62460.1.2.0.0
-  __TEXT.__text: 0x15400
+62460.1.3.0.0
+  __TEXT.__text: 0x15100
   __TEXT.__auth_stubs: 0x540
   __TEXT.__init_offsets: 0x8
   __TEXT.__const: 0xe2c

   __TEXT.__oslogstring: 0x72
   __TEXT.__objc_methname: 0x82
   __TEXT.__dof_security_: 0x289
-  __TEXT.__unwind_info: 0x6f8
+  __TEXT.__unwind_info: 0x780
   __DATA_CONST.__const: 0x1048
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ __ZN20Security_CodeSigning16RequirementLexerC1ERN5antlr11InputBufferE : 2504 -> 2484
~ __ZN20Security_CodeSigning17RequirementParser4exprERN8Security11CodeSigning11Requirement5MakerE : 380 -> 368
~ __ZN20Security_CodeSigning17RequirementParser4termERN8Security11CodeSigning11Requirement5MakerE : 380 -> 368
~ __ZN5antlr11TokenBuffer4fillEj : 340 -> 336
~ __ZN20Security_CodeSigning16RequirementLexer9nextTokenEv : 10192 -> 10112
~ __ZN5antlr11CharScanner2LAEj : 152 -> 140
~ __ZN5antlr11InputBuffer4fillEj : 336 -> 332
~ __ZN5antlr11CharScanner5matchEi : 216 -> 204
~ __ZN5antlr11CharScanner7consumeEv : 296 -> 284
~ __ZN5antlr11CharScanner10matchRangeEii : 232 -> 220
~ __ZN5antlr6Parser5matchEi : 452 -> 440
~ __ZN5antlr11CharScanner5matchERKNS_6BitSetE : 304 -> 292
~ __ZN8Security11CodeSigning11Requirement5Maker7requireEm : 104 -> 100
~ __ZN8Security11CodeSigning11Requirement5Maker7putDataEPKvm : 120 -> 108
~ ____ZN8Security17ModuleNexusCommon6createEPFPvvE_block_invoke : 76 -> 64
~ __ZN5antlr16ParserInputStateD0Ev : 56 -> 44
~ __ZN5antlr11TokenBufferD0Ev : 100 -> 88
~ __ZN5antlr11CommonTokenD0Ev : 112 -> 100
~ __ZN5antlr15LexerInputStateD0Ev : 56 -> 44
~ ___secLogObjForCFScope_block_invoke : 80 -> 68
~ _secLogObjForScope : 144 -> 132
~ _PerformWithBuffer : 392 -> 368
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE17__assign_externalEPKc : 72 -> 60
~ __ZN8Security16ModuleNexusErrorD0Ev : 56 -> 44
~ __ZN8Security9UnixErrorD0Ev : 56 -> 44
~ __ZN8Security7CFErrorD0Ev : 56 -> 44
~ __ZN18SensitiveAllocator4freeEPv : 84 -> 72
~ __ZN18SensitiveAllocator7reallocEPvm : 92 -> 80
~ __ZN18SensitiveAllocator18realloc_typed_implEPvmy : 108 -> 96
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE25__init_copy_ctor_externalEPKcm : 68 -> 56
~ __ZNSt3__16vectorIjNS_9allocatorIjEEE24__emplace_back_slow_pathIJRKjEEEPjDpOT_ : 220 -> 216
~ __ZN5antlr10CharBufferD0Ev : 112 -> 100
~ __ZN5antlr11CharScanner7recoverERKNS_20RecognitionExceptionERKNS_6BitSetE : 112 -> 100
~ __ZN5antlr11CharScanner8matchNotEi : 212 -> 200
~ __ZN5antlr11CharScanner3tabEv : 124 -> 112
~ __ZN5antlr23MismatchedCharExceptionD1Ev : 92 -> 80
~ __ZN5antlr14ANTLRExceptionD0Ev : 112 -> 100
~ __ZNSt3__1ssB9nqe220106IcNS_11char_traitsIcEENS_9allocatorIcEEEEDaRKNS_12basic_stringIT_T0_T1_EESC_ : 124 -> 120
~ __ZN5antlr11InputBuffer4markEv : 196 -> 192
~ __ZN5antlr11InputBuffer6rewindEj : 184 -> 180
~ __ZN5antlr6Parser8matchNotEi : 452 -> 440
~ __ZN5antlr6Parser5matchERKNS_6BitSetE : 496 -> 484
~ __ZN5antlr6Parser4markEv : 152 -> 148
~ __ZN5antlr6Parser6rewindEj : 140 -> 136
~ __ZN5antlr6Parser7recoverERKNS_20RecognitionExceptionERKNS_6BitSetE : 112 -> 100
~ __ZN5antlr24MismatchedTokenExceptionD2Ev : 124 -> 112
~ __ZN5antlr23MismatchedCharExceptionD0Ev : 112 -> 100
~ __ZN5antlr24MismatchedTokenExceptionD0Ev : 56 -> 44
~ __ZN5antlr20NoViableAltExceptionD0Ev : 56 -> 44
~ __ZN5antlr20NoViableAltExceptionD2Ev : 100 -> 88
~ __ZN5antlr27NoViableAltForCharExceptionD0Ev : 56 -> 44
~ __ZN5antlr20RecognitionExceptionD0Ev : 56 -> 44
~ __ZN20Security_CodeSigning16RequirementLexerD0Ev : 56 -> 44
~ __ZN5antlr20TokenStreamExceptionD0Ev : 112 -> 100
~ __ZN5antlr22TokenStreamIOExceptionD0Ev : 56 -> 44
~ __ZN5antlr31TokenStreamRecognitionExceptionD0Ev : 56 -> 44
~ __ZN20Security_CodeSigning17RequirementParserD0Ev : 152 -> 140
~ __ZN5antlr17SemanticExceptionD0Ev : 56 -> 44
~ __ZNSt3__16vectorIN5antlr13TokenRefCountINS1_5TokenEEENS_9allocatorIS4_EEE16__destroy_vectorclB9nqe220106Ev : 112 -> 100
~ __ZNSt3__16vectorIN5antlr13TokenRefCountINS1_5TokenEEENS_9allocatorIS4_EEE24__emplace_back_slow_pathIJRKS4_EEEPS4_DpOT_ : 308 -> 300
~ __ZN8Security11CodeSigning16StdioInputStreamD0Ev : 112 -> 100
~ __ZN8Security11CodeSigning17StringInputStreamD0Ev : 156 -> 144
~ __ZN8Security12CssmAutoDataD0Ev : 132 -> 120
```
