## 🔑 Entitlements

### filesystem

### Contacts

> `/System/Applications/Contacts.app/Contents/MacOS/Contacts`

```diff

 	<true/>
 	<key>com.apple.private.screen-time</key>
 	<true/>
+	<key>com.apple.private.screen-time-settings</key>
+	<true/>
 	<key>com.apple.private.security.storage.MessagesMetaData</key>
 	<true/>
 	<key>com.apple.private.sharing.paired-contacts</key>

 		<string>com.apple.identityservicesd.desktop.auth</string>
 		<string>com.apple.stickers.recency</string>
 		<string>com.apple.sharingd.pairedcontactmanager</string>
+		<string>com.apple.ScreenTimeSettingsAgent.private</string>
 	</array>
 	<key>com.apple.security.temporary-exception.sbpl</key>
 	<array>

```
### Messages

> `/System/Applications/Messages.app/Contents/MacOS/Messages`

```diff

 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.iconservices</string>
+		<string>com.apple.internal.SpotlightAutomationTester</string>
 		<string>com.apple.iconservices.store</string>
 		<string>com.apple.lockdownmoded</string>
 		<string>com.apple.AudioAccessoryAssetManagementXPCService</string>

```
### Feedback Assistant

> `/System/Library/CoreServices/Applications/Feedback Assistant.app/Contents/MacOS/Feedback Assistant`

```diff

 	<array>
 		<string>/private/var/tmp/</string>
 		<string>/private/var/db/com.apple.countryd/</string>
+		<string>/AppleInternal/Library/Application Support/com.apple.feedback/</string>
 	</array>
 	<key>com.apple.security.temporary-exception.iokit-user-client-class</key>
 	<array>

```
### MediaRemoteUIService

> `/System/Library/CoreServices/MediaRemoteUIService.app/Contents/MacOS/MediaRemoteUIService`

```diff

 	<true/>
 	<key>com.apple.private.coreservices.canmaplsdatabase</key>
 	<true/>
+	<key>com.apple.private.menubar.allow-scene-override-associated-apps</key>
+	<true/>
 	<key>com.apple.private.security.container-required</key>
 	<true/>
 	<key>com.apple.private.sessionkit.custom-platter-target</key>

```

### 🆕 capturesettingsdiagnostics

> `/System/Library/CoreServices/capturesettingsdiagnostics`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.security.application-groups</key>
	<array>
		<string>com.apple.settingshost.diagnostics</string>
	</array>
</dict>
</plist>

```
### navd

> `/System/Library/CoreServices/navd`

```diff

 	<true/>
 	<key>com.apple.mobile.deleted.AllowFreeSpace</key>
 	<true/>
+	<key>com.apple.private.assets.accessible-asset-types</key>
+	<array>
+		<string>com.apple.MobileAsset.UAF.Siri.TextToSpeech</string>
+	</array>
 	<key>com.apple.private.coreservices.canmaplsdatabase</key>
 	<true/>
 	<key>com.apple.private.network.socket-delegate</key>

```
### ControlCenterSettings

> `/System/Library/ExtensionKit/Extensions/ControlCenterSettings.appex/Contents/MacOS/ControlCenterSettings`

```diff

 	</array>
 	<key>com.apple.private.controlcenter.controlcentermodule</key>
 	<true/>
+	<key>com.apple.private.networkextension.configuration</key>
+	<true/>
 	<key>com.apple.private.security.restricted-application-groups</key>
 	<array>
 		<string>group.com.apple.controlcenter</string>

 	</array>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.nehelper</string>
 		<string>com.apple.sessionservices</string>
 		<string>com.apple.controlcenter.controlcentermodule</string>
 	</array>

```
### ControlCenterSettingsIntents

> `/System/Library/ExtensionKit/Extensions/ControlCenterSettingsIntents.appex/Contents/MacOS/ControlCenterSettingsIntents`

```diff

 	<true/>
 	<key>com.apple.private.appintents.attribution.bundle-identifier</key>
 	<string>com.apple.Settings</string>
+	<key>com.apple.private.networkextension.configuration</key>
+	<true/>
 	<key>com.apple.private.security.restricted-application-groups</key>
 	<array>
 		<string>group.com.apple.controlcenter</string>

```
### CoreMotionFoundationModelExtension

> `/System/Library/ExtensionKit/Extensions/CoreMotionFoundationModelExtension.appex/Contents/MacOS/CoreMotionFoundationModelExtension`

```diff

 		<!-- Grants access to override assets - deny lists and disabled use case list -->
 		<string>com.apple.MobileAsset.UAF.FM.Overrides</string>
         <string>com.apple.MobileAsset.UAF.CoreMotion.Overrides</string>
-		<!-- grants access to anomaly fm assets -->
-        <string>com.apple.MobileAsset.UAF.MotionAnomalyFM</string>
 	</array>
 
 

 		<!-- Grants access to model assets -->
 		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_GenerativeModels/purpose_auto/</string>
 		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_CoreMotion_IMUFoundationModel/purpose_auto/</string>
