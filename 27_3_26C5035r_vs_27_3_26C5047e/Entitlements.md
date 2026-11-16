## 🔑 Entitlements

### filesystem

### Calendar

> `/System/Applications/Calendar.app/Contents/MacOS/Calendar`

```diff

 	<key>com.apple.security.exception.shared-preference.read-only</key>
 	<array>
 		<string>com.apple.assistant.backedup</string>
+		<string>com.apple.assistant.public</string>
 		<string>com.apple.tokengeneration</string>
 		<string>com.apple.applicationaccess</string>
 	</array>

 	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
 	<array>
 		<string>com.apple.assistant.backedup</string>
+		<string>com.apple.assistant.public</string>
 		<string>com.apple.icloud.managed</string>
 		<string>com.apple.UnifiedAssetFramework</string>
 		<string>com.apple.modelcatalog.ajax</string>

```
### Home

> `/System/Applications/Home.app/Contents/MacOS/Home`

```diff

 	<true/>
 	<key>com.apple.frontboardservices.display-layout-monitor</key>
 	<true/>
+	<key>com.apple.generativeexperiences.availabilityService</key>
+	<true/>
+	<key>com.apple.generativeexperiences.availabilityService.waitlistStatus</key>
+	<true/>
 	<key>com.apple.homekit.private-spi-access</key>
 	<true/>
 	<key>com.apple.intelligentrouting.recommendationservice</key>

 		<string>com.apple.findmy.findmylocate.locationservice</string>
 		<string>com.apple.findmy.findmylocate.settings</string>
 		<string>com.apple.frontboard.systemappservices</string>
+		<string>com.apple.generativeexperiences.availabilityService</string>
 		<string>com.apple.homeenergyd.xpc</string>
 		<string>com.apple.identityservicesd.embedded.auth</string>
 		<string>com.apple.ind.cloudfeatures</string>

 		<string>com.apple.security.octagon</string>
 		<string>com.apple.seeding.client</string>
 		<string>com.apple.siri.VoiceShortcuts.xpc</string>
+		<string>com.apple.siri.ssrvtuitrainingservice.xpc</string>
 		<string>com.apple.siri.uaf.service</string>
 		<string>com.apple.siri.uaf.subscription.service</string>
 		<string>com.apple.symptom_analytics</string>

 		<string>com.apple.findmy.findmylocate.locationservice</string>
 		<string>com.apple.findmy.findmylocate.settings</string>
 		<string>com.apple.frontboard.systemappservices</string>
+		<string>com.apple.generativeexperiences.availabilityService</string>
 		<string>com.apple.homeenergyd.xpc</string>
 		<string>com.apple.identityservicesd.embedded.auth</string>
 		<string>com.apple.ind.cloudfeatures</string>

 		<string>com.apple.security.octagon</string>
 		<string>com.apple.seeding.client</string>
 		<string>com.apple.siri.VoiceShortcuts.xpc</string>
+		<string>com.apple.siri.ssrvtuitrainingservice.xpc</string>
 		<string>com.apple.siri.uaf.service</string>
 		<string>com.apple.siri.uaf.subscription.service</string>
 		<string>com.apple.symptom_analytics</string>

```
### GenerativePlaygroundAppIntents

> `/System/Applications/Image Playground.app/Contents/Extensions/GenerativePlaygroundAppIntents.appex/Contents/MacOS/GenerativePlaygroundAppIntents`

```diff

 	<true/>
 	<key>com.apple.photos.bourgeoisie</key>
 	<true/>
+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>
 	<key>com.apple.private.appintents-attribution-override</key>
 	<true/>
 	<key>com.apple.private.appintents.extend-timeout-on-progress-updates</key>

 	<true/>
 	<key>com.apple.private.hid.client.event-dispatch.internal</key>
 	<true/>
+	<key>com.apple.private.ind.client</key>
+	<true/>
 	<key>com.apple.private.intelligenceplatform.use-cases</key>
 	<dict>
 		<key>GeneratedImageImageGeneration</key>

 		<string>kTCCServicePhotos</string>
 		<string>kTCCServiceAddressBook</string>
 	</array>
+	<key>com.apple.privatecloudcompute.knownRateLimits</key>
+	<true/>
+	<key>com.apple.privatecloudcompute.usage</key>
+	<true/>
 	<key>com.apple.rootless.storage.shortcuts</key>
 	<true/>
 	<key>com.apple.security.app-sandbox</key>

 	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.ind.xpc</string>
+		<string>com.apple.privatecloudcompute</string>
 		<string>com.apple.photos.ImageConversionService</string>
 		<string>com.apple.assistant.cdm</string>
 		<string>com.apple.modelmanager</string>

 	</array>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.ind.xpc</string>
+		<string>com.apple.privatecloudcompute</string>
 		<string>com.apple.assistant.cdm</string>
 		<string>com.apple.modelmanager</string>
 		<string>com.apple.modelcatalog.catalog</string>

```
### Image Playground

> `/System/Applications/Image Playground.app/Contents/MacOS/Image Playground`

```diff

 	<true/>
 	<key>com.apple.posterboardui.externalEditing</key>
 	<true/>
+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>
 	<key>com.apple.private.appintents.extend-timeout-on-progress-updates</key>
 	<true/>
 	<key>com.apple.private.applemediaservices</key>

 	<true/>
 	<key>com.apple.private.hid.client.event-dispatch.internal</key>
 	<true/>
+	<key>com.apple.private.ind.client</key>
+	<true/>
 	<key>com.apple.private.intelligenceplatform.use-cases</key>
 	<dict>
 		<key>GeneratedImageImageGeneration</key>

 	</array>
 	<key>com.apple.privatecloudcompute.knownRateLimits</key>
 	<true/>
+	<key>com.apple.privatecloudcompute.usage</key>
+	<true/>
 	<key>com.apple.rootless.storage.shortcuts</key>
 	<true/>
 	<key>com.apple.runningboard.posterkit.host</key>

 	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.ind.xpc</string>
 		<string>com.apple.privatecloudcompute</string>
 		<string>com.apple.stickers.recency</string>
 		<string>com.apple.photos.ImageConversionService</string>

 	</array>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.AppleMediaServicesUIDynamicService</string>
+		<string>com.apple.ind.xpc</string>
 		<string>com.apple.privatecloudcompute</string>
 		<string>com.apple.stickers.api</string>
 		<string>com.apple.assistant.cdm</string>

```
### Messages

> `/System/Applications/Messages.app/Contents/MacOS/Messages`

```diff

 	<true/>
 	<key>com.apple.private.managed-settings.effective-read</key>
 	<true/>
+	<key>com.apple.private.mediaexperience.personallyidentifiableinformation.allow</key>
+	<true/>
+	<key>com.apple.private.network.socket-delegate</key>
+	<true/>
 	<key>com.apple.private.photos.service.internal.cloud</key>
 	<true/>
 	<key>com.apple.private.pluginkit.manager</key>

```
### Photos

> `/System/Applications/Photos.app/Contents/MacOS/Photos`

```diff

 	</array>
 	<key>com.apple.privatecloudcompute.knownRateLimits</key>
 	<true/>
+	<key>com.apple.privatecloudcompute.usage</key>
+	<true/>
 	<key>com.apple.proactive.eventtracker</key>
 	<true/>
 	<key>com.apple.rootless.storage.remotemanagementd</key>
 	<true/>
+	<key>com.apple.rootless.storage.shortcuts</key>
+	<true/>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
 	<key>com.apple.security.application-groups</key>

 		<string>/Library/UnifiedAssetFramework/</string>
 		<string>/Library/com.apple.modelcatalog/sideload/</string>
 	</array>
+	<key>com.apple.security.temporary-exception.files.home-relative-path.read-write</key>
+	<array>
+		<string>/Library/Shortcuts/</string>
+	</array>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.ind.xpc</string>
+		<string>com.apple.AppleMediaServicesUIDynamicService</string>
 		<string>com.apple.privatecloudcompute</string>
 		<string>com.apple.photos.service</string>
 		<string>com.apple.ScreenTimeSettingsAgent.private</string>

 		<string>com.apple.photos.shareddefaults</string>
 		<string>com.apple.communicationSafetySettings</string>
 	</array>
+	<key>com.apple.shortcuts.stepwise-execution</key>
+	<true/>
+	<key>com.apple.shortcuts.variable-injection</key>
+	<true/>
+	<key>com.apple.siri.VoiceShortcuts.xpc</key>
+	<true/>
 	<key>com.apple.spotlight.photos.entitledattributes</key>
 	<true/>
 	<key>com.apple.symptoms.NetworkOfInterest</key>

```
### PhotosReliveWidget

> `/System/Applications/Photos.app/Contents/PlugIns/PhotosReliveWidget.appex/Contents/MacOS/PhotosReliveWidget`

```diff

 	<true/>
 	<key>com.apple.private.accounts.allaccounts</key>
 	<true/>
+	<key>com.apple.private.managed-settings.effective-read</key>
+	<true/>
 	<key>com.apple.private.photoanalysisd.access</key>
 	<true/>
 	<key>com.apple.private.photos.allowcollectionshare</key>

 	<array>
 		<string>kTCCServiceAddressBook</string>
 	</array>
+	<key>com.apple.rootless.storage.remotemanagementd</key>
+	<true/>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
+	<key>com.apple.security.personal-information.addressbook</key>
+	<true/>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.photoanalysisd</string>
 		<string>com.apple.chronoservices</string>
+		<string>com.apple.ManagedSettingsAgent</string>
+		<string>com.apple.ManagedSettingsAgent.publisher</string>
 	</array>
 	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
 	<array>

```
### Reminders

> `/System/Applications/Reminders.app/Contents/MacOS/Reminders`

```diff

 		<string>com.apple.suggestions</string>
 		<string>com.apple.EmojiPreferences</string>
 		<string>com.apple.assistant.backedup</string>
+		<string>com.apple.assistant.public</string>
 	</array>
 	<key>com.apple.security.temporary-exception.shared-preference.read-write</key>
 	<array>

```
### Shortcuts

> `/System/Applications/Shortcuts.app/Contents/MacOS/Shortcuts`

```diff

 		<key>com.apple.private.appleevents.allowed.aevt.quit</key>
 		<true/>
 	</dict>
+	<key>com.apple.private.applemediaservices</key>
+	<true/>
 	<key>com.apple.private.assets.accessible-asset-types</key>
 	<array>
 		<string>com.apple.MobileAsset.UAF.FM.GenerativeModels</string>

 	<true/>
 	<key>com.apple.private.homekit</key>
 	<true/>
+	<key>com.apple.private.ind.client</key>
+	<true/>
 	<key>com.apple.private.intelligenceplatform.use-cases</key>
 	<dict>
 		<key>DataActionsUsecase</key>

 	<true/>
 	<key>com.apple.privatecloudcompute.knownRateLimits</key>
 	<true/>
+	<key>com.apple.privatecloudcompute.usage</key>
+	<true/>
 	<key>com.apple.proactive.ProactiveSuggestionClientModel.xpc</key>
 	<true/>
 	<key>com.apple.proactiveagentplatform.orchestrator</key>

 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.AppSSO.service-xpc</string>
+		<string>com.apple.AppleMediaServicesUIDynamicService</string>
 		<string>com.apple.BTServer.le</string>
 		<string>com.apple.Maps.MapsSync.cache</string>
 		<string>com.apple.Maps.MapsSync.store</string>

 		<string>com.apple.generativeexperiences.generativeexperiencessession</string>
 		<string>com.apple.generativesearch.server.search</string>
 		<string>com.apple.homed.xpc</string>
+		<string>com.apple.ind.xpc</string>
 		<string>com.apple.intelligenceplatform.InternalBiome</string>
 		<string>com.apple.intelligenceplatform.KnowledgeConstruction</string>
 		<string>com.apple.intelligenceplatform.View</string>

 		<string>com.apple.SpeakSelection</string>
 		<string>com.apple.TimeMachine</string>
 		<string>com.apple.UnifiedAssetFramework</string>
+		<string>com.apple.cloud.quota</string>
 		<string>com.apple.generativesearch</string>
 		<string>com.apple.gms.availability</string>
 		<string>com.apple.modelcatalog.ajax</string>

```
### Siri AI

