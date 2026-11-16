## tccd

> `/System/Library/PrivateFrameworks/TCC.framework/Support/tccd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__data`

```diff

-925.0.4.0.0
-  __TEXT.__text: 0x8d61c
-  __TEXT.__auth_stubs: 0x1600
+925.0.13.3.2
+  __TEXT.__text: 0x9ad9c
+  __TEXT.__auth_stubs: 0x16c0
   __TEXT.__lazy_helpers: 0x54
-  __TEXT.__objc_stubs: 0x9ea0
-  __TEXT.__objc_methlist: 0x43fc
-  __TEXT.__cstring: 0x128f0
-  __TEXT.__const: 0x638
-  __TEXT.__gcc_except_tab: 0x37e4
-  __TEXT.__objc_methname: 0x10897
-  __TEXT.__oslogstring: 0xf3a6
-  __TEXT.__objc_classname: 0x4ae
-  __TEXT.__objc_methtype: 0x14f7
-  __TEXT.__unwind_info: 0x2088
-  __DATA_CONST.__const: 0x27f0
-  __DATA_CONST.__cfstring: 0x86a0
-  __DATA_CONST.__objc_classlist: 0x188
+  __TEXT.__objc_stubs: 0xab00
+  __TEXT.__objc_methlist: 0x493c
+  __TEXT.__cstring: 0x151a2
+  __TEXT.__const: 0x658
+  __TEXT.__gcc_except_tab: 0x3c50
+  __TEXT.__objc_methname: 0x11be4
+  __TEXT.__oslogstring: 0x10539
+  __TEXT.__objc_classname: 0x52c
+  __TEXT.__objc_methtype: 0x1683
+  __TEXT.__unwind_info: 0x23b0
+  __DATA_CONST.__const: 0x2970
+  __DATA_CONST.__cfstring: 0x99e0
+  __DATA_CONST.__objc_classlist: 0x1b0
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0x158
+  __DATA_CONST.__objc_superrefs: 0x168
   __DATA_CONST.__objc_doubleobj: 0x10
-  __DATA_CONST.__objc_arraydata: 0x1808
-  __DATA_CONST.__objc_arrayobj: 0xf0
+  __DATA_CONST.__objc_arraydata: 0x1ad8
+  __DATA_CONST.__objc_arrayobj: 0x150
   __DATA_CONST.__objc_intobj: 0x558
-  __DATA_CONST.__objc_dictobj: 0xfa0
-  __DATA_CONST.__auth_got: 0xb10
-  __DATA_CONST.__got: 0x4b8
-  __DATA_CONST.__auth_ptr: 0x30
-  __DATA.__objc_const: 0x8128
-  __DATA.__objc_selrefs: 0x2e50
-  __DATA.__objc_ivar: 0x6ac
-  __DATA.__objc_data: 0xf50
+  __DATA_CONST.__objc_dictobj: 0x1018
+  __DATA_CONST.__auth_got: 0xb70
+  __DATA_CONST.__got: 0x4f8
+  __DATA_CONST.__auth_ptr: 0x38
+  __DATA.__objc_const: 0x8af0
+  __DATA.__objc_selrefs: 0x31a8
+  __DATA.__objc_ivar: 0x750
+  __DATA.__objc_data: 0x10e0
   __DATA.__lazy_load_got: 0x8
   __DATA.__data: 0x34c
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x368
+  __DATA.__bss: 0x3e0
   __DATA.__common: 0x30
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/Frameworks/SystemExtensions.framework/Versions/A/SystemExtensions
   - /System/Library/Frameworks/UserNotifications.framework/Versions/A/UserNotifications
+  - /System/Library/PrivateFrameworks/AppleMobileFileIntegrity.framework/Versions/A/AppleMobileFileIntegrity
   - /System/Library/PrivateFrameworks/BaseBoard.framework/Versions/A/BaseBoard
   - /System/Library/PrivateFrameworks/BoardServices.framework/Versions/A/BoardServices
   - /System/Library/PrivateFrameworks/CoreAnalytics.framework/Versions/A/CoreAnalytics

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 2663
-  Symbols:   505
-  CStrings:  5290
+  Functions: 2888
+  Symbols:   522
+  CStrings:  5755
 
Symbols:
+ _AMFIExecutionPreflight
+ _CFNumberIsFloatType
+ _OBJC_CLASS_$_NSCharacterSet
+ _OBJC_CLASS_$_NSMutableCharacterSet
+ _OBJC_CLASS_$_NSNull
+ _dispatch_walltime
+ _fchmod
+ _fstat
+ _fsync
+ _kSecCodeInfoDiskRepInfo
+ _kSecCodeInfoDiskRepVersionPlatform
+ _localtime_r
+ _lstat
+ _mktime
+ _os_unfair_recursive_lock_lock
+ _read
+ _rename
+ _unlink
- _os_unfair_recursive_lock_lock_with_options
CStrings:
+ " (not recorded by this tccd)"
+ "!1"
+ "%@ (pid %d)"
+ "%@ could not identify the target app named by the audit token of the indirect object"
+ "%@ does not accept the target %@, which is signed by Apple (UI element: %s, XPC service: %s)"
+ "%@ indirect object audit token has the wrong size"
+ "%@ reset does not accept an indirect object named by an audit token"
+ "%@|"
+ "%llu:%llu:%ld.%09ld:%lld"
+ "%lu bytes, over the %lu byte limit"
+ "%s: service %{public}@ has no text indirect object to write, indirectObjectType: %ld"
+ "%zu bytes, over the %lu byte limit"
+ "%{public}@ decides per indirect object, and there is none with an identifier"
+ "%{public}@: %{public}@ is on the mobile asset list (ListVersion %ld)"
+ "%{public}@: %{public}@: low friction entitlement: %{public}s (%d)"
+ "%{public}@: running code is on the mobile asset list (ListVersion %ld)"
+ "%{public}@: target %{public}@ (type %d, %{public}s)"
+ "%{public}s: %{public}@ has no fine grained records"
+ "%{public}s: Assumed executable %{public}@ is not an Endpoint Security client because AMFI will not allow it to run with its entitlements: %{public}@"
+ "%{public}s: caller %{public}@ (pid %d) lacks entitlement com.apple.private.tcc.mobileasset.check for service %{public}@"
+ "%{public}s: database error %d for %{public}@"
+ "%{public}s: failed to attribute an identity for %{public}@"
+ "%{public}s: failed to create the request context: %{public}@"
+ "%{public}s: missing or invalid authorization right"
+ "%{public}s: missing or invalid mobileasset_list_type"
+ "%{public}s: missing service in request"
+ "%{public}s: passing nil pointer as struct."
+ "%{public}s: requestor %{public}@ is not entitled to check %{public}@ for accessor %{public}@"
+ "%{public}s: target process from target_token, or its responsible process, is not valid"
+ "%{public}s: unable to resolve realpath of %{public}s: %{public}@"
+ "(none)"
+ "-[TCCDMainDatabase copyFineGrainedAuthRecordForSchemaTypeTextIDAndSessionWithService:record:list:]_block_invoke"
+ "-[TCCDMainDatabase fineGrainedStatusWithService:subjectIdentity:right:status:]_block_invoke"
+ "-[TCCDMainDatabase fineGrainedStatusWithService:subjectIdentity:right:status:]_block_invoke_2"
+ "-[TCCDMainDatabase fineGrainedTableExists:forService:]_block_invoke"
+ "-[TCCDMainDatabase getFineGrainedAuthResultForSchemaTypeTextIDAndSessionWithContext:result:]_block_invoke"
+ "-[TCCDMainDatabase sessionTimeRecordsForService:rows:]_block_invoke"
+ "-[TCCDMainDatabase setFineGrainedAuthRecordForSchemaTypeTextIDAndSessionWithAccessRecord:]"
+ "-[TCCDMainDatabase setFineGrainedAuthRecordForSchemaTypeTextIDAndSessionWithAccessRecord:]_block_invoke"
+ "-[TCCDMainDatabase setFineGrainedAuthRecordForSchemaTypeTextIDAndSessionWithContext:result:]_block_invoke"
+ "-[TCCDPlatformMacOS notifyUserOfDeniedAccessTo:forService:indirectObject:]_block_invoke"
+ "-[TCCDServer evaluateComposedAuthorizationToService:context:andAccessSubject:indirectObject:withRelation:authorizationResult:authorizationReason:subjectCodeIdentityDataResult:]"
+ "-[TCCDServer getFineGrainedStatusWithComposedService:subjectIdentity:right:status:]"
+ "-[TCCDServer handleSessionExpiryForRecord:]_block_invoke"
+ ".%@.%d.tmp"
+ ".-_"
+ "@\"TCCDMobileAssetListContents\""
+ "@\"TCCDSessionTimeConfiguration\""
+ "@36@0:8@16@24I32"
+ "@40@0:8@16@24Q32"
+ "@48@0:8@16@24@32@40"
+ "@72@0:8{?=[8I]}16@48@56^@64"
+ "@80@0:8@16@24q32@40q48Q56q64q72"
+ "A"
+ "ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789"
+ "AMFI preflight is not available"
+ "AMFI would not allow it"
+ "AMFI would not let %{public}@ run with its entitlements (platform %d): %{public}@"
+ "Allowed for session time"
+ "An indirect object named by an audit token is only accepted for an access request"
+ "AppStore"
+ "Authorization is set by a configuration profile and cannot be modified"
+ "B24@0:8^@16"
+ "B32@0:8@16Q24"
+ "B32@0:8@16^@24"
+ "B32@0:8q16q24"
+ "B40@0:8@16@24^i32"
+ "B40@0:8@16^Q24^Q32"
+ "B40@0:8^{__SecCode=}16@24Q32"
+ "B80@0:8@16@24@32@40q48^Q56^Q64^@72"
+ "B80@0:8@16B24@28B36^Q40^Q48^i56^@64^B72"
+ "BuiltInListVersion"
+ "BuiltInPath"
+ "BuiltInSubjectLists.plist"
+ "CFBundlePackageType"
+ "CREATE TABLE IF NOT EXISTS %@ (    service            TEXT        NOT NULL,     category           TEXT        NOT NULL,     category_type      INTEGER     NOT NULL,     client             TEXT        NOT NULL,     client_type        INTEGER     NOT NULL,     auth_value         INTEGER     NOT NULL,     auth_reason        INTEGER     NOT NULL,     indirect_object_identifier TEXT NOT NULL DEFAULT 'UNUSED',     session_expiry     INTEGER,     session_boot_uuid  TEXT,     session_version    INTEGER     NOT NULL DEFAULT 0,     target_csreq       BLOB,     PRIMARY KEY (category, category_type, client, client_type)    FOREIGN KEY (service, client, client_type, indirect_object_identifier) REFERENCES access(service, client, client_type, indirect_object_identifier) ON DELETE CASCADE)"
+ "DB error (%d) checking locked PPPC grant for %{public}@:%@; treating as locked"
+ "DO UPDATE SET auth_value=excluded.auth_value, auth_reason=excluded.auth_reason, session_expiry=CASE WHEN excluded.auth_value=auth_value THEN session_expiry ELSE NULL END, session_boot_uuid=CASE WHEN excluded.auth_value=auth_value THEN session_boot_uuid ELSE NULL END, session_version=CASE WHEN excluded.auth_value=auth_value THEN session_version ELSE session_version+1 END, target_csreq=COALESCE(excluded.target_csreq, target_csreq)"
+ "DO UPDATE SET auth_value=excluded.auth_value, auth_reason=excluded.auth_reason, session_expiry=excluded.session_expiry, session_version=session_version+1, target_csreq=COALESCE(excluded.target_csreq, target_csreq)"
+ "DO UPDATE SET target_csreq=excluded.target_csreq"
+ "DR of the target of client %@ does not match"
+ "DeveloperID"
+ "Distribution"
+ "Error: process.responsiblePath is nil"
+ "FormatVersion"
+ "HighestAcceptedListVersion"
+ "HighestAcceptedListVersion.plist"
+ "INSERT INTO %@ (service, category, category_type, client, client_type, auth_value, auth_reason, indirect_object_identifier, session_expiry, session_version) VALUES(?, ?, ?, ?, ?, ?, ?, ?, ?, (random() & 0x7FFFFFFFFFFFFFFF)) ON CONFLICT(category, category_type, client, client_type) DO UPDATE SET auth_value=excluded.auth_value, auth_reason=excluded.auth_reason, session_expiry=excluded.session_expiry, session_version=session_version+1 RETURNING session_version"
+ "INSERT INTO %@ (service, category, category_type, client, client_type, auth_value, auth_reason, indirect_object_identifier, session_version, target_csreq, session_expiry) VALUES(?, ?, ?, ?, ?, ?, ?, ?, (random() & 0x7FFFFFFFFFFFFFFF), ?, ?) ON CONFLICT(category, category_type, client, client_type) %@ RETURNING session_version"
+ "Ignoring AllowStandardUserToSetSystemService for %{public}@ (unsupported): identifier=%@"
+ "InUse"
+ "InUseListVersion"
+ "ListVersion"
+ "ListVersion %ld is lower than %ld already accepted"
+ "Lists"
+ "MobileAssetList"
+ "MobileAssetListInstall"
+ "MobileAssetListRemove"
+ "MobileAssetListState"
+ "NULL"
+ "No platform for %{public}@"
+ "Not notifying for access %{public}@: target %{public}@ is not valid for prompting"
+ "Override: skipping %{public}@ for %@ as its Authorization is unsupported for the service"
+ "Posted notification: %s, composed with %{public}@"
+ "RecordedVersionUnusable"
+ "SELECT 1 FROM access WHERE service=? AND client=? AND client_type=? LIMIT 1"
+ "SELECT 1 FROM sqlite_schema WHERE type='table' AND name=?"
+ "SELECT auth_value, %@ FROM %@ WHERE client=? AND client_type=?"
+ "SELECT auth_value, auth_reason, session_expiry, session_version, target_csreq FROM %@ WHERE category=? AND category_type=? AND client=? AND client_type=?"
+ "SELECT auth_value, session_expiry, session_version FROM %@ WHERE category=? AND category_type=? AND client=? AND client_type=?"
+ "SELECT category, category_type, client, client_type, auth_value, auth_reason, session_expiry, session_boot_uuid, session_version, target_csreq FROM %@ WHERE service=? AND client=? AND client_type=?"
+ "SELECT category, category_type, client, client_type, session_expiry, session_version, auth_value FROM %@ WHERE auth_value=?"
+ "Service %{public}@ allows Session Time but has no sessionTimeConfig"
+ "Session demotion failed for %{public}@: %d"
+ "Session expiry check failed for %{public}@: %d"
+ "Session sweep failed for %{public}@: %d"
+ "Session time auth expired for client %@"
+ "SetSessionEndTime"
+ "SetSessionEndTime: %{public}@ now %lld seconds after midnight"
+ "SetSessionEndTime: needs a service that allows Session Time and a time of day (service %{public}s, seconds %lld)"
+ "SetSessionTimeDuration"
+ "SetSessionTimeDuration: %{public}@ now %lld seconds"
+ "SetSessionTimeDuration: needs a service that allows Session Time and a positive length (service %{public}s, seconds %lld)"
+ "T@\"NSArray\",C,N,V_lowFrictionEntitlements"
+ "T@\"NSData\",&,N,V_fineGrainedTargetCSReq"
+ "T@\"NSNumber\",&,N,V_fineGrainedSessionVersion"
+ "T@\"NSString\",C,N,V_category"
+ "T@\"NSString\",C,N,V_client"
+ "T@\"NSString\",R,C,N,V_source"
+ "T@\"TCCDAccessIdentity\",&,V_targetIdentity"
+ "T@\"TCCDSessionTimeConfiguration\",&,N,V_sessionTimeConfig"
+ "TB,N,V_attributesTargetApp"
+ "TB,N,V_composedServiceCodeRequirementMismatch"
+ "TB,N,V_keepMainRowWithEmptyIndirectObjectList"
+ "TB,N,V_mdm_pppcGrantIsNonModifiable"
+ "TB,N,V_recordsListVersions"
+ "TB,V_targetIdentityAttributed"
+ "TCCAccessCheckAppInMobileAssetList"
+ "TCCAccessGetFineGrainedStatus"
+ "TCCAssetList.plist"
+ "TCCDLowFrictionEntitlement"
+ "TCCDMobileAssetList"
+ "TCCDMobileAssetListContents"
+ "TCCDSessionTimeConfiguration"
+ "TCCDSessionTimeRecord"
+ "TCCD_MSG_HAS_FINE_GRAINED_RECORD_KEY"
+ "TCCD_MSG_HAS_MAIN_RECORD_KEY"
+ "TCCD_MSG_HAS_RECORD_WITH_RIGHT_KEY"
+ "TCCD_MSG_QUERY_AUTHORIZATION_RIGHT_KEY"
+ "TCCMobileAsset"
+ "TQ,N,V_defaultExpiredAuth"
+ "TeamIdentifier"
+ "Ti,N,V_doUpdateOfTargetVerifierData"
+ "Tq,N,V_categoryType"
+ "Tq,N,V_clientType"
+ "Tq,N,V_fineGrainedSessionExpiry"
+ "Tq,N,V_sessionExpiry"
+ "Tq,N,V_sessionVersion"
+ "Tq,R,N"
+ "Tq,R,N,V_listVersion"
+ "UPDATE access SET csreq = ? WHERE service = ? AND client = ? AND client_type = ? AND csreq IS NULL"
+ "UPDATE managed_overrides SET   admin_auth_value = ?,   auth_value = CASE WHEN ? = 1 AND auth_reason IN (?, ?) THEN auth_value ELSE ? END,   auth_reason = ?,   flags = ((flags | ?) & ~?),   last_modified = CAST(strftime('%s','now') AS INTEGER) WHERE service = ? AND client = ? AND client_type = ?"
+ "UPDATE managed_overrides SET auth_value = CASE WHEN admin_auth_value >= ? THEN ? ELSE ? END, auth_reason = ?, flags = 0, last_modified = CAST(strftime('%s','now') AS INTEGER) WHERE NOT ((flags & ?) AND NOT (flags & ?) AND instr(?, '|' || service || '|') > 0)"
+ "Update Access Record: rejecting update of %{public}@ for %@:%{public}d: authorization is set by a configuration profile and cannot be modified"
+ "UpdateListVersion"
+ "UpdatePath"
+ "XPC!"
+ "_appStoreTeamsByService"
+ "_attributesTargetApp"
+ "_builtIn"
+ "_builtInLoaded"
+ "_builtInPath"
+ "_category"
+ "_categoryType"
+ "_client"
+ "_clientType"
+ "_composedServiceCodeRequirementMismatch"
+ "_defaultExpiredAuth"
+ "_doUpdateOfTargetVerifierData"
+ "_endsAtTimeOfDay"
+ "_fineGrainedSessionExpiry"
+ "_fineGrainedSessionVersion"
+ "_fineGrainedTargetCSReq"
+ "_highestAccepted"
+ "_highestVersionPath"
+ "_indexesByService"
+ "_keepMainRowWithEmptyIndirectObjectList"
+ "_listVersion"
+ "_lowFrictionEntitlements"
+ "_mdm_pppcGrantIsNonModifiable"
+ "_postAuthorizationChangedNotificationOfComposedService:composedWith:"
+ "_postAuthorizationChangedNotificationsForServicesComposedWithService:"
+ "_recordUnusable"
+ "_recordsListVersions"
+ "_requiredOwner"
+ "_requirementsByService"
+ "_seconds"
+ "_sessionExpiry"
+ "_sessionTimeConfig"
+ "_sessionTimeQueue"
+ "_sessionVersion"
+ "_source"
+ "_targetIdentity"
+ "_targetIdentityAttributed"
+ "_update"
+ "_updateDirectory"
+ "_updateIdentity"
+ "_updatePath"
+ "accessRecordForDemotedSessionTimeRecord:"
+ "addCharactersInString:"
+ "alphanumericCharacterSet"
+ "anchor apple generic"
+ "appStoreTeamsForService:listType:"
+ "attributed"
+ "attributesTargetApp"
+ "attribution_method"
+ "authorization_indirect_object"
+ "built in"
+ "canBeConvertedToEncoding:"
+ "cannot remove %@: %s"
+ "cannot write %@: %s"
+ "category"
+ "categoryType"
+ "characterSetWithCharactersInString:"
+ "claims none"
+ "clientType"
+ "codeAtURL:holdsLowFrictionEntitlementForService:"
+ "codeAtURL:isListedForService:listType:"
+ "com.apple.AMSUIAuthenticationViewService"
+ "com.apple.AMSUIPaymentViewService"
+ "com.apple.AVKit.OutputDeviceMenuService"
+ "com.apple.AVKit.RoutePickerViewService"
+ "com.apple.Arabesque"
+ "com.apple.CMViewSrvc"
+ "com.apple.CharacterPicker.RemoteGenerationViewService"
+ "com.apple.DataDetectorsViewService"
+ "com.apple.Flurry"
+ "com.apple.GameOverlayViewService"
+ "com.apple.GenerativePlaygroundApp.remoteUIExtension"
+ "com.apple.HydraQLPreviewExtension"
+ "com.apple.HydraRenderingService"
+ "com.apple.InstallerRemotePluginService.arm64"
+ "com.apple.InstallerRemotePluginService.x86_64"
+ "com.apple.LinkedNotesUIService"
+ "com.apple.LookupViewService"
+ "com.apple.MADViewServiceExtension"
+ "com.apple.MediaRemoteUIService"
+ "com.apple.Music.VisualizerService"
+ "com.apple.OFDPreview"
+ "com.apple.PaperKit.extension.ui"
+ "com.apple.PressAndHold"
+ "com.apple.PreviewShell"
+ "com.apple.PreviewShellMac"
+ "com.apple.QuickLookUIFramework.QLPreviewGenerationExtension"
+ "com.apple.RAQLPreviewExtension"
+ "com.apple.ReminderKitUI.ReminderCreationViewService"
+ "com.apple.RemotePDEService"
+ "com.apple.RemotePDEServiceARM"
+ "com.apple.Safari.SafariQuickLookPreview"
+ "com.apple.SceneKitQLPreviewExtension"
+ "com.apple.ScreenSaver.Computer-Name"
+ "com.apple.ScreenSaver.Drift"
+ "com.apple.ScreenSaver.Engine.legacyScreenSaver"
+ "com.apple.ScreenSaver.Engine.legacyScreenSaver.x86-64"
+ "com.apple.ScreenSaver.Hello"
+ "com.apple.ScreenSaver.Monterey"
+ "com.apple.ScreenSaver.Ventura"
+ "com.apple.ScreenSaver.iLife-Slideshow-Extension"
+ "com.apple.ScreenTime.ScreenTimeWebExtension"
+ "com.apple.ScreenTimeViewService"
+ "com.apple.Shell"
+ "com.apple.TextInputUI.xpc.CursorUIViewService"
+ "com.apple.Translation.TranslationAPIExtension"
+ "com.apple.Translation.TranslationAPISupportExtension"
+ "com.apple.TranslationUIServices.TranslationUIService"
+ "com.apple.WebKit."
+ "com.apple.WordOfTheDay"
+ "com.apple.WorkflowUI.FocusConfigurationXPCServiceMac"
+ "com.apple.appkit.xpc.LegacyExternalColorPickerService.arm64"
+ "com.apple.appkit.xpc.LegacyExternalColorPickerService.x86_64"
+ "com.apple.appkit.xpc.ThemeWidgetControlViewService"
+ "com.apple.audio.AUHostingService.arm64e"
+ "com.apple.audio.AUHostingService.x86-64"
+ "com.apple.developer.assistive-technology"
+ "com.apple.developer.backup-utility"
+ "com.apple.freeform.USDRendererExtension"
+ "com.apple.gamecenter.GameCenterUIService"
+ "com.apple.helpviewer.HelpViewer-Quicklook"
+ "com.apple.inputmethod.ChineseHandwriting"
+ "com.apple.inputmethod.EmojiFunctionRowItem"
+ "com.apple.inputmethod.Korean"
+ "com.apple.inputmethod.Kotoeri.KanaTyping"
+ "com.apple.inputmethod.Kotoeri.RomajiTyping"
+ "com.apple.inputmethod.SCIM"
+ "com.apple.inputmethod.TCIM"
+ "com.apple.inputmethod.TYIM"
+ "com.apple.inputmethod.TransliterationIM"
+ "com.apple.inputmethod.VietnameseIM"
+ "com.apple.mail.MailQuickLookExtension"
+ "com.apple.mapkit.private.RemoteUI"
+ "com.apple.osanalytics.IPSExtension"
+ "com.apple.private.tcc.mobileasset.check"
+ "com.apple.quicklook.QuickLookUIService"
+ "com.apple.reminders.quicklookextension"
+ "com.apple.replayKit.RPBroadcastActivityExtension-macOS"
+ "com.apple.replayKit.RPVideoEditorExtension-macOS"
+ "com.apple.screensaver.AlbumArtwork"
+ "com.apple.shortcuts.QuickLookExtension"
+ "com.apple.sidecar.DisplayMarkup"
+ "com.apple.speech.VoiceControlUIService"
+ "com.apple.springboard.SBRendererService"
+ "com.apple.tccd.session-time.expiry"
+ "com.apple.tips.TipsQuicklook"
+ "com.apple.xpc.TypographyPanelService"
+ "composedServiceCodeRequirementMismatch"
+ "configurationEndingAtLocalSecondsOfDay:"
+ "configurationWithDurationSeconds:"
+ "contentsWithData:source:"
+ "copyFineGrainedAuthRecordForSchemaTypeTextIDAndSessionWithService:record:list:"
+ "currentContents"
+ "dataWithLength:"
+ "decomposedStringWithCanonicalMapping"
+ "defaultExpiredAuth"
+ "demoteAllExpiredSessions"
+ "demoteSessionTimeRecord:to:"
+ "demoting all expired sessions"
+ "doUpdateOfTargetVerifierData"
+ "evaluateAccessToService:defaultAccessAllowed:by:checkCodeRequirements:authorizationResult:authorizationReason:flags:subjectCodeIdentityDataResult:subjectRequirementMismatch:"
+ "evaluateComposedAuthorizationToService:context:andAccessSubject:indirectObject:withRelation:authorizationResult:authorizationReason:subjectCodeIdentityDataResult:"
+ "evaluateFineGrainedAccessWithContext:authorizationResult:authorizationReason:"
+ "expiryForSessionSetAt:"
+ "fineGrainedSessionExpiry"
+ "fineGrainedSessionVersion"
+ "fineGrainedStatusWithService:subjectIdentity:right:status:"
+ "fineGrainedTableExists:forService:"
+ "fineGrainedTargetCSReq"
+ "fine_grained_session_boot_uuid"
+ "fine_grained_session_expiry"
+ "fine_grained_session_version"
+ "fine_grained_target_csreq"
+ "getFineGrainedAuthResultForSchemaTypeTextIDAndSessionWithContext:result:"
+ "getFineGrainedStatusWithComposedService:subjectIdentity:right:status:"
+ "handleSessionExpiryForRecord:"
+ "handle_TCCAccessCheckAppInMobileAssetList"
+ "handle_TCCAccessCheckAppInMobileAssetList_with_attribution_chain"
+ "handle_TCCAccessGetFineGrainedStatus"
+ "highestAcceptedListVersion"
+ "holds"
+ "holds (Apple's own code)"
+ "i32@0:8^B16@24"
+ "i48@0:8@16@24Q32^{?=BBBQ@@}40"
+ "identifier \"%@\" and anchor apple generic and certificate 1[field.1.2.840.113635.100.6.2.6] exists and certificate leaf[field.1.2.840.113635.100.6.1.13] exists and certificate leaf[subject.OU] = \"%@\""
+ "identifier \"%@\" and anchor apple generic and certificate leaf[field.1.2.840.113635.100.6.1.9] exists"
+ "identifierType"
+ "indexesOfEntriesForService:identifier:listType:"
+ "indirect_object_audit_token"
+ "indirect_object_bundle_path"
+ "indirect_object_target_app_attribution_method"
+ "initSessionTimeRecordWithService:category:categoryType:client:clientType:authorizationValue:sessionExpiry:sessionVersion:"
+ "initWithAccessingProcess:requestingProcess:evaluateResponsibility:"
+ "initWithService:subjectIdentity:indirectObject:attributionChain:"
+ "initWithUnattributedProcess:requestingProcess:"
+ "initWithUpdateDirectory:builtInPath:"
+ "initWithUpdateDirectory:builtInPath:requiredOwner:"
+ "installUpdateWithData:error:"
+ "invertedSet"
+ "isEligibleForFullSheetATTAllowedForBundleID:"
+ "isExpired:now:"
+ "kTCCServiceAccessibilityPerTarget"
+ "kTCCServiceListenEventPerTarget"
+ "kTCCServicePostEventPerTarget"
+ "keepMainRowWithEmptyIndirectObjectList"
+ "listVersion"
+ "loadAtStartup"
+ "loadIfNeeded"
+ "lowFrictionEntitlements"
+ "mdm_pppcGrantIsNonModifiable"
+ "mobile asset list (%{public}@): %lu bytes, over the %lu byte limit; not used"
+ "mobile asset list (%{public}@): FormatVersion %ld is not %ld; not used"
+ "mobile asset list (%{public}@): no ListVersion; not used"
+ "mobile asset list (%{public}@): no Lists dictionary; not used"
+ "mobile asset list (%{public}@): not a property list dictionary: %{public}@"
+ "mobile asset list (%{public}@): skipped %lu entries that are not valid"
+ "mobile asset list: %{public}@ grew over the %lu byte limit while being read; not used"
+ "mobile asset list: %{public}@ has ListVersion %ld, lower than %ld already accepted; not used"
+ "mobile asset list: %{public}@ is %lld bytes, over the %lu byte limit; not opened"
+ "mobile asset list: %{public}@ is not a regular file"
+ "mobile asset list: %{public}@ is not owned by uid %d, or others can write it (uid %d, mode %o)"
+ "mobile asset list: %{public}@ was replaced after its properties were checked; not read"
+ "mobile asset list: cannot get the properties of %{public}@: %{darwin.errno}d"
+ "mobile asset list: cannot get the properties of the recorded ListVersion at %{public}@: %{darwin.errno}d"
+ "mobile asset list: cannot open %{public}@: %{darwin.errno}d"
+ "mobile asset list: cannot read %{public}@: %{darwin.errno}d"
+ "mobile asset list: cannot record ListVersion %ld: %{darwin.errno}d"
+ "mobile asset list: loaded at startup; built in %ld, highest accepted %ld%{public}s"
+ "mobile asset list: no usable built-in list at %{public}@"
+ "mobile asset list: the recorded ListVersion at %{public}@ cannot be used; %{public}@ (ListVersion %ld) not used, only the built-in list"
+ "mobile asset list: the recorded ListVersion at %{public}@ is there but cannot be used (%{public}s); no update is used and it is not overwritten until it can be read"
+ "mobile asset list: using ListVersion %ld from %{public}@ (built in: %ld)"
+ "mobileasset_list_type"
+ "mutableBytes"
+ "no code"
+ "no list given"
+ "no positive ListVersion"
+ "no running code"
+ "not Apple anchored"
+ "not Apple anchored as it runs"
+ "not a list with FormatVersion %ld and a ListVersion"
+ "not attributed"
+ "not readable or not trusted"
+ "notifyUserOfDeniedAccessTo: for  %{public}@ fails when requestor has UID 0"
+ "notifyUserOfDeniedAccessTo:forService:indirectObject:"
+ "null"
+ "only the system tccd of an internal build manages the mobile asset list"
+ "pathForResource:ofType:"
+ "plist"
+ "process:holdsLowFrictionEntitlementForService:"
+ "q24@0:8^q16"
+ "q24@0:8q16"
+ "rangeOfCharacterFromSet:"
+ "readHighestAcceptedVersion:"
+ "recordsListVersions"
+ "removeUpdateWithError:"
+ "requirementStringForEntry:"
+ "requirementsForService:listType:"
+ "runningCode:isListedForService:listType:"
+ "scheduleSessionExpiryCheckForRecord:"
+ "scheduleSessionExpiryCheckForRecord:afterSeconds:"
+ "sessionExpiry"
+ "sessionTimeConfig"
+ "sessionTimeRecordsForService:rows:"
+ "sessionVersion"
+ "session_expiry"
+ "setAttributesTargetApp:"
+ "setCategory:"
+ "setCategoryType:"
+ "setClient:"
+ "setClientType:"
+ "setComposedServiceCodeRequirementMismatch:"
+ "setDefaultExpiredAuth:"
+ "setDoUpdateOfTargetVerifierData:"
+ "setFineGrainedAuthRecordForSchemaTypeTextIDAndSessionWithAccessRecord:"
+ "setFineGrainedAuthRecordForSchemaTypeTextIDAndSessionWithContext:result:"
+ "setFineGrainedSessionExpiry:"
+ "setFineGrainedSessionVersion:"
+ "setFineGrainedTargetCSReq:"
+ "setKeepMainRowWithEmptyIndirectObjectList:"
+ "setLength:"
+ "setLowFrictionEntitlements:"
+ "setMdm_pppcGrantIsNonModifiable:"
+ "setRecordsListVersions:"
+ "setSessionExpiry:"
+ "setSessionTimeConfig:"
+ "setSessionTimeConfigForTesting:"
+ "setSessionVersion:"
+ "setSharedListForTesting:"
+ "setTargetIdentity:"
+ "setTargetIdentityAttributed:"
+ "sharedList"
+ "source"
+ "stateDescription"
+ "supportsSessionTime"
+ "targetAppForAuditToken:requestingProcess:service:error:"
+ "targetIdentity"
+ "targetIdentityAttributed"
+ "targets"
+ "the recorded ListVersion at %@ is there but cannot be used, so the floor is unknown; fix or remove it first"
+ "to install"
+ "unknown mobile asset list operation"
+ "update"
+ "v32@0:8@16q24"
+ "v32@?0@8@16^B24"
+ "wallClockSeconds"
+ "writeData:toPath:error:"
+ "writeHighestAcceptedVersion:"
+ "{os_unfair_recursive_lock_s=\"_os_unfair_recursive_lock_opaque\"[2I]}"
+ "|"
+ "\xf0\xf0\xf0\xf01\xf0\x83"
- "-[TCCDPlatformMacOS notifyUserOfDeniedAccessBy:forService:]_block_invoke"
- "-[TCCDServer evaluateComposedAuthorizationToService:andAccessSubject:withRelation:authorizationResult:authorizationReason:subjectCodeIdentityDataResult:]"
- "B64@0:8@16@24q32^Q40^Q48^@56"
- "TB,R,V_isEligibleForFullSheetATTAllowed"
- "UPDATE managed_overrides SET   admin_auth_value = ?,   auth_value = CASE WHEN auth_reason IN (?, ?) THEN auth_value ELSE ? END,   auth_reason = ?,   flags = ((flags | ?) & ~?),   last_modified = CAST(strftime('%s','now') AS INTEGER) WHERE service = ? AND client = ? AND client_type = ?"
- "UPDATE managed_overrides SET auth_value = CASE WHEN admin_auth_value >= ? THEN ? ELSE ? END, auth_reason = ?, flags = 0, last_modified = CAST(strftime('%s','now') AS INTEGER)"
- "_isEligibleForFullSheetATTAllowed"
- "evaluateComposedAuthorizationToService:andAccessSubject:withRelation:authorizationResult:authorizationReason:subjectCodeIdentityDataResult:"
- "isEligibleForFullSheetATTAllowed"
- "notifyUserOfDeniedAccessBy: for  %{public}@ fails when requestor has UID 0"
- "notifyUserOfDeniedAccessBy:forService:"
- "{os_unfair_recursive_lock_s=\"ourl_lock\"{os_unfair_lock_s=\"_os_unfair_lock_opaque\"I}\"ourl_count\"I}"
- "\xf0\xf0\xf0\xf01\xf0c"
```