-		<!-- Grants access to anomaly fm assets -->
-		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_MotionAnomalyFM/purpose_auto/</string>
 		<!-- Grants access to override assets - deny lists and disabled use case list -->
 		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_Overrides/purpose_auto/</string>
 		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_CoreMotion_IMUFoundationModel_Overrides/purpose_auto/</string>

 		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_CoreMotion_IMUFoundationModel/</string>
 		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_CoreMotion_IMUFoundationModel/</string>
 
-		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_MotionAnomalyFM/</string>
-		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_MotionAnomalyFM/</string>
-
 		<!-- Grants access to override assets - deny lists and disabled use case list -->
 		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_FM_Overrides/</string>
 		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_FM_Overrides/</string>

```
### FedAutoEvalPlugin

> `/System/Library/ExtensionKit/Extensions/FedAutoEvalPlugin.appex/Contents/MacOS/FedAutoEvalPlugin`

```diff

 		<string>com.apple.UnifiedAssetFramework</string>
 		<string>com.apple.modelcatalog.ajax</string>
 	</array>
+	<key>com.apple.security.exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.priml.crashrecords</string>
+		<string>com.apple.priml.participations</string>
+		<string>com.apple.priml.submissioncooldown</string>
+	</array>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.spotlight.IndexAgent</string>

```

### 🆕 MotionAnomalyFMExtension

> `/System/Library/ExtensionKit/Extensions/MotionAnomalyFMExtension.appex/Contents/MacOS/MotionAnomalyFMExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple Computer//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
    <key>com.apple.security.iokit-user-client-class</key>
	<array>
		<string>H11ANEInDirectPathClient</string>
		<string>AGXDeviceUserClient</string>
		<string>IOSurfaceRootUserClient</string>
	</array>
	<key>com.apple.aned.private.allow</key>
	<true/>
	<key>com.apple.aned.private.ANEAccess.allow</key>
	<true/>
	<key>com.apple.private.security.no-sandbox</key>
	<true/>

	<key>com.apple.modelmanager.inference</key>
	<true/>
	<key>com.apple.modelcatalog.full-access</key>
	<true/>
	<key>com.apple.private.assets.accessible-asset-types</key>
	<array>
		<!-- Grants access to AnomalyFM model assets -->
        <string>com.apple.MobileAsset.UAF.MotionAnomalyFM</string>
		<!-- Grants access to override assets - deny lists and disabled use case list -->
		<string>com.apple.MobileAsset.UAF.FM.Overrides</string>
	</array>

	<!-- File System -->
	<key>com.apple.security.exception.files.absolute-path.read-only</key>
	<array>
		<!-- Grants the sandboxed client process access to create a short term lock on the asset set -->
		<string>/private/var/MobileAsset/AssetsV2/locks/com.apple.UnifiedAssetFramework/</string>

		<!-- Grants the sandboxed client process access to read AnomalyFM assets -->
		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_MotionAnomalyFM/purpose_auto/</string>
		<!-- Grants access to override assets - deny lists and disabled use case list -->
		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_Overrides/purpose_auto/</string>

		<!-- Access to read preinstalled assets -->
		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_MotionAnomalyFM/</string>
		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_MotionAnomalyFM/</string>

		<!-- Grants access to override assets - deny lists and disabled use case list -->
		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_FM_Overrides/</string>
		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_FM_Overrides/</string>
	</array>

	<!-- UserDefaults -->
	<key>com.apple.security.exception.shared-preference.read-only</key>
	<array>
		<!-- Access to UAF UserDefaults -->
		<string>com.apple.UnifiedAssetFramework</string>

		<!-- Access to AJAX override UserDefaults -->
		<string>com.apple.modelcatalog.ajax</string>
	</array>

	<!-- XPC -->
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.modelmanager</string>
		<!-- Grants access to XPC with modelcatalogd -->
		<string>com.apple.modelcatalog.catalog</string>

		<!-- Needed to talk to UAF to do subscribe and unsubscribe -->
		<string>com.apple.siri.uaf.service</string>

		<!-- Grants access to XPC with mobileassetd -->
		<string>com.apple.mobileasset.autoasset</string>

		<!-- Needed for asset roots to work -->
		<string>com.apple.mobileassetd.v2</string>
	</array>
</dict>
</plist>

