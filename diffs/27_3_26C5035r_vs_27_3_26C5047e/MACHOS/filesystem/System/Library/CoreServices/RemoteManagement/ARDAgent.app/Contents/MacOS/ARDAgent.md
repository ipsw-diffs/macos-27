## ARDAgent

> `/System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/MacOS/ARDAgent`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-768.2.15.1.0
-  __TEXT.__text: 0xa12d0
-  __TEXT.__auth_stubs: 0x28a0
-  __TEXT.__objc_stubs: 0x2a80
-  __TEXT.__objc_methlist: 0xf00
-  __TEXT.__const: 0x1038
-  __TEXT.__oslogstring: 0x7274
-  __TEXT.__cstring: 0x23136
-  __TEXT.__objc_methname: 0x2883
+768.6.0.0.0
+  __TEXT.__text: 0xa72a0
+  __TEXT.__auth_stubs: 0x2940
+  __TEXT.__objc_stubs: 0x2ac0
+  __TEXT.__objc_methlist: 0xf10
+  __TEXT.__const: 0x1050
+  __TEXT.__oslogstring: 0x7585
+  __TEXT.__cstring: 0x24d86
+  __TEXT.__objc_methname: 0x28b5
   __TEXT.__objc_classname: 0x17f
   __TEXT.__objc_methtype: 0x972
-  __TEXT.__unwind_info: 0x1788
-  __DATA_CONST.__const: 0x998
-  __DATA_CONST.__cfstring: 0x3a40
+  __TEXT.__unwind_info: 0x1888
+  __DATA_CONST.__const: 0x9f8
+  __DATA_CONST.__cfstring: 0x3a60
   __DATA_CONST.__objc_classlist: 0x70
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x28

   __DATA_CONST.__objc_superrefs: 0x68
   __DATA_CONST.__objc_arraydata: 0x58
   __DATA_CONST.__objc_arrayobj: 0x60
-  __DATA_CONST.__auth_got: 0x1458
+  __DATA_CONST.__auth_got: 0x14a8
   __DATA_CONST.__got: 0x4f0
   __DATA_CONST.__auth_ptr: 0x38
   __DATA.__objc_const: 0x1440
-  __DATA.__objc_selrefs: 0xd40
+  __DATA.__objc_selrefs: 0xd50
   __DATA.__objc_ivar: 0xb0
   __DATA.__objc_data: 0x460
-  __DATA.__data: 0x3e8
-  __DATA.__bss: 0x1380
-  __DATA.__common: 0xd7ed
+  __DATA.__data: 0x470
+  __DATA.__thread_vars: 0x18
+  __DATA.__thread_bss: 0x1
+  __DATA.__bss: 0x13d8
+  __DATA.__common: 0xf1c5
   __CGPreLoginApp.__cgpreloginapp: 0x0
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/libpcre2-8.0.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1536
-  Symbols:   817
-  CStrings:  4534
+  Functions: 1604
+  Symbols:   828
+  CStrings:  4652
 