> `/System/Applications/Siri AI.app/Contents/MacOS/Siri AI`

```diff

 	</array>
 	<key>com.apple.intelligenceflow.querydecoration</key>
 	<true/>
+	<key>com.apple.intelligenceflow.quota</key>
+	<true/>
 	<key>com.apple.intelligenceflow.toolbox</key>
 	<true/>
 	<key>com.apple.intelligenceflow.transcript-entity-querying</key>

 		<string>com.apple.internal.SpotlightAutomationTester</string>
 		<string>com.apple.intelligenceflow.context</string>
 		<string>com.apple.intelligenceflow.contextTool</string>
+		<string>com.apple.intelligenceflow.quota</string>
 		<string>com.apple.intelligenceflow.uiContext</string>
 		<string>com.apple.siri.VoiceShortcuts.xpc</string>
 		<string>com.apple.MediaGroups.daemon</string>

```
### AirPlay Receiver

> `/System/Library/CoreServices/AirPlay Receiver.app/Contents/MacOS/AirPlay Receiver`

```diff

 	<true/>
 	<key>com.apple.private.screencapturekit.suppress-screen-indicator</key>
 	<true/>
+	<key>com.apple.private.sessionkit.sessionRequest</key>
+	<true/>
 	<key>com.apple.private.tcc.allow</key>
 	<array>
 		<string>kTCCServiceScreenCapture</string>

 		<string>com.apple.private.corewifi-xpc</string>
 		<string>com.apple.wifip2pd</string>
 		<string>com.apple.videoconference.camera</string>
+		<string>com.apple.sessionservices</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-only</key>
 	<array>

```

### 🆕 AirPlayReceiverWidgetExtension

> `/System/Library/CoreServices/AirPlay Receiver.app/Contents/PlugIns/AirPlayReceiverWidgetExtension.appex/Contents/MacOS/AirPlayReceiverWidgetExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.security.app-sandbox</key>
	<true/>
</dict>
</plist>

```
### ScreenSharingLiveActivityAgent

> `/System/Library/CoreServices/RemoteManagement/ScreenSharingLiveActivityAgent.app/Contents/MacOS/ScreenSharingLiveActivityAgent`

```diff

 	<true/>
 	<key>com.apple.private.contactsui</key>
 	<true/>
+	<key>com.apple.private.menubar.disable-user-hiding</key>
+	<true/>
 	<key>com.apple.private.sessionkit.bypassAuthorizationUI</key>
 	<true/>
 	<key>com.apple.private.sessionkit.custom-platter-target</key>

```
### Setup Assistant

> `/System/Library/CoreServices/Setup Assistant.app/Contents/MacOS/Setup Assistant`

```diff

 	<true/>
 	<key>com.apple.generativeexperiences.availabilityService</key>
 	<true/>
+	<key>com.apple.generativeexperiences.availabilityService.waitlistStatus</key>
+	<true/>
 	<key>com.apple.icloud.findmydeviced.access</key>
 	<true/>
 	<key>com.apple.keystore.device.smart-card</key>

 	<true/>
 	<key>com.apple.private.coreservices.lsuseractivityd.LSAlwaysPick</key>
 	<true/>
+	<key>com.apple.private.corespeech.uitrainingservice</key>
+	<true/>
 	<key>com.apple.private.corespeech.xpc.remote</key>
 	<true/>
 	<key>com.apple.private.findmymacd.spi</key>

 	<true/>
 	<key>com.apple.private.intelligenceplatform.use-cases</key>
 	<dict>
+		<key>AppleIntelligenceReporting</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>AppleIntelligence.Reporting.Buddy</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+			</dict>
+		</dict>
 		<key>ProactiveAppPrediction</key>
 		<dict>
 			<key>Streams</key>

 		<string>com.apple.system.opendirectoryd.api</string>
 		<string>com.apple.usernoted.prefs</string>
 		<string>com.apple.ScreenTimeSettingsAgent.private</string>
+		<string>com.apple.generativeexperiences.availabilityService</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-only</key>
 	<array>
 		<string>com.apple.applicationaccess</string>
+		<string>com.apple.assistant</string>
+		<string>com.apple.gms.availability</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-write</key>
 	<array>

```
### MiniLauncher

> `/System/Library/CoreServices/Setup Assistant.app/Contents/SharedSupport/MiniLauncher`

```diff

 		<string>com.apple.usernoted.prefs</string>
 		<string>com.apple.AuthenticationServices.AuthenticationServicesAgent.FileVaultRecoveryKeys</string>
 	</array>
+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.assistant</string>
+	</array>
 	<key>com.apple.security.exception.shared-preference.read-write</key>
 	<array>
 		<string>com.apple.usernotificationskit</string>

```
### WiFiAgent

> `/System/Library/CoreServices/WiFiAgent.app/Contents/MacOS/WiFiAgent`

```diff

 	<true/>
 	<key>com.apple.private.security.storage.wifi</key>
 	<true/>
+	<key>com.apple.private.sharing.hotspot</key>
+	<true/>
 	<key>com.apple.private.system-keychain</key>
 	<true/>
 	<key>com.apple.private.ubiquity-kvstore-access</key>

```
### screencaptureui

> `/System/Library/CoreServices/screencaptureui.app/Contents/MacOS/screencaptureui`

```diff

 	<array>
 		<string>kTCCServiceCamera</string>
 		<string>kTCCServiceMicrophone</string>
-		<string>kTCCServiceCalendar</string>
 		<string>kTCCServiceAddressBook</string>
 	</array>
 	<key>com.apple.private.windowmanager</key>

 	<true/>
 	<key>com.apple.security.personal-information.addressbook</key>
 	<true/>
-	<key>com.apple.security.personal-information.calendars</key>
-	<true/>
 	<key>com.apple.security.temporary-exception.files.home-relative-path.read-only</key>
 	<string>/Library/Containers/com.apple.Preview/Data/Library/Preferences/com.apple.Preview.signatures.plist</string>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.appstoreagent.xpc</string>
 		<string>com.apple.visualintelligence.visual-action-prediction</string>
-		<string>com.apple.CalendarAgent</string>
-		<string>com.apple.calaccessd</string>
 		<string>com.apple.contactsd</string>
 		<string>com.apple.generativeexperiences.agentMediaStore</string>
 		<string>com.apple.generativeexperiences.ExternalProviderService</string>

```
### AppleIDSettings

> `/System/Library/ExtensionKit/Extensions/AppleIDSettings.appex/Contents/MacOS/AppleIDSettings`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>AvpFairPlayUserClient.access</key>
+	<true/>
 	<key>adi-client</key>
 	<string>4127693656</string>
 	<key>com.apple.SystemConfiguration.SCPreferences-write-access</key>

 	<array>
 		<string>com.apple.applicationaccess</string>
 		<string>com.apple.assistant.backedup</string>
+		<string>com.apple.assistant.public</string>
 	</array>
 	<key>com.apple.security.files.user-selected.read-write</key>
 	<true/>
+	<key>com.apple.security.iokit-user-client-class</key>
+	<array>
+		<string>AvpFairPlayUserClient</string>
+	</array>
 	<key>com.apple.security.network.client</key>
 	<true/>
 	<key>com.apple.security.personal-information.addressbook</key>

 		<string>familycircled</string>
 		<string>com.apple.cloud.quota</string>
 		<string>com.apple.assistant.backedup</string>
+		<string>com.apple.assistant.public</string>
 		<string>com.apple.GenerativeModels.AgentSessionKit</string>
 	</array>
 	<key>com.apple.security.temporary-exception.shared-preference.read-write</key>

```
### BlackPowderInferenceExtension

> `/System/Library/ExtensionKit/Extensions/BlackPowderInferenceExtension.appex/Contents/MacOS/BlackPowderInferenceExtension`

```diff

 	<key>keychain-access-groups</key>
 	<array>
 		<string>com.apple.openai</string>
+		<string>com.apple.snowflake</string>
 		<string>com.apple.openai.xcode</string>
 	</array>
 </dict>

```
### CalUIRemoteUIExtension

> `/System/Library/ExtensionKit/Extensions/CalUIRemoteUIExtension.appex/Contents/MacOS/CalUIRemoteUIExtension`

```diff

 <dict>
 	<key>application-identifier</key>
 	<string>com.apple.calendar.CalUIRemoteUIExtension</string>
+	<key>com.apple.private.attribution.implicitly-assumed-identity</key>
+	<dict>
+		<key>type</key>
+		<string>bundleID</string>
+		<key>value</key>
+		<string>com.apple.iCal</string>
+	</dict>
+	<key>com.apple.private.calendar.eventkitui-remoteui-extension</key>
+	<true/>
 	<key>com.apple.private.tcc.allow</key>
+	<array>
+		<string>kTCCServiceAddressBook</string>
+		<string>kTCCServiceCalendar</string>
+	</array>
+	<key>com.apple.private.tcc.manager.check-by-audit-token</key>
 	<array>
 		<string>kTCCServiceCalendar</string>
 	</array>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
+	<key>com.apple.security.personal-information.addressbook</key>
+	<true/>
 	<key>com.apple.security.personal-information.calendars</key>
 	<true/>
+	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.cmfsyncagent.auth</string>
+		<string>com.apple.communicationtrustd.service</string>
+		<string>com.apple.coreduetd.knowledge</string>
+		<string>com.apple.coreduetd.people.user</string>
+	</array>
 </dict>
 </plist>
 

```
### FedStatsPluginDynamic

> `/System/Library/ExtensionKit/Extensions/FedStatsPluginDynamic.appex/Contents/MacOS/FedStatsPluginDynamic`

```diff

 				</dict>
 			</dict>
 		</dict>
+		<key>Safari-Auto-Dark-Mode</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>Safari.AutoDarkMode</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>
 		<key>Safari-Pop-ups</key>
 		<dict>
 			<key>Streams</key>

```
### FedStatsPluginStatic

> `/System/Library/ExtensionKit/Extensions/FedStatsPluginStatic.appex/Contents/MacOS/FedStatsPluginStatic`

```diff

 				</dict>
 			</dict>
 		</dict>
+		<key>Safari-Auto-Dark-Mode</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>Safari.AutoDarkMode</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>
 		<key>Safari-Pop-ups</key>
 		<dict>
 			<key>Streams</key>

```
### GPUIExtension

> `/System/Library/ExtensionKit/Extensions/GPUIExtension.appex/Contents/MacOS/GPUIExtension`

```diff

 	<true/>
 	<key>com.apple.photos.bourgeoisie</key>
 	<true/>
+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>
 	<key>com.apple.private.appintents.extend-timeout-on-progress-updates</key>
 	<true/>
 	<key>com.apple.private.applemediaservices</key>

 	<true/>
 	<key>com.apple.private.feedback.drafting</key>
 	<true/>
