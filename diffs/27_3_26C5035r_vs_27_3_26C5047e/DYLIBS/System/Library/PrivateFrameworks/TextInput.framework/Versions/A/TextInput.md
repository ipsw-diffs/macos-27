## TextInput

> `/System/Library/PrivateFrameworks/TextInput.framework/Versions/A/TextInput`

```diff

-3568.2.4.0.0
-  __TEXT.__text: 0x82320
-  __TEXT.__objc_methlist: 0xb6a8
+3568.2.7.0.0
+  __TEXT.__text: 0x829c8
+  __TEXT.__objc_methlist: 0xb740
   __TEXT.__dlopen_cstrs: 0x1ea
-  __TEXT.__const: 0x4d0
-  __TEXT.__cstring: 0x4920a
+  __TEXT.__const: 0x4e0
+  __TEXT.__cstring: 0x49220
   __TEXT.__ustring: 0xc8bd8
-  __TEXT.__oslogstring: 0xb19
-  __TEXT.__unwind_info: 0x2948
+  __TEXT.__oslogstring: 0xbeb
+  __TEXT.__unwind_info: 0x2958
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x100
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5640
+  __DATA_CONST.__objc_selrefs: 0x56a8
   __DATA_CONST.__objc_protorefs: 0x60
   __DATA_CONST.__objc_superrefs: 0x408
-  __DATA_CONST.__objc_arraydata: 0x101a90
+  __DATA_CONST.__objc_arraydata: 0x101aa8
   __DATA_CONST.__got: 0x608
-  __AUTH_CONST.__const: 0x1fc0
-  __AUTH_CONST.__cfstring: 0x255be0
-  __AUTH_CONST.__objc_const: 0x11d58
+  __AUTH_CONST.__const: 0x1ff0
+  __AUTH_CONST.__cfstring: 0x255c00
+  __AUTH_CONST.__objc_const: 0x11df0
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x50a0
   __AUTH_CONST.__objc_dictobj: 0xf1b8

   __AUTH_CONST.__objc_doubleobj: 0xc0
   __AUTH_CONST.__auth_got: 0x6b8
   __AUTH.__objc_data: 0x25d0
-  __DATA.__objc_ivar: 0xb84
+  __DATA.__objc_ivar: 0xb90
   __DATA.__data: 0xc90
   __DATA.__bss: 0x758
   __DATA_DIRTY.__objc_data: 0x1400

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 4035
-  Symbols:   9285
-  CStrings:  76779
+  Functions: 4049
+  Symbols:   9312
+  CStrings:  76782
 
Symbols:
+ +[TIKeyboardCandidate prefersArchivedResultSetCoding]
+ +[TIKeyboardCandidateResultSet _archivedCandidatesFromData:]
+ +[TIKeyboardCandidateResultSetCoder decodeWithData:archivedCandidates:]
+ +[TIKeyboardCandidateResultSetCoder encodeWithCandidateResultSet:archivedCandidates:]
+ -[TIKeyboardCandidateResultSetCoder archivedCandidates]
+ -[TIKeyboardCandidateResultSetCoder encodeCandidate:]
+ -[TIKeyboardCandidateResultSetCoder encodedCandidateCount]
+ -[TIKeyboardCandidateResultSetCoder replacementCandidates]
+ -[TIKeyboardCandidateResultSetCoder setArchivedCandidates:]
+ -[TIKeyboardCandidateResultSetCoder setEncodedCandidateCount:]
+ -[TIKeyboardCandidateResultSetCoder setReplacementCandidates:]
+ -[TIPreferencesController shouldSuppressEnglishCandidates]
+ -[TIPreferencesController shouldSuppressPredictionCandidates]
+ _OBJC_IVAR_$_TIKeyboardCandidateResultSetCoder._archivedCandidates
+ _OBJC_IVAR_$_TIKeyboardCandidateResultSetCoder._encodedCandidateCount
+ _OBJC_IVAR_$_TIKeyboardCandidateResultSetCoder._replacementCandidates
+ ___60+[TIKeyboardCandidateResultSet _archivedCandidatesFromData:]_block_invoke
+ ___block_descriptor_40_8_32s_e15_v32?0816^B24l
+ _objc_msgSend$_archivedCandidatesFromData:
+ _objc_msgSend$archivedCandidates
+ _objc_msgSend$decodeWithData:archivedCandidates:
+ _objc_msgSend$encodeCandidate:
+ _objc_msgSend$encodeWithCandidateResultSet:archivedCandidates:
+ _objc_msgSend$encodedCandidateCount
+ _objc_msgSend$prefersArchivedResultSetCoding
+ _objc_msgSend$replacementCandidates
+ _objc_msgSend$setArchivedCandidates:
+ _objc_msgSend$setEncodedCandidateCount:
+ _objc_msgSend$setReplacementCandidates:
- _objc_msgSend$decodeWithData:
- _objc_msgSend$encodeWithCandidateResultSet:
CStrings:
+ "Could not archive candidates of a candidate result set: domain=%{public}@ code=%{public}ld: %{private}@"
+ "Could not unarchive candidates of a candidate result set: domain=%{public}@ code=%{public}ld: %{private}@"
+ "archivedCandidates"
```