```

### 🆕 PFLSamplePlugin

> `/System/Library/ExtensionKit/Extensions/PFLSamplePlugin.appex/Contents/MacOS/PFLSamplePlugin`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.priml.pfl.PFLSamplePlugin</string>
	<key>com.apple.developer.icloud-container-environment</key>
	<string>production</string>
	<key>com.apple.developer.icloud-container-identifiers</key>
	<array>
		<string>com.apple.priml.dev.container</string>
		<string>com.apple.priml.preprod.container</string>
		<string>com.apple.priml.prod.container</string>
	</array>
	<key>com.apple.developer.icloud-services</key>
	<array>
		<string>CloudKit</string>
	</array>
	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
	<string>com.apple.priml.pfl.plugins</string>
	<key>com.apple.generativeexperiences.availabilityService</key>
	<true/>
	<key>com.apple.mediaanalysisd.client</key>
	<true/>
	<key>com.apple.modelcatalog.full-access</key>
	<true/>
	<key>com.apple.modelmanager.inference</key>
	<true/>
	<key>com.apple.priml.pfl.Morpheus.allowed</key>
	<true/>
	<key>com.apple.private.appleaccount.app-hidden-from-icloud-settings</key>
	<true/>
	<key>com.apple.private.assets.accessible-asset-types</key>
	<array>
		<string>com.apple.MobileAsset.UAF.FM.GenerativeModels</string>
		<string>com.apple.MobileAsset.UAF.FM.Overrides</string>
	</array>
	<key>com.apple.private.biome.read-only</key>
	<array>
		<string>Lighthouse.Ledger.TaskCustomEvent</string>
	</array>
	<key>com.apple.private.biome.writer</key>
	<array>
		<string>Lighthouse.Ledger.TaskCustomEvent</string>
	</array>
	<key>com.apple.private.cloudkit.masquerade</key>
	<true/>
	<key>com.apple.private.cloudkit.setEnvironment</key>
	<true/>
	<key>com.apple.private.cloudkit.spi</key>
	<true/>
	<key>com.apple.private.cloudkit.systemService</key>
	<true/>
	<key>com.apple.private.coreservices.canmaplsdatabase</key>
	<true/>
	<key>com.apple.private.dprivacyd.allow</key>
	<true/>
	<key>com.apple.private.dprivacyd.metadata.allow</key>
	<true/>
	<key>com.apple.private.intelligenceplatform.use-cases</key>
	<dict>
		<key>MLHostTelemetry</key>
		<dict>
			<key>Streams</key>
			<array>
				<string>Lighthouse.Ledger.TaskCustomEvent</string>
			</array>
		</dict>
	</dict>
	<key>com.apple.private.security.storage.MobileAssetGenerativeModels</key>
	<true/>
	<key>com.apple.private.tcc.allow</key>
	<array>
		<string>kTCCServiceLiverpool</string>
	</array>
	<key>com.apple.security.exception.files.absolute-path.read-only</key>
	<array>
		<string>/private/var/MobileAsset/AssetsV2/locks/com.apple.UnifiedAssetFramework/</string>
		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_GenerativeModels/purpose_auto/</string>
		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_Overrides/purpose_auto/</string>
		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_FM_GenerativeModels/</string>
		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_FM_Overrides/</string>
		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_FM_GenerativeModels/</string>
		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_FM_Overrides/</string>
		<string>/private/var/mobile/Library/com.apple.modelcatalog/sideload/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.mlhostd.xpc</string>
		<string>com.apple.cloudd</string>
		<string>com.apple.modelcatalog.catalog</string>
		<string>com.apple.modelmanager</string>
		<string>com.apple.siri.uaf.service</string>
		<string>com.apple.mobileasset.autoasset</string>
		<string>com.apple.mobileassetd.v2</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.gms.availability</string>
		<string>com.apple.UnifiedAssetFramework</string>
		<string>com.apple.modelcatalog.ajax</string>
		<string>com.apple.GenerativeFunctions.GenerativeFunctionsInstrumentation</string>
		<string>kCFPreferencesAnyApplication</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.priml.crashrecords</string>
		<string>com.apple.priml.participations</string>
		<string>com.apple.priml.submissioncooldown</string>
	</array>
</dict>
</plist>

```

### 🆕 SafariFeatureUploadWorker

> `/System/Library/ExtensionKit/Extensions/SafariFeatureUploadWorker.appex/Contents/MacOS/SafariFeatureUploadWorker`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>abs-client</key>
	<string>1821501079</string>
	<key>application-identifier</key>
	<string>com.apple.unilog.SafariFeatureUploadWorker</string>
	<key>com.apple.developer.networking.multipath_extended</key>
	<true/>
	<key>com.apple.private.biome.read-only</key>
	<array>
		<string>Unilog.SafariFeature.Aggregation</string>
	</array>
	<key>com.apple.private.intelligenceplatform.client-identifier</key>
	<string>com.apple.unilog.datacollector.SafariFeatureUploadWorker</string>
	<key>com.apple.private.intelligenceplatform.use-cases</key>
	<dict>
		<key>UnilogSafariFeatureAggregation</key>
		<dict>
			<key>Streams</key>
			<dict>
				<key>Unilog.SafariFeature.Aggregation</key>
				<dict>
					<key>mode</key>
					<string>read-only</string>
				</dict>
			</dict>
		</dict>
		<key>com.apple.aiml.unilog.healthTelemetry</key>
		<dict>
			<key>Streams</key>
			<dict>
				<key>Unilog.HealthAggregatedSummary</key>
				<dict>
					<key>mode</key>
					<string>read-only</string>
				</dict>
				<key>Unilog.HealthTelemetry</key>
				<dict>
					<key>mode</key>
					<string>read-write</string>
				</dict>
			</dict>
		</dict>
	</dict>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.application-groups</key>
	<array>
		<string>com.apple.SafariFeatureUploadWorker</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.biome.access.user</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.SafariFeatureUploadWorker</string>
	</array>
	<key>com.apple.security.network.client</key>
	<true/>
	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.biome.access.user</string>
	</array>
	<key>com.apple.security.temporary-exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.SafariFeatureUploadWorker</string>
	</array>
	<key>fairplay-client</key>
	<string>511712240</string>
	<key>keychain-access-groups</key>
	<array>
		<string>com.apple.siri.osprey</string>
	</array>