+	<key>com.apple.private.ind.client</key>
+	<true/>
 	<key>com.apple.private.intelligenceplatform.use-cases</key>
 	<dict>
 		<key>GeneratedImageImageGeneration</key>

 	</array>
 	<key>com.apple.privatecloudcompute.knownRateLimits</key>
 	<true/>
+	<key>com.apple.privatecloudcompute.usage</key>
+	<true/>
 	<key>com.apple.rootless.storage.shortcuts</key>
 	<true/>
 	<key>com.apple.security.app-sandbox</key>

 	</array>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.AppleMediaServicesUIDynamicService</string>
+		<string>com.apple.ind.xpc</string>
 		<string>com.apple.privatecloudcompute</string>
 		<string>com.apple.photos.ImageConversionService</string>
 		<string>com.apple.assistant.cdm</string>

```
### GenerativeAssistantExtension

> `/System/Library/ExtensionKit/Extensions/GenerativeAssistantExtension.appex/Contents/MacOS/GenerativeAssistantExtension`

```diff

 	<array>
 		<string>apple</string>
 		<string>com.apple.openai</string>
+		<string>com.apple.snowflake</string>
 	</array>
 	<key>platform-application</key>
 	<true/>

```
### MapsIntents

> `/System/Library/ExtensionKit/Extensions/MapsIntents.appex/Contents/MacOS/MapsIntents`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.Maps</string>
 	<key>com.apple.locationd.dynamic_accuracy_reduction</key>
 	<true/>
 	<key>com.apple.locationd.effective_bundle</key>

 	<true/>
 	<key>com.apple.private.appintents.attribution.bundle-identifier</key>
 	<string>com.apple.Maps</string>
+	<key>com.apple.private.security.restricted-application-groups</key>
+	<array>
+		<string>group.com.apple.Maps</string>
+	</array>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.Maps</string>
+	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.Maps.MapsSync.store</string>
 		<string>com.apple.Maps.MapsSync.service</string>
+		<string>com.apple.Maps.MapsSync.cache</string>
 	</array>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.Maps.MapsSync.store</string>
 		<string>com.apple.Maps.MapsSync.service</string>
+		<string>com.apple.Maps.MapsSync.cache</string>
 	</array>
 </dict>
 </plist>

```

### 🆕 MarkdownThumbnailExtension

> `/System/Library/ExtensionKit/Extensions/MarkdownThumbnailExtension.appex/Contents/MacOS/MarkdownThumbnailExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.developer.hardened-process</key>
	<true/>
	<key>com.apple.private.extension-sandbox-profile</key>
	<string>quicklook-thumbnail-secure</string>
	<key>com.apple.private.security.message-filter</key>
	<true/>
	<key>com.apple.security.script-restrictions</key>
	<true/>
</dict>
</plist>

```
### Network

> `/System/Library/ExtensionKit/Extensions/Network.appex/Contents/MacOS/Network`

```diff

 	<true/>
 	<key>com.apple.private.appfirewallclient</key>
 	<true/>
+	<key>com.apple.private.networkextension.configuration</key>
+	<true/>
 	<key>com.apple.private.networkserviceproxy</key>
 	<true/>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.ALF.ApplicationFirewall.message</string>
+		<string>com.apple.nehelper</string>
 	</array>
 	<key>com.apple.wifi.associate</key>
 	<true/>

```
### ScreenTimePreferencesExtension

> `/System/Library/ExtensionKit/Extensions/ScreenTimePreferencesExtension.appex/Contents/MacOS/ScreenTimePreferencesExtension`

```diff

 	<array>
 		<string>group.com.apple.DeviceActivity</string>
 	</array>
+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>
 	<key>com.apple.private.suggestions.contacts</key>
 	<true/>
 	<key>com.apple.private.tcc.allow</key>

 	<true/>
 	<key>com.apple.security.personal-information.addressbook</key>
 	<true/>
+	<key>com.apple.security.temporary-exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/db/os_eligibility/eligibility.plist</string>
+	</array>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.ScreenTimeAgent.settings</string>

```
### SecurityPrivacyExtension

> `/System/Library/ExtensionKit/Extensions/SecurityPrivacyExtension.appex/Contents/MacOS/SecurityPrivacyExtension`

```diff

 	<true/>
 	<key>com.apple.private.efilogin-helper</key>
 	<true/>
+	<key>com.apple.private.email</key>
+	<true/>
 	<key>com.apple.private.extensionkit.host.unsandboxed-extensions-for-extension-points</key>
 	<array>
 		<string>com.apple.Settings.extension.ui</string>

 	<true/>
 	<key>com.apple.private.icloudweb.settings</key>
 	<true/>
+	<key>com.apple.private.imcore.spi.database-access</key>
+	<true/>
 	<key>com.apple.private.ind.client</key>
 	<true/>
 	<key>com.apple.private.intelligenceplatform.use-cases</key>

 	<key>com.apple.private.tcc.manager.access.delete</key>
 	<array>
 		<string>kTCCServiceAll</string>
+		<string>kTCCServiceSystemPolicyPrivateFolders</string>
+		<string>kTCCServiceAccessibilityPerTarget</string>
 		<string>kTCCServiceEndpointSecurityClient</string>
 	</array>
 	<key>com.apple.private.tcc.manager.access.modify</key>
 	<array>
 		<string>kTCCServiceAll</string>
+		<string>kTCCServiceSystemPolicyPrivateFolders</string>
+		<string>kTCCServiceAccessibilityPerTarget</string>
 		<string>kTCCServiceEndpointSecurityClient</string>
 	</array>
 	<key>com.apple.private.tcc.manager.access.read</key>
 	<array>
 		<string>kTCCServiceAll</string>
+		<string>kTCCServiceSystemPolicyPrivateFolders</string>
+		<string>kTCCServiceAccessibilityPerTarget</string>
 		<string>kTCCServiceEndpointSecurityClient</string>
 	</array>
 	<key>com.apple.private.tcc.manager.service-composition</key>
 	<true/>
+	<key>com.apple.private.tcc.mobileasset.check</key>
+	<array>
+		<string>kTCCServiceAccessibility</string>
+		<string>kTCCServiceSystemPolicyAllFiles</string>
+	</array>
 	<key>com.apple.rootless.restricted-block-devices</key>
 	<true/>
 	<key>com.apple.rootless.storage.remotemanagementd</key>

```
### WallpaperAerialsExtension

> `/System/Library/ExtensionKit/Extensions/WallpaperAerialsExtension.appex/Contents/MacOS/WallpaperAerialsExtension`

```diff

 		<string>com.apple.timed.xpc</string>
 		<string>com.apple.cache_delete</string>
 	</array>
+	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.SoftwareUpdate</string>
+	</array>
 	<key>com.apple.security.temporary-exception.shared-preference.read-write</key>
 	<array>
 		<string>com.apple.wallpaper</string>

```
### frauddefensepfl

> `/System/Library/ExtensionKit/Extensions/frauddefensepfl.appex/Contents/MacOS/frauddefensepfl`

```diff

 	<string>production</string>
 	<key>com.apple.developer.icloud-container-identifiers</key>
 	<array>
+		<string>com.apple.pfl.container</string>
+		<string>com.apple.pfl.preprod.container</string>
 		<string>com.apple.priml.dev.container</string>
 		<string>com.apple.priml.preprod.container</string>
 		<string>com.apple.priml.prod.container</string>

```
### printtool

> `/System/Library/Frameworks/ApplicationServices.framework/Versions/A/Frameworks/PrintCore.framework/Versions/A/printtool`

```diff

 	<array>
 		<string>group.com.apple.printtool</string>
 	</array>
+	<key>com.apple.private.xpc.smd-job-submit</key>
+	<true/>
 	<key>com.apple.security.application-groups</key>
 	<array>
 		<string>group.com.apple.printtool</string>

```
### printtool

> `/System/Library/Frameworks/ApplicationServices.framework/Versions/Current/Frameworks/PrintCore.framework/Versions/A/printtool`

```diff

 	<array>
 		<string>group.com.apple.printtool</string>
 	</array>
+	<key>com.apple.private.xpc.smd-job-submit</key>
+	<true/>
 	<key>com.apple.security.application-groups</key>
 	<array>
 		<string>group.com.apple.printtool</string>

```
### contactsd

> `/System/Library/Frameworks/Contacts.framework/Support/contactsd`

```diff

 	<true/>
 	<key>com.apple.private.accounts.allaccounts</key>
 	<true/>
+	<key>com.apple.private.contacts</key>
+	<true/>
 	<key>com.apple.private.contacts.disable-remote-database-access</key>
 	<true/>
 	<key>com.apple.private.contacts.provider-host</key>

```
### spotlightknowledged

> `/System/Library/Frameworks/CoreSpotlight.framework/spotlightknowledged`

```diff

 	<array>
 		<string>CLIENT_ENTITLEMENT</string>
 	</array>
+	<key>com.apple.private.agentmanager.client.itemStatus</key>
+	<true/>
 	<key>com.apple.private.cascade.donation-requester</key>
 	<true/>
 	<key>com.apple.private.ciphermld.allow</key>

 		<string>com.apple.generativesearch.server.indexing</string>
 		<string>com.apple.corepersonalization.server.graphEmbedding</string>
 		<string>com.apple.generativesearch.server.salientpostings</string>
+		<string>com.apple.agentmanager.server.itemStatus</string>
 		<string>com.apple.FileDerivativeService</string>
 	</array>
 	<key>com.apple.security.exception.mach-register.global-name</key>

```
### Assistive Control

> `/System/Library/Input Methods/Assistive Control.app/Contents/MacOS/Assistive Control`

```diff

 	</array>
 	<key>com.apple.private.security.storage.universalaccess</key>
 	<true/>
+	<key>com.apple.private.skylight.event-tap.direct-touch</key>
+	<true/>
 	<key>com.apple.private.speech.synthesis.custom.voices.allow</key>
 	<true/>
 	<key>com.apple.private.sysdiagnose</key>

```
### JapaneseIM-KanaTyping

> `/System/Library/Input Methods/JapaneseIM-KanaTyping.app/Contents/PlugIns/JapaneseIM-KanaTyping.appex/Contents/MacOS/JapaneseIM-KanaTyping`

```diff

 		<string>com.apple.CrashReporterSupportHelper</string>
 		<string>com.apple.GSSCred</string>
 	</array>
+	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.applicationaccess</string>
+	</array>
 	<key>com.apple.security.temporary-exception.shared-preference.read-write</key>
 	<array>
 		<string>com.apple.inputmethod.Kotoeri</string>

```
### JapaneseIM-RomajiTyping

> `/System/Library/Input Methods/JapaneseIM-RomajiTyping.app/Contents/PlugIns/JapaneseIM-RomajiTyping.appex/Contents/MacOS/JapaneseIM-RomajiTyping`

```diff

 		<string>com.apple.inputmethod.Kotoeri.RomajiTyping_Connection</string>
 		<string>com.apple.inputmethod.Kotoeri.KanaTyping_Connection</string>
 	</array>
+	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.applicationaccess</string>
+	</array>
 	<key>com.apple.security.temporary-exception.shared-preference.read-write</key>
 	<array>
 		<string>com.apple.inputmethod.Kotoeri</string>

```
### AMPArtworkAgent

> `/System/Library/PrivateFrameworks/AMPLibrary.framework/Versions/A/Support/AMPArtworkAgent`

```diff

 	<true/>
 	<key>com.apple.private.network.system-token-fetch</key>
 	<true/>
+	<key>com.apple.private.tcc.manager.check-by-audit-token</key>
+	<array>
+		<string>kTCCServiceMediaLibrary</string>
+	</array>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
 	<key>com.apple.security.network.client</key>

```
### AMPArtworkAgent

