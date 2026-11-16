## HomeKitMatter

> `/System/Library/PrivateFrameworks/HomeKitMatter.framework/Versions/A/HomeKitMatter`

```diff

-1535.0.0.0.2
-  __TEXT.__text: 0x198ec4
-  __TEXT.__objc_methlist: 0xb03c
+1535.3.8.0.0
+  __TEXT.__text: 0x19cd90
+  __TEXT.__objc_methlist: 0xb1b4
   __TEXT.__const: 0x290
   __TEXT.__dlopen_cstrs: 0x58
-  __TEXT.__gcc_except_tab: 0x3454
-  __TEXT.__cstring: 0x6f70
-  __TEXT.__oslogstring: 0x4e06b
+  __TEXT.__gcc_except_tab: 0x341c
+  __TEXT.__cstring: 0x701b
+  __TEXT.__oslogstring: 0x4f159
   __TEXT.__ustring: 0x68
-  __TEXT.__unwind_info: 0x3f08
+  __TEXT.__unwind_info: 0x3fc8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xc20
+  __DATA_CONST.__const: 0xc70
   __DATA_CONST.__objc_classlist: 0x460
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x138
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x71a0
+  __DATA_CONST.__objc_selrefs: 0x72b0
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x318
-  __DATA_CONST.__objc_arraydata: 0x250
-  __DATA_CONST.__got: 0x9c0
-  __AUTH_CONST.__const: 0x5a70
-  __AUTH_CONST.__cfstring: 0x6f40
-  __AUTH_CONST.__objc_const: 0x10818
-  __AUTH_CONST.__objc_intobj: 0x17a0
-  __AUTH_CONST.__objc_arrayobj: 0x198
+  __DATA_CONST.__objc_arraydata: 0x260
+  __DATA_CONST.__got: 0x9d0
+  __AUTH_CONST.__const: 0x5ba0
+  __AUTH_CONST.__cfstring: 0x7020
+  __AUTH_CONST.__objc_const: 0x10908
+  __AUTH_CONST.__objc_intobj: 0x1878
+  __AUTH_CONST.__objc_arrayobj: 0x1c8
   __AUTH_CONST.__objc_doubleobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x1ea0
-  __DATA.__objc_ivar: 0xbd0
+  __DATA.__objc_ivar: 0xbe4
   __DATA.__data: 0xea0
-  __DATA.__bss: 0x4c8
+  __DATA.__bss: 0x4b8
   __DATA_DIRTY.__objc_data: 0xd20
-  __DATA_DIRTY.__bss: 0xa0
+  __DATA_DIRTY.__bss: 0xb0
   - /System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /System/Library/PrivateFrameworks/UARPKit.framework/Versions/A/UARPKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 4659
-  Symbols:   10444
-  CStrings:  5723
+  Functions: 4721
+  Symbols:   10564
+  CStrings:  5779
 
Symbols:
+ -[HMMTRAccessoryServer _handleAppleLockDoorPositionDetectionEnabledReport:]
+ -[HMMTRAccessoryServer _resumeDayOneFwUpdateIfReadyWithTrigger:]
+ -[HMMTRAccessoryServer dayOneFwUpdateFlagDidClear]
+ -[HMMTRAccessoryServer dayOneResumePending]
+ -[HMMTRAccessoryServer requestDayOneFwUpdateResume]
+ -[HMMTRAccessoryServer setDayOneResumePending:]
+ -[HMMTRAccessoryServerBrowser updateOTAProviderForServer:]
+ -[HMMTRDescriptorClusterManager _isDoorPositionDetectionDisabledForDoorLockAtCHIPEndpoint:device:]
+ -[HMMTRDoorLockClusterAPIRouter appendAliroCredentialsToUsers:flow:completion:]
+ -[HMMTRDoorLockClusterAPIRouter findEvictableEndpointKeyIndexForUserIndex:flow:completion:]
+ -[HMMTRDoorLockClusterAPIRouter getAppleAliroCredentialsWithCredentialType:flow:]
+ -[HMMTRDoorLockClusterAPIRouter getUserWithParams:flow:completion:]
+ -[HMMTRDoorLockClusterAPIRouter sweepAppleAliroCredentialsWithFlow:]
+ -[HMMTRDoorLockClusterAPIRouter walkAppleAliroCredentialsWithCredentialType:flow:visit:]
+ -[HMMTRDoorLockClusterAPIRouter walkAppleAliroCredentialsWithCredentialType:startingAtIndex:flow:visit:]
+ -[HMMTRFirmwareUpdateStatus _dayOneFwUpdateRetryInterval]
+ -[HMMTRFirmwareUpdateStatus _isDayOneFwUpdateFlagSet]
+ -[HMMTRFirmwareUpdateStatus _retryDayOneFwUpdate]
+ -[HMMTRFirmwareUpdateStatus _startDayOneFwUpdateRetryTimer]
+ -[HMMTRFirmwareUpdateStatus _stopDayOneRetryTimer]
+ -[HMMTRFirmwareUpdateStatus _updateIdleResetTimerForDayOneFwUpdate:]
+ -[HMMTRFirmwareUpdateStatus _updateIdleResetTimerWithRegularTimeout]
+ -[HMMTRFirmwareUpdateStatus dayOneFwUpdateFlagDidClear]
+ -[HMMTRFirmwareUpdateStatus dayOneRetryTimer]
+ -[HMMTRFirmwareUpdateStatus setDayOneRetryTimer:]
+ -[HMMTRSyncClusterDoorLock appendAliroCredentialsToUsers:flow:]
+ -[HMMTRSyncClusterDoorLock cacheUserResponse:includesAliroCredentials:]
+ -[HMMTRSyncClusterDoorLock clearEvictableDeviceKeyOfUser:flow:]
+ -[HMMTRSyncClusterDoorLock clearUsers:flow:]
+ -[HMMTRSyncClusterDoorLock ensureAccessoryConnected:countsAsProgress:flow:]
+ -[HMMTRSyncClusterDoorLock ensureAccessoryConnectedForCacheRead:flow:]
+ -[HMMTRSyncClusterDoorLock findHomeUserWithUniqueID:indexStartingAtSlot:assumingTotalNumberOfSlots:availableSlots:usersOfOurFabric:currentFabricIndex:flow:]
+ -[HMMTRSyncClusterDoorLock futureRecordingProgressOfCommand:]
+ -[HMMTRSyncClusterDoorLock knownCurrentFabricIndex]
+ -[HMMTRSyncClusterDoorLock lastOperationProgressUptime]
+ -[HMMTRSyncClusterDoorLock reverifyCachedUser:flow:]
+ -[HMMTRSyncClusterDoorLock setDoorLocked:accessoryUUID:completionHandler:]
+ -[HMMTRSyncClusterDoorLock setKnownCurrentFabricIndex:]
+ -[HMMTRSyncClusterDoorLock setLastOperationProgressUptime:]
+ -[HomeUserSlotResults setUsersOfOurFabric:]
+ -[HomeUserSlotResults usersOfOurFabric]
+ GCC_except_table1001
+ GCC_except_table1033
+ GCC_except_table1037
+ GCC_except_table1039
+ GCC_except_table1041
+ GCC_except_table1043
+ GCC_except_table1047
+ GCC_except_table1050
+ GCC_except_table1113
+ GCC_except_table1119
+ GCC_except_table1121
+ GCC_except_table1246
+ GCC_except_table1314
+ GCC_except_table1360
+ GCC_except_table1368
+ GCC_except_table1421
+ GCC_except_table1429
+ GCC_except_table1466
+ GCC_except_table1504
+ GCC_except_table1531
+ GCC_except_table1730
+ GCC_except_table1773
+ GCC_except_table1929
+ GCC_except_table1931
+ GCC_except_table1956
+ GCC_except_table1957
+ GCC_except_table1958
+ GCC_except_table1961
+ GCC_except_table1964
+ GCC_except_table1966
+ GCC_except_table1967
+ GCC_except_table1968
+ GCC_except_table1969
+ GCC_except_table1970
+ GCC_except_table1984
+ GCC_except_table1996
+ GCC_except_table2005
+ GCC_except_table2012
+ GCC_except_table2014
+ GCC_except_table2016
+ GCC_except_table2017
+ GCC_except_table2019
+ GCC_except_table2088
+ GCC_except_table2094
+ GCC_except_table2182
+ GCC_except_table2300
+ GCC_except_table2333
+ GCC_except_table2344
+ GCC_except_table2346
+ GCC_except_table2402
+ GCC_except_table2450
+ GCC_except_table2475
+ GCC_except_table2547
+ GCC_except_table2846
+ GCC_except_table2848
+ GCC_except_table2850
+ GCC_except_table2854
+ GCC_except_table2915
+ GCC_except_table2948
+ GCC_except_table2997
+ GCC_except_table2999
+ GCC_except_table3030
+ GCC_except_table3031
+ GCC_except_table3032
+ GCC_except_table3054
+ GCC_except_table3055
+ GCC_except_table3056
+ GCC_except_table3057
+ GCC_except_table3058
+ GCC_except_table3059
+ GCC_except_table3060
+ GCC_except_table3061
+ GCC_except_table3071
+ GCC_except_table3073
+ GCC_except_table3121
+ GCC_except_table3127
+ GCC_except_table3142
+ GCC_except_table3145
+ GCC_except_table3149
+ GCC_except_table3164
+ GCC_except_table3171
+ GCC_except_table3173
+ GCC_except_table3203
+ GCC_except_table3212
+ GCC_except_table3217
+ GCC_except_table3229
+ GCC_except_table3286
+ GCC_except_table3703
+ GCC_except_table3728
+ GCC_except_table3729
+ GCC_except_table3730
+ GCC_except_table3734
+ GCC_except_table3740
+ GCC_except_table3743
+ GCC_except_table3759
+ GCC_except_table3774
+ GCC_except_table3843
+ GCC_except_table3844
+ GCC_except_table3877
+ GCC_except_table3886
+ GCC_except_table3890
+ GCC_except_table3924
+ GCC_except_table3928
+ GCC_except_table3936
+ GCC_except_table3958
+ GCC_except_table3962
+ GCC_except_table4005
+ GCC_except_table4007
+ GCC_except_table4009
+ GCC_except_table4030
+ GCC_except_table4032
+ GCC_except_table4053
+ GCC_except_table4136
+ GCC_except_table4183
+ GCC_except_table4228
+ GCC_except_table4232
+ GCC_except_table4247
+ GCC_except_table4248
+ GCC_except_table4249
+ GCC_except_table4255
+ GCC_except_table4262
+ GCC_except_table4267
+ GCC_except_table4304
+ GCC_except_table4326
+ GCC_except_table4372
+ GCC_except_table4378
+ GCC_except_table4381
+ GCC_except_table4468
+ GCC_except_table4526
+ GCC_except_table4529
+ GCC_except_table458
+ GCC_except_table4593
+ GCC_except_table4653
+ GCC_except_table4657
+ GCC_except_table4663
+ GCC_except_table4667
+ GCC_except_table4701
+ GCC_except_table538
+ GCC_except_table576
+ GCC_except_table580
+ GCC_except_table610
+ GCC_except_table616
+ GCC_except_table618
+ GCC_except_table622
+ GCC_except_table791
+ GCC_except_table792
+ GCC_except_table849
+ GCC_except_table850
+ GCC_except_table851
+ GCC_except_table924
+ GCC_except_table966
+ _HMMTRAllSettledFailingOnAnyError
+ _HMMTRCredentialIndexOfType
+ _HMMTRDoorLockDlStatusErrorKey
+ _HMMTRDoorLockErrorForSettledResults
+ _HMMTRDoorLockFailedCommandCountErrorKey
+ _HMMTRDoorLockReadCredentialUserTuplesErrorKey
+ _HMMTRDoorLockTotalCommandCountErrorKey
+ _HMMTRErrorForSetCredentialResponse
+ _HMMTRErrorIsLockNotAnswering
+ _HMMTRQueryImageInitiationTypeIsInternalAvailabilityCheck
+ _OBJC_CLASS_$_NAScheduler
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_IVAR_$_HMMTRAccessoryServer._dayOneResumePending
+ _OBJC_IVAR_$_HMMTRFirmwareUpdateStatus._dayOneRetryTimer
+ _OBJC_IVAR_$_HMMTRSyncClusterDoorLock._knownCurrentFabricIndex
+ _OBJC_IVAR_$_HMMTRSyncClusterDoorLock._lastOperationProgressUptime
+ _OBJC_IVAR_$_HomeUserSlotResults._usersOfOurFabric
+ ___104-[HMMTRDoorLockClusterAPIRouter walkAppleAliroCredentialsWithCredentialType:startingAtIndex:flow:visit:]_block_invoke
+ ___121-[HMMTRSyncClusterDoorLock findAllUsersWithCreatorFabricIndex:indexStartingAtSlot:assumingTotalNumberOfSlots:users:flow:]_block_invoke
+ ___125-[HMMTRSyncClusterDoorLock findOrAddUserWithUniqueID:withWeekDaySchedules:andYearDaySchedules:requireFullScheduleAudit:flow:]_block_invoke_2
+ ___156-[HMMTRSyncClusterDoorLock findHomeUserWithUniqueID:indexStartingAtSlot:assumingTotalNumberOfSlots:availableSlots:usersOfOurFabric:currentFabricIndex:flow:]_block_invoke
+ ___39-[HMMTRSyncClusterDoorLock getAllUsers]_block_invoke_2
+ ___40-[HMMTRAccessoryServer setChipDelegate:]_block_invoke
+ ___44-[HMMTRSyncClusterDoorLock clearUsers:flow:]_block_invoke
+ ___47-[HMMTRAnnounceOtaSchedulerTimer timerDidFire:]_block_invoke
+ ___49-[HMMTRFirmwareUpdateStatus _retryDayOneFwUpdate]_block_invoke
+ ___49-[HMMTRFirmwareUpdateStatus _retryDayOneFwUpdate]_block_invoke_2
+ ___49-[HMMTRSyncClusterDoorLock _getUserAtIndex:flow:]_block_invoke
+ ___49-[HMMTRSyncClusterDoorLock _getUserAtIndex:flow:]_block_invoke_2
+ ___51-[HMMTRAccessoryServer requestDayOneFwUpdateResume]_block_invoke
+ ___52-[HMMTRSyncClusterDoorLock reverifyCachedUser:flow:]_block_invoke
+ ___55-[HMMTRFirmwareUpdateStatus dayOneFwUpdateFlagDidClear]_block_invoke
+ ___55-[HMMTRSyncClusterDoorLock getUsersWithUniqueIDs:flow:]_block_invoke_6
+ ___57-[HMMTRSyncClusterDoorLock fetchCurrentFabricIndex_flow:]_block_invoke_3
+ ___58-[HMMTRAccessoryServerBrowser updateOTAProviderForServer:]_block_invoke
+ ___61-[HMMTRSyncClusterDoorLock futureRecordingProgressOfCommand:]_block_invoke
+ ___63-[HMMTRSyncClusterDoorLock appendAliroCredentialsToUsers:flow:]_block_invoke
+ ___63-[HMMTRSyncClusterDoorLock appendAliroCredentialsToUsers:flow:]_block_invoke_2
+ ___63-[HMMTRSyncClusterDoorLock clearEvictableDeviceKeyOfUser:flow:]_block_invoke
+ ___63-[HMMTRSyncClusterDoorLock clearEvictableDeviceKeyOfUser:flow:]_block_invoke_2
+ ___67-[HMMTRDoorLockClusterAPIRouter getUserWithParams:flow:completion:]_block_invoke
+ ___68-[HMMTRDoorLockClusterAPIRouter sweepAppleAliroCredentialsWithFlow:]_block_invoke
+ ___68-[HMMTRFirmwareUpdateStatus _updateIdleResetTimerForDayOneFwUpdate:]_block_invoke
+ ___68-[HMMTRFirmwareUpdateStatus _updateIdleResetTimerWithRegularTimeout]_block_invoke
+ ___68-[HMMTRSyncClusterDoorLock findOrAddUserWithUniqueID:userType:flow:]_block_invoke_2
+ ___74-[HMMTRSyncClusterDoorLock setDoorLocked:accessoryUUID:completionHandler:]_block_invoke
+ ___74-[HMMTRSyncClusterDoorLock setDoorLocked:accessoryUUID:completionHandler:]_block_invoke_2
+ ___75-[HMMTRAccessoryServer _handleAppleLockDoorPositionDetectionEnabledReport:]_block_invoke
+ ___75-[HMMTRSyncClusterDoorLock ensureAccessoryConnected:countsAsProgress:flow:]_block_invoke
+ ___75-[HMMTRSyncClusterDoorLock ensureAccessoryConnected:countsAsProgress:flow:]_block_invoke_2
+ ___79-[HMMTRDoorLockClusterAPIRouter appendAliroCredentialsToUsers:flow:completion:]_block_invoke
+ ___79-[HMMTRDoorLockClusterAPIRouter appendAliroCredentialsToUsers:flow:completion:]_block_invoke_2
+ ___81-[HMMTRDoorLockClusterAPIRouter getAppleAliroCredentialsWithCredentialType:flow:]_block_invoke
+ ___90-[HMMTRSyncClusterDoorLock addOrUpdateIssuerKeyData:forUserUniqueID:isUnifiedAccess:flow:]_block_invoke_2
+ ___90-[HMMTRSyncClusterDoorLock addOrUpdateIssuerKeyData:forUserUniqueID:isUnifiedAccess:flow:]_block_invoke_3
+ ___91-[HMMTRDoorLockClusterAPIRouter findEvictableEndpointKeyIndexForUserIndex:flow:completion:]_block_invoke
+ ___92-[HMMTRSyncClusterDoorLock getAllUsersStartingAtSlot:assumingTotalNumberOfSlots:users:flow:]_block_invoke
+ ___98-[HMMTRDescriptorClusterManager _isDoorPositionDetectionDisabledForDoorLockAtCHIPEndpoint:device:]_block_invoke
+ ___HMMTRAllSettledFailingOnAnyError_block_invoke
+ ___HMMTRCredentialIndexOfType_block_invoke
+ ___HMMTRDoorLockErrorForSettledResults_block_invoke
+ ___block_descriptor_32_e27_"NAFuture"16?0"NSArray"8l
+ ___block_descriptor_32_e49_B16?0"MTRDoorLockClusterGetUserResponseParams"8l
+ ___block_descriptor_40_e8_32bs_e45_{_HMFFutureBlockOutcome=q}16?0"HMFFuture"8l
+ ___block_descriptor_40_e8_32bs_e75_{_HMFFutureBlockOutcome=q}16?0"MTRDoorLockClusterGetUserResponseParams"8l
+ ___block_descriptor_40_e8_32s_e18_"NAFuture"16?08l
+ ___block_descriptor_40_e8_32s_e22_B16?0"NSDictionary"8l
+ ___block_descriptor_48_e8_32bs40r_e8_v16?08l
+ ___block_descriptor_48_e8_32s40bs_e16_"HMFFuture"8?0l
+ ___block_descriptor_48_e8_32s40r_e64_B24?0q8"MTRDoorLockClusterGetCredentialStatusResponseParams"16l
+ ___block_descriptor_48_e8_32s40s_e68_v24?0"HMMTRSoftwareUpdateProviderQueryResponseParams"8"NSError"16l
+ ___block_descriptor_48_e8_32s_e64_B24?0q8"MTRDoorLockClusterGetCredentialStatusResponseParams"16l
+ ___block_descriptor_49_e8_32s40s_e44_{_HMFFutureBlockOutcome=q}16?0"NSString"8l
+ ___block_descriptor_56_e8_32s40s48s_e75_{_HMFFutureBlockOutcome=q}16?0"MTRDoorLockClusterGetUserResponseParams"8l
+ ___block_descriptor_57_e8_32s40s48s_e16_"HMFFuture"8?0l
+ ___block_descriptor_57_e8_32s40s48s_e44_{_HMFFutureBlockOutcome=q}16?0"NSNumber"8l
+ ___block_descriptor_64_e8_32s40s48s56bs_e22_v16?0"NSDictionary"8l
+ ___block_descriptor_64_e8_32s40s48s56bs_e43_{_HMFFutureBlockOutcome=q}16?0"NSError"8l
+ ___block_descriptor_65_e8_32s40s48s56s_e34_{_HMFFutureBlockOutcome=q}16?08l
+ ___block_descriptor_72_e8_32s40s48bs_e71_"NAFuture"16?0"MTRDoorLockClusterGetCredentialStatusResponseParams"8l
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e20_v20?0B8"NSError"12l
+ ___block_descriptor_72_e8_32s40s48s56s_e50_{_HMFFutureBlockOutcome=q}16?0"<HMFAlwaysNil>"8l
+ ___block_descriptor_72_e8_32s40s48s_e87_{_HMFFutureBlockOutcome=q}16?0"MTRDoorLockClusterGetCredentialStatusResponseParams"8l
+ ___block_descriptor_80_e8_32s40s48s56s64s72s_e44_{_HMFFutureBlockOutcome=q}16?0"NSNumber"8l
+ ___block_descriptor_80_e8_32s40s48s56s64s_e43_{_HMFFutureBlockOutcome=q}16?0"NSError"8l
+ ___block_descriptor_80_e8_32s40s48s56s_e75_{_HMFFutureBlockOutcome=q}16?0"MTRDoorLockClusterGetUserResponseParams"8l
+ ___block_descriptor_89_e8_32s40s48s56s64s72s80s_e75_{_HMFFutureBlockOutcome=q}16?0"MTRDoorLockClusterGetUserResponseParams"8l
+ _logCategory._hmf_once_t1317
+ _logCategory._hmf_once_t14
+ _logCategory._hmf_once_t357
+ _logCategory._hmf_once_t471
+ _logCategory._hmf_once_t67
+ _logCategory._hmf_once_t771
+ _logCategory._hmf_once_v1318
+ _logCategory._hmf_once_v15
+ _logCategory._hmf_once_v358
+ _logCategory._hmf_once_v472
+ _logCategory._hmf_once_v68
+ _logCategory._hmf_once_v772
+ _objc_msgSend$_dayOneFwUpdateRetryInterval
+ _objc_msgSend$_handleAppleLockDoorPositionDetectionEnabledReport:
+ _objc_msgSend$_isDayOneFwUpdateFlagSet
+ _objc_msgSend$_isDoorPositionDetectionDisabledForDoorLockAtCHIPEndpoint:device:
+ _objc_msgSend$_resumeDayOneFwUpdateIfReadyWithTrigger:
+ _objc_msgSend$_retryDayOneFwUpdate
+ _objc_msgSend$_startDayOneFwUpdateRetryTimer
+ _objc_msgSend$_stopDayOneRetryTimer
+ _objc_msgSend$_updateIdleResetTimerForDayOneFwUpdate:
+ _objc_msgSend$_updateIdleResetTimerWithRegularTimeout
+ _objc_msgSend$appendAliroCredentialsToUsers:flow:
+ _objc_msgSend$appendAliroCredentialsToUsers:flow:completion:
+ _objc_msgSend$cacheUserResponse:includesAliroCredentials:
+ _objc_msgSend$clearEvictableDeviceKeyOfUser:flow:
+ _objc_msgSend$clearUsers:flow:
+ _objc_msgSend$combineAllFutures:ignoringErrors:scheduler:
+ _objc_msgSend$dayOneFwUpdateFlagDidClear
+ _objc_msgSend$dayOneResumePending
+ _objc_msgSend$dayOneRetryTimer
+ _objc_msgSend$ensureAccessoryConnected:countsAsProgress:flow:
+ _objc_msgSend$ensureAccessoryConnectedForCacheRead:flow:
+ _objc_msgSend$findEvictableEndpointKeyIndexForUserIndex:flow:completion:
+ _objc_msgSend$findHomeUserWithUniqueID:indexStartingAtSlot:assumingTotalNumberOfSlots:availableSlots:usersOfOurFabric:currentFabricIndex:flow:
+ _objc_msgSend$futureRecordingProgressOfCommand:
+ _objc_msgSend$futureWithNoResult
+ _objc_msgSend$getAppleAliroCredentialsWithCredentialType:flow:
+ _objc_msgSend$getUserWithParams:flow:completion:
+ _objc_msgSend$idleResetTimerQueue
+ _objc_msgSend$initWithServer:nodeId:queue:
+ _objc_msgSend$knownCurrentFabricIndex
+ _objc_msgSend$processInfo
+ _objc_msgSend$readAttributePaths:
+ _objc_msgSend$requestDayOneFwUpdateResume
+ _objc_msgSend$reverifyCachedUser:flow:
+ _objc_msgSend$schedulerWithDispatchQueue:
+ _objc_msgSend$setDayOneResumePending:
+ _objc_msgSend$setDayOneRetryTimer:
+ _objc_msgSend$setDoorLocked:accessoryUUID:completionHandler:
+ _objc_msgSend$setKnownCurrentFabricIndex:
+ _objc_msgSend$setLastOperationProgressUptime:
+ _objc_msgSend$setUsersOfOurFabric:
+ _objc_msgSend$sweepAppleAliroCredentialsWithFlow:
+ _objc_msgSend$systemUptime
+ _objc_msgSend$updateOTAProviderForServer:
+ _objc_msgSend$usersOfOurFabric
+ _objc_msgSend$walkAppleAliroCredentialsWithCredentialType:flow:visit:
+ _objc_msgSend$walkAppleAliroCredentialsWithCredentialType:startingAtIndex:flow:visit:
- -[HMMTRDoorLockClusterAPIRouter getAppleAliroCredentialsWithCredentialType:startingAtIndex:credentials:flow:]
- -[HMMTRDoorLockClusterAPIRouter getUserWithParams:includeAliroCredentials:temporaryCachedAliroCredentials:flow:completion:]
- -[HMMTRSyncClusterDoorLock __getUserAtIndex:includeAliroCredentials:temporaryCachedAliroCredentials:flow:]
- -[HMMTRSyncClusterDoorLock findAllUsersWithCreatorFabricIndex:indexStartingAtSlot:assumingTotalNumberOfSlots:users:temporaryCachedAliroCredentials:flow:]
- -[HMMTRSyncClusterDoorLock findHomeUserWithUniqueID:indexStartingAtSlot:assumingTotalNumberOfSlots:availableSlots:currentFabricIndex:flow:]
- -[HMMTRSyncClusterDoorLock findHomeUserWithUniqueID:indexStartingAtSlot:assumingTotalNumberOfSlots:availableSlots:currentFabricIndex:temporaryCachedAliroCredentials:flow:]
- -[HMMTRSyncClusterDoorLock getAllUsersStartingAtSlot:assumingTotalNumberOfSlots:users:temporaryCachedAliroCredentials:flow:]
- -[HMMTRSyncClusterDoorLock issuerCredentialForUser:flow:]
- -[HMMTRSyncClusterDoorLock pinCredentialForUser:flow:]
- -[HMMTRSyncClusterDoorLock rfidCredentialForUser:flow:]
- GCC_except_table1004
- GCC_except_table1008
- GCC_except_table1010
- GCC_except_table1012
- GCC_except_table1014
- GCC_except_table1018
- GCC_except_table1021
- GCC_except_table1084
- GCC_except_table1090
- GCC_except_table1092
- GCC_except_table1215
- GCC_except_table1283
- GCC_except_table1329
- GCC_except_table1337
- GCC_except_table1390
- GCC_except_table1398
- GCC_except_table1435
- GCC_except_table1473
- GCC_except_table1500
- GCC_except_table1699
- GCC_except_table1742
- GCC_except_table1898
- GCC_except_table1899
- GCC_except_table1900
- GCC_except_table1903
- GCC_except_table1923
- GCC_except_table1924
- GCC_except_table1925
- GCC_except_table1926
- GCC_except_table1927
- GCC_except_table1933
- GCC_except_table1935
- GCC_except_table1936
- GCC_except_table1937
- GCC_except_table1938
- GCC_except_table1939
- GCC_except_table1950
- GCC_except_table1953
- GCC_except_table1974
- GCC_except_table1983
- GCC_except_table1988
- GCC_except_table2057
- GCC_except_table2063
- GCC_except_table2151
- GCC_except_table2269
- GCC_except_table2271
- GCC_except_table2313
- GCC_except_table2315
- GCC_except_table2371
- GCC_except_table2417
- GCC_except_table2442
- GCC_except_table2514
- GCC_except_table2812
- GCC_except_table2814
- GCC_except_table2816
- GCC_except_table2820
- GCC_except_table2881
- GCC_except_table2914
- GCC_except_table2961
- GCC_except_table2963
- GCC_except_table2994
- GCC_except_table2995
- GCC_except_table2996
- GCC_except_table3018
- GCC_except_table3019
- GCC_except_table3020
- GCC_except_table3021
- GCC_except_table3022
- GCC_except_table3023
- GCC_except_table3024
- GCC_except_table3025
- GCC_except_table3035
- GCC_except_table3037
- GCC_except_table3049
- GCC_except_table3070
- GCC_except_table3091
- GCC_except_table3109
- GCC_except_table3113
- GCC_except_table3128
- GCC_except_table3131
- GCC_except_table3135
- GCC_except_table3137
- GCC_except_table3176
- GCC_except_table3181
- GCC_except_table3193
- GCC_except_table3247
- GCC_except_table3248
- GCC_except_table3649
- GCC_except_table3674
- GCC_except_table3675
- GCC_except_table3676
- GCC_except_table3680
- GCC_except_table3686
- GCC_except_table3689
- GCC_except_table3705
- GCC_except_table3720
- GCC_except_table3789
- GCC_except_table3790
- GCC_except_table3823
- GCC_except_table3832
- GCC_except_table3836
- GCC_except_table3870
- GCC_except_table3874
- GCC_except_table3882
- GCC_except_table3904
- GCC_except_table3908
- GCC_except_table3951
- GCC_except_table3953
- GCC_except_table3955
- GCC_except_table3976
- GCC_except_table3978
- GCC_except_table3999
- GCC_except_table4076
- GCC_except_table4123
- GCC_except_table4143
- GCC_except_table4166
- GCC_except_table4170
- GCC_except_table4185
- GCC_except_table4186
- GCC_except_table4187
- GCC_except_table4193
- GCC_except_table4200
- GCC_except_table4242
- GCC_except_table4264
- GCC_except_table4310
- GCC_except_table4316
- GCC_except_table4319
- GCC_except_table4405
- GCC_except_table4406
- GCC_except_table443
- GCC_except_table4464
- GCC_except_table4531
- GCC_except_table4591
- GCC_except_table4595
- GCC_except_table4601
- GCC_except_table4605
- GCC_except_table4639
- GCC_except_table524
- GCC_except_table562
- GCC_except_table566
- GCC_except_table596
- GCC_except_table602
- GCC_except_table604
- GCC_except_table608
- GCC_except_table777
- GCC_except_table778
- GCC_except_table835
- GCC_except_table836
- GCC_except_table837
- GCC_except_table910
- GCC_except_table952
- ___106-[HMMTRSyncClusterDoorLock __getUserAtIndex:includeAliroCredentials:temporaryCachedAliroCredentials:flow:]_block_invoke
- ___106-[HMMTRSyncClusterDoorLock __getUserAtIndex:includeAliroCredentials:temporaryCachedAliroCredentials:flow:]_block_invoke_2
- ___109-[HMMTRDoorLockClusterAPIRouter getAppleAliroCredentialsWithCredentialType:startingAtIndex:credentials:flow:]_block_invoke
- ___123-[HMMTRDoorLockClusterAPIRouter getUserWithParams:includeAliroCredentials:temporaryCachedAliroCredentials:flow:completion:]_block_invoke
- ___124-[HMMTRSyncClusterDoorLock getAllUsersStartingAtSlot:assumingTotalNumberOfSlots:users:temporaryCachedAliroCredentials:flow:]_block_invoke
- ___153-[HMMTRSyncClusterDoorLock findAllUsersWithCreatorFabricIndex:indexStartingAtSlot:assumingTotalNumberOfSlots:users:temporaryCachedAliroCredentials:flow:]_block_invoke
- ___171-[HMMTRSyncClusterDoorLock findHomeUserWithUniqueID:indexStartingAtSlot:assumingTotalNumberOfSlots:availableSlots:currentFabricIndex:temporaryCachedAliroCredentials:flow:]_block_invoke
- ___42-[HMMTRSyncClusterDoorLock removeAllUsers]_block_invoke_3
- ___54-[HMMTRSyncClusterDoorLock pinCredentialForUser:flow:]_block_invoke
- ___55-[HMMTRSyncClusterDoorLock rfidCredentialForUser:flow:]_block_invoke
- ___57-[HMMTRSyncClusterDoorLock issuerCredentialForUser:flow:]_block_invoke
- ___58-[HMMTRSyncClusterDoorLock ensureAccessoryConnected:flow:]_block_invoke
- ___58-[HMMTRSyncClusterDoorLock ensureAccessoryConnected:flow:]_block_invoke_2
- ___72-[HMMTRSyncClusterDoorLock lockDoorWithAccessoryUUID:completionHandler:]_block_invoke
- ___72-[HMMTRSyncClusterDoorLock lockDoorWithAccessoryUUID:completionHandler:]_block_invoke_2
- ___74-[HMMTRSyncClusterDoorLock unlockDoorWithAccessoryUUID:completionHandler:]_block_invoke
- ___block_descriptor_32_e51_B32?0"MTRDoorLockClusterCredentialStruct"8Q16^B24l
- ___block_descriptor_40_e8_32s_e49_16?0"MTRDoorLockClusterGetUserResponseParams"8l
- ___block_descriptor_48_e8_32s40s_e60_"HMFFuture"16?0"MTRDoorLockClusterGetUserResponseParams"8l
- ___block_descriptor_56_e8_32s40s48bs_e36_v24?0"<HMFAlwaysNil>"8"NSError"16l
- ___block_descriptor_56_e8_32s40s48bs_e43_{_HMFFutureBlockOutcome=q}16?0"NSError"8l
- ___block_descriptor_56_e8_32s40s48bs_e44_{_HMFFutureBlockOutcome=q}16?0"NSString"8l
- ___block_descriptor_56_e8_32s40s48s_e45_{_HMFFutureBlockOutcome=q}16?0"HMFFuture"8l
- ___block_descriptor_64_e8_32s40s48s56bs_e44_{_HMFFutureBlockOutcome=q}16?0"NSNumber"8l
- ___block_descriptor_64_e8_32s40s48s_e87_{_HMFFutureBlockOutcome=q}16?0"MTRDoorLockClusterGetCredentialStatusResponseParams"8l
- ___block_descriptor_65_e8_32s40s48s_e16_"HMFFuture"8?0l
- ___block_descriptor_66_e8_32s40s48s56bs_e61_v24?0"MTRDoorLockClusterGetUserResponseParams"8"NSError"16l
- ___block_descriptor_72_e8_32s40s48s56s64s_e75_{_HMFFutureBlockOutcome=q}16?0"MTRDoorLockClusterGetUserResponseParams"8l
- ___block_descriptor_72_e8_32s40s48s_e71_"NAFuture"16?0"MTRDoorLockClusterGetCredentialStatusResponseParams"8l
- ___block_descriptor_73_e8_32s40s48s56s64bs_e20_v20?0B8"NSError"12l
- ___block_descriptor_73_e8_32s40s48s56s64s_e75_{_HMFFutureBlockOutcome=q}16?0"MTRDoorLockClusterGetUserResponseParams"8l
- ___block_descriptor_88_e8_32s40s48s56s64s_e75_{_HMFFutureBlockOutcome=q}16?0"MTRDoorLockClusterGetUserResponseParams"8l
- _logCategory._hmf_once_t1304
- _logCategory._hmf_once_t346
- _logCategory._hmf_once_t49
- _logCategory._hmf_once_t492
- _logCategory._hmf_once_t66
- _logCategory._hmf_once_t761
- _logCategory._hmf_once_v1305
- _logCategory._hmf_once_v347
- _logCategory._hmf_once_v493
- _logCategory._hmf_once_v50
- _logCategory._hmf_once_v67
- _logCategory._hmf_once_v762
- _objc_msgSend$__getUserAtIndex:includeAliroCredentials:temporaryCachedAliroCredentials:flow:
- _objc_msgSend$all:
- _objc_msgSend$combineAllFutures:
- _objc_msgSend$findAllUsersWithCreatorFabricIndex:indexStartingAtSlot:assumingTotalNumberOfSlots:users:temporaryCachedAliroCredentials:flow:
- _objc_msgSend$findHomeUserWithUniqueID:indexStartingAtSlot:assumingTotalNumberOfSlots:availableSlots:currentFabricIndex:flow:
- _objc_msgSend$findHomeUserWithUniqueID:indexStartingAtSlot:assumingTotalNumberOfSlots:availableSlots:currentFabricIndex:temporaryCachedAliroCredentials:flow:
- _objc_msgSend$getAllUsersStartingAtSlot:assumingTotalNumberOfSlots:users:temporaryCachedAliroCredentials:flow:
- _objc_msgSend$getAppleAliroCredentialsWithCredentialType:startingAtIndex:credentials:flow:
- _objc_msgSend$getUserWithParams:includeAliroCredentials:temporaryCachedAliroCredentials:flow:completion:
- _objc_msgSend$pinCredentialForUser:flow:
- _objc_msgSend$rfidCredentialForUser:flow:
- _objc_sync_enter
- _objc_sync_exit
CStrings:
+ "%lu of %lu commands failed. First error: %{public}@ %ld"
+ "@\"NAFuture\"16@?0@\"NSArray\"8"
+ "@\"NAFuture\"16@?0@8"
+ "A"
+ "Accessory server is no longer available, skipping OTA provider announcement"
+ "Apple Lock DoorPositionDetectionEnabled changed to %{public}@ on endpoint %{public}@, re-enumerating services"
+ "Apple Lock DoorPositionDetectionEnabled is false for characteristic %@ at endpoint %@ of node %@"
+ "B16@?0@\"NSDictionary\"8"
+ "B24@?0q8@\"MTRDoorLockClusterGetCredentialStatusResponseParams\"16"
+ "Cannot get the status of the software update, announcing OTA provider anyway: %{public}@ (%ld)"
+ "Current device cannot be an OTA provider for node %{public}@ (fabric found: %{public}@)"
+ "Day 1 firmware update flag cleared for accessory server [%{public}@]"
+ "Day 1 firmware update is in progress (%@), postponing the retry for accessory server [%{public}@]"
+ "Day 1 firmware update not resumed, not allowed on this device for node %@ (trigger: %{public}@)"
+ "Day 1 firmware update resume is waiting for the chip delegate for node %@"
+ "Day 1 firmware update resume requested after service enumeration for node %@ (chip delegate attached: %{public}@, OTA state: %{public}@, announce timer set: %{public}@)"
+ "Day 1 firmware update retry skipped, accessory server [%{public}@] is unreachable"
+ "Day 1 firmware update retry skipped, cannot get the status of the update for accessory server [%{public}@], error %{public}@ %ld"
+ "Day 1 firmware update retry skipped, no update available for accessory server [%{public}@]"
+ "DayOneRetryTimer"
+ "Enumeration per Apple Lock DoorPositionDetectionEnabled change complete with error domain: %{public}@ code: %ld"
+ "HMMTRDoorLockDlStatus"
+ "HMMTRDoorLockFailedCommandCount"
+ "HMMTRDoorLockReadCredentialUserTuples"
+ "HMMTRDoorLockTotalCommandCount"
+ "InternalDayOneRetry"
+ "Locking"
+ "OTA announce timer is already set, not updating the OTA provider for node %@"
+ "Resuming the Day 1 firmware update with the OTA announce timer for node %@ (trigger: %{public}@)"
+ "Retrying the Day 1 firmware update for accessory server [%{public}@]"
+ "Server is not enabled. Not updating default OTA provider"
+ "Starting Day 1 firmware update retry timer with delay of %f seconds for accessory server [%{public}@]"
+ "Stop idle reset timer for accessory server [%{public}@]"
+ "The software update is not available, no need to announce OTA provider"
+ "Unlocking"
+ "Update default OTA provider completed for server:%@ with Error: %@."
+ "Update default OTA provider completed for server:%@."
+ "Using DoorPositionDetectionEnabled from endpoint %@ for the DoorLock at endpoint %@ of node %@"
+ "[%{public}@] %lu of %lu commands failed. First error: %{public}@ %ld"
+ "[%{public}@] Accessory server is no longer available, skipping OTA provider announcement"
+ "[%{public}@] Apple Lock DoorPositionDetectionEnabled changed to %{public}@ on endpoint %{public}@, re-enumerating services"
+ "[%{public}@] Apple Lock DoorPositionDetectionEnabled is false for characteristic %@ at endpoint %@ of node %@"
+ "[%{public}@] Cannot get the status of the software update, announcing OTA provider anyway: %{public}@ (%ld)"
+ "[%{public}@] Current device cannot be an OTA provider for node %{public}@ (fabric found: %{public}@)"
+ "[%{public}@] Day 1 firmware update flag cleared for accessory server [%{public}@]"
+ "[%{public}@] Day 1 firmware update is in progress (%@), postponing the retry for accessory server [%{public}@]"
+ "[%{public}@] Day 1 firmware update not resumed, not allowed on this device for node %@ (trigger: %{public}@)"
+ "[%{public}@] Day 1 firmware update resume is waiting for the chip delegate for node %@"
+ "[%{public}@] Day 1 firmware update resume requested after service enumeration for node %@ (chip delegate attached: %{public}@, OTA state: %{public}@, announce timer set: %{public}@)"
+ "[%{public}@] Day 1 firmware update retry skipped, accessory server [%{public}@] is unreachable"
+ "[%{public}@] Day 1 firmware update retry skipped, cannot get the status of the update for accessory server [%{public}@], error %{public}@ %ld"
+ "[%{public}@] Day 1 firmware update retry skipped, no update available for accessory server [%{public}@]"
+ "[%{public}@] Enumeration per Apple Lock DoorPositionDetectionEnabled change complete with error domain: %{public}@ code: %ld"
+ "[%{public}@] OTA announce timer is already set, not updating the OTA provider for node %@"
+ "[%{public}@] Resuming the Day 1 firmware update with the OTA announce timer for node %@ (trigger: %{public}@)"
+ "[%{public}@] Retrying the Day 1 firmware update for accessory server [%{public}@]"
+ "[%{public}@] Server is not enabled. Not updating default OTA provider"
+ "[%{public}@] Starting Day 1 firmware update retry timer with delay of %f seconds for accessory server [%{public}@]"
+ "[%{public}@] Stop idle reset timer for accessory server [%{public}@]"
+ "[%{public}@] The software update is not available, no need to announce OTA provider"
+ "[%{public}@] Update default OTA provider completed for server:%@ with Error: %@."
+ "[%{public}@] Update default OTA provider completed for server:%@."
+ "[%{public}@] Using DoorPositionDetectionEnabled from endpoint %@ for the DoorLock at endpoint %@ of node %@"
+ "[%{public}@] [Flow: %@] Cached user for uniqueID %@ at index %@ is stale on the lock"
+ "[%{public}@] [Flow: %@] Cached user has no issuer key index, reading userIndex: %ld with its credentials"
+ "[%{public}@] [Flow: %@] Calling completion with error: %{public}@ %ld"
+ "[%{public}@] [Flow: %@] Clearing %lu abandoned users that belong to deleted fabrics"
+ "[%{public}@] [Flow: %@] Couldn't read the user of %@ of %lu PINs, first error: %{public}@ %ld"
+ "[%{public}@] [Flow: %@] Dropping credential whose user slot is marked Available. Credential: %@"
+ "[%{public}@] [Flow: %@] Failed to clear credential with error: %{public}@ %ld"
+ "[%{public}@] [Flow: %@] Failed to clear every abandoned user, continuing: %{public}@ %ld"
+ "[%{public}@] [Flow: %@] Failed to read user %@ of a PIN credential, error: %{public}@ %ld"
+ "[%{public}@] [Flow: %@] Failed to verify cached user for userUniqueID %{public}@, walking the lock: %{public}@ %ld"
+ "[%{public}@] [Flow: %@] Found cached user for userUniqueID %@ at index %@, verifying"
+ "[%{public}@] [Flow: %@] Lock reports user %ld has no room for a PIN"
+ "[%{public}@] [NewFlow: %@ {\"Feature\":\"Lock ReadWrite\"}] %s door with accessoryUUID: %@"
+ "[Flow: %@] Cached user for uniqueID %@ at index %@ is stale on the lock"
+ "[Flow: %@] Cached user has no issuer key index, reading userIndex: %ld with its credentials"
+ "[Flow: %@] Calling completion with error: %{public}@ %ld"
+ "[Flow: %@] Clearing %lu abandoned users that belong to deleted fabrics"
+ "[Flow: %@] Couldn't read the user of %@ of %lu PINs, first error: %{public}@ %ld"
+ "[Flow: %@] Dropping credential whose user slot is marked Available. Credential: %@"
+ "[Flow: %@] Failed to clear credential with error: %{public}@ %ld"
+ "[Flow: %@] Failed to clear every abandoned user, continuing: %{public}@ %ld"
+ "[Flow: %@] Failed to read user %@ of a PIN credential, error: %{public}@ %ld"
+ "[Flow: %@] Failed to verify cached user for userUniqueID %{public}@, walking the lock: %{public}@ %ld"
+ "[Flow: %@] Found cached user for userUniqueID %@ at index %@, verifying"
+ "[Flow: %@] Lock reports user %ld has no room for a PIN"
+ "[NewFlow: %@ {\"Feature\":\"Lock ReadWrite\"}] %s door with accessoryUUID: %@"
+ "chip delegate"
+ "enumeration"
+ "hmmtr.dayone.fwupdate.retry.interval"
+ "v16@?0@8"
- "@\"HMFFuture\"16@?0@\"MTRDoorLockClusterGetUserResponseParams\"8"
- "MatteriPhoneOnlyPairingForWatchEnabled"
- "[%{public}@] [Flow: %@] Begin process to re-add AliroCredentialsToUser: %@"
- "[%{public}@] [Flow: %@] Cached user is stale on the lock: %@"
- "[%{public}@] [Flow: %@] Cached user matches identifiers with the lock's current user on index %ld."
- "[%{public}@] [Flow: %@] Calling completion with error: %@"
- "[%{public}@] [Flow: %@] Clear abandoned user: %@ since it belongs to a deleted fabric"
- "[%{public}@] [Flow: %@] Could not find corresponding issuer key index in our cache for userIndex: %ld."
- "[%{public}@] [Flow: %@] Dropping credential that we could not fetch a user for. Credential: %@, Error: %@"
- "[%{public}@] [Flow: %@] Dropping credential that we could not fetch a user for. The user slot was marked Available. Credential: %@"
- "[%{public}@] [Flow: %@] Failed to remove user with index: %@ and uniqueID: %@. Error: %@"
- "[%{public}@] [Flow: %@] Failure to remove all abandoned users with error: %@"
- "[%{public}@] [Flow: %@] Found user on index verify userUniqueID %@"
- "[%{public}@] [Flow: %@] Successfully removed %lu abandoned users"
- "[%{public}@] [Flow: %@] issuerCredentialForUser: %@"
- "[%{public}@] [Flow: %@] pinCredentialForUser: %@"
- "[%{public}@] [NewFlow: %@ {\"Feature\":\"Lock ReadWrite\"}] Locking door with accessoryUUID: %@ completionHandler: %@"
- "[%{public}@] [NewFlow: %@ {\"Feature\":\"Lock ReadWrite\"}] Unlocking door with accessoryUUID: %@ completionHandler: %@"
- "[Flow: %@] Begin process to re-add AliroCredentialsToUser: %@"
- "[Flow: %@] Cached user is stale on the lock: %@"
- "[Flow: %@] Cached user matches identifiers with the lock's current user on index %ld."
- "[Flow: %@] Calling completion with error: %@"
- "[Flow: %@] Clear abandoned user: %@ since it belongs to a deleted fabric"
- "[Flow: %@] Could not find corresponding issuer key index in our cache for userIndex: %ld."
- "[Flow: %@] Dropping credential that we could not fetch a user for. Credential: %@, Error: %@"
- "[Flow: %@] Dropping credential that we could not fetch a user for. The user slot was marked Available. Credential: %@"
- "[Flow: %@] Failed to remove user with index: %@ and uniqueID: %@. Error: %@"
- "[Flow: %@] Failure to remove all abandoned users with error: %@"
- "[Flow: %@] Found user on index verify userUniqueID %@"
- "[Flow: %@] Successfully removed %lu abandoned users"
- "[Flow: %@] issuerCredentialForUser: %@"
- "[Flow: %@] pinCredentialForUser: %@"
- "[NewFlow: %@ {\"Feature\":\"Lock ReadWrite\"}] Locking door with accessoryUUID: %@ completionHandler: %@"
- "[NewFlow: %@ {\"Feature\":\"Lock ReadWrite\"}] Unlocking door with accessoryUUID: %@ completionHandler: %@"
- "aliroCredentials"
- "v24@?0@\"<HMFAlwaysNil>\"8@\"NSError\"16"
- "v24@?0@\"MTRDoorLockClusterGetUserResponseParams\"8@\"NSError\"16"
```
