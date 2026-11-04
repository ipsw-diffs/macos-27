## com.apple.driver.AppleDPDisplayTCON

> `com.apple.driver.AppleDPDisplayTCON`

```diff

-230.41.1.0.0
-  __TEXT.__cstring: 0x1240
+230.60.4.0.0
+  __TEXT.__cstring: 0x226b
   __TEXT.__const: 0x50
-  __TEXT_EXEC.__text: 0xddd0
-  __TEXT_EXEC.__auth_stubs: 0x220
+  __TEXT_EXEC.__text: 0x10ae0
+  __TEXT_EXEC.__auth_stubs: 0x230
   __DATA.__data: 0xc4
-  __DATA.__common: 0x228
-  __DATA_CONST.__mod_init_func: 0x40
-  __DATA_CONST.__mod_term_func: 0x40
-  __DATA_CONST.__const: 0x8408
-  __DATA_CONST.__kalloc_type: 0x340
-  __DATA_CONST.__auth_got: 0x110
+  __DATA.__common: 0x250
+  __DATA_CONST.__mod_init_func: 0x48
+  __DATA_CONST.__mod_term_func: 0x48
+  __DATA_CONST.__const: 0x8ec0
+  __DATA_CONST.__kalloc_type: 0x380
+  __DATA_CONST.__auth_got: 0x118
   __DATA_CONST.__got: 0x60
-  __DATA_CONST.__auth_ptr: 0x8
-  Functions: 424
-  Symbols:   796
-  CStrings:  166
+  __DATA_CONST.__auth_ptr: 0x10
+  Functions: 489
+  Symbols:   854
+  CStrings:  254
 
Symbols:
+ _OUTLINED_FUNCTION_10
+ _OUTLINED_FUNCTION_11
+ _OUTLINED_FUNCTION_12
+ _OUTLINED_FUNCTION_13
+ _OUTLINED_FUNCTION_14
+ _OUTLINED_FUNCTION_15
+ _OUTLINED_FUNCTION_16
+ _OUTLINED_FUNCTION_7
+ _OUTLINED_FUNCTION_8
+ _OUTLINED_FUNCTION_9
+ __GLOBAL__sub_I_AppleSamsungIxoraTCON.cpp
+ __ZL25AppleSamsungIxoraTCON_ktv
+ __ZN21AppleSamsungIxoraTCON10gMetaClassE
+ __ZN21AppleSamsungIxoraTCON10handleStopEP9IOService
+ __ZN21AppleSamsungIxoraTCON10readMemoryEP18AppleTCONComponentjPhj
+ __ZN21AppleSamsungIxoraTCON10superClassE
+ __ZN21AppleSamsungIxoraTCON11handleStartEP9IOService
+ __ZN21AppleSamsungIxoraTCON11nvmReadDataEjjPh
+ __ZN21AppleSamsungIxoraTCON11writeMemoryEP18AppleTCONComponentjPKhj
+ __ZN21AppleSamsungIxoraTCON12nvmWriteDataEjPKhj
+ __ZN21AppleSamsungIxoraTCON12waitForReadyEPh
+ __ZN21AppleSamsungIxoraTCON13nvmWriteBlockEjPKh
+ __ZN21AppleSamsungIxoraTCON13readPMICChunkEhtPhj
+ __ZN21AppleSamsungIxoraTCON14nvmEraseBlocksEjj
+ __ZN21AppleSamsungIxoraTCON14writePMICChunkEhtPKhj
+ __ZN21AppleSamsungIxoraTCON15resetAndRecoverEv
+ __ZN21AppleSamsungIxoraTCON16_apiErrorStringsE
+ __ZN21AppleSamsungIxoraTCON2rdEjPhj
+ __ZN21AppleSamsungIxoraTCON2wrEjPKhj
+ __ZN21AppleSamsungIxoraTCON7readPLSEtPhj
+ __ZN21AppleSamsungIxoraTCON7sendCmdEhhhhtPh
+ __ZN21AppleSamsungIxoraTCON8readDataEjPh
+ __ZN21AppleSamsungIxoraTCON8readPMICEhtPhj
+ __ZN21AppleSamsungIxoraTCON8setModelEv
+ __ZN21AppleSamsungIxoraTCON8writePLSEtPKhj
+ __ZN21AppleSamsungIxoraTCON8writeRegEhjPKhj
+ __ZN21AppleSamsungIxoraTCON9MetaClassC1Ev
+ __ZN21AppleSamsungIxoraTCON9MetaClassC2Ev
+ __ZN21AppleSamsungIxoraTCON9MetaClassD0Ev
+ __ZN21AppleSamsungIxoraTCON9MetaClassD1Ev
+ __ZN21AppleSamsungIxoraTCON9getStatusEPh
+ __ZN21AppleSamsungIxoraTCON9metaClassE
+ __ZN21AppleSamsungIxoraTCON9writeDataEPKhj
+ __ZN21AppleSamsungIxoraTCON9writePMICEhtPKhj
+ __ZN21AppleSamsungIxoraTCONC1EPK11OSMetaClass
+ __ZN21AppleSamsungIxoraTCONC1Ev
+ __ZN21AppleSamsungIxoraTCONC2EPK11OSMetaClass
+ __ZN21AppleSamsungIxoraTCONC2Ev
+ __ZN21AppleSamsungIxoraTCOND0Ev
+ __ZN21AppleSamsungIxoraTCOND1Ev
+ __ZN21AppleSamsungIxoraTCOND2Ev
+ __ZN21AppleSamsungIxoraTCONdlEPvm
+ __ZN21AppleSamsungIxoraTCONnwEm
+ __ZNK21AppleSamsungIxoraTCON12getMetaClassEv
+ __ZNK21AppleSamsungIxoraTCON9MetaClass5allocEv
+ __ZTV21AppleSamsungIxoraTCON
+ __ZTVN21AppleSamsungIxoraTCON9MetaClassE
+ _clock_interval_to_deadline
CStrings:
+ "%s: Cmd Sent: 0x%02X 0x%02X 0x%02X 0x%02X 0x%04X\n"
+ "%s: Failed to open SPI provider.\n"
+ "%s: NVM_EraseBlocks completed successfully. Final status: 0x%02X\n"
+ "%s: NVM_EraseBlocks failed. Status: 0x%02X, Error: 0x%02X (%s)\n"
+ "%s: NVM_EraseBlocks failed. Status: 0x%02X, Unknown Error: 0x%02X\n"
+ "%s: NVM_EraseBlocks failed. Status: 0x%02X. Could not read error code.\n"
+ "%s: NVM_EraseBlocks: Addr=0x%08X, Count=%u\n"
+ "%s: NVM_ReadData completed with result 0x%x\n"
+ "%s: NVM_ReadData failed. Status: 0x%02X, Error: 0x%02X (%s)\n"
+ "%s: NVM_ReadData failed. Status: 0x%02X, Unknown Error: 0x%02X\n"
+ "%s: NVM_ReadData failed. Status: 0x%02X. Could not read error code.\n"
+ "%s: NVM_ReadData: Addr=0x%08X, Count=%u\n"
+ "%s: NVM_ReadData: sendCmd failed with 0x%x\n"
+ "%s: NVM_WriteData completed with result 0x%x\n"
+ "%s: NVM_WriteData: Addr=0x%08X, Count=%u\n"
+ "%s: Read length (%u) exceeds maximum allowed length (%u)\n"
+ "%s: STATUS after Recovery: 0x%02X\n"
+ "%s: STATUS before Recovery: 0x%02X\n"
+ "%s: STATUS before sendCmd: 0x%02X, resetting buffer before new API\n"
+ "%s: Write command length (%u) exceeds buffer size (%lu)\n"
+ "%s: nvmEraseBlocks address (0x%X) must be 4K-aligned.\n"
+ "%s: nvmEraseBlocks count (%u) must be a non-zero multiple of 4096.\n"
+ "%s: nvmWriteBlock failed. Addr: 0x%08X, Status: 0x%02X, Error: 0x%02X (%s)\n"
+ "%s: nvmWriteBlock failed. Addr: 0x%08X, Status: 0x%02X, Unknown Error: 0x%02X\n"
+ "%s: nvmWriteBlock failed. Addr: 0x%08X, Status: 0x%02X. Could not read error code.\n"
+ "%s: nvmWriteBlock: sendCmd failed for addr 0x%08X with 0x%x\n"
+ "%s: provider is not AppleARMSPIDevice\n"
+ "%s: readData timed out.\n"
+ "%s: readData: Notified TCON at 0x%08X\n"
+ "%s: readData: read %u bytes from 0x%08X\n"
+ "%s: readMemory called for non-SPI component.\n"
+ "%s: readPLS completed with result 0x%x\n"
+ "%s: readPLS failed after sendCmd. Status: 0x%02X, Error: 0x%02X (%s)\n"
+ "%s: readPLS failed after sendCmd. Status: 0x%02X, Unknown Error: 0x%02X\n"
+ "%s: readPLS length (%u) must be between 1 and 1024.\n"
+ "%s: readPLS: Addr=0x%04X, Length=%u\n"
+ "%s: readPLS: sendCmd failed with 0x%x\n"
+ "%s: readPMIC completed with result 0x%x\n"
+ "%s: readPMIC length (%u) must be between 1 and %u.\n"
+ "%s: readPMIC: sub_cmd=0x%02X, Addr=0x%04X, Length=%u\n"
+ "%s: readPMICChunk attempt %d failed. Status: 0x%02X, Error: 0x%02X (%s)\n"
+ "%s: readPMICChunk attempt %d failed. Status: 0x%02X, Unknown Error: 0x%02X\n"
+ "%s: readPMICChunk exhausted %d retries\n"
+ "%s: readPMICChunk: sendCmd failed with 0x%x\n"
+ "%s: resetAndRecover timed out after %llu ms. Last status: 0x%02X\n"
+ "%s: ret: 0x%02X\n"
+ "%s: started\n"
+ "%s: super::handleStart failed\n"
+ "%s: waitForReady timed out. Last status: 0x%02X\n"
+ "%s: writeData timed out. Last status: 0x%02X\n"
+ "%s: writeData: Notified TCON at 0x%08X\n"
+ "%s: writeData: wrote %u bytes to 0x%08X\n"
+ "%s: writeMemory called for non-SPI component.\n"
+ "%s: writePLS completed with result 0x%x\n"
+ "%s: writePLS failed after sendCmd. Status: 0x%02X, Error: 0x%02X (%s)\n"
+ "%s: writePLS failed after sendCmd. Status: 0x%02X, Unknown Error: 0x%02X\n"
+ "%s: writePLS length (%u) must be between 1 and 1024.\n"
+ "%s: writePLS: Addr=0x%04X, Length=%u\n"
+ "%s: writePLS: sendCmd failed with 0x%x\n"
+ "%s: writePMIC completed with result 0x%x\n"
+ "%s: writePMIC length (%u) must be between 1 and %u.\n"
+ "%s: writePMIC: sub_cmd=0x%02X, Addr=0x%04X, Length=%u\n"
+ "%s: writePMICChunk attempt %d failed. Status: 0x%02X, Error: 0x%02X (%s)\n"
+ "%s: writePMICChunk attempt %d failed. Status: 0x%02X, Unknown Error: 0x%02X\n"
+ "%s: writePMICChunk exhausted %d retries\n"
+ "%s: writePMICChunk: sendCmd failed with 0x%x\n"
+ "12111112122212121112222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222"
+ "API_AUTHENTICATION_FAILED"
+ "API_CMD_NOT_SUPPORRTED"
+ "API_DEVICEID_MISMATCH"
+ "API_ILLEGAL_PARAMETERS"
+ "API_NO_ERROR"
+ "API_NVM_ERASE_ERROR"
+ "API_NVM_READ_ERROR"
+ "API_NVM_WRITE_ERROR"
+ "API_READ_ERROR"
+ "API_RESET_BY_HOST"
+ "API_SECURITY_LEVEL_NOT_MET"
+ "API_SHA_ERROR"
+ "API_WRITE_ERROR"
+ "AppleSamsungIxoraTCON"
+ "Error: TCON command timed out after %d ms\n"
+ "OTP_PROGRAM_ERROR"
+ "OTP_READ_ERROR"
+ "RESTORE_CONDITIONS_NOT_MET"
+ "S6TUDP1"
+ "av_log_level"
+ "site.AppleSamsungIxoraTCON"
```