</dict>
</plist>

```

### 🆕 SafariFeatureUsageRetentionExtension

> `/System/Library/ExtensionKit/Extensions/SafariFeatureUsageRetentionExtension.appex/Contents/MacOS/SafariFeatureUsageRetentionExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.safari.SafariFeatureUsageRetentionExtension</string>
	<key>com.apple.private.intelligenceplatform.client-identifier</key>
	<string>com.apple.safari.SafariFeatureUsageRetentionExtension</string>
	<key>com.apple.private.intelligenceplatform.use-cases</key>
	<dict>
		<key>SafariFeatureUsageRetention</key>
		<dict>
			<key>Streams</key>
			<dict>
				<key>Lighthouse.Ledger.TaskCustomEvent</key>
				<dict>
					<key>mode</key>
					<string>read-write</string>
				</dict>
				<key>Unilog.SafariFeature.Aggregation</key>
				<dict>
					<key>mode</key>
					<string>read-write</string>
				</dict>
				<key>Unilog.SafariFeature.Stage</key>
				<dict>
					<key>mode</key>
					<string>read-only</string>
				</dict>
			</dict>
		</dict>
		<key>UnilogInstrumentation.IdentifierProvider</key>
		<dict>
			<key>Streams</key>
			<dict>
				<key>Unilog.SafariFeature.LongTermAggregationId</key>
				<dict>
					<key>mode</key>
					<string>read-write</string>
				</dict>
			</dict>
		</dict>
		<key>com.apple.aiml.unilog.healthTelemetry</key>
		<dict>
			<key>Streams</key>
			<dict>
				<key>Unilog.HealthTelemetry</key>
				<dict>
					<key>mode</key>
					<string>read-write</string>
				</dict>
			</dict>
		</dict>
	</dict>
	<key>com.apple.private.mlhost.allowedDictionaryGroups</key>
	<array>
		<string>SafariFeatureUsageRetention</string>
	</array>
	<key>com.apple.private.mlhost.dictionaryDelete</key>
	<true/>
	<key>com.apple.private.mlhost.dictionaryRead</key>
	<true/>
	<key>com.apple.private.mlhost.dictionaryWrite</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.biome.access.user</string>
		<string>com.apple.mlhostd.xpc</string>
	</array>
	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.biome.access.user</string>
		<string>com.apple.mlhostd.xpc</string>
	</array>
</dict>
</plist>

```
### SiriASRScoringExtension

> `/System/Library/ExtensionKit/Extensions/SiriASRScoringExtension.appex/Contents/MacOS/SiriASRScoringExtension`

```diff

 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.private.siriappintentsd.orchestrator</string>
+		<string>com.apple.siri.analytics.assistant</string>
 	</array>
 </dict>
 </plist>

```
### SiriLogProcessor

> `/System/Library/ExtensionKit/Extensions/SiriLogProcessor.appex/Contents/MacOS/SiriLogProcessor`

```diff

 		<string>com.apple.feedbacklogger</string>
 		<string>com.apple.aiml.siri.OLEOrchestrator</string>
 	</array>
+	<key>com.apple.security.exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.siri.analytics.assistant</string>
+	</array>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.siri.analytics.assistant</string>
 		<string>com.apple.feedbacklogger</string>
 		<string>com.apple.aiml.siri.OLEOrchestrator</string>
 	</array>
+	<key>com.apple.security.temporary-exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.siri.analytics.assistant</string>
+	</array>
 	<key>com.apple.siri.analytics.assistant</key>
 	<array>
 		<string>runtime.host</string>

```
### SiriSuggestionsLightHousePlugin

> `/System/Library/ExtensionKit/Extensions/SiriSuggestionsLightHousePlugin.appex/Contents/MacOS/SiriSuggestionsLightHousePlugin`

```diff

 	<key>com.apple.security.exception.shared-preference.read-only</key>
 	<array>
 		<string>com.apple.assistant.backedup</string>
+		<string>com.apple.assistant.public</string>
 		<string>com.apple.assistant.settings</string>
 		<string>com.apple.ironwood.support</string>
 	</array>

 	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
 	<array>
 		<string>com.apple.assistant.backedup</string>
+		<string>com.apple.assistant.public</string>
 	</array>
 	<key>com.apple.siri.VoiceShortcuts.xpc</key>
 	<true/>

```
### SiriTranscriptScoringExtension

> `/System/Library/ExtensionKit/Extensions/SiriTranscriptScoringExtension.appex/Contents/MacOS/SiriTranscriptScoringExtension`

```diff

 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.private.siriappintentsd.orchestrator</string>
