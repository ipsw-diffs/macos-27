## 🔑 Entitlements

### SystemOS

### jsc

> `/System/Library/Frameworks/JavaScriptCore.framework/Versions/A/Helpers/jsc`

```diff

 	<true/>
 	<key>com.apple.private.verified-jit</key>
 	<true/>
+	<key>com.apple.private.verified-jit-mode</key>
+	<integer>1</integer>
 	<key>com.apple.security.cs.allow-jit</key>
 	<true/>
 	<key>com.apple.security.cs.jit-write-allowlist</key>

```
### com.apple.SafariServices

> `/System/Library/Frameworks/SafariServices.framework/Versions/A/XPCServices/com.apple.SafariServices.xpc/Contents/MacOS/com.apple.SafariServices`

```diff

 <dict>
 	<key>com.apple.private.accounts.allaccounts</key>
 	<true/>
+	<key>com.apple.private.coreservices.canopenactivity</key>
+	<true/>
 	<key>com.apple.private.security.storage.Safari</key>
 	<true/>
 	<key>keychain-access-groups</key>

```
### com.apple.SafariServices

> `/System/Library/Frameworks/SafariServices.framework/Versions/Current/XPCServices/com.apple.SafariServices.xpc/Contents/MacOS/com.apple.SafariServices`

```diff

 <dict>
 	<key>com.apple.private.accounts.allaccounts</key>
 	<true/>
+	<key>com.apple.private.coreservices.canopenactivity</key>
+	<true/>
 	<key>com.apple.private.security.storage.Safari</key>
 	<true/>
 	<key>keychain-access-groups</key>

```
### com.apple.WebKit.WebContent.CaptivePortal

> `/System/Library/Frameworks/WebKit.framework/Versions/A/XPCServices/com.apple.WebKit.WebContent.CaptivePortal.xpc/Contents/MacOS/com.apple.WebKit.WebContent.CaptivePortal`

```diff

 		<string>com.apple.mediaaccessibility.audibleMediaSettingsChanged</string>
 		<string>com.apple.mediaaccessibility.captionAppearanceSettingsChanged</string>
 		<string>com.apple.powerlog.state_changed</string>
+		<string>com.apple.powerlog.state_changed.ClientID.*</string>
 		<string>com.apple.preferences.sounds.keyboard-audio.changed</string>
 		<string>com.apple.runningboard.daemonstartup</string>
 		<string>com.apple.system.logging.prefschanged</string>

```
### com.apple.WebKit.WebContent.EnhancedSecurity

> `/System/Library/Frameworks/WebKit.framework/Versions/A/XPCServices/com.apple.WebKit.WebContent.EnhancedSecurity.xpc/Contents/MacOS/com.apple.WebKit.WebContent.EnhancedSecurity`

```diff

 		<string>com.apple.mediaaccessibility.audibleMediaSettingsChanged</string>
 		<string>com.apple.mediaaccessibility.captionAppearanceSettingsChanged</string>
 		<string>com.apple.powerlog.state_changed</string>
+		<string>com.apple.powerlog.state_changed.ClientID.*</string>
 		<string>com.apple.preferences.sounds.keyboard-audio.changed</string>
 		<string>com.apple.runningboard.daemonstartup</string>
 		<string>com.apple.system.logging.prefschanged</string>

```
### com.apple.WebKit.WebContent

> `/System/Library/Frameworks/WebKit.framework/Versions/A/XPCServices/com.apple.WebKit.WebContent.xpc/Contents/MacOS/com.apple.WebKit.WebContent`

```diff

 		<string>com.apple.mediaaccessibility.audibleMediaSettingsChanged</string>
 		<string>com.apple.mediaaccessibility.captionAppearanceSettingsChanged</string>
 		<string>com.apple.powerlog.state_changed</string>
+		<string>com.apple.powerlog.state_changed.ClientID.*</string>
 		<string>com.apple.preferences.sounds.keyboard-audio.changed</string>
 		<string>com.apple.runningboard.daemonstartup</string>
 		<string>com.apple.system.logging.prefschanged</string>

 	<true/>
 	<key>com.apple.private.verified-jit</key>
 	<true/>
+	<key>com.apple.private.verified-jit-mode</key>
+	<integer>1</integer>
 	<key>com.apple.private.webkit.use-xpc-endpoint</key>
 	<true/>
 	<key>com.apple.rootless.storage.WebKitWebContentSandbox</key>

```
### com.apple.WebKit.WebContent.CaptivePortal

