## PMBrowser

> `/System/Library/CoreServices/AddPrinter.app/Contents/Frameworks/PMBrowser.framework/Versions/A/PMBrowser`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 21.0.0.0.0
-  __TEXT.__text: 0x13270
+  __TEXT.__text: 0x12d80
   __TEXT.__auth_stubs: 0xae0
   __TEXT.__objc_stubs: 0x30a0
   __TEXT.__objc_methlist: 0x1458

   __TEXT.__const: 0x40
   __TEXT.__oslogstring: 0x74
   __TEXT.__gcc_except_tab: 0x28
-  __TEXT.__unwind_info: 0x498
+  __TEXT.__unwind_info: 0x600
   __DATA_CONST.__const: 0xb60
   __DATA_CONST.__cfstring: 0x2d80
   __DATA_CONST.__objc_classlist: 0x88
Functions:
~ -[PMBrowserPlugin awakeFromNib] : 60 -> 48
~ -[PMBrowserPrinter browserIdentifier] : 64 -> 52
~ -[PMBrowserPrinter compare:] : 76 -> 64
~ +[PMPluginsManager defaultManager] : 104 -> 92
~ +[PMPluginsManager browserName:] : 204 -> 192
~ +[PMPluginsManager browserIcon:] : 296 -> 284
~ +[PMPluginsManager browserIdentifier:] : 48 -> 36
~ ___18-[PPDManager ppds]_block_invoke : 84 -> 72
~ ___18-[PPDManager ppds]_block_invoke_2 : 104 -> 92
~ ___copy_helper_block_e8_32o40o : 80 -> 68
~ ___destroy_helper_block_e8_32o40o : 68 -> 56
~ -[PPDManager matchPPDsByDeviceID:model:product:] : 92 -> 80
~ _ppdComparator : 180 -> 168
~ -[PPDManager genericFaxPPD] : 116 -> 104
~ -[PPDManager genericURFPPD] : 116 -> 104
~ -[PPDManager isApplePPD:] : 136 -> 124
~ +[PPDManager(ConvenienceMethods) localizedPPD:] : 44 -> 32
~ -[PMPPDPopUpButton awakeFromNib] : 68 -> 56
~ -[PMPPDPopUpButton faxPPDs] : 48 -> 36
~ -[PMPPDPopUpButton rasterPPDs] : 48 -> 36
~ -[PMPPDPopUpButton postscriptPPDs] : 48 -> 36
~ -[PMPPDPopUpButton setDrivers:supportsAutoSelect:supportsPostscript:supportsPCL:supportsFax:selectStandardDefaults:] : 1452 -> 1440
~ _driverComparator : 228 -> 216
~ -[PMPPDPopUpButton addOtherPPD:] : 92 -> 80
~ -[PMPPDPopUpButton represetedObjectAtSelection] : 180 -> 156
~ -[PMPPDPopUpButton(PrivateMethods) startTracking:] : 108 -> 96
~ -[PMPPDPopUpButton(PrivateMethods) stopTracking:] : 108 -> 96
~ ___34-[PrinterInspector driverChanged:]_block_invoke : 492 -> 480
~ -[PrinterInspector setCurrentSelection:] : 232 -> 220
~ -[PrinterInspector selectionChanged:] : 148 -> 136
~ -[PrinterInspector updateUI] : 996 -> 972
~ ___35-[PrinterInspector printerUpdated:]_block_invoke : 852 -> 840
~ ___copy_helper_block_e8_32o40o48o : 96 -> 84
~ ___destroy_helper_block_e8_32o40o48o : 80 -> 68
~ -[PrinterInspector sendPrinterChangedNotification] : 352 -> 340
~ _PMDriverSupportsPrinter : 556 -> 544
~ -[NSString(PMStringAdditions) stringForKey:] : 68 -> 56
~ -[NSString(PMStringAdditions) commandSet] : 128 -> 116
~ -[NSString(PMStringAdditions) compatibleIDs] : 116 -> 104
~ -[NSString(PMStringAdditions) make] : 284 -> 272
~ -[NSString(PMStringAdditions) model] : 332 -> 320
~ -[NSString(PMStringAdditions) serialNumber] : 136 -> 124
~ -[NSString(PMStringAdditions) pmStringByAddingPercentEscapes] : 76 -> 64
~ -[NSDictionary(PMDictionaryAdditions) commandSet] : 148 -> 136
~ -[NSDictionary(PMDictionaryAdditions) compatibleIDs] : 128 -> 116
~ -[NSDictionary(PMDictionaryAdditions) make] : 264 -> 252
~ -[NSDictionary(PMDictionaryAdditions) model] : 284 -> 272
~ -[NSDictionary(PMDictionaryAdditions) serialNumber] : 168 -> 156
~ -[NSDictionary(PMDictionaryAdditions) deviceName] : 40 -> 28
~ +[PrinterConfigure(PrinterConfigureCreation) PrinterConfigureWithPrinterURI:] : 68 -> 56
~ _AutoSelectCallBack : 152 -> 140
~ -[PrinterConfigure ppds] : 80 -> 68
~ -[PrinterConfigure setLocation:] : 96 -> 84
~ -[PrinterConfigure startConfigure] : 116 -> 104
~ -[PrinterConfigure stopConfigure] : 96 -> 84
~ -[PrinterConfigure autoSelectedThread:] : 140 -> 128
~ -[PrinterConfigure autoSelectEvent:] : 432 -> 420
~ +[DNSSDBrowser instantiatePlugin] : 48 -> 36
~ _browse_callback : 300 -> 288
~ -[DNSSDBrowser callBack:interface:name:regType:domain:] : 724 -> 712
~ +[DNSServiceObject objectWithRef:] : 68 -> 56
~ +[DNSSDConfigure(DNSSDConfigureCreation) dnssdConfigureWithPrinter:] : 68 -> 56
~ -[DNSSDConfigure stopConfigure] : 64 -> 52
~ -[DNSSDConfigure configureDone] : 120 -> 108
~ __42-[DNSSDConfigure sortTxtRecordsByPriority]_block_invoke.41 : 468 -> 456
~ -[DNSSDConfigure addTxtRecord:forName:] : 208 -> 196
~ _netAuthGetCredentialsCallback : 76 -> 64
~ -[DNSSDPrinter browserIdentifier] : 208 -> 196
~ -[DNSSDPrinter supportsFaxOperations] : 60 -> 48
~ -[DNSSDPrinter isLocallyShared] : 72 -> 60
~ -[DNSSDPrinter textRecords] : 96 -> 84
~ -[DNSSDPrinter printer1284DeviceID] : 80 -> 68
~ -[DNSSDPrinter matchesICDevice:] : 132 -> 120
~ -[DNSSDPrinter setScannerUUID:modulePath:] : 64 -> 52
~ -[DNSSDPrinter(DNSSDPrinterPrivate) deviceID] : 84 -> 72
~ -[DNSSDPrinter(DNSSDPrinterPrivate) setConfigureObject:] : 132 -> 120
~ +[DNSSDPrinter(DNSSDPrinterCreation) dnssdPrinterWithName:domain:type:] : 92 -> 80
~ -[DNSSDPrinter(DNSSDConfigureDelegate) dnssdConfigure:didCompleteConfigure:] : 184 -> 172
~ +[IPPrinter IPPrinterWithProtocol:hostAddress:queue:on:] : 100 -> 88
~ -[IPPrinter name] : 216 -> 204
~ -[IPPrinter uri:] : 192 -> 180
~ ___22-[IPPrinter configure]_block_invoke_2 : 328 -> 316
~ ___copy_helper_block_e8_32o40o48o56o64r : 128 -> 116
~ ___destroy_helper_block_e8_32o40o48o56o64r : 104 -> 92
~ ___copy_helper_block_e8_32o40r : 80 -> 68
~ ___destroy_helper_block_e8_32o40r : 68 -> 56
~ -[IPPrinter ppdMatches] : 152 -> 140
~ _examineFile : 832 -> 828
~ _FilterDNSSDSuffix : 188 -> 176
~ ___USBGetDeviceIDUsingInterface_block_invoke : 188 -> 176
~ _USBGetDeviceInfo2 : 280 -> 268
~ _device_added : 204 -> 192
~ -[PPDPickerWindowController ok:] : 128 -> 104
~ -[PPDPickerWindowController cancel:] : 128 -> 104
~ -[PPDPickerWindowController selectedPPD] : 96 -> 84
~ -[ScannerPrinter browserIdentifier] : 252 -> 240
~ -[ScannerPrinter name] : 40 -> 28
~ -[ScannerPrinter ppdMatches] : 268 -> 256
~ +[ScannerPrinter(ScannerPrinterCreation) scannerWithDevice:] : 68 -> 56
~ _getPrinterClassDriverPath : 104 -> 92
~ -[DNSSDConfigure mainRef].cold.1 : 80 -> 68
~ -[DNSSDConfigure setMainRef:].cold.1 : 92 -> 80
```