> `/System/Library/PrivateFrameworks/AMPLibrary.framework/Versions/Current/Support/AMPArtworkAgent`

```diff

 	<true/>
 	<key>com.apple.private.network.system-token-fetch</key>
 	<true/>
+	<key>com.apple.private.tcc.manager.check-by-audit-token</key>
+	<array>
+		<string>kTCCServiceMediaLibrary</string>
+	</array>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
 	<key>com.apple.security.network.client</key>

```
### AXMediaUtilitiesService

> `/System/Library/PrivateFrameworks/AXMediaUtilities.framework/XPCServices/AXMediaUtilitiesService.xpc/Contents/MacOS/AXMediaUtilitiesService`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>com.apple.accessibility.api</key>
+	<true/>
+	<key>com.apple.aned.private.ANEAccess.allow</key>
+	<true/>
+	<key>com.apple.mediaanalysisd.client</key>
+	<true/>
+	<key>com.apple.private.assets.accessible-asset-types</key>
+	<array>
+		<string>com.apple.MobileAsset.VCPMobileAssets</string>
+		<string>com.apple.MobileAsset.AXIconVision</string>
+		<string>com.apple.MobileAsset.ImageCaptionModel</string>
+	</array>
+	<key>com.apple.private.assets.change-daemon-config</key>
+	<true/>
+	<key>com.apple.private.photoanalysisd.access</key>
+	<true/>
+	<key>com.apple.private.privacy.accounting.write</key>
+	<true/>
+	<key>com.apple.private.translation</key>
+	<true/>
+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.mediaanalysisd.analysis</string>
+		<string>com.apple.privacyaccountingd</string>
+		<string>com.apple.analyticsd</string>
+		<string>com.apple.translationd</string>
+	</array>
+	<key>com.apple.security.exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.mediaanalysisd</string>
+		<string>com.apple.Accessibility.Assets</string>
+	</array>
+</dict>
+</plist>
 

```
### akd

> `/System/Library/PrivateFrameworks/AuthKit.framework/Versions/A/Support/akd`

```diff

 	<true/>
 	<key>com.apple.private.security.daemon-container</key>
 	<true/>
+	<key>com.apple.private.security.restricted-application-groups</key>
+	<array>
+		<string>group.com.apple.akd</string>
+	</array>
 	<key>com.apple.private.security.storage.Safari</key>
 	<true/>
 	<key>com.apple.private.security.storage.os_eligibility.readonly</key>

 	<key>com.apple.security.application-groups</key>
 	<array>
 		<string>com.apple.CoreODI</string>
+		<string>group.com.apple.akd</string>
 	</array>
 	<key>com.apple.security.attestation.access</key>
 	<true/>

```
### com.apple.siri.embeddedspeech

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/Versions/A/XPCServices/com.apple.siri.embeddedspeech.xpc/Contents/MacOS/com.apple.siri.embeddedspeech`

```diff

 	</array>
 	<key>com.apple.private.assets.bypass-asset-types-check</key>
 	<true/>
+	<key>com.apple.private.assistant.settings</key>
+	<true/>
 	<key>com.apple.private.attribution.implicitly-assumed-identity</key>
 	<dict>
 		<key>type</key>

```
### com.apple.siri.embeddedspeech

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/Versions/Current/XPCServices/com.apple.siri.embeddedspeech.xpc/Contents/MacOS/com.apple.siri.embeddedspeech`

```diff

 	</array>
 	<key>com.apple.private.assets.bypass-asset-types-check</key>
 	<true/>
+	<key>com.apple.private.assistant.settings</key>
+	<true/>
 	<key>com.apple.private.attribution.implicitly-assumed-identity</key>
 	<dict>
 		<key>type</key>

```
### speechmaintenanced

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/speechmaintenanced`

```diff

 	</array>
 	<key>com.apple.private.assets.bypass-asset-types-check</key>
 	<true/>
+	<key>com.apple.private.assistant.settings</key>
+	<true/>
 	<key>com.apple.private.biome.read-write</key>
 	<array>
 		<string>IntelligenceFlow.JointResolverTelemetry</string>

```
### fairplayd

> `/System/Library/PrivateFrameworks/CoreFP.framework/Versions/A/fairplayd`

```diff

     <true/>
     <key>AvpFairPlayUserClient.access</key>
     <true/>
+	<key>adi-client</key>
+	<string>315444076</string>
 </dict>
 </plist>
 

```
### suggestd

> `/System/Library/PrivateFrameworks/CoreSuggestions.framework/Versions/A/Support/suggestd`

```diff

 	<string>serverPreferred</string>
 	<key>com.apple.CoreRoutine.LocationOfInterest</key>
 	<true/>
-	<key>com.apple.CoreRoutine.ScenarioTrigger</key>
-	<true/>
 	<key>com.apple.Maps.MapsSync.access</key>
 	<true/>
 	<key>com.apple.Pasteboard.background-access</key>

```
### DuetDiagnosticExtension

> `/System/Library/PrivateFrameworks/DASDaemon.framework/PlugIns/DuetDiagnosticExtension.appex/Contents/MacOS/DuetDiagnosticExtension`

```diff

 	<true/>
 	<key>com.apple.private.logging.diagnostic</key>
 	<true/>
+	<key>com.apple.security.app-sandbox</key>
+	<true/>
+	<key>com.apple.security.temporary-exception.files.absolute-path.read-write</key>
+	<array>
+		<string>/private/var/log/</string>
+	</array>
 </dict>
 </plist>
 

```
### ArchiveService

> `/System/Library/PrivateFrameworks/DesktopServicesPriv.framework/Versions/A/XPCServices/ArchiveService.xpc/Contents/MacOS/ArchiveService`

```diff

 	<string>com.apple.desktopservices.ArchiveService</string>
 	<key>com.apple.fileprovider.fetch-url</key>
 	<true/>
+	<key>com.apple.private.CacheDelete</key>
+	<array>
+		<string>CLIENT_ENTITLEMENT</string>
+		<string>PURGEABLE_ENTITLEMENT</string>
+		<string>PURGE_ENTITLEMENT</string>
+	</array>
 	<key>com.apple.private.QuarantineService.XPC</key>
 	<true/>
 	<key>com.apple.private.sandbox.profile:embedded</key>

 	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.cache_delete</string>
 		<string>com.apple.CoreServices.coreservicesd</string>
 	</array>
 	<key>keychain-access-groups</key>

```
### ArchiveServiceUnquarantined

> `/System/Library/PrivateFrameworks/DesktopServicesPriv.framework/Versions/A/XPCServices/ArchiveServiceUnquarantined.xpc/Contents/MacOS/ArchiveServiceUnquarantined`

```diff

 	<string>com.apple.desktopservices.ArchiveServiceUnquarantined</string>
 	<key>com.apple.fileprovider.fetch-url</key>
 	<true/>
+	<key>com.apple.private.CacheDelete</key>
+	<array>
+		<string>CLIENT_ENTITLEMENT</string>
+		<string>PURGEABLE_ENTITLEMENT</string>
+		<string>PURGE_ENTITLEMENT</string>
+	</array>
 	<key>com.apple.private.QuarantineService.XPC</key>
 	<true/>
 	<key>com.apple.private.security.restricted-application-groups</key>

 	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.cache_delete</string>
 		<string>com.apple.CoreServices.coreservicesd</string>
 	</array>
 	<key>keychain-access-groups</key>

```
### ArchiveService

> `/System/Library/PrivateFrameworks/DesktopServicesPriv.framework/Versions/Current/XPCServices/ArchiveService.xpc/Contents/MacOS/ArchiveService`

```diff

 	<string>com.apple.desktopservices.ArchiveService</string>
 	<key>com.apple.fileprovider.fetch-url</key>
 	<true/>
+	<key>com.apple.private.CacheDelete</key>
+	<array>
+		<string>CLIENT_ENTITLEMENT</string>
+		<string>PURGEABLE_ENTITLEMENT</string>
+		<string>PURGE_ENTITLEMENT</string>
+	</array>
 	<key>com.apple.private.QuarantineService.XPC</key>
 	<true/>
 	<key>com.apple.private.sandbox.profile:embedded</key>

 	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.cache_delete</string>
 		<string>com.apple.CoreServices.coreservicesd</string>
 	</array>
 	<key>keychain-access-groups</key>

```
### ArchiveServiceUnquarantined

> `/System/Library/PrivateFrameworks/DesktopServicesPriv.framework/Versions/Current/XPCServices/ArchiveServiceUnquarantined.xpc/Contents/MacOS/ArchiveServiceUnquarantined`

```diff

 	<string>com.apple.desktopservices.ArchiveServiceUnquarantined</string>
 	<key>com.apple.fileprovider.fetch-url</key>
 	<true/>
+	<key>com.apple.private.CacheDelete</key>
+	<array>
+		<string>CLIENT_ENTITLEMENT</string>
+		<string>PURGEABLE_ENTITLEMENT</string>
+		<string>PURGE_ENTITLEMENT</string>
+	</array>
 	<key>com.apple.private.QuarantineService.XPC</key>
 	<true/>
 	<key>com.apple.private.security.restricted-application-groups</key>

 	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.cache_delete</string>
 		<string>com.apple.CoreServices.coreservicesd</string>
 	</array>
 	<key>keychain-access-groups</key>

```
### generativeexperiencesd

> `/System/Library/PrivateFrameworks/GenerativeExperiencesRuntime.framework/Versions/A/generativeexperiencesd`

```diff

 	<true/>
 	<key>com.apple.private.intelligenceplatform.use-cases</key>
 	<dict>
+		<key>RegionalSafetyAnalysisMetrics</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>RegionalSafetyAnalysis.Disablement</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+				<key>RegionalSafetyAnalysis.Eligibility</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+			</dict>
+		</dict>
 		<key>com.apple.AppleIntelligence.Reporting.AssetDeliveryLog</key>
 		<dict>
 			<key>Streams</key>

 	<true/>
 	<key>com.apple.private.replicator.dataProvider</key>
 	<true/>
+	<key>com.apple.private.security.restricted-application-groups</key>
+	<array>
+		<string>group.com.apple.aiml.RapidResourceDelivery</string>
+	</array>
 	<key>com.apple.private.security.storage.AppleIntelligencePlatform</key>
 	<true/>
 	<key>com.apple.private.security.storage.MobileAssetGenerativeModels</key>

 	<true/>
 	<key>com.apple.rootless.storage.triald</key>
 	<true/>
+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.aiml.RapidResourceDelivery</string>
+	</array>
 	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
 	<array>
 		<string>/Library/AppleIntelligencePlatform/</string>
 	</array>
+	<key>com.apple.security.network.client</key>
+	<true/>
 	<key>com.apple.security.temporary-exception.files.home-relative-path.read-write</key>
 	<array>
 		<string>/Library/Shortcuts/</string>

 	<key>keychain-access-groups</key>
 	<array>
 		<string>com.apple.openai</string>
+		<string>com.apple.snowflake</string>
 		<string>apple</string>
 	</array>
 </dict>

```
### identityservicesd

> `/System/Library/PrivateFrameworks/IDS.framework/identityservicesd.app/Contents/MacOS/identityservicesd`

```diff

 		<string>com.apple.private.ac</string>
 		<string>com.apple.private.alloy.digitalhealth</string>
 		<string>com.apple.private.ids</string>
-		<string>com.apple.private.ids.reauth</string>
+		<string>com.apple.ids.regionchange</string>
 		<string>com.apple.madrid</string>
 		<string>com.apple.madrid.lite</string>
 		<string>com.apple.private.alloy.accessibility.switchcontrol</string>

```
### IMDPersistenceAgent