> `/System/Library/Frameworks/WebKit.framework/Versions/Current/XPCServices/com.apple.WebKit.WebContent.CaptivePortal.xpc/Contents/MacOS/com.apple.WebKit.WebContent.CaptivePortal`

```diff

 		<string>com.apple.mediaaccessibility.audibleMediaSettingsChanged</string>
 		<string>com.apple.mediaaccessibility.captionAppearanceSettingsChanged</string>
 		<string>com.apple.powerlog.state_changed</string>
+		<string>com.apple.powerlog.state_changed.ClientID.*</string>
 		<string>com.apple.preferences.sounds.keyboard-audio.changed</string>
 		<string>com.apple.runningboard.daemonstartup</string>
 		<string>com.apple.system.logging.prefschanged</string>

```
### com.apple.WebKit.WebContent.EnhancedSecurity

> `/System/Library/Frameworks/WebKit.framework/Versions/Current/XPCServices/com.apple.WebKit.WebContent.EnhancedSecurity.xpc/Contents/MacOS/com.apple.WebKit.WebContent.EnhancedSecurity`

```diff

 		<string>com.apple.mediaaccessibility.audibleMediaSettingsChanged</string>
 		<string>com.apple.mediaaccessibility.captionAppearanceSettingsChanged</string>
 		<string>com.apple.powerlog.state_changed</string>
+		<string>com.apple.powerlog.state_changed.ClientID.*</string>
 		<string>com.apple.preferences.sounds.keyboard-audio.changed</string>
 		<string>com.apple.runningboard.daemonstartup</string>
 		<string>com.apple.system.logging.prefschanged</string>

```
### com.apple.WebKit.WebContent

> `/System/Library/Frameworks/WebKit.framework/Versions/Current/XPCServices/com.apple.WebKit.WebContent.xpc/Contents/MacOS/com.apple.WebKit.WebContent`

```diff

 		<string>com.apple.mediaaccessibility.audibleMediaSettingsChanged</string>
 		<string>com.apple.mediaaccessibility.captionAppearanceSettingsChanged</string>
 		<string>com.apple.powerlog.state_changed</string>
+		<string>com.apple.powerlog.state_changed.ClientID.*</string>
 		<string>com.apple.preferences.sounds.keyboard-audio.changed</string>
 		<string>com.apple.runningboard.daemonstartup</string>
 		<string>com.apple.system.logging.prefschanged</string>

 	<true/>
 	<key>com.apple.private.verified-jit</key>
 	<true/>
+	<key>com.apple.private.verified-jit-mode</key>
+	<integer>1</integer>
 	<key>com.apple.private.webkit.use-xpc-endpoint</key>
 	<true/>
 	<key>com.apple.rootless.storage.WebKitWebContentSandbox</key>

```
### com.apple.SafariPlatformSupport.Helper

> `/System/Library/PrivateFrameworks/SafariPlatformSupport.framework/Versions/A/XPCServices/com.apple.SafariPlatformSupport.Helper.xpc/Contents/MacOS/com.apple.SafariPlatformSupport.Helper`

