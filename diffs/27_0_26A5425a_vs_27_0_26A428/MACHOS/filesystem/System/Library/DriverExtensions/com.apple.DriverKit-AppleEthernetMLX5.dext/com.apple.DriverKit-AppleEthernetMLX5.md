## com.apple.DriverKit-AppleEthernetMLX5

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleEthernetMLX5.dext/com.apple.DriverKit-AppleEthernetMLX5`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 171.0.0.0.0
-  __TEXT.__text: 0x193e0
+  __TEXT.__text: 0x190b0
   __TEXT.__auth_stubs: 0x660
   __TEXT.__cstring: 0x3ff3
   __TEXT.__const: 0x2268
Functions:
~ __ZN27DriverKit_AppleEthernetMLX54freeEv : 76 -> 64
~ __ZN33DriverKit_AppleEthernetMLX5_NetIf18SetPowerState_ImplEj : 136 -> 124
~ __ZN33DriverKit_AppleEthernetMLX5_NetIf9Stop_ImplEP9IOService : 140 -> 128
~ __ZN27DriverKit_AppleEthernetMLX519QueueInterrupt_ImplEP8OSActionyy : 108 -> 100
~ __ZN27DriverKit_AppleEthernetMLX524HealthTimerOccurred_ImplEP8OSActiony : 124 -> 112
~ __ZN27DriverKit_AppleEthernetMLX521CmdTimerOccurred_ImplEP8OSActiony : 116 -> 104
~ __ZN33DriverKit_AppleEthernetMLX5_NetIf30SetAllMulticastModeEnable_ImplEb : 140 -> 128
~ __ZZN33DriverKit_AppleEthernetMLX5_NetIf23SetInterfaceEnable_ImplEbEN3$_08__invokeERZNS_23SetInterfaceEnable_ImplEbE7context : 124 -> 112
~ __ZZN33DriverKit_AppleEthernetMLX5_NetIf20SelectMediaType_ImplEjEN3$_08__invokeERZNS_20SelectMediaType_ImplEjE7context : 124 -> 112
~ __ZN4mlx56FSBaseD0Ev : 124 -> 112
~ __ZN4mlx56FSBase10removeNodeEb : 168 -> 156
~ __ZN4mlx57FTEntry13freeStarEntryEv : 192 -> 180
~ __ZN4mlx59FlowTable11setStarRuleEP33DriverKit_AppleEthernetMLX5_IVarsPS0_ : 256 -> 244
~ __ZN4mlx59FlowTable15createFlowGroupEPh : 204 -> 192
~ __ZN4mlx59FlowGroup13cmdRemoveNodeEv : 204 -> 192
~ __ZN4mlx57FTEntry7addRuleEPNS_8FlowRuleE : 164 -> 152
~ __ZN4mlx58FlowRule3delEv : 116 -> 104
~ __ZN4mlx58FlowRuleD0Ev : 124 -> 112
~ __ZN4mlx57FTEntryD0Ev : 124 -> 112
~ __ZN4mlx59FlowTableD0Ev : 124 -> 112
~ __ZN4mlx59FlowGroupD0Ev : 124 -> 112
~ __ZN4mlx56FSPrioD0Ev : 124 -> 112
~ __ZN4mlx517FlowRootNamespaceD0Ev : 124 -> 112
~ __ZN4mlx513FlowNamespaceD0Ev : 124 -> 112
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _OUTLINED_FUNCTION_1 : 32 -> 20
~ _OUTLINED_FUNCTION_2 : 44 -> 32
~ _OUTLINED_FUNCTION_3 : 28 -> 16
~ _OUTLINED_FUNCTION_4 : 28 -> 16
~ __ZN33DriverKit_AppleEthernetMLX5_IVars6free4kEy : 1660 -> 1648
~ __ZN23AppleEthernetMLX5FwPageD0Ev : 56 -> 44
~ __ZN33DriverKit_AppleEthernetMLX5_IVars18handleCQCompletionEj : 152 -> 140
~ __ZN23AppleEthernetMLX5DMABufD0Ev : 56 -> 44
~ __ZN33DriverKit_AppleEthernetMLX5_IVars16allocDBFromPgDirER24AppleEthernetMLX5DBPgDirRN4mlx52DBE : 76 -> 80
~ __ZN33DriverKit_AppleEthernetMLX5_IVars7allocDBERN4mlx52DBE : 224 -> 232
~ __ZN24AppleEthernetMLX5DBPgDirD0Ev : 56 -> 44
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars16dequeueTxPacketsEPN4mlx55EthSQE : 1012 -> 1016
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars7drainSQERN4mlx55EthSQE : 524 -> 528
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars23vportContextUpdateVlansEv : 784 -> 744
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars14addVlanRuleSubEN4mlx514vlan_rule_typeEtPhS2_ : 320 -> 324
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars11delVlanRuleEN4mlx514vlan_rule_typeEt : 200 -> 188
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars15addAllVlanRulesEv : 772 -> 756
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars15delAllVlanRulesEv : 428 -> 412
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars13executeActionEPN4mlx515EthAddrHashNodeE : 752 -> 736
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars18vPortContextUpdateEv : 88 -> 76
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars12handleIfAddrEb : 160 -> 148
~ __ZN33DriverKit_AppleEthernetMLX5_IVars17createL2FlowTableEv : 140 -> 128
~ __ZN33DriverKit_AppleEthernetMLX5_IVars19createVlanFlowTableEv : 140 -> 128
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars23createInnerRssFlowTableEv : 152 -> 140
~ __ZN33DriverKit_AppleEthernetMLX5_IVars18createFlowSteeringEv : 72 -> 60
~ __ZN33DriverKit_AppleEthernetMLX5_IVars19destroyFlowSteeringEv : 68 -> 56
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars18createFlowSteeringEv : 76 -> 64
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars19destroyFlowSteeringEv : 68 -> 56
~ __ZNK19AppleEthernetMLX5EQ15queue_interruptEj : 1184 -> 1164
~ __ZN19AppleEthernetMLX5EQD0Ev : 56 -> 44
~ __ZN33DriverKit_AppleEthernetMLX5_IVars7getCapsEN4mlx58cap_typeE : 88 -> 76
~ __ZN33DriverKit_AppleEthernetMLX5_IVars5eventEN4mlx59dev_eventEm : 104 -> 92
~ __ZN27AppleEthernetMLX5CmdWorkEnt4dumpEb : 388 -> 376
~ __ZL8dump_bufPvibi : 268 -> 256
~ __ZN20AppleEthernetMLX5Cmd13releaseCmdMsgEP23AppleEthernetMLX5CmdMsg : 144 -> 132
~ ____ZN20AppleEthernetMLX5Cmd4execEPviS0_i_block_invoke : 692 -> 676
~ __ZN20AppleEthernetMLX5Cmd6invokeEP23AppleEthernetMLX5CmdMsgS1_Phb : 840 -> 824
~ __ZN20AppleEthernetMLX5CmdD2Ev : 252 -> 240
~ __ZN20AppleEthernetMLX5CmdD0Ev : 56 -> 44
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ __ZN33DriverKit_AppleEthernetMLX5_IVars17setNicVPortMcListEiPyi : 332 -> 336
~ __ZN33DriverKit_AppleEthernetMLX5_IVars20queryNicVPortMacListEtN4mlx59list_typeEPA6_hPi : 332 -> 336
~ __ZN33DriverKit_AppleEthernetMLX5_IVars21modifyNicVPortMacListEN4mlx59list_typeEPA6_hi : 336 -> 340
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars7closeRQERN4mlx55EthRQE : 104 -> 92
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars7closeSQERN4mlx55EthSQE : 108 -> 96
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars6openCQERN4mlx510EthCQParamERNS0_5EthCQEPFjPNS0_2CQEEi : 108 -> 96
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars7closeCQERN4mlx55EthCQE : 84 -> 72
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars11openChannelERN4mlx510EthChannelERNS0_15EthChannelParamEi : 216 -> 204
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars14disableChannelERN4mlx510EthChannelE : 64 -> 52
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars12closeChannelERN4mlx510EthChannelE : 88 -> 76
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars12openChannelsEv : 176 -> 180
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars13closeChannelsEv : 208 -> 216
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars11activateRQTEv : 232 -> 236
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars14startInterfaceEv : 1720 -> 1724
~ _ZNK19AppleEthernetMLX5EQ15queue_interruptEj.cold.1 : 248 -> 236
~ _ZN33DriverKit_AppleEthernetMLX5_IVars9detectMSIEv.cold.1 : 92 -> 88
```