> `/System/Library/PrivateFrameworks/IMDPersistence.framework/XPCServices/IMDPersistenceAgent.xpc/Contents/MacOS/IMDPersistenceAgent`

```diff

 	<true/>
 	<key>com.apple.application-identifier</key>
 	<string>com.apple.imdpersistenceagent</string>
+	<key>com.apple.businessservicesd.brandLogo</key>
+	<true/>
 	<key>com.apple.datadetectors.source-read.user</key>
 	<true/>
 	<key>com.apple.developer.hardened-process</key>

 		<string>com.apple.biome.access.user</string>
 		<string>com.apple.biome.compute.source.user</string>
 		<string>com.apple.kvsd</string>
+		<string>com.apple.businessservicesd</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-only</key>
 	<array>

```

### 🆕 FileAccessService

> `/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/Versions/A/XPCServices/FileAccessService.xpc/Contents/MacOS/FileAccessService`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.fileprovider.fetch-url</key>
	<true/>
	<key>platform-application</key>
	<true/>
</dict>
</plist>

```
### intelligenceflowd

> `/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/Versions/A/intelligenceflowd`

```diff

 	<true/>
 	<key>com.apple.application-identifier</key>
 	<string>com.apple.intelligenceflow.intelligenceflowd</string>
+	<key>com.apple.appprotectiond.guard.access</key>
+	<true/>
 	<key>com.apple.appprotectiond.read.access</key>
 	<true/>
 	<key>com.apple.arkit.camera-access-private-formats.allow</key>

 	<true/>
 	<key>com.apple.cards.all-access</key>
 	<true/>
+	<key>com.apple.chronoservices</key>
+	<true/>
 	<key>com.apple.coreaudio.allow-opus-codec</key>
 	<true/>
 	<key>com.apple.coreduetd.allow</key>

 	<true/>
 	<key>com.apple.private.assistant.audio-session-event</key>
 	<true/>
+	<key>com.apple.private.assistant.flow_service</key>
+	<true/>
 	<key>com.apple.private.attentionawareness</key>
 	<true/>
 	<key>com.apple.private.attentionawareness.poll</key>

 	</array>
 	<key>com.apple.private.imcore.spi.database-access</key>
 	<true/>
+	<key>com.apple.private.intelligenceflow.FileAccessService.XPC</key>
+	<true/>
 	<key>com.apple.private.intelligenceplatform.use-cases</key>
 	<dict>
 		<key>Dormancy</key>

```
### mediaremoted

> `/System/Library/PrivateFrameworks/MediaRemote.framework/Support/mediaremoted`

```diff

 	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.linkd.application-service</string>
 		<string>com.apple.nehelper</string>
 		<string>com.apple.musicd</string>
 		<string>com.apple.apsd</string>

```
### mobiletimerd

> `/System/Library/PrivateFrameworks/MobileTimer.framework/Executables/mobiletimerd`

```diff

 	<string>com.apple.mobiletimer</string>
 	<key>com.apple.private.appintents-attribution-override</key>
 	<true/>
+	<key>com.apple.private.appintents-bundle-absolute-paths</key>
+	<array>
+		<string>/System/Library/PrivateFrameworks/MobileTimerSupport.framework</string>
+	</array>
 	<key>com.apple.private.appintents.allowed-bundle-identifiers</key>
 	<array>
 		<string>com.apple.mobiletimer</string>

 		<string>com.apple.NanoAlarm</string>
 		<string>com.apple.private.NanoTimer</string>
 	</array>
+	<key>com.apple.private.appintents.connection</key>
+	<true/>
 	<key>com.apple.private.appintents.exception.allow-foreign-bundle-identifiers</key>
 	<true/>
 	<key>com.apple.private.appintents.live-entities.write</key>

```
### amsondevicestoraged

> `/System/Library/PrivateFrameworks/OnDeviceStorage.framework/Support/amsondevicestoraged`

```diff

 	<string>com.apple.amsondevicestoraged</string>
 	<key>aps-connection-initiate</key>
 	<true/>
+	<key>com.apple.authkit.client.internal</key>
+	<true/>
 	<key>com.apple.developer.icloud-container-identifiers</key>
 	<array>
 		<string>com.apple.applemediaservices.ondevicestorage</string>

 	</array>
 	<key>com.apple.duet.activityscheduler.allow</key>
 	<true/>
+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>
 	<key>com.apple.private.applemediaservices</key>
 	<true/>
 	<key>com.apple.private.aps-connection-initiate</key>

```
### photoanalysisd

> `/System/Library/PrivateFrameworks/PhotoAnalysis.framework/Versions/A/Support/photoanalysisd`

```diff

 		<string>com.apple.UnifiedAssetFramework</string>
 		<string>com.apple.modelcatalog.ajax</string>
 		<string>com.apple.mobileslideshow</string>
+		<string>com.apple.ambient</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-write</key>
 	<array>

```
### privatecloudcomputed

> `/System/Library/PrivateFrameworks/PrivateCloudCompute.framework/privatecloudcomputed.app/Contents/MacOS/privatecloudcomputed`

```diff

 <dict>
 	<key>application-identifier</key>
 	<string>com.apple.privatecloudcomputed</string>
+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>
 	<key>com.apple.duet.activityscheduler.allow</key>
 	<true/>
+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>
 	<key>com.apple.private.appleaccount.app-hidden-from-icloud-settings</key>
 	<true/>
 	<key>com.apple.private.biome.read-write</key>

 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.SBUserNotification</string>
+		<string>com.apple.ind.cloudfeatures</string>
+	</array>
+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.CloudSubscriptionFeatures.cache</string>
 	</array>
 	<key>com.apple.springboard.CFUserNotification</key>
 	<true/>

```
### ScreenTimeAgent

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/Versions/A/ScreenTimeAgent`

```diff

 	<array>
 		<string>group.com.apple.DeviceActivity</string>
 	</array>
+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>
 	<key>com.apple.private.system-keychain</key>
 	<true/>
 	<key>com.apple.private.tcc.allow</key>

 	<true/>
 	<key>com.apple.security.personal-information.addressbook</key>
 	<true/>
+	<key>com.apple.security.temporary-exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/db/os_eligibility/eligibility.plist</string>
+	</array>
 	<key>com.apple.security.temporary-exception.files.absolute-path.read-write</key>
 	<array>
 		<string>/private/var/tmp/ScreenTimeDiagnostics/</string>

```
### SecureMessagingAgent

> `/System/Library/PrivateFrameworks/SecureMessaging.framework/SecureMessagingAgent`

```diff

 	<true/>
 	<key>com.apple.security.network.client</key>
 	<true/>
+	<key>com.apple.symptom_diagnostics.report</key>
+	<true/>
 	<key>keychain-access-groups</key>
 	<array>
 		<string>com.apple.securemessaging</string>

```
### ShareSheetUI

> `/System/Library/PrivateFrameworks/ShareKit.framework/Versions/A/PlugIns/ShareSheetUI.appex/Contents/MacOS/ShareSheetUI`

```diff

 	<string>com.apple.sharing.ShareSheetUI</string>
 	<key>com.apple.private.contactsui</key>
 	<true/>
+	<key>com.apple.private.network.socket-delegate</key>
+	<true/>
 	<key>com.apple.private.tcc.allow</key>
 	<array>
 		<string>kTCCServiceAddressBook</string>

```
### ShareSheetUI

> `/System/Library/PrivateFrameworks/ShareKit.framework/Versions/Current/PlugIns/ShareSheetUI.appex/Contents/MacOS/ShareSheetUI`

```diff

 	<string>com.apple.sharing.ShareSheetUI</string>
 	<key>com.apple.private.contactsui</key>
 	<true/>
+	<key>com.apple.private.network.socket-delegate</key>
+	<true/>
 	<key>com.apple.private.tcc.allow</key>
 	<array>
 		<string>kTCCServiceAddressBook</string>

```
### spaceattributiond

> `/System/Library/PrivateFrameworks/SpaceAttribution.framework/spaceattributiond`

```diff

 	<true/>
 	<key>com.apple.accounts.appleaccount.fullaccess</key>
 	<true/>
+	<key>com.apple.apfs.itod.internal</key>
+	<true/>
 	<key>com.apple.apfs.spec_telemetry</key>
 	<true/>
 	<key>com.apple.duet.activityscheduler.allow</key>

 	<true/>
 	<key>com.apple.private.security.storage.FileProvider</key>
 	<true/>
+	<key>com.apple.private.vfs.unmunged-access-time</key>
+	<true/>
 	<key>com.apple.rootless.datavault.metadata</key>
 	<true/>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>

```
### StoreKitUIServiceMac

> `/System/Library/PrivateFrameworks/StoreKitUIMac.framework/Versions/A/XPCServices/StoreKitUIServiceMac.xpc/Contents/MacOS/StoreKitUIServiceMac`

```diff

 	<true/>
 	<key>com.apple.private.coreservices.canmaplsdatabase</key>
 	<true/>
+	<key>com.apple.private.network.socket-delegate</key>
+	<true/>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
 	<key>com.apple.security.exception.files.home-relative-path.read-write</key>

```
### StoreKitUIServiceMac

> `/System/Library/PrivateFrameworks/StoreKitUIMac.framework/Versions/Current/XPCServices/StoreKitUIServiceMac.xpc/Contents/MacOS/StoreKitUIServiceMac`

```diff

 	<true/>
 	<key>com.apple.private.coreservices.canmaplsdatabase</key>
 	<true/>
+	<key>com.apple.private.network.socket-delegate</key>
+	<true/>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
 	<key>com.apple.security.exception.files.home-relative-path.read-write</key>

```
### voicebankingd

> `/System/Library/PrivateFrameworks/TextToSpeechVoiceBankingSupport.framework/Support/voicebankingd`

```diff

 	<true/>
 	<key>com.apple.SystemConfiguration.SCDynamicStore-read-access</key>
 	<true/>
+	<key>com.apple.accessibility.AccessibilityPersonalVoiceAllowSynthesisWhileLocked</key>
+	<true/>
 	<key>com.apple.accessibility.AccessibilityPersonalVoiceUsageOverride</key>
 	<true/>
 	<key>com.apple.accessibility.axassets</key>

```
### AXVisualSupportAgent

> `/System/Library/PrivateFrameworks/UniversalAccess.framework/Versions/A/Resources/AXVisualSupportAgent.app/Contents/MacOS/AXVisualSupportAgent`