```diff

 <dict>
 	<key>com.apple.accounts.appleaccount.fullaccess</key>
 	<true/>
+	<key>com.apple.ahp</key>
+	<true/>
 	<key>com.apple.appleaccount.identity.read</key>
 	<true/>
 	<key>com.apple.authentication-services.access-credential-identities</key>

 	<true/>
 	<key>com.apple.coreduetd.people</key>
 	<true/>
+	<key>com.apple.developer.usernotifications.time-sensitive</key>
+	<true/>
 	<key>com.apple.private.CoreAuthentication.SPI</key>
 	<true/>
+	<key>com.apple.private.LocalAuthentication.CallerName</key>
+	<true/>
 	<key>com.apple.private.MobileContainerManager.lookup</key>
 	<dict>
 		<key>appData</key>

 	<true/>
 	<key>com.apple.private.accounts.allaccounts</key>
 	<true/>
+	<key>com.apple.private.airdrop.client</key>
+	<true/>
 	<key>com.apple.private.applemediaservices</key>
 	<true/>
 	<key>com.apple.private.associated-domains</key>

 	</array>
 	<key>com.apple.private.coreservices.canmaplsdatabase</key>
 	<true/>
+	<key>com.apple.private.corewifi</key>
+	<true/>
+	<key>com.apple.private.corewifi.keychain</key>
+	<true/>
 	<key>com.apple.private.email</key>
 	<true/>
+	<key>com.apple.private.familycircle</key>
+	<true/>
+	<key>com.apple.private.feedback.drafting</key>
+	<true/>
 	<key>com.apple.private.hid.client.event-dispatch.internal</key>
 	<true/>
 	<key>com.apple.private.imcore.imagent</key>

 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.SharedWebCredentials</string>
+		<string>com.apple.feedbackd.centralized-feedback</string>
 	</array>
 	<key>com.apple.security.network.client</key>
 	<true/>

 		<string>org.mozilla.firefox</string>
 		<string>org.mozilla.firefoxdeveloperedition</string>
 		<string>org.mozilla.nightly</string>
+		<string>net.librewolf.librewolf</string>
 		<string>company.thebrowser.Browser</string>
 		<string>company.thebrowser.dia</string>
 		<string>com.brave.Browser</string>

 		<string>com.kagi.kagimacOS.RC</string>
 		<string>org.chromium.Chromium</string>
 		<string>app.zen-browser.zen</string>
+		<string>systems.acon.odin.browser</string>
 		<string>com.bookry.wavebox</string>
 		<string>com.quark.desktop</string>
 		<string>com.naver.Whale</string>

 		<string>com.tab-browser.Tabbit</string>
 		<string>com.tabbit-ai.Tabbit</string>
 		<string>me.bnfy.bowser</string>
+		<string>com.kavoye.Linen</string>
 	</array>
 	<key>com.apple.security.temporary-exception.files.absolute-path.read-only</key>
 	<array>

 		<string>com.apple.ind.cloudfeatures</string>
 		<string>com.apple.email.maild</string>
 		<string>com.apple.imagent.desktop.auth</string>
+		<string>com.apple.private.corewifi-xpc</string>
 		<string>com.apple.ak.privateemail.xpc</string>
 		<string>com.apple.sharing.airdrop.service</string>
 		<string>com.apple.privatecloudcompute</string>

```
### com.apple.SafariPlatformSupport.Helper

> `/System/Library/PrivateFrameworks/SafariPlatformSupport.framework/Versions/Current/XPCServices/com.apple.SafariPlatformSupport.Helper.xpc/Contents/MacOS/com.apple.SafariPlatformSupport.Helper`