+		<string>com.apple.siri.analytics.assistant</string>
 	</array>
 </dict>
 </plist>

```
### frauddefensepfl

> `/System/Library/ExtensionKit/Extensions/frauddefensepfl.appex/Contents/MacOS/frauddefensepfl`

```diff

 	</array>
 	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
 	<string>com.apple.priml.pfl.plugins</string>
+	<key>com.apple.mediaanalysisd.client</key>
+	<true/>
 	<key>com.apple.priml.pfl.Morpheus.allowed</key>
 	<true/>
 	<key>com.apple.private.appleaccount.app-hidden-from-icloud-settings</key>
 	<true/>
+	<key>com.apple.private.assets.accessible-asset-types</key>
+	<array>
+		<string>com.apple.MobileAsset.UAF.FM.GenerativeModels</string>
+		<string>com.apple.MobileAsset.UAF.FM.Overrides</string>
+	</array>
 	<key>com.apple.private.biome.writer</key>
 	<array>
 		<string>Lighthouse.Ledger.TaskCustomEvent</string>

 	<true/>
 	<key>com.apple.private.cloudkit.systemService</key>
 	<true/>
+	<key>com.apple.private.coreservices.canmaplsdatabase</key>
+	<true/>
 	<key>com.apple.private.dprivacyd.allow</key>
 	<true/>
 	<key>com.apple.private.dprivacyd.metadata.allow</key>
 	<true/>
+	<key>com.apple.private.imcore.imdpersistence.database-access</key>
+	<true/>
 	<key>com.apple.private.intelligenceplatform.use-cases</key>
 	<dict>
 		<key>MLHostTelemetry</key>

 			</array>
 		</dict>
 	</dict>
+	<key>com.apple.private.security.storage.MobileAssetGenerativeModels</key>
+	<true/>
 	<key>com.apple.private.tcc.allow</key>
 	<array>
 		<string>kTCCServiceLiverpool</string>
 	</array>
+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/MobileAsset/AssetsV2/locks/com.apple.UnifiedAssetFramework/</string>
+		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_GenerativeModels/purpose_auto/</string>
+		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_Overrides/purpose_auto/</string>
+		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_FM_GenerativeModels/</string>
+		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_FM_Overrides/</string>
+		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_FM_GenerativeModels/</string>
+		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_FM_Overrides/</string>
+		<string>/private/var/mobile/Library/com.apple.modelcatalog/sideload/</string>
+	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.mlhostd.xpc</string>
 		<string>com.apple.cloudd</string>
+		<string>com.apple.imdpersistence.IMDPersistenceAgent</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-write</key>
 	<array>

```

### 🆕 SiriFindMyFlowTools

> `/System/Library/FlowTools/Tools/SiriFindMyFlowTools.flowtool/Contents/MacOS/SiriFindMyFlowTools`

- No entitlements *(yet)*
### com.apple.AddressBook.ABPersonViewService

> `/System/Library/Frameworks/AddressBook.framework/Versions/A/XPCServices/com.apple.AddressBook.ABPersonViewService.xpc/Contents/MacOS/com.apple.AddressBook.ABPersonViewService`

```diff

 	<true/>
 	<key>com.apple.private.screen-time</key>
 	<true/>
+	<key>com.apple.private.screen-time-settings</key>
+	<true/>
 	<key>com.apple.private.suggestions</key>
 	<true/>
 	<key>com.apple.private.tcc.allow</key>

 		<string>com.apple.identityservicesd.idquery.desktop.auth</string>
 		<string>com.apple.corerecents.recentsd</string>
 		<string>com.apple.ScreenTimeAgent.Contacts</string>
+		<string>com.apple.ScreenTimeSettingsAgent.private</string>
 	</array>
 	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
 	<array>

```
### com.apple.AddressBook.ABPersonViewService

> `/System/Library/Frameworks/AddressBook.framework/Versions/Current/XPCServices/com.apple.AddressBook.ABPersonViewService.xpc/Contents/MacOS/com.apple.AddressBook.ABPersonViewService`

```diff

 	<true/>
 	<key>com.apple.private.screen-time</key>
 	<true/>
+	<key>com.apple.private.screen-time-settings</key>
+	<true/>
 	<key>com.apple.private.suggestions</key>
 	<true/>
 	<key>com.apple.private.tcc.allow</key>

 		<string>com.apple.identityservicesd.idquery.desktop.auth</string>
 		<string>com.apple.corerecents.recentsd</string>
 		<string>com.apple.ScreenTimeAgent.Contacts</string>
+		<string>com.apple.ScreenTimeSettingsAgent.private</string>
 	</array>
 	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
 	<array>

```
### spotlightknowledged

> `/System/Library/Frameworks/CoreSpotlight.framework/spotlightknowledged`

```diff

 	<true/>
 	<key>com.apple.tailspin.dump-output</key>
 	<true/>
+	<key>com.apple.trial.client</key>
+	<array>
+		<string>333</string>
+		<string>336</string>
+	</array>
 </dict>
 </plist>
 