```diff

 	<true/>
 	<key>com.apple.private.accessibility.visuals</key>
 	<true/>
+	<key>com.apple.private.activitykit.ephemeralActivityRequester</key>
+	<true/>
+	<key>com.apple.private.activitykit.unboundedActivityRequester</key>
+	<true/>
 	<key>com.apple.private.corespeech.corespeechd.xpc</key>
 	<true/>
 	<key>com.apple.private.corespeech.xpc</key>

 	<true/>
 	<key>com.apple.private.hid.manager.client</key>
 	<true/>
+	<key>com.apple.private.menubar.allow</key>
+	<true/>
+	<key>com.apple.private.menubar.disable-user-hiding</key>
+	<true/>
+	<key>com.apple.private.menubar.hide-live-activity-settings</key>
+	<true/>
 	<key>com.apple.private.screencapturekit.noprompt</key>
 	<true/>
 	<key>com.apple.private.screencapturekit.suppress-screen-indicator</key>
 	<true/>
 	<key>com.apple.private.security.storage.universalaccess</key>
 	<true/>
+	<key>com.apple.private.sessionkit.custom-platter-target</key>
+	<true/>
+	<key>com.apple.private.sessionkit.sessionRequest</key>
+	<true/>
 	<key>com.apple.private.skylight.event-tap.direct-touch</key>
 	<true/>
 	<key>com.apple.private.speech.synthesis.custom.voices.allow</key>

 		<string>kTCCServiceVoiceBanking</string>
 		<string>kTCCServiceListenEvent</string>
 	</array>
+	<key>com.apple.private.tcc.manager.check-by-audit-token</key>
+	<array>
+		<string>kTCCServiceAccessibility</string>
+		<string>kTCCServiceAccessibilityPerTarget</string>
+		<string>kTCCServicePostEvent</string>
+		<string>kTCCServiceListenEvent</string>
+	</array>
+	<key>com.apple.rootless.critical</key>
+	<true/>
 	<key>com.apple.security.device.audio-input</key>
 	<true/>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>

```
### universalAccessAuthWarn

> `/System/Library/PrivateFrameworks/UniversalAccess.framework/Versions/A/Resources/universalAccessAuthWarn.app/Contents/MacOS/universalAccessAuthWarn`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.private.security.storage.universalaccess</key>
+	<true/>
 	<key>com.apple.private.tcc.manager.access.modify</key>
 	<array>
 		<string>kTCCServiceAccessibility</string>

 		<string>kTCCServiceScreenCapture</string>
 		<string>kTCCServiceListenEvent</string>
 		<string>kTCCServiceRemoteDesktop</string>
+		<string>kTCCServiceAccessibilityPerTarget</string>
 	</array>
 	<key>com.apple.private.tcc.manager.access.read</key>
 	<array>

 		<string>kTCCServiceScreenCapture</string>
 		<string>kTCCServiceListenEvent</string>
 		<string>kTCCServiceRemoteDesktop</string>
+		<string>kTCCServiceAccessibilityPerTarget</string>
+	</array>
+	<key>com.apple.private.tcc.manager.check-by-audit-token</key>
+	<array>
+		<string>kTCCServiceAccessibilityPerTarget</string>
 	</array>
 </dict>
 </plist>

```
### AXVisualSupportAgent

> `/System/Library/PrivateFrameworks/UniversalAccess.framework/Versions/Current/Resources/AXVisualSupportAgent.app/Contents/MacOS/AXVisualSupportAgent`

```diff

 	<true/>
 	<key>com.apple.private.accessibility.visuals</key>
 	<true/>
+	<key>com.apple.private.activitykit.ephemeralActivityRequester</key>
+	<true/>
+	<key>com.apple.private.activitykit.unboundedActivityRequester</key>
+	<true/>
 	<key>com.apple.private.corespeech.corespeechd.xpc</key>
 	<true/>
 	<key>com.apple.private.corespeech.xpc</key>

 	<true/>
 	<key>com.apple.private.hid.manager.client</key>
 	<true/>
+	<key>com.apple.private.menubar.allow</key>
+	<true/>
+	<key>com.apple.private.menubar.disable-user-hiding</key>
+	<true/>
+	<key>com.apple.private.menubar.hide-live-activity-settings</key>
+	<true/>
 	<key>com.apple.private.screencapturekit.noprompt</key>
 	<true/>
 	<key>com.apple.private.screencapturekit.suppress-screen-indicator</key>
 	<true/>
 	<key>com.apple.private.security.storage.universalaccess</key>
 	<true/>
+	<key>com.apple.private.sessionkit.custom-platter-target</key>
+	<true/>
+	<key>com.apple.private.sessionkit.sessionRequest</key>
+	<true/>
 	<key>com.apple.private.skylight.event-tap.direct-touch</key>
 	<true/>
 	<key>com.apple.private.speech.synthesis.custom.voices.allow</key>

 		<string>kTCCServiceVoiceBanking</string>
 		<string>kTCCServiceListenEvent</string>
 	</array>
+	<key>com.apple.private.tcc.manager.check-by-audit-token</key>
+	<array>
+		<string>kTCCServiceAccessibility</string>
+		<string>kTCCServiceAccessibilityPerTarget</string>
+		<string>kTCCServicePostEvent</string>
+		<string>kTCCServiceListenEvent</string>
+	</array>
+	<key>com.apple.rootless.critical</key>
+	<true/>
 	<key>com.apple.security.device.audio-input</key>
 	<true/>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>

```
### universalAccessAuthWarn

> `/System/Library/PrivateFrameworks/UniversalAccess.framework/Versions/Current/Resources/universalAccessAuthWarn.app/Contents/MacOS/universalAccessAuthWarn`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.private.security.storage.universalaccess</key>
+	<true/>
 	<key>com.apple.private.tcc.manager.access.modify</key>
 	<array>
 		<string>kTCCServiceAccessibility</string>

 		<string>kTCCServiceScreenCapture</string>
 		<string>kTCCServiceListenEvent</string>
 		<string>kTCCServiceRemoteDesktop</string>
+		<string>kTCCServiceAccessibilityPerTarget</string>
 	</array>
 	<key>com.apple.private.tcc.manager.access.read</key>
 	<array>

 		<string>kTCCServiceScreenCapture</string>
 		<string>kTCCServiceListenEvent</string>
 		<string>kTCCServiceRemoteDesktop</string>
+		<string>kTCCServiceAccessibilityPerTarget</string>
+	</array>
+	<key>com.apple.private.tcc.manager.check-by-audit-token</key>
+	<array>
+		<string>kTCCServiceAccessibilityPerTarget</string>
 	</array>
 </dict>
 </plist>

```
### siriactionsd

> `/System/Library/PrivateFrameworks/VoiceShortcuts.framework/Versions/A/Support/siriactionsd`

```diff

 					<key>mode</key>
 					<string>read-only</string>
 				</dict>
+				<key>Device.ScreenLocked</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
 				<key>Device.Wireless.AirplaneMode</key>
 				<dict>
 					<key>mode</key>

 	<true/>
 	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
 	<true/>
+	<key>com.apple.private.sessionkit.assertionRequester</key>
+	<true/>
+	<key>com.apple.private.sessionkit.prominentPresentationAssertionRequester</key>
+	<true/>
 	<key>com.apple.private.spotlight.search.internal</key>
 	<true/>
 	<key>com.apple.private.tcc.allow</key>

 	<true/>
 	<key>com.apple.privatecloudcompute.knownRateLimits</key>
 	<true/>
+	<key>com.apple.privatecloudcompute.usage</key>
+	<true/>
 	<key>com.apple.proactiveagentplatform.orchestrator</key>
 	<true/>
 	<key>com.apple.proactiveagentplatform.orchestrator.features</key>

 		<string>com.apple.private.corewifi-xpc</string>
 		<string>com.apple.privatecloudcompute</string>
 		<string>com.apple.proactiveagentplatform.orchestrator</string>
+		<string>com.apple.sessionservices</string>
 		<string>com.apple.shortcuts.view-service</string>
 		<string>com.apple.siri.uaf.service</string>
 		<string>com.apple.siri.vocabularyupdates</string>

```
### ShortcutsIntents

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/PlugIns/ShortcutsIntents.appex/Contents/MacOS/ShortcutsIntents`

```diff

 	<true/>
 	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
 	<true/>
+	<key>com.apple.private.sessionkit.assertionRequester</key>
+	<true/>
+	<key>com.apple.private.sessionkit.prominentPresentationAssertionRequester</key>
+	<true/>
 	<key>com.apple.private.shazamkit.allow-external-audio-recording</key>
 	<true/>
 	<key>com.apple.private.shazamkit.allow-internal-audio-recording</key>

 	<true/>
 	<key>com.apple.privatecloudcompute.knownRateLimits</key>
 	<true/>
+	<key>com.apple.privatecloudcompute.usage</key>
+	<true/>
 	<key>com.apple.rootless.storage.shortcuts</key>
 	<true/>
 	<key>com.apple.runningboard.assertions.shortcuts</key>

 		<string>com.apple.private.corewifi-xpc</string>
 		<string>com.apple.privatecloudcompute</string>
 		<string>com.apple.remindd</string>
+		<string>com.apple.sessionservices</string>
 		<string>com.apple.sharing.airdrop.service</string>
 		<string>com.apple.shazamd</string>
 		<string>com.apple.shortcuts.dialogpresentation</string>

```
### BackgroundShortcutRunner

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/XPCServices/BackgroundShortcutRunner.xpc/Contents/MacOS/BackgroundShortcutRunner`

```diff

 	<true/>
 	<key>com.apple.private.ids.agent.GroupRestricted</key>
 	<true/>
+	<key>com.apple.private.ind.client</key>
+	<true/>
 	<key>com.apple.private.intelligenceplatform.client-identifier</key>
 	<string>com.apple.shortcuts</string>
 	<key>com.apple.private.intelligenceplatform.use-cases</key>

 	<true/>
 	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
 	<true/>
+	<key>com.apple.private.sessionkit.assertionRequester</key>
+	<true/>
+	<key>com.apple.private.sessionkit.prominentPresentationAssertionRequester</key>
+	<true/>
 	<key>com.apple.private.shazamkit.allow-external-audio-recording</key>
 	<true/>
 	<key>com.apple.private.shazamkit.allow-internal-audio-recording</key>

 	<true/>
 	<key>com.apple.privatecloudcompute.knownRateLimits</key>
 	<true/>
+	<key>com.apple.privatecloudcompute.usage</key>
+	<true/>
 	<key>com.apple.rootless.storage.shortcuts</key>
 	<true/>
 	<key>com.apple.rootless.storage.shortcuts_sandbox_profile</key>

 	</array>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.AppleMediaServicesUIDynamicService</string>
 		<string>com.apple.PerfPowerTelemetryClientRegistrationService</string>
 		<string>com.apple.SetStoreUpdateService</string>
 		<string>com.apple.airplay.endpoint.xpc</string>

 		<string>com.apple.generativeexperiences.availabilityService</string>
 		<string>com.apple.generativeexperiences.generativeexperiencessession</string>
 		<string>com.apple.generativesearch.server.search</string>
+		<string>com.apple.ind.xpc</string>
 		<string>com.apple.intelligenceflow.contextTool</string>
 		<string>com.apple.intelligenceplatform.EntityResolution</string>
 		<string>com.apple.intelligenceplatform.View</string>

 		<string>com.apple.private.corewifi.internal-xpc</string>
 		<string>com.apple.privatecloudcompute</string>
 		<string>com.apple.remindd</string>
+		<string>com.apple.sessionservices</string>
 		<string>com.apple.sharing.airdrop.service</string>
 		<string>com.apple.shortcuts.view-service</string>
 		<string>com.apple.siri.uaf.service</string>

 		<string>com.apple.GenerativeFunctions.GenerativeFunctionsInstrumentation</string>
 		<string>com.apple.TimeMachine</string>
 		<string>com.apple.UnifiedAssetFramework</string>
+		<string>com.apple.cloud.quota</string>
 		<string>com.apple.generativesearch</string>
 		<string>com.apple.gms.availability</string>
 		<string>com.apple.modelcatalog.ajax</string>

```
### WritingToolsViewService

> `/System/Library/PrivateFrameworks/WritingToolsUI.framework/Versions/A/XPCServices/WritingToolsViewService.xpc/Contents/MacOS/WritingToolsViewService`

```diff

 	<key>keychain-access-groups</key>
 	<array>
 		<string>com.apple.openai</string>
+		<string>com.apple.snowflake</string>
 	</array>
 </dict>
 </plist>

```
### WritingToolsViewService