```diff

 <dict>
 	<key>com.apple.accounts.appleaccount.fullaccess</key>
 	<true/>
+	<key>com.apple.ahp</key>
+	<true/>
 	<key>com.apple.appleaccount.identity.read</key>
 	<true/>
 	<key>com.apple.authentication-services.access-credential-identities</key>

 	<true/>
 	<key>com.apple.coreduetd.people</key>
 	<true/>
+	<key>com.apple.developer.usernotifications.time-sensitive</key>
+	<true/>
 	<key>com.apple.private.CoreAuthentication.SPI</key>
 	<true/>
+	<key>com.apple.private.LocalAuthentication.CallerName</key>
+	<true/>
 	<key>com.apple.private.MobileContainerManager.lookup</key>
 	<dict>
 		<key>appData</key>

 	<true/>
 	<key>com.apple.private.accounts.allaccounts</key>
 	<true/>
+	<key>com.apple.private.airdrop.client</key>
+	<true/>
 	<key>com.apple.private.applemediaservices</key>
 	<true/>
 	<key>com.apple.private.associated-domains</key>

 	</array>
 	<key>com.apple.private.coreservices.canmaplsdatabase</key>
 	<true/>
+	<key>com.apple.private.corewifi</key>
+	<true/>
+	<key>com.apple.private.corewifi.keychain</key>
+	<true/>
 	<key>com.apple.private.email</key>
 	<true/>
+	<key>com.apple.private.familycircle</key>
+	<true/>
+	<key>com.apple.private.feedback.drafting</key>
+	<true/>
 	<key>com.apple.private.hid.client.event-dispatch.internal</key>
 	<true/>
 	<key>com.apple.private.imcore.imagent</key>

 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.SharedWebCredentials</string>
+		<string>com.apple.feedbackd.centralized-feedback</string>
 	</array>
 	<key>com.apple.security.network.client</key>
 	<true/>

 		<string>org.mozilla.firefox</string>
 		<string>org.mozilla.firefoxdeveloperedition</string>
 		<string>org.mozilla.nightly</string>
+		<string>net.librewolf.librewolf</string>
 		<string>company.thebrowser.Browser</string>
 		<string>company.thebrowser.dia</string>
 		<string>com.brave.Browser</string>

 		<string>com.kagi.kagimacOS.RC</string>
 		<string>org.chromium.Chromium</string>
 		<string>app.zen-browser.zen</string>
+		<string>systems.acon.odin.browser</string>
 		<string>com.bookry.wavebox</string>
 		<string>com.quark.desktop</string>
 		<string>com.naver.Whale</string>

 		<string>com.tab-browser.Tabbit</string>
 		<string>com.tabbit-ai.Tabbit</string>
 		<string>me.bnfy.bowser</string>
+		<string>com.kavoye.Linen</string>
 	</array>
 	<key>com.apple.security.temporary-exception.files.absolute-path.read-only</key>
 	<array>

 		<string>com.apple.ind.cloudfeatures</string>
 		<string>com.apple.email.maild</string>
 		<string>com.apple.imagent.desktop.auth</string>
+		<string>com.apple.private.corewifi-xpc</string>
 		<string>com.apple.ak.privateemail.xpc</string>
 		<string>com.apple.sharing.airdrop.service</string>
 		<string>com.apple.privatecloudcompute</string>

```
### jsc

> `/System/iOSSupport/System/Library/Frameworks/JavaScriptCore.framework/Versions/A/Helpers/jsc`

```diff

 	<true/>
 	<key>com.apple.private.verified-jit</key>
 	<true/>
+	<key>com.apple.private.verified-jit-mode</key>
+	<integer>1</integer>
 	<key>com.apple.security.cs.allow-jit</key>
 	<true/>
 	<key>com.apple.security.cs.jit-write-allowlist</key>

```
### com.apple.WebKit.WebContent.Development

> `/System/iOSSupport/System/Library/Frameworks/WebKit.framework/Versions/A/XPCServices/com.apple.WebKit.WebContent.Development.xpc/Contents/MacOS/com.apple.WebKit.WebContent.Development`

```diff

 	</array>
 	<key>com.apple.private.verified-jit</key>
 	<true/>
+	<key>com.apple.private.verified-jit-mode</key>
+	<integer>1</integer>
 	<key>com.apple.private.webkit.use-xpc-endpoint</key>
 	<true/>
 	<key>com.apple.runningboard.assertions.webkit</key>

```
### com.apple.WebKit.WebContent

> `/System/iOSSupport/System/Library/Frameworks/WebKit.framework/Versions/A/XPCServices/com.apple.WebKit.WebContent.xpc/Contents/MacOS/com.apple.WebKit.WebContent`

```diff

 	</array>
 	<key>com.apple.private.verified-jit</key>
 	<true/>
+	<key>com.apple.private.verified-jit-mode</key>
+	<integer>1</integer>
 	<key>com.apple.private.webkit.use-xpc-endpoint</key>
 	<true/>
 	<key>com.apple.runningboard.assertions.webkit</key>

```
### com.apple.WebKit.WebContent.Development

> `/System/iOSSupport/System/Library/Frameworks/WebKit.framework/Versions/Current/XPCServices/com.apple.WebKit.WebContent.Development.xpc/Contents/MacOS/com.apple.WebKit.WebContent.Development`

