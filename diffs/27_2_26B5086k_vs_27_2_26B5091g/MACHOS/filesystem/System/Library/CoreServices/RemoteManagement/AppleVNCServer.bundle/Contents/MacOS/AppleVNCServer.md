## AppleVNCServer

> `/System/Library/CoreServices/RemoteManagement/AppleVNCServer.bundle/Contents/MacOS/AppleVNCServer`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`

```diff

-766.5.0.0.0
-  __TEXT.__text: 0x87278
-  __TEXT.__auth_stubs: 0x2650
-  __TEXT.__objc_stubs: 0x34a0
-  __TEXT.__objc_methlist: 0x1490
-  __TEXT.__cstring: 0x20640
-  __TEXT.__oslogstring: 0xf035
+766.6.0.0.0
+  __TEXT.__text: 0x876fc
+  __TEXT.__auth_stubs: 0x2670
+  __TEXT.__objc_stubs: 0x3580
+  __TEXT.__objc_methlist: 0x1528
+  __TEXT.__cstring: 0x20832
+  __TEXT.__oslogstring: 0xf0e0
   __TEXT.__const: 0x20b8
-  __TEXT.__objc_methname: 0x45b4
-  __TEXT.__objc_classname: 0x203
-  __TEXT.__objc_methtype: 0x2a6b
-  __TEXT.__gcc_except_tab: 0xa0
-  __TEXT.__unwind_info: 0x1398
+  __TEXT.__gcc_except_tab: 0xc8
+  __TEXT.__objc_methname: 0x4672
+  __TEXT.__objc_classname: 0x244
+  __TEXT.__objc_methtype: 0x2a73
+  __TEXT.__unwind_info: 0x13d0
   __DATA_CONST.__const: 0xef0
   __DATA_CONST.__cfstring: 0x1780
-  __DATA_CONST.__objc_classlist: 0x60
-  __DATA_CONST.__objc_protolist: 0x70
+  __DATA_CONST.__objc_classlist: 0x68
+  __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0x48
+  __DATA_CONST.__objc_superrefs: 0x50
   __DATA_CONST.__objc_intobj: 0x18
   __DATA_CONST.__objc_arraydata: 0x28
   __DATA_CONST.__objc_arrayobj: 0x18
-  __DATA_CONST.__auth_got: 0x1338
+  __DATA_CONST.__auth_got: 0x1348
   __DATA_CONST.__got: 0x4a8
   __DATA_CONST.__auth_ptr: 0x28
-  __DATA.__objc_const: 0x1a90
-  __DATA.__objc_selrefs: 0x11a0
-  __DATA.__objc_ivar: 0xfc
-  __DATA.__objc_data: 0x3c0
-  __DATA.__data: 0x3678
+  __DATA.__objc_const: 0x1bb8
+  __DATA.__objc_selrefs: 0x11d8
+  __DATA.__objc_ivar: 0x104
+  __DATA.__objc_data: 0x410
+  __DATA.__data: 0x36d8
   __DATA.__bss: 0xcf8
   __DATA.__common: 0x6cc1
   __CGPreLoginApp.__cgpreloginapp: 0x0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1324
-  Symbols:   771
-  CStrings:  3842
+  Functions: 1336
+  Symbols:   773
+  CStrings:  3861
 
