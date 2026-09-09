## ldapdl

> `/System/Library/Security/ldapdl.bundle/Contents/MacOS/ldapdl`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 55005.0.2.0.0
-  __TEXT.__text: 0x740c
+  __TEXT.__text: 0x729c
   __TEXT.__auth_stubs: 0x480
   __TEXT.__gcc_except_tab: 0x5a8
   __TEXT.__cstring: 0x22c
   __TEXT.__const: 0x2a6
-  __TEXT.__unwind_info: 0x4e8
+  __TEXT.__unwind_info: 0x5d0
   __DATA_CONST.__const: 0xbb8
   __DATA_CONST.__auth_got: 0x248
   __DATA_CONST.__got: 0xa0
Functions:
~ __ZN11BigNumValueD0Ev : 124 -> 112
~ __ZN9BlobValueD0Ev : 124 -> 112
~ __ZN22CssmSelectionPredicate27CloneCssmSelectionPredicateERS_RKS_ : 264 -> 252
~ sub_285c -> sub_2838 : 112 -> 100
~ __ZN13TableRelationD2Ev : 192 -> 180
~ __ZN13TableRelationD0Ev : 56 -> 44
~ __ZN10TableQueryD0Ev : 56 -> 44
~ sub_31b8 -> sub_3164 : 56 -> 44
~ sub_3208 -> sub_31a8 : 56 -> 44
~ __ZN11DSX509TupleD2Ev : 216 -> 204
~ __ZN11DSX509TupleD0Ev : 56 -> 44
~ __ZN22DSX509UniqueIdentifierD2Ev : 116 -> 104
~ __ZN22DSX509UniqueIdentifierD0Ev : 56 -> 44
~ __ZN14DSX509RelationD2Ev : 96 -> 84
~ __ZN14DSX509RelationD0Ev : 56 -> 44
~ __ZN11DSX509QueryD0Ev : 56 -> 44
~ __ZN12LDAPDLModule19InitializeRelationsEv : 100 -> 88
~ __ZN12LDAPDLModuleD0Ev : 56 -> 44
~ __ZN12LDAPDatabaseD2Ev : 108 -> 96
~ __ZN12LDAPDatabaseD0Ev : 56 -> 44
~ __ZN12LDAPDatabase6DbOpenEPKcPK16cssm_net_addressjPK23cssm_access_credentialsPKv : 72 -> 60
~ __ZN12LDAPDatabase21DbGetDbNameFromHandleEPPc : 108 -> 96
~ __ZN12LDAPDatabase14CopyAttributesEP8RelationP5TupleP29cssm_db_record_attribute_data : 420 -> 400
~ __ZN12LDAPDatabase18DbFreeUniqueRecordEP21cssm_db_unique_record : 104 -> 92
~ __ZN12LDAPDatabase27DbDataGetFromUniqueRecordIDEP21cssm_db_unique_recordP29cssm_db_record_attribute_dataP9cssm_data : 200 -> 188
~ sub_5bf8 -> sub_5ac4 : 56 -> 44
~ __ZN16AttachedInstance25GetDatabaseFromDLDBHandleERK17cssm_dl_db_handle : 72 -> 60
~ __ZN15PartialRelationD2Ev : 196 -> 184
~ sub_6f98 -> sub_6e40 : 260 -> 248
~ sub_709c -> sub_6f38 : 64 -> 52
```