```diff

 	</array>
 	<key>com.apple.private.verified-jit</key>
 	<true/>
+	<key>com.apple.private.verified-jit-mode</key>
+	<integer>1</integer>
 	<key>com.apple.private.webkit.use-xpc-endpoint</key>
 	<true/>
 	<key>com.apple.runningboard.assertions.webkit</key>

```
### com.apple.WebKit.WebContent

> `/System/iOSSupport/System/Library/Frameworks/WebKit.framework/Versions/Current/XPCServices/com.apple.WebKit.WebContent.xpc/Contents/MacOS/com.apple.WebKit.WebContent`

```diff

 	</array>
 	<key>com.apple.private.verified-jit</key>
 	<true/>
+	<key>com.apple.private.verified-jit-mode</key>
+	<integer>1</integer>
 	<key>com.apple.private.webkit.use-xpc-endpoint</key>
 	<true/>
 	<key>com.apple.runningboard.assertions.webkit</key>

```


### AppOS

### Safari

> `/System/Applications/Safari.app/Contents/MacOS/Safari`

```diff

 	<true/>
 	<key>com.apple.accounts.appleaccount.fullaccess</key>
 	<true/>
+	<key>com.apple.ahp</key>
+	<true/>
 	<key>com.apple.appattest.spi</key>
 	<true/>
 	<key>com.apple.appleaccount.identity.read</key>

 	<true/>
 	<key>com.apple.developer.maps</key>
 	<true/>
+	<key>com.apple.developer.usernotifications.time-sensitive</key>
+	<true/>
 	<key>com.apple.dock.add-item</key>
 	<true/>
 	<key>com.apple.duet.activityscheduler.allow</key>

 	<true/>
 	<key>com.apple.private.accounts.allaccounts</key>
 	<true/>
+	<key>com.apple.private.airdrop.client</key>
+	<true/>
 	<key>com.apple.private.app-sandbox.unquarantine</key>
 	<true/>
 	<key>com.apple.private.appintents-bundle-absolute-paths</key>

 	<true/>
 	<key>com.apple.private.coreservices.lsuseractivityd.bestappsuggestion</key>
 	<true/>
+	<key>com.apple.private.corewifi</key>
+	<true/>
+	<key>com.apple.private.corewifi.keychain</key>
+	<true/>
 	<key>com.apple.private.dmd.policy</key>
 	<true/>
 	<key>com.apple.private.dprivacyd.allow</key>

 	<true/>
 	<key>com.apple.private.extension-host.safari-extension</key>
 	<true/>
+	<key>com.apple.private.familycircle</key>
+	<true/>
 	<key>com.apple.private.feedback.drafting</key>
 	<true/>
 	<key>com.apple.private.hid.client.event-dispatch.internal</key>

 	<array>
 		<string>com.apple.analyticsd</string>
 		<string>com.apple.AppSSO.service-xpc</string>
-		<string>com.apple.biometrickitd</string>
 		<string>com.apple.commerce</string>
 		<string>com.apple.cookied</string>
 		<string>com.apple.CrashReporterSupportHelper</string>

 		<string>com.apple.security.kcsharing</string>
 		<string>com.apple.coreduetd.people.user</string>
 		<string>com.apple.familycircle.agent</string>
+		<string>com.apple.private.corewifi-xpc</string>
 		<string>com.apple.sharing.airdrop.service</string>
 		<string>com.apple.privatecloudcompute</string>
 		<string>com.apple.mdmclient.daemon.unrestricted</string>

```
### PasswordManagerBrowserExtensionHelper

> `/System/Library/CoreServices/PasswordManagerBrowserExtensionHelper.app/Contents/MacOS/PasswordManagerBrowserExtensionHelper`