```
### PhotosViewService

> `/System/Library/Frameworks/PhotosUI.framework/Versions/A/XPCServices/PhotosViewService.xpc/Contents/MacOS/PhotosViewService`

```diff

 	<array>
 		<string>CloudKit</string>
 	</array>
+	<key>com.apple.private.LocalAuthentication.CallerName</key>
+	<true/>
+	<key>com.apple.private.LocalAuthentication.CallerPID</key>
+	<true/>
 	<key>com.apple.private.cloudphotod.access</key>
 	<true/>
 	<key>com.apple.private.familycircle</key>

```
### AppPredictionWidgetDiagnosticExtension

> `/System/Library/PrivateFrameworks/AppPredictionInternal.framework/PlugIns/AppPredictionWidgetDiagnosticExtension.appex/Contents/MacOS/AppPredictionWidgetDiagnosticExtension`

```diff

 		<string>SemanticLocation</string>
 		<string>HomeKitClientAccessoryControl</string>
 	</array>
+	<key>com.apple.private.coreservices.canmaplsdatabase</key>
+	<true/>
 	<key>com.apple.private.hid.client.event-monitor</key>
 	<true/>
 	<key>com.apple.private.intelligenceplatform.use-cases</key>

 	<true/>
 	<key>com.apple.proactive.UsageInsights</key>
 	<true/>
+	<key>com.apple.proactive.appDirectory</key>
+	<true/>
 	<key>com.apple.proactive.eventtracker</key>
 	<true/>
 	<key>com.apple.rootless.storage.coreduet_knowledge_store</key>

 		<string>com.apple.duet.expertcenter</string>
 		<string>com.apple.lsd.xpc</string>
 		<string>com.apple.ModeEntityScorer</string>
+		<string>com.apple.proactive.appDirectory</string>
 		<string>com.apple.proactive.SuggestedPages</string>
 		<string>com.apple.routined.registration</string>
 		<string>com.apple.usernotifications.usernotificationsettingsservice</string>

```
### AMSFollowUpExtension

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/PlugIns/AMSFollowUpExtension.appex/Contents/MacOS/AMSFollowUpExtension`

```diff

 	<true/>
 	<key>com.apple.private.applemediaservices</key>
 	<true/>
+	<key>com.apple.private.appstorecomponents.small-offer-button</key>
+	<true/>
 	<key>com.apple.private.appstored</key>
 	<array>
 		<string>Library</string>

```
### callintelligenced

> `/System/Library/PrivateFrameworks/CallIntelligence.framework/callintelligenced`

```diff

 	<true/>
 	<key>com.apple.coretelephony.Identity.get</key>
 	<true/>
+	<key>com.apple.duet.activityscheduler.allow</key>
+	<true/>
 	<key>com.apple.facetimemessagestored.service</key>
 	<array>
 		<string>access-facetime-messaging</string>

 		<string>com.apple.PerfPowerTelemetryClientRegistrationService</string>
 		<string>com.apple.TextUnderstanding.process</string>
 		<string>com.apple.generativeexperiences.agentSessionStore</string>
+		<string>com.apple.duetactivityscheduler</string>
 	</array>
 	<key>com.apple.security.exception.mach-lookup.xpc-service-name</key>
 	<array>

```
### accessoryd

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/Support/accessoryd`

```diff

 	</array>
 	<key>com.apple.private.ZhuGeSupport.CopyValue</key>
 	<true/>
+	<key>com.apple.private.accessories.transport-client</key>
+	<true/>
 	<key>com.apple.private.hid.client.event-monitor</key>
 	<true/>
 	<key>com.apple.private.notificationcenter-system</key>

```
### parsecd

> `/System/Library/PrivateFrameworks/CoreParsec.framework/parsecd`

```diff

 	<true/>
 	<key>com.apple.managedconfiguration.profiled-access</key>
 	<true/>
+	<key>com.apple.nano.nanoregistry.generalaccess</key>
+	<true/>
 	<key>com.apple.private.MobileGestalt.AllowedProtectedKeys</key>
 	<array>
 		<string>RegionCode</string>

```
### BluetoothHeadset

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/BluetoothHeadset.appex/Contents/MacOS/BluetoothHeadset`

```diff

 	<array>
 		<string>com.apple.BTLELoggingManager.xpc</string>
 		<string>com.apple.bluetooth.xpc</string>
+		<string>com.apple.bluetoothuser.xpc</string>
 	</array>
 	<key>com.apple.security.temporary-exception.files.absolute-path.read-only</key>
 	<array>

```
### DraftingExtension-macOS

> `/System/Library/PrivateFrameworks/Feedback.framework/PlugIns/DraftingExtension-macOS.appex/Contents/MacOS/DraftingExtension-macOS`

```diff

 	<key>com.apple.security.temporary-exception.files.absolute-path.read-only</key>
 	<array>
 		<string>/private/var/db/com.apple.countryd/</string>
+		<string>/AppleInternal/Library/Application Support/com.apple.feedback/</string>
 	</array>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
 	<array>

```
### intelligenceplatformd