> `/System/Library/PrivateFrameworks/WritingToolsUI.framework/Versions/Current/XPCServices/WritingToolsViewService.xpc/Contents/MacOS/WritingToolsViewService`

```diff

 	<key>keychain-access-groups</key>
 	<array>
 		<string>com.apple.openai</string>
+		<string>com.apple.snowflake</string>
 	</array>
 </dict>
 </plist>

```
### iCloudNotificationAgent

> `/System/Library/PrivateFrameworks/iCloudNotification.framework/iCloudNotificationAgent`

```diff

 	<true/>
 	<key>com.apple.accounts.appleaccount.fullaccess</key>
 	<true/>
+	<key>com.apple.accounts.idms.fullaccess</key>
+	<true/>
 	<key>com.apple.application-identifier</key>
 	<string>com.apple.iCloudNotificationAgent</string>
 	<key>com.apple.authkit.client.private</key>

```

### 🆕 CaptiveUserAgent

> `/System/Library/UserEventPlugins/CaptiveUserAgent.plugin/Contents/MacOS/CaptiveUserAgent`

- No entitlements *(yet)*
### GPUIExtension

> `/System/iOSSupport/System/Library/ExtensionKit/Extensions/GPUIExtension.appex/Contents/MacOS/GPUIExtension`

```diff

 	<true/>
 	<key>com.apple.photos.bourgeoisie</key>
 	<true/>
+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>
 	<key>com.apple.private.appintents.extend-timeout-on-progress-updates</key>
 	<true/>
 	<key>com.apple.private.applemediaservices</key>

 	<true/>
 	<key>com.apple.private.feedback.drafting</key>
 	<true/>
+	<key>com.apple.private.ind.client</key>
+	<true/>
 	<key>com.apple.private.intelligenceplatform.use-cases</key>
 	<dict>
 		<key>GeneratedImageImageGeneration</key>

 	</array>
 	<key>com.apple.privatecloudcompute.knownRateLimits</key>
 	<true/>
+	<key>com.apple.privatecloudcompute.usage</key>
+	<true/>
 	<key>com.apple.rootless.storage.shortcuts</key>
 	<true/>
 	<key>com.apple.security.app-sandbox</key>

 	</array>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.AppleMediaServicesUIDynamicService</string>
+		<string>com.apple.ind.xpc</string>
 		<string>com.apple.privatecloudcompute</string>
 		<string>com.apple.photos.ImageConversionService</string>
 		<string>com.apple.assistant.cdm</string>

```
### launchctl

> `/bin/launchctl`

```diff

 <dict>
 	<key>com.apple.private.xpc.launchd.setenv-pid-domain</key>
 	<true/>
+	<key>com.apple.private.xpc.launchd.system-job-bootstrap</key>
+	<true/>
 	<key>com.apple.private.xpc.launchd.userspace-reboot</key>
 	<true/>
 	<key>com.apple.private.xpc.persona-creator</key>

```

### 🆕 curlinfo

> `/usr/bin/curlinfo`

- No entitlements *(yet)*
### appleh16camerad

> `/usr/libexec/appleh16camerad`

```diff

 	<true/>
 	<key>com.apple.private.ZhuGeSupport.CopyValue</key>
 	<true/>
+	<key>com.apple.private.camera.isp-setfile-load</key>
+	<true/>
 	<key>com.apple.private.cmio.extension.configuration</key>
 	<true/>
 	<key>com.apple.private.tcc.manager.check-by-audit-token</key>

```
### audioanalyticsd

> `/usr/libexec/audioanalyticsd`

```diff

 	<array>
 		<string>com.apple.MobileAsset.AudioAnalytics</string>
 	</array>
+	<key>com.apple.private.attentionawareness</key>
+	<true/>
 	<key>com.apple.private.biome.client-identifier</key>
 	<string>com.apple.coreaudio</string>
 	<key>com.apple.private.biome.writer</key>

 		<string>com.apple.usernotifications.usernotificationservice</string>
 		<string>com.apple.ctcategories.service</string>
 		<string>com.apple.account.AppleAccount</string>
+		<string>com.apple.backlightd</string>
+		<string>com.apple.AttentionAwareness</string>
+		<string>com.apple.iohideventsystem</string>
 	</array>
 	<key>com.apple.security.iokit-user-client-class</key>
 	<array>

```
### companiond

> `/usr/libexec/companiond`

```diff

 	<true/>
 	<key>com.apple.frontboard.launchapplications</key>
 	<true/>
+	<key>com.apple.frontboardservices.display-layout-monitor</key>
+	<true/>
 	<key>com.apple.homekit.private-spi-access</key>
 	<true/>
 	<key>com.apple.linkd.registry</key>

```
### dasd

> `/usr/libexec/dasd`

```diff

 	<true/>
 	<key>com.apple.accounts.appleaccount.fullaccess</key>
 	<true/>
+	<key>com.apple.batteryintelligenced.thermalprediction-read</key>
+	<true/>
 	<key>com.apple.bulletinboard.dataprovider</key>
 	<true/>
 	<key>com.apple.companionappd.connect.allow</key>

 	<true/>
 	<key>com.apple.powerd.lowpowermode.allow</key>
 	<true/>
+	<key>com.apple.powerui.smartcharging</key>
+	<true/>
 	<key>com.apple.private.CacheDelete</key>
 	<array>
 		<string>PURGEABLE_ENTITLEMENT</string>

 		<string>com.apple.griddatad.registration</string>
 		<string>com.apple.biome.ContextSync</string>
 		<string>com.apple.biomesyncd.sync</string>
+		<string>com.apple.batteryintelligenced.thermalprediction</string>
+		<string>com.apple.powerui.smartChargeManager</string>
 	</array>
 	<key>com.apple.security.exception.process-info</key>
 	<true/>

 		<string>COREOS_DAS</string>
 		<string>COREOS_APRS</string>
 		<string>COREOS_CLAS</string>
+		<string>COREOS_DRM_APRS</string>
 	</array>
 	<key>platform-application</key>
 	<true/>

```
### icloudmailagent

> `/usr/libexec/icloudmailagent`

```diff

 	<array>
 		<string>com.apple.kvsd</string>
 		<string>com.apple.apsd</string>
+		<string>com.apple.mediaanalysisd.service.public</string>
 	</array>
 	<key>com.apple.security.temporary-exception.files.home-relative-path.read-only</key>
 	<array>

```
### managedappsd

> `/usr/libexec/managedappsd`

```diff

 <dict>
 	<key>application-identifier</key>
 	<string>com.apple.devicemanagementclient.managedappsd</string>
+	<key>com.apple.private.device-configuration.effective-configuration-ids.read</key>
+	<array>
+		<string>com.apple.ManagedApps</string>
+	</array>
+	<key>com.apple.private.device-configuration.provider.allowed-provider-ids</key>
+	<array>
+		<string>com.apple.ManagedApps</string>
+	</array>
 	<key>com.apple.private.managedclient.configurationprofiles</key>
 	<true/>
 	<key>com.apple.private.managedclient.configurationprofiles.installsource</key>
 	<string>RemoteManagement</string>
+	<key>com.apple.private.managedclient.managedapps.install</key>
+	<true/>
 	<key>com.apple.private.remotemanagement.subscriber</key>
 	<true/>
 	<key>com.apple.private.security.protected-system-container</key>

```
### mobilerepaird

> `/usr/libexec/mobilerepaird`

```diff

 	<true/>
 	<key>com.apple.private.corerepair.xpc</key>
 	<true/>
+	<key>com.apple.private.device-configuration.effective-configuration-ids.read</key>
+	<array>
+		<string>com.apple.CoreRepair</string>
+	</array>
 	<key>com.apple.private.exclaves.conclave-host</key>
 	<true/>
 	<key>com.apple.private.followup</key>

 	<true/>
 	<key>com.apple.private.iokit.batteryhealthstate</key>
 	<true/>
+	<key>com.apple.private.mobilerepair.shipmode</key>
+	<true/>
 	<key>com.apple.private.security.AppleImage4.user-client</key>
 	<true/>
 	<key>com.apple.private.security.bootpolicy</key>

 		<string>com.apple.ctkd.token-client</string>
 		<string>com.apple.ctkd</string>
 		<string>com.apple.devicedatareset.DeviceDataResetService</string>
+		<string>com.apple.deviceconfigurationd.consumer</string>
+		<string>com.apple.mobilerepair.shipmode</string>
 	</array>
 	<key>com.apple.security.iokit-user-client-class</key>
 	<array>

```
### ospredictiond

> `/usr/libexec/ospredictiond`

```diff

 	<true/>
 	<key>com.apple.coremedia.cameraviewfinder</key>
 	<true/>
+	<key>com.apple.das.private.usagepriorities</key>
+	<true/>
 	<key>com.apple.duet.activityscheduler.allow</key>
 	<true/>
 	<key>com.apple.locationd.activity</key>

 	<key>com.apple.private.biome.read-only</key>
 	<array>
 		<string>Activity.Level</string>
+		<string>App.InFocus</string>
 		<string>Device.Power.PluggedIn</string>
 		<string>NowPlaying</string>
 		<string>Device.ScreenLocked</string>

 				<string>Activity.Level</string>
 			</array>
 		</dict>
+		<key>OSPersonalizedScheduling</key>
+		<dict>
+			<key>Streams</key>
+			<array>
+				<string>App.InFocus</string>
+			</array>
+		</dict>
 	</dict>
 	<key>com.apple.private.mobiletimerd</key>
 	<true/>

```
### powerexperienced

> `/usr/libexec/powerexperienced`

```diff

 			<dict/>
 		</dict>
 	</dict>
+	<key>com.apple.batteryintelligenced.thermalprediction-read</key>
+	<true/>
 	<key>com.apple.coremedia.cameraviewfinder</key>
 	<true/>
 	<key>com.apple.locationd.asmanager</key>

 	<true/>
 	<key>com.apple.powerd.extendedbattery</key>
 	<true/>
+	<key>com.apple.powerui.smartcharging</key>
+	<true/>
 	<key>com.apple.private.applesmc.user-access</key>
 	<true/>
 	<key>com.apple.private.clpc.policy</key>

 		<string>com.apple.PerfPowerTelemetryClientRegistrationService</string>
 		<string>com.apple.OSIntelligence.battery</string>
 		<string>com.apple.powerd.extendedbattery</string>
+		<string>com.apple.batteryintelligenced.thermalprediction</string>
+		<string>com.apple.powerui.smartChargeManager</string>
 	</array>
 	<key>com.apple.security.iokit-user-client-class</key>
 	<array>

```
### promotedcontentd

> `/usr/libexec/promotedcontentd`

```diff

 		<string>AD_PLATFORMS_APPSTORE_SRP_INCREMENTALITYAPPSTORE</string>
 		<string>AD_PLATFORMS_APPSTORE_TT_INCREMENTALITYAPPSTORE</string>
 		<string>AD_PLATFORMS_APPSTORE_PP_INCREMENTALITYAPPSTORE</string>
-		<string>AD_PLATFORMS_RN_CORE_SEARCH_RN_AA_TEST</string>
-		<string>AD_PLATFORMS_RN_SEARCH_HOME_RN_AA_TEST</string>
+		<string>AD_PLATFORMS_RN_CORE_SEARCH_RNONDEVICEAATESTFACTOR</string>
+		<string>AD_PLATFORMS_RN_SEARCH_HOME_RNONDEVICEAATESTFACTOR</string>
 		<string>AD_PLATFORMS_APPSTORE_SLP_ADEVENTKIT</string>
 		<string>AD_PLATFORMS_APPSTORE_SRP_ADEVENTKIT</string>
 		<string>AD_PLATFORMS_APPSTORE_TT_ADEVENTKIT</string>

```
### rapportd