```diff

 <dict>
 	<key>com.apple.accounts.appleaccount.fullaccess</key>
 	<true/>
+	<key>com.apple.ahp</key>
+	<true/>
 	<key>com.apple.appleaccount.identity.read</key>
 	<true/>
 	<key>com.apple.authentication-services.access-credential-identities</key>

 	<true/>
 	<key>com.apple.coreduetd.people</key>
 	<true/>
+	<key>com.apple.developer.usernotifications.time-sensitive</key>
+	<true/>
 	<key>com.apple.private.CoreAuthentication.SPI</key>
 	<true/>
 	<key>com.apple.private.LocalAuthentication.CallerName</key>

 	<true/>
 	<key>com.apple.private.accounts.allaccounts</key>
 	<true/>
+	<key>com.apple.private.airdrop.client</key>
+	<true/>
 	<key>com.apple.private.amfi.version-restriction</key>
 	<integer>4</integer>
 	<key>com.apple.private.applemediaservices</key>

 	<true/>
 	<key>com.apple.private.email</key>
 	<true/>
+	<key>com.apple.private.familycircle</key>
+	<true/>
+	<key>com.apple.private.feedback.drafting</key>
+	<true/>
 	<key>com.apple.private.hid.client.event-dispatch.internal</key>
 	<true/>
 	<key>com.apple.private.imcore.imagent</key>

 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.SharedWebCredentials</string>
+		<string>com.apple.feedbackd.centralized-feedback</string>
 	</array>
 	<key>com.apple.security.network.client</key>
 	<true/>

           "team-identifier": "43AQ936H96"
         }
       },
+      {
+        "$and": {
+          "signing-identifier": "net.librewolf.librewolf",
+          "team-identifier": "2S5C46ZFKS"
+        }
+      },
       {
         "$and": {
           "signing-identifier": {

           "team-identifier": "9V5K9TP787"
         }
       },
+      {
+        "$and": {
+          "signing-identifier": "systems.acon.odin.browser",
+          "team-identifier": "P37H8YFS4S"
+        }
+      },
       {
         "$and": {
           "signing-identifier": "com.bookry.wavebox",

           "signing-identifier": "me.bnfy.bowser",
           "team-identifier": "XYGUCY4498"
         }
+      },
+      {
+        "$and": {
+          "signing-identifier": "com.kavoye.Linen",
+          "team-identifier": "T8677WC8DG"
+        }
       }
     ]
   },

```
### Web App

> `/System/Library/CoreServices/Web App.app/Contents/MacOS/Web App`

```diff

 	<true/>
 	<key>com.apple.accounts.appleaccount.fullaccess</key>
 	<true/>
+	<key>com.apple.ahp</key>
+	<true/>
 	<key>com.apple.appattest.spi</key>
 	<true/>
 	<key>com.apple.appleaccount.identity.read</key>

 	<true/>
 	<key>com.apple.developer.maps</key>
 	<true/>
+	<key>com.apple.developer.usernotifications.time-sensitive</key>
+	<true/>
 	<key>com.apple.dock.add-item</key>
 	<true/>
 	<key>com.apple.duet.activityscheduler.allow</key>

 	<true/>
 	<key>com.apple.private.accounts.allaccounts</key>
 	<true/>
+	<key>com.apple.private.airdrop.client</key>
+	<true/>
 	<key>com.apple.private.app-sandbox.unquarantine</key>
 	<true/>
 	<key>com.apple.private.appleaccount.app-hidden-from-icloud-settings</key>

 	<true/>
 	<key>com.apple.private.coreservices.lsuseractivityd.bestappsuggestion</key>
 	<true/>
+	<key>com.apple.private.corewifi</key>
+	<true/>
+	<key>com.apple.private.corewifi.keychain</key>
+	<true/>
 	<key>com.apple.private.dmd.policy</key>
 	<true/>
 	<key>com.apple.private.dprivacyd.allow</key>

 	<true/>
 	<key>com.apple.private.extension-host.safari-extension</key>
 	<true/>
+	<key>com.apple.private.familycircle</key>
+	<true/>
 	<key>com.apple.private.feedback.drafting</key>
 	<true/>
 	<key>com.apple.private.guided-browsing-target</key>

 	<array>
 		<string>com.apple.analyticsd</string>
 		<string>com.apple.AppSSO.service-xpc</string>
-		<string>com.apple.biometrickitd</string>
 		<string>com.apple.commerce</string>
 		<string>com.apple.cookied</string>
 		<string>com.apple.CrashReporterSupportHelper</string>

 		<string>com.apple.security.kcsharing</string>
 		<string>com.apple.coreduetd.people.user</string>
 		<string>com.apple.familycircle.agent</string>
+		<string>com.apple.private.corewifi-xpc</string>
 		<string>com.apple.sharing.airdrop.service</string>
 		<string>com.apple.privatecloudcompute</string>
 		<string>com.apple.mdmclient.daemon.unrestricted</string>

```
### AuthenticationServicesAgent

