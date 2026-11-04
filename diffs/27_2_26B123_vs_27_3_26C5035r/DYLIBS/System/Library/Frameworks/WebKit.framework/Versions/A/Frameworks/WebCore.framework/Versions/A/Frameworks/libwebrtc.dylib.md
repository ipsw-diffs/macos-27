## libwebrtc.dylib

> `/System/Library/Frameworks/WebKit.framework/Versions/A/Frameworks/WebCore.framework/Versions/A/Frameworks/libwebrtc.dylib`

```diff

-625.2.8.11.9
-  __TEXT.__text: 0xad8144
+626.1.12.11.4
+  __TEXT.__text: 0xad807c
   __TEXT.__objc_methlist: 0x14cc
   __TEXT.__const: 0xa71f8
   __TEXT.__cstring: 0x5b92f

   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_dictobj: 0xa0
-  __AUTH_CONST.__auth_got: 0x970
+  __AUTH_CONST.__auth_got: 0x978
   __AUTH.__thread_vars: 0x48
   __AUTH.__thread_bss: 0x18
   __DATA.__objc_ivar: 0x250

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 18776
-  Symbols:   24213
+  Symbols:   24214
   CStrings:  9144
 
Symbols:
+ _strdup
Functions:
~ __ZN6webrtc25DtlsTransportInternalImpl18CompleteDtlsInStunEb : 404 -> 272
~ __ZN4absl22internal_any_invocable12LocalInvokerILb0EvRZN6webrtc8TurnPort18ResolveTurnAddressERKNS2_13SocketAddressEE3$_0JEEET0_PNS0_15TypeErasedStateEDpNS0_18ForwardedParameterIT2_E4typeE : 876 -> 948
~ __ZN4bssl21x509_verify_signatureEPK13X509_algor_stPK14asn1_string_stNS_4SpanIKhLm18446744073709551615EEEP11evp_pkey_st : 472 -> 468
~ __ZN4bssl14ERR_save_stateEv : 496 -> 440
~ __ZN4bssl17ERR_restore_stateEPKNS_17err_save_state_stE : 420 -> 364
~ __ZN4bsslL25tls_seal_align_prefix_lenEPKNS_7SSLImplE : 228 -> 212
~ __ZN4bssl19ssl_get_new_sessionEPNS_13SSL_HANDSHAKEE : 1060 -> 1052
```