> `/usr/libexec/rapportd`

```diff

 	<true/>
 	<key>com.apple.private.contacts</key>
 	<true/>
+	<key>com.apple.private.continuitycapture.capabilities</key>
+	<true/>
 	<key>com.apple.private.coreservices.canmapbundleidtouuid</key>
 	<true/>
 	<key>com.apple.private.corewifi</key>

 		<string>com.apple.sharing.airdrop.service</string>
 		<string>com.apple.ApplicationService.ServiceDiscovery</string>
 		<string>com.apple.duetactivityscheduler</string>
+		<string>com.apple.continuitycaptured.capabilities</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-only</key>
 	<array>

```
### searchpartyd

> `/usr/libexec/searchpartyd`

```diff

 	<true/>
 	<key>com.apple.findmy.findmylocate.settings</key>
 	<true/>
+	<key>com.apple.findmy.locationquality.access</key>
+	<true/>
 	<key>com.apple.geoanalyticsd.telemetry</key>
 	<true/>
 	<key>com.apple.geoservices.setanydefault</key>

```
### searchpartyuseragent

> `/usr/libexec/searchpartyuseragent`

```diff

 		<string>com.apple.findmy</string>
 		<string>com.apple.FindMySafetyAlertsNotifications</string>
 	</array>
+	<key>com.apple.searchparty.DirectScannerActivationContext</key>
+	<true/>
+	<key>com.apple.searchparty.DirectScannerMonitor</key>
+	<true/>
 	<key>com.apple.security.application-groups</key>
 	<array>
 		<string>com.apple.icloud.searchpartyd.container.appGroup</string>

```
### seserviced

> `/usr/libexec/seserviced`

```diff

 		<string>com.apple.imessage.bag</string>
 		<string>com.apple.AppSupport.plist</string>
 		<string>com.apple.stockholm</string>
+		<string>com.apple.purplebuddy</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-write</key>
 	<array>

 	<true/>
 	<key>com.apple.security.ts.identity-services-client</key>
 	<true/>
+	<key>com.apple.security.ts.ipc-posix-sem</key>
+	<string>purplebuddy.sentinel</string>
 	<key>com.apple.security.ts.power-assertions</key>
 	<true/>
 	<key>com.apple.security.ts.read-factory-files</key>

```
### smd

> `/usr/libexec/smd`

```diff

 	<string>com.apple.xpc.ServiceManagement</string>
 	<key>com.apple.private.xpc.launchd.loginitem-bootstrapper</key>
 	<true/>
+	<key>com.apple.private.xpc.launchd.system-job-bootstrap</key>
+	<true/>
 	<key>com.apple.private.xpc.protected-services</key>
 	<true/>
 	<key>com.apple.rootless.xpc.effective-root</key>

```
### spotlightknowledged.graph

> `/usr/libexec/spotlightknowledged.graph`

```diff

 	<array>
 		<string>CLIENT_ENTITLEMENT</string>
 	</array>
+	<key>com.apple.private.agentmanager.client.itemStatus</key>
+	<true/>
 	<key>com.apple.private.cascade.donation-requester</key>
 	<true/>
 	<key>com.apple.private.ciphermld.allow</key>

 		<string>com.apple.generativesearch.server.indexing</string>
 		<string>com.apple.corepersonalization.server.graphEmbedding</string>
 		<string>com.apple.generativesearch.server.salientpostings</string>
+		<string>com.apple.agentmanager.server.itemStatus</string>
 		<string>com.apple.FileDerivativeService</string>
 	</array>
 	<key>com.apple.security.exception.mach-register.global-name</key>

```
### spotlightknowledged.importer

> `/usr/libexec/spotlightknowledged.importer`

```diff

 	<array>
 		<string>CLIENT_ENTITLEMENT</string>
 	</array>
+	<key>com.apple.private.agentmanager.client.itemStatus</key>
+	<true/>
 	<key>com.apple.private.cascade.donation-requester</key>
 	<true/>
 	<key>com.apple.private.ciphermld.allow</key>

 		<string>com.apple.generativesearch.server.indexing</string>
 		<string>com.apple.corepersonalization.server.graphEmbedding</string>
 		<string>com.apple.generativesearch.server.salientpostings</string>
+		<string>com.apple.agentmanager.server.itemStatus</string>
 		<string>com.apple.FileDerivativeService</string>
 	</array>
 	<key>com.apple.security.exception.mach-register.global-name</key>

```
### spotlightknowledged.updater

> `/usr/libexec/spotlightknowledged.updater`

```diff

 	<array>
 		<string>CLIENT_ENTITLEMENT</string>
 	</array>
+	<key>com.apple.private.agentmanager.client.itemStatus</key>
+	<true/>
 	<key>com.apple.private.cascade.donation-requester</key>
 	<true/>
 	<key>com.apple.private.ciphermld.allow</key>

 		<string>com.apple.generativesearch.server.indexing</string>
 		<string>com.apple.corepersonalization.server.graphEmbedding</string>
 		<string>com.apple.generativesearch.server.salientpostings</string>
+		<string>com.apple.agentmanager.server.itemStatus</string>
 		<string>com.apple.FileDerivativeService</string>
 	</array>
 	<key>com.apple.security.exception.mach-register.global-name</key>

```
### textunderstandingd

> `/usr/libexec/textunderstandingd`

```diff

 	<true/>
 	<key>com.apple.modelmanager.inference</key>
 	<true/>
+	<key>com.apple.private.appintents.connection</key>
+	<true/>
 	<key>com.apple.private.appintents.extension-host</key>
 	<true/>
 	<key>com.apple.private.assets.accessible-asset-types</key>

```
### tvremoted

> `/usr/libexec/tvremoted`

```diff

 	<array>
 		<string>/Applications/</string>
 		<string>/private/var/containers/Bundle/Application/</string>
+		<string>/private/var/mobile/Library/UserConfigurationProfiles/EffectiveUserSettings.plist</string>
 		<string>/private/var/preferences/SystemConfiguration/com.apple.wifi.plist</string>
 		<string>/usr/libexec/</string>
 	</array>

```
### appleh16camerad

> `/usr/sbin/appleh16camerad`

```diff

 	<true/>
 	<key>com.apple.private.ZhuGeSupport.CopyValue</key>
 	<true/>
+	<key>com.apple.private.camera.isp-setfile-load</key>
+	<true/>
 	<key>com.apple.private.cmio.extension.configuration</key>
 	<true/>
 	<key>com.apple.private.tcc.manager.check-by-audit-token</key>

```


### SystemOS

### com.apple.WebKit.WebContent.CaptivePortal

> `/System/Library/Frameworks/WebKit.framework/Versions/A/XPCServices/com.apple.WebKit.WebContent.CaptivePortal.xpc/Contents/MacOS/com.apple.WebKit.WebContent.CaptivePortal`

```diff

 		<string>com.apple.sessionagent.shieldWindowIsShowing</string>
 		<string>com.apple.sessionagent.shieldWindowLowered</string>
 		<string>com.apple.sessionagent.shieldWindowRaised</string>
+		<string>com.apple.tcc.access.changed</string>
 		<string>__ABDataBaseChangedByOtherProcessNotification</string>
 		<string>_AXNotification_AXSAppValidatingTestingPreference</string>
 		<string>_AXNotification_IsAXValidationRunnerCollectingValidations</string>

```
### com.apple.WebKit.WebContent.EnhancedSecurity

> `/System/Library/Frameworks/WebKit.framework/Versions/A/XPCServices/com.apple.WebKit.WebContent.EnhancedSecurity.xpc/Contents/MacOS/com.apple.WebKit.WebContent.EnhancedSecurity`

```diff

 		<string>com.apple.sessionagent.shieldWindowIsShowing</string>
 		<string>com.apple.sessionagent.shieldWindowLowered</string>
 		<string>com.apple.sessionagent.shieldWindowRaised</string>
+		<string>com.apple.tcc.access.changed</string>
 		<string>__ABDataBaseChangedByOtherProcessNotification</string>
 		<string>_AXNotification_AXSAppValidatingTestingPreference</string>
 		<string>_AXNotification_IsAXValidationRunnerCollectingValidations</string>

```
### com.apple.WebKit.WebContent

> `/System/Library/Frameworks/WebKit.framework/Versions/A/XPCServices/com.apple.WebKit.WebContent.xpc/Contents/MacOS/com.apple.WebKit.WebContent`

```diff

 		<string>com.apple.sessionagent.shieldWindowIsShowing</string>
 		<string>com.apple.sessionagent.shieldWindowLowered</string>
 		<string>com.apple.sessionagent.shieldWindowRaised</string>
+		<string>com.apple.tcc.access.changed</string>
 		<string>__ABDataBaseChangedByOtherProcessNotification</string>
 		<string>_AXNotification_AXSAppValidatingTestingPreference</string>
 		<string>_AXNotification_IsAXValidationRunnerCollectingValidations</string>

```
### com.apple.WebKit.WebContent.CaptivePortal

> `/System/Library/Frameworks/WebKit.framework/Versions/Current/XPCServices/com.apple.WebKit.WebContent.CaptivePortal.xpc/Contents/MacOS/com.apple.WebKit.WebContent.CaptivePortal`

```diff

 		<string>com.apple.sessionagent.shieldWindowIsShowing</string>
 		<string>com.apple.sessionagent.shieldWindowLowered</string>
 		<string>com.apple.sessionagent.shieldWindowRaised</string>
+		<string>com.apple.tcc.access.changed</string>
 		<string>__ABDataBaseChangedByOtherProcessNotification</string>
 		<string>_AXNotification_AXSAppValidatingTestingPreference</string>
 		<string>_AXNotification_IsAXValidationRunnerCollectingValidations</string>

```
### com.apple.WebKit.WebContent.EnhancedSecurity

> `/System/Library/Frameworks/WebKit.framework/Versions/Current/XPCServices/com.apple.WebKit.WebContent.EnhancedSecurity.xpc/Contents/MacOS/com.apple.WebKit.WebContent.EnhancedSecurity`

```diff

 		<string>com.apple.sessionagent.shieldWindowIsShowing</string>
 		<string>com.apple.sessionagent.shieldWindowLowered</string>
 		<string>com.apple.sessionagent.shieldWindowRaised</string>
+		<string>com.apple.tcc.access.changed</string>
 		<string>__ABDataBaseChangedByOtherProcessNotification</string>
 		<string>_AXNotification_AXSAppValidatingTestingPreference</string>
 		<string>_AXNotification_IsAXValidationRunnerCollectingValidations</string>

```
### com.apple.WebKit.WebContent

> `/System/Library/Frameworks/WebKit.framework/Versions/Current/XPCServices/com.apple.WebKit.WebContent.xpc/Contents/MacOS/com.apple.WebKit.WebContent`

```diff

 		<string>com.apple.sessionagent.shieldWindowIsShowing</string>
 		<string>com.apple.sessionagent.shieldWindowLowered</string>
 		<string>com.apple.sessionagent.shieldWindowRaised</string>
+		<string>com.apple.tcc.access.changed</string>
 		<string>__ABDataBaseChangedByOtherProcessNotification</string>
 		<string>_AXNotification_AXSAppValidatingTestingPreference</string>
 		<string>_AXNotification_IsAXValidationRunnerCollectingValidations</string>

```