> `/System/Library/PrivateFrameworks/IntelligencePlatformCore.framework/Versions/A/intelligenceplatformd`

```diff

 		<string>kTCCServicePhotos</string>
 		<string>kTCCServiceWillow</string>
 	</array>
+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>
 	<key>com.apple.private.usage-tracking</key>
 	<true/>
 	<key>com.apple.proactive.eventtracker</key>

```
### knowledgeconstructiond

> `/System/Library/PrivateFrameworks/IntelligencePlatformCore.framework/Versions/A/knowledgeconstructiond`

```diff

 		<string>kTCCServicePhotos</string>
 		<string>kTCCServiceWillow</string>
 	</array>
+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>
 	<key>com.apple.private.usage-tracking</key>
 	<true/>
 	<key>com.apple.proactive.PersonalizationPortrait.Contact</key>

```
### com.apple.photos.VideoConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/Versions/A/XPCServices/com.apple.photos.VideoConversionService.xpc/Contents/MacOS/com.apple.photos.VideoConversionService`

```diff

 	<true/>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/MobileAsset/AssetsV2/locks/com.apple.UnifiedAssetFramework/</string>
+	</array>
+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/UnifiedAssetFramework/</string>
+	</array>
+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.siri.uaf.service</string>
+		<string>com.apple.siri.uaf.subscription.service</string>
+		<string>com.apple.mobileasset.autoasset</string>
+		<string>com.apple.mobileassetd.v2</string>
+	</array>
+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.UnifiedAssetFramework</string>
+		<string>com.apple.AppleDepth</string>
+	</array>
 	<key>com.apple.security.hardened-process</key>
 	<true/>
 	<key>com.apple.security.hardened-process.checked-allocations</key>

```
### com.apple.photos.VideoConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/Versions/Current/XPCServices/com.apple.photos.VideoConversionService.xpc/Contents/MacOS/com.apple.photos.VideoConversionService`

```diff

 	<true/>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/MobileAsset/AssetsV2/locks/com.apple.UnifiedAssetFramework/</string>
+	</array>
+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/UnifiedAssetFramework/</string>
+	</array>
+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.siri.uaf.service</string>
+		<string>com.apple.siri.uaf.subscription.service</string>
+		<string>com.apple.mobileasset.autoasset</string>
+		<string>com.apple.mobileassetd.v2</string>
+	</array>
+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.UnifiedAssetFramework</string>
+		<string>com.apple.AppleDepth</string>
+	</array>
 	<key>com.apple.security.hardened-process</key>
 	<true/>
 	<key>com.apple.security.hardened-process.checked-allocations</key>

```
### SiriSuggestionsBookkeepingService

> `/System/Library/PrivateFrameworks/SiriSuggestionsSupport.framework/Versions/A/XPCServices/SiriSuggestionsBookkeepingService.xpc/Contents/MacOS/SiriSuggestionsBookkeepingService`

```diff

 		<string>com.apple.assistant.backedup</string>
 		<string>com.apple.assistant.settings</string>
 		<string>com.apple.suggestions</string>
+		<string>com.apple.assistant.public</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-write</key>
 	<array>

```
### SiriSuggestionsBookkeepingService

> `/System/Library/PrivateFrameworks/SiriSuggestionsSupport.framework/Versions/Current/XPCServices/SiriSuggestionsBookkeepingService.xpc/Contents/MacOS/SiriSuggestionsBookkeepingService`

```diff

 		<string>com.apple.assistant.backedup</string>
 		<string>com.apple.assistant.settings</string>
 		<string>com.apple.suggestions</string>
+		<string>com.apple.assistant.public</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-write</key>
 	<array>

```
### ContactViewViewService

> `/System/iOSSupport/System/Library/Frameworks/ContactsUI.framework/PlugIns/ContactViewViewService.appex/Contents/MacOS/ContactViewViewService`

```diff

 	<true/>
 	<key>com.apple.private.screen-time</key>
 	<true/>
+	<key>com.apple.private.screen-time-settings</key>
+	<true/>
 	<key>com.apple.private.screentime-communication</key>
 	<true/>
 	<key>com.apple.private.security.storage.CallHistory</key>

 		<string>com.apple.biome.access.user</string>
 		<string>com.apple.biome.compute.source</string>
 		<string>com.apple.ScreenTimeAgent.communication</string>
+		<string>com.apple.ScreenTimeSettingsAgent.private</string>
 		<string>com.apple.appprotectiond.read</string>
 		<string>com.apple.Archetype.personalContext</string>
 		<string>com.apple.familycircle.agent</string>

```
### ContactsViewService

> `/System/iOSSupport/System/Library/Frameworks/ContactsUI.framework/PlugIns/ContactsViewService.appex/Contents/MacOS/ContactsViewService`