> `/usr/libexec/AuthenticationServicesAgent`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.BTServer.rawBytesAdvertise</key>
+	<true/>
 	<key>com.apple.CommCenter.fine-grained</key>
 	<array>
 		<string>spi</string>

 	<true/>
 	<key>com.apple.bluetooth.system</key>
 	<true/>
+	<key>com.apple.developer.usernotifications.time-sensitive</key>
+	<true/>
 	<key>com.apple.keystore.sik.access</key>
 	<true/>
 	<key>com.apple.mobileactivationd.bridge</key>

 	</array>
 	<key>com.apple.private.email</key>
 	<true/>
+	<key>com.apple.private.familycircle</key>
+	<true/>
 	<key>com.apple.private.imcore.imagent</key>
 	<true/>
 	<key>com.apple.private.keychain.inet_expansion_fields</key>

```
### PasswordBreachAgent

> `/usr/libexec/PasswordBreachAgent`

```diff

 <dict>
 	<key>com.apple.application-identifier</key>
 	<string>com.apple.Safari</string>
+	<key>com.apple.developer.usernotifications.time-sensitive</key>
+	<true/>
 	<key>com.apple.private.AuthenticationServicesAgent.AutomaticSecurityUpgrade</key>
 	<true/>
 	<key>com.apple.private.security.storage.Safari</key>

```
### SafariBookmarksSyncAgent

> `/usr/libexec/SafariBookmarksSyncAgent`

```diff

 	<true/>
 	<key>com.apple.private.corespotlight.bundleid</key>
 	<string>com.apple.Safari</string>
+	<key>com.apple.private.ids.messaging</key>
+	<array>
+		<string>com.apple.private.alloy.safari.notify</string>
+	</array>
+	<key>com.apple.private.ids.messaging.urgent-priority</key>
+	<array>
+		<string>com.apple.private.alloy.safari.notify</string>
+	</array>
+	<key>com.apple.private.ids.registration</key>
+	<array>
+		<string>com.apple.private.alloy.safari.notify</string>
+	</array>
 	<key>com.apple.private.interstellar.data-access</key>
 	<string>*</string>
 	<key>com.apple.private.safari.can-use-sandbox-broker</key>

 	</array>
 	<key>com.apple.runningboard.process-state</key>
 	<true/>
+	<key>com.apple.security.exception.mach-register.global-name</key>
+	<array>
+		<string>com.apple.private.alloy.safari.notify-idswake</string>
+	</array>
 	<key>com.apple.security.exception.shared-preference.read-write</key>
 	<array>
 		<string>com.apple.Safari</string>
 	</array>
+	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.siriactionsd.xpc</string>
+	</array>
+	<key>com.apple.shortcuts.trigger-editing</key>
+	<true/>
+	<key>com.apple.siri.VoiceShortcuts.xpc</key>
+	<true/>
 	<key>keychain-access-groups</key>
 	<array>
 		<string>com.apple.Safari.WBSDevice</string>

```
### webpushd

> `/usr/libexec/webpushd`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.developer.hardened-process</key>
+	<true/>
 	<key>com.apple.private.aps-connection-initiate</key>
 	<true/>
 	<key>com.apple.private.launchservices.entitledtoaccessothersessions</key>

 	<array>
 		<string>group.com.apple.webkit.webpushd</string>
 	</array>
+	<key>com.apple.security.hardened-process.checked-allocations.no-tagged-receive</key>
+	<true/>
+	<key>com.apple.security.hardened-process.checked-allocations.soft-mode</key>
+	<true/>
 	<key>com.apple.security.hardened-process.containment.ipc</key>
 	<true/>
 	<key>com.apple.sqlite.defensive</key>

```


