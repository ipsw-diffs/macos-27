## ThreadNetwork

> `/System/Library/Frameworks/ThreadNetwork.framework/Versions/A/ThreadNetwork`

```diff

-447.0.1.0.0
+447.0.2.0.0
   __TEXT.__text: 0x10938
   __TEXT.__objc_methlist: 0xe98
   __TEXT.__const: 0xb8
-  __TEXT.__cstring: 0x1b3f
+  __TEXT.__cstring: 0x1b49
   __TEXT.__oslogstring: 0xc8f
   __TEXT.__gcc_except_tab: 0x190
   __TEXT.__unwind_info: 0x5f8
Symbols:
+ -[THNearbyNetworkCredentials initThreadCredentials:extendedPANID:borderAgentID:activeOperationalDataSet:PSKC:networkKey:channel:panID:creationDate:lastModificationDate:isForPreferredNetwork:]
+ -[THNearbyNetworkCredentials initThreadCredentials:isForPreferredNetwork:]
+ -[THNearbyNetworkCredentials initWithActiveDataSetRecord:isForPreferredNetwork:]
+ -[THNearbyNetworkCredentials isForPreferredNetwork]
+ _OBJC_IVAR_$_THNearbyNetworkCredentials._isForPreferredNetwork
+ _objc_msgSend$initThreadCredentials:extendedPANID:borderAgentID:activeOperationalDataSet:PSKC:networkKey:channel:panID:creationDate:lastModificationDate:isForPreferredNetwork:
+ _objc_msgSend$initWithActiveDataSetRecord:isForPreferredNetwork:
+ _objc_msgSend$isForPreferredNetwork
- -[THNearbyNetworkCredentials initThreadCredentials:extendedPANID:borderAgentID:activeOperationalDataSet:PSKC:networkKey:channel:panID:creationDate:lastModificationDate:isPreferredNetworkCredentials:]
- -[THNearbyNetworkCredentials initThreadCredentials:isPreferredNetworkCredentials:]
- -[THNearbyNetworkCredentials initWithActiveDataSetRecord:isPreferredNetworkCredentials:]
- -[THNearbyNetworkCredentials isPreferredNetworkCredentials]
- _OBJC_IVAR_$_THNearbyNetworkCredentials._isPreferredNetworkCredentials
- _objc_msgSend$initThreadCredentials:extendedPANID:borderAgentID:activeOperationalDataSet:PSKC:networkKey:channel:panID:creationDate:lastModificationDate:isPreferredNetworkCredentials:
- _objc_msgSend$initWithActiveDataSetRecord:isPreferredNetworkCredentials:
- _objc_msgSend$isPreferredNetworkCredentials
CStrings:
+ "THNearbyNetworkCredentials.isForPreferredNetwork"
- "THNearbyNetworkCredentials.isPreferred"
```
