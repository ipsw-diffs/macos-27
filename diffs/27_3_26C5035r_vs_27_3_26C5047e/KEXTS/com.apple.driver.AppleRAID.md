## com.apple.driver.AppleRAID

> `com.apple.driver.AppleRAID`

```diff

-29.60.4.0.0
-  __TEXT.__const: 0x10
-  __TEXT.__cstring: 0x173a
-  __TEXT_EXEC.__text: 0x14314
+29.60.5.0.0
+  __TEXT.__const: 0x1b
+  __TEXT.__cstring: 0x1945
+  __TEXT_EXEC.__text: 0x14664
   __TEXT_EXEC.__auth_stubs: 0x490
   __DATA.__data: 0xc8
   __DATA.__common: 0x230
   __DATA_CONST.__mod_init_func: 0x58
   __DATA_CONST.__mod_term_func: 0x58
-  __DATA_CONST.__const: 0x6920
+  __DATA_CONST.__const: 0x6948
   __DATA_CONST.__kalloc_type: 0x340
   __DATA_CONST.__kalloc_var: 0x230
   __DATA_CONST.__auth_got: 0x248
   __DATA_CONST.__got: 0xc0
   __DATA_CONST.__auth_ptr: 0x8
   Functions: 482
-  Symbols:   1043
-  CStrings:  153
+  Symbols:   1044
+  CStrings:  158
 
Symbols:
+ __ZL25kAppleRAIDHeaderKeyPrefix
+ __ZNK15AppleRAIDMember18isMediaQuarantinedEv
+ __ZZN12AppleRAIDSet9resizeSetEjE20kalloc_type_view_527
+ __ZZN12AppleRAIDSet9resizeSetEjE20kalloc_type_view_547
+ __ZZN23AppleRAIDStorageRequest20initWithAppleRAIDSetEP12AppleRAIDSetE19kalloc_type_view_96
+ __ZZN23AppleRAIDStorageRequest20initWithAppleRAIDSetEP12AppleRAIDSetE19kalloc_type_view_99
- __ZN12AppleRAIDSet20releaseActiveMembersEPP15AppleRAIDMemberj
- __ZZN12AppleRAIDSet9resizeSetEjE20kalloc_type_view_494
- __ZZN12AppleRAIDSet9resizeSetEjE20kalloc_type_view_514
- __ZZN23AppleRAIDStorageRequest20initWithAppleRAIDSetEP12AppleRAIDSetE19kalloc_type_view_95
- __ZZN23AppleRAIDStorageRequest20initWithAppleRAIDSetEP12AppleRAIDSetE19kalloc_type_view_98
CStrings:
+ "AppleRAID::newMember refusing quarantined member %s for set \"%s\" (%s): quarantined media may not join a RAID set.\n"
+ "AppleRAIDMember::parseRAIDHeaderV1: member count %u is out of range (1 - %u).\n"
+ "AppleRAIDMember::parseRAIDHeaderV2: member count %u is out of range (1 - %u).\n"
+ "AppleRAIDSet::addMember() member %s has a newer sequenceNumber (%u) but a member count (%d) that does not match the set's (%u), refusing the member.\n"
+ "AppleRAIDSet::reconfigureSet() new member list has %u entries, over the limit of %u.\n"
+ "bs-apple-quarantine-info"
- "AppleRAID-"
```