```diff

 	<true/>
 	<key>com.apple.private.screen-time</key>
 	<true/>
+	<key>com.apple.private.screen-time-settings</key>
+	<true/>
 	<key>com.apple.private.screentime-communication</key>
 	<true/>
 	<key>com.apple.private.security.storage.CallHistory</key>

 		<string>com.apple.biome.access.user</string>
 		<string>com.apple.biome.compute.source</string>
 		<string>com.apple.ScreenTimeAgent.communication</string>
+		<string>com.apple.ScreenTimeSettingsAgent.private</string>
 		<string>com.apple.appprotectiond.read</string>
 		<string>com.apple.Archetype.personalContext</string>
 		<string>com.apple.familycircle.agent</string>

```
### nfsd

> `/sbin/nfsd`

```diff

 <dict>
 	<key>com.apple.private.system-nfssvc</key>
 	<true/>
+	<key>com.apple.private.xpc.launchd.system-job-bootstrap</key>
+	<true/>
 </dict>
 </plist>
 

```
### feedbackd

> `/usr/libexec/feedbackd`

```diff

 	<key>com.apple.security.exception.files.absolute-path.read-only</key>
 	<array>
 		<string>/private/var/db/com.apple.countryd/</string>
+		<string>/AppleInternal/Library/Application Support/com.apple.feedback/</string>
 	</array>
 	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
 	<array>

```
### generativelearningd

> `/usr/libexec/generativelearningd`

```diff

 		<string>GenerativeModels.GenerativeFunctions.Events</string>
 		<string>GenerativeModels.GenerativeFunctions.ModelIO</string>
 	</array>
+	<key>com.apple.private.corepersonalization.client.workflowExecution</key>
+	<true/>
 	<key>com.apple.private.generativesearch.client.index</key>
 	<true/>
 	<key>com.apple.private.generativesearch.client.search</key>

```
### mdmclient

> `/usr/libexec/mdmclient`

```diff

 	<array>
 		<string>com.apple.mdmclient.usernotifications.v2</string>
 	</array>
+	<key>com.apple.private.xpc.smd-job-submit</key>
+	<true/>
 	<key>com.apple.rootless.storage.ConfigurationProfilesPrivate</key>
 	<true/>
 	<key>com.apple.rootless.volume.iSCPreboot</key>

```
### modelmanagerd

> `/usr/libexec/modelmanagerd`

```diff

 		<string>com.apple.MobileAsset.UAF.FM.Overrides</string>
 		<string>com.apple.MobileAsset.UAF.FM.Visual</string>
 		<string>com.apple.MobileAsset.UAF.IF.Planner</string>
+		<string>com.apple.MobileAsset.UAF.MotionAnomalyFM</string>
 		<string>com.apple.MobileAsset.UAF.Music.ConcertsRanking</string>
 		<string>com.apple.MobileAsset.UAF.Photos.SpatialPhotosRelive</string>
 		<string>com.apple.MobileAsset.UAF.Translation.Assets</string>

 		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_Photos_SpatialPhotosRelive/</string>
 		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_IF_Planner/</string>
 		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_IF_PlannerOverrides/</string>
+		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_MotionAnomalyFM/</string>
 		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_Music_ConcertsRanking/</string>
 		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_Siri_DialogAssets/</string>
 		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_Siri_FindMyConfigurationFiles/</string>

 		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_Photos_SpatialPhotosRelive/</string>
 		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_IF_Planner/</string>
 		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_IF_PlannerOverrides/</string>
+		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_MotionAnomalyFM/</string>
 		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_Music_ConcertsRanking/</string>
 		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_Siri_DialogAssets/</string>
 		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_Siri_FindMyConfigurationFiles/</string>

```
### rapportd

> `/usr/libexec/rapportd`

```diff

 	</array>
 	<key>com.apple.private.homekit</key>
 	<true/>
+	<key>com.apple.private.homekit.home-location</key>
+	<true/>
 	<key>com.apple.private.homekit.pairing-identity</key>
 	<true/>
 	<key>com.apple.private.homekit.pairing-identity.private</key>

```
### spotlightknowledged.graph

> `/usr/libexec/spotlightknowledged.graph`

```diff

 	<true/>
 	<key>com.apple.tailspin.dump-output</key>
 	<true/>
+	<key>com.apple.trial.client</key>
+	<array>
+		<string>333</string>
+		<string>336</string>
+	</array>
 </dict>
 </plist>
 

```
### spotlightknowledged.importer

> `/usr/libexec/spotlightknowledged.importer`

```diff

 	<true/>
 	<key>com.apple.tailspin.dump-output</key>
 	<true/>
+	<key>com.apple.trial.client</key>
+	<array>
+		<string>333</string>
+		<string>336</string>
+	</array>
 </dict>
 </plist>
 

```
### spotlightknowledged.updater

> `/usr/libexec/spotlightknowledged.updater`

```diff

 	<true/>
 	<key>com.apple.tailspin.dump-output</key>
 	<true/>
+	<key>com.apple.trial.client</key>
+	<array>
+		<string>333</string>
+		<string>336</string>
+	</array>
 </dict>
 </plist>
 

```
### rpc.lockd

> `/usr/sbin/rpc.lockd`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>com.apple.private.xpc.launchd.system-job-bootstrap</key>
+	<true/>
+</dict>
+</plist>
 

```