Symbols:
+ _CCHmac
+ _CCHmacFinal
+ _CCHmacInit
+ _CCHmacUpdate
+ _CFArrayContainsValue
+ _CFPropertyListCreateDeepCopy
+ _NSStringFromClass
+ __tlv_bootstrap
+ _getpeername
+ _memchr
+ _timingsafe_bcmp
CStrings:
+ "(null)"
+ "+[RSAKeyPair loadRSAPublicKeyWithLabel:]"
+ "A saved task entry is not a dictionary."
+ "ARD file copy packet MAC"
+ "Admin %.12s authorized to install packages as '%s' (security 0x%x)."
+ "Admin %.12s is not authorized to install packages (adminState %d, security 0x%x)."
+ "Admin %.12s: no validated session uses this connection's key."
+ "Admin %.12s: the install is refused. The session lacks a privilege an install needs, or the admin entry no longer allows this login."
+ "Admin %.12s: the session's login does not own this admin entry."
+ "Admin %.12s: the session's login is not authorized for the Task Server (login lookup, directory check, or Generate Reports)."
+ "Admin %.12s: the validated session does not hold Generate Reports."
+ "Admin entries %.12s and %.12s differ only in the case of their IDs. On a case-insensitive volume they share a task directory."
+ "AuthGetRandomBytes failed; zero-filling substituted RSA payload"
+ "AuthRSACopyDecryptedOrRandom"
+ "Canceling the task: a package name could not be read."
+ "Canceling the task: its package list is shorter than its package count."
+ "Canceling the task: package %s is not in its task directory."
+ "Could not copy the settings for writing. The settings file was not updated."
+ "Could not create the remote DOC address for the admin entry. The admin list was not changed."
+ "Could not create the values for the admin entry. The admin list was not changed."
+ "Could not prepare the packages for installation. No task was created."
+ "DOCAddAdminPacketToV2"
+ "DOCAddAdminToDOCAdminsHandler: incompatible packet (%d bytes, version %d)"
+ "DOCCopyAdminIdentity"
+ "DOCLoadAdminListFromPreferences"
+ "DOCLogCaseVariantAdminIDs"
+ "DOCLoginMayUseAdminEntry"
+ "DOCPrepareLocalAdminEntry"
+ "DOCQueueSettingsCopy"
+ "DOCSendNotConnectedToLocalAdmin"
+ "DOCSessionMayUseTaskServer"
+ "DOCStoredTaskIsContained"
+ "DOC_SendDelegationStatusToLocalAdmin"
+ "DecryptUDPPacketFromKey: packet from %s refused: the session has no MAC key"
+ "DecryptUDPPacketFromKey: packet tag error"
+ "EnqueueLocalDatagram"
+ "Error sending the DIP task status to the admin."
+ "FT2ProbeSecureCopyNodes"
+ "FT2ReceiverToSenderHandler - status from %s refused: it does not carry this copy's tag"
+ "FT2ReceiverToSenderHandler - status too short from %s"
+ "FT2SendInfoWithReply"
+ "FT2WritePacketToSender: the status could not be tagged, so it was not sent"
+ "Failed to allocate %u bytes for task data."
+ "Failed to allocate the tables for %u packages."
+ "Failed to create package file %s (item %d)."
+ "Failed to create package file %s for item %d."
+ "InitLocalDatagramPipe"
+ "Not deleting %s: it is not a client task directory."
+ "Not deleting %s: it is not a task directory."
+ "Not evicting the session with this hardware ID: its login neither owns the admin entry nor authenticated the old session."
+ "Not loading saved task %d: its admin ID or package paths are not in its own task directory, or it lacks a path for a package."
+ "Not sending package %s: it is not in its task directory."
+ "Not sending the task: a package name could not be read."
+ "Out of memory for an add-admin request. Nothing was changed."
+ "Out of memory for the add-admin reply. The admin list was not changed."
+ "Package path for item %d does not fit in the path buffer."
+ "PostCopyCommandIsAllowed"
+ "RSA decrypt unusable; continuing with a substituted key"
+ "RSA decrypt unusable; continuing with substituted SRP data"
+ "RSA host key changed for %s; adopting the new key unverified"
+ "RSA public key store holds %s, not data; ignoring it"
+ "Recorded the local login as the owner of an admin entry."
+ "Refusing a callback whose admin ID is not 12 upper-case hex digits."
+ "Refusing an admin identity shorter than 52 characters."
+ "Refusing an admin identity whose admin ID is not 12 upper-case hex digits."
+ "Refusing package name of length %d for item %d."
+ "Refusing the session: the old session with this hardware ID cannot be evicted."
+ "Refusing to add admin %.12s: an entry for the same ID in other letter case is stored."
+ "Refusing to add an admin whose ID is shorter than 52 characters or not 12 upper-case hex digits."
+ "Refusing to add an admin whose entry would have no owner: the sender has no login."
+ "Refusing to change an admin entry whose owners do not include the sender's login."
+ "Refusing to change an admin entry whose owners do not include the sender's login. The admin list changed after the add was checked."
+ "Refusing to remove an admin entry: the sender's login does not own it."
+ "Rejecting a DH public value outside [2, p-2]."
+ "Rejecting a task from an admin whose ID is not 12 upper-case hex digits."
+ "Rejecting a task whose %u clients do not fit in %u bytes."
+ "Rejecting kCmdSLSCommandReq (sub-command %u) because the packet length (%d) has no room for an MDItemRef"
+ "Rejecting kCmdSLSCommandReq (sub-command slsStartSearch) because the folder scope path (%u bytes) does not fit in the packet (%d)."
+ "Rejecting kCmdSLSCommandReq (sub-command slsStartSearch) because the packet length (%d) has no room for the folder scope path size"
+ "Rejecting kCmdSLSCommandReq (sub-command slsStartSearch) because the packet length (%d) is smaller than the header (%u)"
+ "Rejecting kCmdSLSCommandReq because %d trailing bytes cannot hold a search item header (%zu)"
+ "Rejecting kCmdSLSCommandReq because an unknown sub-command (%u) was received."
+ "Rejecting kCmdSLSCommandReq because the packet length (%d) is smaller than the header (%zu)"
+ "Rejecting package name of length %d for package %d."
+ "Rejecting task data of %u bytes."
+ "Removing admin %.12s from the DOC admin list: its entry has no owner list."
+ "SRP auth from an admin that never requested our key; sending it so a stale key can recover"
+ "Unable to allocate %ld bytes in delete selected"
+ "Unable to allocate %ld bytes in delete selected query"
+ "Unable to write to gLocalDatagramPipe"
+ "admin command refused: the admin has no encrypted connection"
+ "admin command refused: the packet length is not valid"
+ "com.apple.RemoteDesktop.DOCSettingsWrite"
+ "copy not started: receiver %d has no encrypted connection"
+ "copy not started: the sender did not answer the secure copy probe"
+ "copy not supported: receiver %d answered the probe with %d"
+ "copy not supported: the admin's arm is too short or did not come through a patched agent %d"
+ "copy not supported: the send-info did not come through a patched agent"
+ "copy not supported: the sender is not a secure copy agent"
+ "custom install path is not terminated inside the packet"
+ "dropping datagram from loopback source"
+ "final status could not be tagged, so it was not sent"
+ "hp->addrequal %d hp->localOrigin %d hp->valid %d flags %d"
+ "invalid datagram size %ld"
+ "isEqualToData:"
+ "memory error"
+ "no free admin table entry; dropping validate packet"
+ "not importing public key for %s: does not parse as an RSA public key"
+ "ownerLogins"
+ "path data out of range - pktIndex %u dataSize %d dataLen %d"
+ "performSLS_Thread: folder scope path component (%d bytes) does not fit in the remaining path data (%d) - ignoring scope."
+ "performSLS_Thread: folder scope path is truncated at offset %d of %u - ignoring scope."
+ "plaintext copy packet refused"
+ "post copy command %d refused: the admin does not have the privilege it needs"
+ "rejecting RSA key: declared %u > %zu received"
+ "rejecting SRP start: declared %u > %lu available"
+ "rejecting SRP step: declared %u > %zu received"
+ "rejecting downgrade proof: declared %u > %zu received"
+ "rejecting op 2: wire srpDataLen %u exceeds packet (len:%d)"
+ "retrieveRSAPublicKeyDataWithLabel:"
+ "slsCopyToHFSUniStr255"
+ "slsCopyToHFSUniStr255: truncating a %ld character name to %d"
+ "slsNotficationCallback"
+ "slsNotficationCallback: dropping a search result whose entry (%u bytes) does not fit in an empty packet (%d)"
+ "source file destination path index %u is not one of the destination paths"
+ "source file info names items %u to %u but the copy has %u items"
+ "source file info refused: the copy is not set up (send info %s, receivers %u of %u, items %u)"
+ "source file path is empty"
+ "source file path is not terminated inside the packet"
+ "unable to create local datagram pipe. errno %d %s"
+ "validation for admin slot %d was superseded; not attaching"
- "%s/%u"
- "Admin %.12s authorized for task server as '%s' (security 0x%x)."
- "Admin %.12s is not authorized for task server operations (adminState %d, security 0x%x)."
- "DOCAddAdminToDOCAdminsHandler: incompatible version (%d instead of %d)"
- "DecryptUDPPacketFromKey: packet checksum error"
- "FT2_AdminReceiverAuthorizePkt too small %d"
- "SendUnencryptedPacket"
- "error from UDPReceiverHandlePacket() %d"
- "error from file enc decrypt %d"
- "hp->addrequal %d hp->selfsend %d hp->valid %d flags %d"
- "path data out of range"
- "unknown packet received %d"
- "unknown packet type in SendUnencryptedPacket %d"
```