Symbols:
+ _objc_sync_enter
+ _objc_sync_exit
CStrings:
+ "-[RFBMediaStreamTimeoutDelegate SSMediaStreamServerDidDie]"
+ "-[RFBMediaStreamTimeoutDelegate SSMediaStreamTimeout]"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/RemoteDesktop/RFBServer/RFBMediaStreamTimeoutDelegate.m"
+ "AVC media stream RTCP timeout for viewer %u - closing connection"
+ "AVC media stream server died for viewer %u - closing connection"
+ "AVCMediaStream was active"
+ "MediaStreamCleanup"
+ "RFBMediaStreamTimeoutDelegate"
+ "SSAVCMediaStreamControllerDelegate"
+ "TB,V_handled"
+ "TI,V_descriptorIndex"
+ "T^{?=i^{?}IICCSISCCCICII{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{?=CCCCSSSCCCCCC}CCCC{Point=ss}{Point=ss}IIIIICCCCCCCCCCCCCCCCCCCCii[4{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}][4i][4i]{UserInfoEncoding=CC{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}[4{SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}]^?*S[16C]^{?}^{?}^{?}^{?}@^{?}^v^v^v^{_opaque_pthread_t}^vIiCCCCd*ISSSSSssS^{CGContext}^{CGColorSpace}^vI^{ARDBigNum}^{ARDBigNum}^{ARDBigNum}SCCI^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}ICCCCCCCCCCCC^{?}IISCCICCCC*III*IIICCS{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}IS[16C][512C]^v^{ScreenChangeInfo}^{ScreenChangeInfo}{UnsignedWide=II}IICCCIS[16C][16C]CC[16C][16C]II**^{__CFString}{MVSInfo=SSSSISs{Rect=ssss}CC{Rect=ssss}{Rect=ssss}CC[2c]I{Point=ss}S**^vC^{MVSCoefficeintInfo}{?=^{MVSCacheEntryInfo}SSI^SIIIIi}}^{?}^{CachedCursor}*I{Rect=ssss}^{RFBSenderInfoUDP}^{RFBReceiverInfoUDP}{ZRLEInfo={SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}*II}[25{ScaledScreenInfo=^{_CGLContextObject}^{_CGLPixelFormatObject}^{_CGLPBufferObject}^{CGColorSpace}}]CCCCI{ViewerInfo=iIIIIIII[32C]}ICCCCI^{FileCopy_Globals}IIIIBCCCCCSCC^{UnixToolSessionInfo}^v*^{?}^vB@^{__CFRunLoopTimer}{ViewerMouseInfo={CGPoint=dd}ISQI}{Rect=ssss}CCCCI[25I][25{Rect=ssss}]{Point=ss}QCCIi{kevent=QsSIq^v}I^{srp_context}CCCCCQ^v*I***CCCCiSC[51C]CCCCCCS[2C]CCCCCCCI@CCC^v^v[64c]IC},V_viewer"
+ "^{?=i^{?}IICCSISCCCICII{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{?=CCCCSSSCCCCCC}CCCC{Point=ss}{Point=ss}IIIIICCCCCCCCCCCCCCCCCCCCii[4{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}][4i][4i]{UserInfoEncoding=CC{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}[4{SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}]^?*S[16C]^{?}^{?}^{?}^{?}@^{?}^v^v^v^{_opaque_pthread_t}^vIiCCCCd*ISSSSSssS^{CGContext}^{CGColorSpace}^vI^{ARDBigNum}^{ARDBigNum}^{ARDBigNum}SCCI^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}ICCCCCCCCCCCC^{?}IISCCICCCC*III*IIICCS{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}IS[16C][512C]^v^{ScreenChangeInfo}^{ScreenChangeInfo}{UnsignedWide=II}IICCCIS[16C][16C]CC[16C][16C]II**^{__CFString}{MVSInfo=SSSSISs{Rect=ssss}CC{Rect=ssss}{Rect=ssss}CC[2c]I{Point=ss}S**^vC^{MVSCoefficeintInfo}{?=^{MVSCacheEntryInfo}SSI^SIIIIi}}^{?}^{CachedCursor}*I{Rect=ssss}^{RFBSenderInfoUDP}^{RFBReceiverInfoUDP}{ZRLEInfo={SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}*II}[25{ScaledScreenInfo=^{_CGLContextObject}^{_CGLPixelFormatObject}^{_CGLPBufferObject}^{CGColorSpace}}]CCCCI{ViewerInfo=iIIIIIII[32C]}ICCCCI^{FileCopy_Globals}IIIIBCCCCCSCC^{UnixToolSessionInfo}^v*^{?}^vB@^{__CFRunLoopTimer}{ViewerMouseInfo={CGPoint=dd}ISQI}{Rect=ssss}CCCCI[25I][25{Rect=ssss}]{Point=ss}QCCIi{kevent=QsSIq^v}I^{srp_context}CCCCCQ^v*I***CCCCiSC[51C]CCCCCCS[2C]CCCCCCCI@CCC^v^v[64c]IC}"
+ "^{?=i^{?}IICCSISCCCICII{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{?=CCCCSSSCCCCCC}CCCC{Point=ss}{Point=ss}IIIIICCCCCCCCCCCCCCCCCCCCii[4{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}][4i][4i]{UserInfoEncoding=CC{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}[4{SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}]^?*S[16C]^{?}^{?}^{?}^{?}@^{?}^v^v^v^{_opaque_pthread_t}^vIiCCCCd*ISSSSSssS^{CGContext}^{CGColorSpace}^vI^{ARDBigNum}^{ARDBigNum}^{ARDBigNum}SCCI^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}ICCCCCCCCCCCC^{?}IISCCICCCC*III*IIICCS{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}IS[16C][512C]^v^{ScreenChangeInfo}^{ScreenChangeInfo}{UnsignedWide=II}IICCCIS[16C][16C]CC[16C][16C]II**^{__CFString}{MVSInfo=SSSSISs{Rect=ssss}CC{Rect=ssss}{Rect=ssss}CC[2c]I{Point=ss}S**^vC^{MVSCoefficeintInfo}{?=^{MVSCacheEntryInfo}SSI^SIIIIi}}^{?}^{CachedCursor}*I{Rect=ssss}^{RFBSenderInfoUDP}^{RFBReceiverInfoUDP}{ZRLEInfo={SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}*II}[25{ScaledScreenInfo=^{_CGLContextObject}^{_CGLPixelFormatObject}^{_CGLPBufferObject}^{CGColorSpace}}]CCCCI{ViewerInfo=iIIIIIII[32C]}ICCCCI^{FileCopy_Globals}IIIIBCCCCCSCC^{UnixToolSessionInfo}^v*^{?}^vB@^{__CFRunLoopTimer}{ViewerMouseInfo={CGPoint=dd}ISQI}{Rect=ssss}CCCCI[25I][25{Rect=ssss}]{Point=ss}QCCIi{kevent=QsSIq^v}I^{srp_context}CCCCCQ^v*I***CCCCiSC[51C]CCCCCCS[2C]CCCCCCCI@CCC^v^v[64c]IC}16@0:8"
+ "_descriptorIndex"
+ "_handled"
+ "descriptorIndex"
+ "handled"
+ "initWithDescriptorIndex:"
+ "invalidate"
+ "notifyInviteAgentAndCloseConnection"
+ "setDescriptorIndex:"
+ "setHandled:"
+ "unable to resolve descriptor index for viewer %p - media stream timeout detection disabled"
+ "v24@0:8^{?=i^{?}IICCSISCCCICII{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{?=CCCCSSSCCCCCC}CCCC{Point=ss}{Point=ss}IIIIICCCCCCCCCCCCCCCCCCCCii[4{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}][4i][4i]{UserInfoEncoding=CC{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}[4{SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}]^?*S[16C]^{?}^{?}^{?}^{?}@^{?}^v^v^v^{_opaque_pthread_t}^vIiCCCCd*ISSSSSssS^{CGContext}^{CGColorSpace}^vI^{ARDBigNum}^{ARDBigNum}^{ARDBigNum}SCCI^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}ICCCCCCCCCCCC^{?}IISCCICCCC*III*IIICCS{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}IS[16C][512C]^v^{ScreenChangeInfo}^{ScreenChangeInfo}{UnsignedWide=II}IICCCIS[16C][16C]CC[16C][16C]II**^{__CFString}{MVSInfo=SSSSISs{Rect=ssss}CC{Rect=ssss}{Rect=ssss}CC[2c]I{Point=ss}S**^vC^{MVSCoefficeintInfo}{?=^{MVSCacheEntryInfo}SSI^SIIIIi}}^{?}^{CachedCursor}*I{Rect=ssss}^{RFBSenderInfoUDP}^{RFBReceiverInfoUDP}{ZRLEInfo={SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}*II}[25{ScaledScreenInfo=^{_CGLContextObject}^{_CGLPixelFormatObject}^{_CGLPBufferObject}^{CGColorSpace}}]CCCCI{ViewerInfo=iIIIIIII[32C]}ICCCCI^{FileCopy_Globals}IIIIBCCCCCSCC^{UnixToolSessionInfo}^v*^{?}^vB@^{__CFRunLoopTimer}{ViewerMouseInfo={CGPoint=dd}ISQI}{Rect=ssss}CCCCI[25I][25{Rect=ssss}]{Point=ss}QCCIi{kevent=QsSIq^v}I^{srp_context}CCCCCQ^v*I***CCCCiSC[51C]CCCCCCS[2C]CCCCCCCI@CCC^v^v[64c]IC}16"
+ "v28@0:8i16^{?=i^{?}IICCSISCCCICII{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{?=CCCCSSSCCCCCC}CCCC{Point=ss}{Point=ss}IIIIICCCCCCCCCCCCCCCCCCCCii[4{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}][4i][4i]{UserInfoEncoding=CC{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}[4{SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}]^?*S[16C]^{?}^{?}^{?}^{?}@^{?}^v^v^v^{_opaque_pthread_t}^vIiCCCCd*ISSSSSssS^{CGContext}^{CGColorSpace}^vI^{ARDBigNum}^{ARDBigNum}^{ARDBigNum}SCCI^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}ICCCCCCCCCCCC^{?}IISCCICCCC*III*IIICCS{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}IS[16C][512C]^v^{ScreenChangeInfo}^{ScreenChangeInfo}{UnsignedWide=II}IICCCIS[16C][16C]CC[16C][16C]II**^{__CFString}{MVSInfo=SSSSISs{Rect=ssss}CC{Rect=ssss}{Rect=ssss}CC[2c]I{Point=ss}S**^vC^{MVSCoefficeintInfo}{?=^{MVSCacheEntryInfo}SSI^SIIIIi}}^{?}^{CachedCursor}*I{Rect=ssss}^{RFBSenderInfoUDP}^{RFBReceiverInfoUDP}{ZRLEInfo={SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}*II}[25{ScaledScreenInfo=^{_CGLContextObject}^{_CGLPixelFormatObject}^{_CGLPBufferObject}^{CGColorSpace}}]CCCCI{ViewerInfo=iIIIIIII[32C]}ICCCCI^{FileCopy_Globals}IIIIBCCCCCSCC^{UnixToolSessionInfo}^v*^{?}^vB@^{__CFRunLoopTimer}{ViewerMouseInfo={CGPoint=dd}ISQI}{Rect=ssss}CCCCI[25I][25{Rect=ssss}]{Point=ss}QCCIi{kevent=QsSIq^v}I^{srp_context}CCCCCQ^v*I***CCCCiSC[51C]CCCCCCS[2C]CCCCCCCI@CCC^v^v[64c]IC}20"
- "AVCMediaStream  active - call release"
- "AVCMediaStreams not currently active"
- "T^{?=i^{?}IICCSISCCCICII{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{?=CCCCSSSCCCCCC}CCCC{Point=ss}{Point=ss}IIIIICCCCCCCCCCCCCCCCCCCCii[4{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}][4i][4i]{UserInfoEncoding=CC{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}[4{SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}]^?*S[16C]^{?}^{?}^{?}^{?}@^{?}^v^v^v^{_opaque_pthread_t}^vIiCCCCd*ISSSSSssS^{CGContext}^{CGColorSpace}^vI^{ARDBigNum}^{ARDBigNum}^{ARDBigNum}SCCI^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}ICCCCCCCCCCCC^{?}IISCCICCCC*III*IIICCS{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}IS[16C][512C]^v^{ScreenChangeInfo}^{ScreenChangeInfo}{UnsignedWide=II}IICCCIS[16C][16C]CC[16C][16C]II**^{__CFString}{MVSInfo=SSSSISs{Rect=ssss}CC{Rect=ssss}{Rect=ssss}CC[2c]I{Point=ss}S**^vC^{MVSCoefficeintInfo}{?=^{MVSCacheEntryInfo}SSI^SIIIIi}}^{?}^{CachedCursor}*I{Rect=ssss}^{RFBSenderInfoUDP}^{RFBReceiverInfoUDP}{ZRLEInfo={SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}*II}[25{ScaledScreenInfo=^{_CGLContextObject}^{_CGLPixelFormatObject}^{_CGLPBufferObject}^{CGColorSpace}}]CCCCI{ViewerInfo=iIIIIIII[32C]}ICCCCI^{FileCopy_Globals}IIIIBCCCCCSCC^{UnixToolSessionInfo}^v*^{?}^vB@^{__CFRunLoopTimer}{ViewerMouseInfo={CGPoint=dd}ISQI}{Rect=ssss}CCCCI[25I][25{Rect=ssss}]{Point=ss}QCCIi{kevent=QsSIq^v}I^{srp_context}CCCCCQ^v*I***CCCCiSC[51C]CCCCCCS[2C]CCCCCCCI@CCC^v[64c]IC},V_viewer"
- "^{?=i^{?}IICCSISCCCICII{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{?=CCCCSSSCCCCCC}CCCC{Point=ss}{Point=ss}IIIIICCCCCCCCCCCCCCCCCCCCii[4{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}][4i][4i]{UserInfoEncoding=CC{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}[4{SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}]^?*S[16C]^{?}^{?}^{?}^{?}@^{?}^v^v^v^{_opaque_pthread_t}^vIiCCCCd*ISSSSSssS^{CGContext}^{CGColorSpace}^vI^{ARDBigNum}^{ARDBigNum}^{ARDBigNum}SCCI^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}ICCCCCCCCCCCC^{?}IISCCICCCC*III*IIICCS{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}IS[16C][512C]^v^{ScreenChangeInfo}^{ScreenChangeInfo}{UnsignedWide=II}IICCCIS[16C][16C]CC[16C][16C]II**^{__CFString}{MVSInfo=SSSSISs{Rect=ssss}CC{Rect=ssss}{Rect=ssss}CC[2c]I{Point=ss}S**^vC^{MVSCoefficeintInfo}{?=^{MVSCacheEntryInfo}SSI^SIIIIi}}^{?}^{CachedCursor}*I{Rect=ssss}^{RFBSenderInfoUDP}^{RFBReceiverInfoUDP}{ZRLEInfo={SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}*II}[25{ScaledScreenInfo=^{_CGLContextObject}^{_CGLPixelFormatObject}^{_CGLPBufferObject}^{CGColorSpace}}]CCCCI{ViewerInfo=iIIIIIII[32C]}ICCCCI^{FileCopy_Globals}IIIIBCCCCCSCC^{UnixToolSessionInfo}^v*^{?}^vB@^{__CFRunLoopTimer}{ViewerMouseInfo={CGPoint=dd}ISQI}{Rect=ssss}CCCCI[25I][25{Rect=ssss}]{Point=ss}QCCIi{kevent=QsSIq^v}I^{srp_context}CCCCCQ^v*I***CCCCiSC[51C]CCCCCCS[2C]CCCCCCCI@CCC^v[64c]IC}"
- "^{?=i^{?}IICCSISCCCICII{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{?=CCCCSSSCCCCCC}CCCC{Point=ss}{Point=ss}IIIIICCCCCCCCCCCCCCCCCCCCii[4{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}][4i][4i]{UserInfoEncoding=CC{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}[4{SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}]^?*S[16C]^{?}^{?}^{?}^{?}@^{?}^v^v^v^{_opaque_pthread_t}^vIiCCCCd*ISSSSSssS^{CGContext}^{CGColorSpace}^vI^{ARDBigNum}^{ARDBigNum}^{ARDBigNum}SCCI^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}ICCCCCCCCCCCC^{?}IISCCICCCC*III*IIICCS{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}IS[16C][512C]^v^{ScreenChangeInfo}^{ScreenChangeInfo}{UnsignedWide=II}IICCCIS[16C][16C]CC[16C][16C]II**^{__CFString}{MVSInfo=SSSSISs{Rect=ssss}CC{Rect=ssss}{Rect=ssss}CC[2c]I{Point=ss}S**^vC^{MVSCoefficeintInfo}{?=^{MVSCacheEntryInfo}SSI^SIIIIi}}^{?}^{CachedCursor}*I{Rect=ssss}^{RFBSenderInfoUDP}^{RFBReceiverInfoUDP}{ZRLEInfo={SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}*II}[25{ScaledScreenInfo=^{_CGLContextObject}^{_CGLPixelFormatObject}^{_CGLPBufferObject}^{CGColorSpace}}]CCCCI{ViewerInfo=iIIIIIII[32C]}ICCCCI^{FileCopy_Globals}IIIIBCCCCCSCC^{UnixToolSessionInfo}^v*^{?}^vB@^{__CFRunLoopTimer}{ViewerMouseInfo={CGPoint=dd}ISQI}{Rect=ssss}CCCCI[25I][25{Rect=ssss}]{Point=ss}QCCIi{kevent=QsSIq^v}I^{srp_context}CCCCCQ^v*I***CCCCiSC[51C]CCCCCCS[2C]CCCCCCCI@CCC^v[64c]IC}16@0:8"
- "v24@0:8^{?=i^{?}IICCSISCCCICII{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{?=CCCCSSSCCCCCC}CCCC{Point=ss}{Point=ss}IIIIICCCCCCCCCCCCCCCCCCCCii[4{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}][4i][4i]{UserInfoEncoding=CC{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}[4{SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}]^?*S[16C]^{?}^{?}^{?}^{?}@^{?}^v^v^v^{_opaque_pthread_t}^vIiCCCCd*ISSSSSssS^{CGContext}^{CGColorSpace}^vI^{ARDBigNum}^{ARDBigNum}^{ARDBigNum}SCCI^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}ICCCCCCCCCCCC^{?}IISCCICCCC*III*IIICCS{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}IS[16C][512C]^v^{ScreenChangeInfo}^{ScreenChangeInfo}{UnsignedWide=II}IICCCIS[16C][16C]CC[16C][16C]II**^{__CFString}{MVSInfo=SSSSISs{Rect=ssss}CC{Rect=ssss}{Rect=ssss}CC[2c]I{Point=ss}S**^vC^{MVSCoefficeintInfo}{?=^{MVSCacheEntryInfo}SSI^SIIIIi}}^{?}^{CachedCursor}*I{Rect=ssss}^{RFBSenderInfoUDP}^{RFBReceiverInfoUDP}{ZRLEInfo={SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}*II}[25{ScaledScreenInfo=^{_CGLContextObject}^{_CGLPixelFormatObject}^{_CGLPBufferObject}^{CGColorSpace}}]CCCCI{ViewerInfo=iIIIIIII[32C]}ICCCCI^{FileCopy_Globals}IIIIBCCCCCSCC^{UnixToolSessionInfo}^v*^{?}^vB@^{__CFRunLoopTimer}{ViewerMouseInfo={CGPoint=dd}ISQI}{Rect=ssss}CCCCI[25I][25{Rect=ssss}]{Point=ss}QCCIi{kevent=QsSIq^v}I^{srp_context}CCCCCQ^v*I***CCCCiSC[51C]CCCCCCS[2C]CCCCCCCI@CCC^v[64c]IC}16"
- "v28@0:8i16^{?=i^{?}IICCSISCCCICII{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{Rect=ssss}{?=CCCCSSSCCCCCC}CCCC{Point=ss}{Point=ss}IIIIICCCCCCCCCCCCCCCCCCCCii[4{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}][4i][4i]{UserInfoEncoding=CC{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}[4{SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}]^?*S[16C]^{?}^{?}^{?}^{?}@^{?}^v^v^v^{_opaque_pthread_t}^vIiCCCCd*ISSSSSssS^{CGContext}^{CGColorSpace}^vI^{ARDBigNum}^{ARDBigNum}^{ARDBigNum}SCCI^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}^{_CCCryptor}ICCCCCCCCCCCC^{?}IISCCICCCC*III*IIICCS{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I}IS[16C][512C]^v^{ScreenChangeInfo}^{ScreenChangeInfo}{UnsignedWide=II}IICCCIS[16C][16C]CC[16C][16C]II**^{__CFString}{MVSInfo=SSSSISs{Rect=ssss}CC{Rect=ssss}{Rect=ssss}CC[2c]I{Point=ss}S**^vC^{MVSCoefficeintInfo}{?=^{MVSCacheEntryInfo}SSI^SIIIIi}}^{?}^{CachedCursor}*I{Rect=ssss}^{RFBSenderInfoUDP}^{RFBReceiverInfoUDP}{ZRLEInfo={SubZlibCodecInfo=Cc{z_stream_s=*IQ*IQ*^{internal_state}^?^?^viQQ}}*II}[25{ScaledScreenInfo=^{_CGLContextObject}^{_CGLPixelFormatObject}^{_CGLPBufferObject}^{CGColorSpace}}]CCCCI{ViewerInfo=iIIIIIII[32C]}ICCCCI^{FileCopy_Globals}IIIIBCCCCCSCC^{UnixToolSessionInfo}^v*^{?}^vB@^{__CFRunLoopTimer}{ViewerMouseInfo={CGPoint=dd}ISQI}{Rect=ssss}CCCCI[25I][25{Rect=ssss}]{Point=ss}QCCIi{kevent=QsSIq^v}I^{srp_context}CCCCCQ^v*I***CCCCiSC[51C]CCCCCCS[2C]CCCCCCCI@CCC^v[64c]IC}20"
```
