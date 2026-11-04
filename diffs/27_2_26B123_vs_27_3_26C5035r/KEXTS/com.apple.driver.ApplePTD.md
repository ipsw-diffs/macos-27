## com.apple.driver.ApplePTD

> `com.apple.driver.ApplePTD`

```diff

-50.40.4.0.0
-  __TEXT.__cstring: 0x1d85
+50.60.5.0.0
+  __TEXT.__cstring: 0x20e3
   __TEXT.__const: 0x20
-  __TEXT_EXEC.__text: 0x90a8
+  __TEXT_EXEC.__text: 0xaae8
   __TEXT_EXEC.__auth_stubs: 0x310
   __DATA.__data: 0xc4
   __DATA.__common: 0x120
   __DATA_CONST.__mod_init_func: 0x20
   __DATA_CONST.__mod_term_func: 0x20
-  __DATA_CONST.__const: 0x1cc0
+  __DATA_CONST.__const: 0x1d68
   __DATA_CONST.__kalloc_type: 0x140
   __DATA_CONST.__kalloc_var: 0x1e0
   __DATA_CONST.__auth_got: 0x188
   __DATA_CONST.__got: 0xa0
-  Functions: 276
-  Symbols:   615
-  CStrings:  219
+  Functions: 297
+  Symbols:   634
+  CStrings:  243
 
Symbols:
+ __ZN18ApplePTDUserClient18externalMethodImplEP26ApplePTDUserClientProviderjP25IOExternalMethodArguments
+ __ZN21ApplePTDAccessorLocalC1EP8ApplePTD
+ __ZN21ApplePTDAccessorLocalD0Ev
+ __ZN21ApplePTDAccessorLocalD1Ev
+ __ZN8ApplePTD10ptdDoCmdOpE9ptd_cmd_tP18ptd_gather_request
+ __ZN8ApplePTD10readViaSMCEjhhbPyS0_
+ __ZN8ApplePTD11writeViaSMCEjhhPy
+ __ZN8ApplePTD15ptdDoMultiCmdOpE9ptd_cmd_tP19ptd_data_entry_v1_tj
+ __ZNK21ApplePTDAccessorLocal4readEP19ptd_data_entry_v1_tP18ptd_gather_requestb
+ __ZNK21ApplePTDAccessorLocal5writeEP19ptd_data_entry_v1_tP18ptd_gather_request
+ __ZNK21ApplePTDAccessorLocal9isUpdatedEP19ptd_data_entry_v1_tP18ptd_gather_request
+ __ZNK8ApplePTD13getPTDEntryIdEi
+ __ZNK8ApplePTD16getPTDEntryCountEv
+ __ZTV21ApplePTDAccessorLocal
+ __ZThn160_N8ApplePTD10ptdDoCmdOpE9ptd_cmd_tP18ptd_gather_request
+ __ZThn160_N8ApplePTD10readViaSMCEjhhbPyS0_
+ __ZThn160_N8ApplePTD11writeViaSMCEjhhPy
+ __ZThn160_N8ApplePTD13dumpInterruptEP9IOServicei
+ __ZThn160_N8ApplePTD14causeInterruptEP9IOServicei
+ __ZThn160_N8ApplePTD15enableInterruptEP9IOServicei
+ __ZThn160_N8ApplePTD15ptdDoMultiCmdOpE9ptd_cmd_tP19ptd_data_entry_v1_tj
+ __ZThn160_N8ApplePTD16disableInterruptEP9IOServicei
+ __ZThn160_N8ApplePTDD0Ev
+ __ZThn160_N8ApplePTDD1Ev
+ __ZThn160_NK8ApplePTD13getPTDEntryIdEi
+ __ZThn160_NK8ApplePTD16getPTDEntryCountEv
+ __ZZN8ApplePTD10initVectorEiP17IOInterruptVectorE20kalloc_type_view_548
+ __ZZN8ApplePTD12deleteVectorEiP17IOInterruptVectorE20kalloc_type_view_633
+ __ZZN8ApplePTD16_ptdAllocVectorsEvE20kalloc_type_view_716
+ __ZZN8ApplePTD17registerInterruptEP9IOServiceiPvPFvS2_S2_S2_iES2_E20kalloc_type_view_243
+ __ZZN8ApplePTD19unregisterInterruptEP9IOServiceiE20kalloc_type_view_308
- __ZN24ApplePTDAccessorConcreteC1EP8ApplePTD
- __ZN24ApplePTDAccessorConcreteD0Ev
- __ZN24ApplePTDAccessorConcreteD1Ev
- __ZNK24ApplePTDAccessorConcrete4readEP19ptd_data_entry_v1_tP18ptd_gather_requestb
- __ZNK24ApplePTDAccessorConcrete5writeEP19ptd_data_entry_v1_tP18ptd_gather_request
- __ZNK24ApplePTDAccessorConcrete9isUpdatedEP19ptd_data_entry_v1_tP18ptd_gather_request
- __ZTV24ApplePTDAccessorConcrete
- __ZZN8ApplePTD10initVectorEiP17IOInterruptVectorE20kalloc_type_view_534
- __ZZN8ApplePTD12deleteVectorEiP17IOInterruptVectorE20kalloc_type_view_619
- __ZZN8ApplePTD16_ptdAllocVectorsEvE20kalloc_type_view_688
- __ZZN8ApplePTD17registerInterruptEP9IOServiceiPvPFvS2_S2_S2_iES2_E20kalloc_type_view_229
- __ZZN8ApplePTD19unregisterInterruptEP9IOServiceiE20kalloc_type_view_294
CStrings:
+ "%s: DumpVector src %d (%d)\n"
+ "%s: EnableVector src %d en %d (%d)\n"
+ "%s: TestVector src %d loops %d (%d)\n"
+ "%s: client %p provider %p\n"
+ "%s: client not supported!\n"
+ "%s: cmd %d ptd_id 0x%x (%d)\n"
+ "%s: cmd %d ptd_id 0x%x vers 0x%x (%d)\n"
+ "%s: kApplePTDUserClientMethodGetAllPTD\n"
+ "%s: kApplePTDUserClientMethodLookupPTD\n"
+ "%s: no provider found for client!!!!\n"
+ "%s: pData %p len %u\n"
+ "%s: ptd_id 0x%x offset 0x%x entries 0x%x pData %p len %d\n"
+ "%s: ptd_id 0x%x pData %p len %d\n"
+ "%s: smc interface %p\n"
+ "%s: smc rd ptd_id 0x%x (%d)\n"
+ "%s: smc wr ptd_id 0x%x (%d)\n"
+ "%s: waitForMatchingService timed out for target %d\n"
+ "121111121222121211111111111111112222222211112"
+ "AppleBTM"
+ "AppleCLPC"
+ "ApplePTDAccessorLocal::ApplePTDAccessorLocal(ApplePTD *)"
+ "GetUserClientProvider"
+ "entries == 0 || (msgOut && metaOut)"
+ "entries == 0 || msgIn"
+ "virtual IOReturn ApplePTD::dumpInterrupt(IOService *, int)"
+ "virtual IOReturn ApplePTD::readViaSMC(uint32_t, uint8_t, uint8_t, bool, uint64_t *, uint64_t *)"
+ "virtual IOReturn ApplePTD::writeViaSMC(uint32_t, uint8_t, uint8_t, uint64_t *)"
- "12111112122212121111111111111112222222211112"
- "ApplePTDAccessorConcrete::ApplePTDAccessorConcrete(ApplePTD *)"
- "IOReturn ApplePTD::dumpInterrupt(IOService *, int)"
```
