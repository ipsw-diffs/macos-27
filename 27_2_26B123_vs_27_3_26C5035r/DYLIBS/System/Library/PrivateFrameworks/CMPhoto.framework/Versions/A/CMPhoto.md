## CMPhoto

> `/System/Library/PrivateFrameworks/CMPhoto.framework/Versions/A/CMPhoto`

```diff

-488.40.6.0.0
-  __TEXT.__text: 0x294540
+488.60.5.0.0
+  __TEXT.__text: 0x2bff8c
   __TEXT.__objc_methlist: 0x5c4
-  __TEXT.__const: 0x1bf30
-  __TEXT.__cstring: 0x4c816
+  __TEXT.__const: 0x1cc58
+  __TEXT.__cstring: 0x4e281
   __TEXT.__gcc_except_tab: 0x2094
-  __TEXT.__oslogstring: 0x7f65
+  __TEXT.__oslogstring: 0x824a
   __TEXT.__ustring: 0x170
-  __TEXT.__swift5_typeref: 0x1f8a
-  __TEXT.__swift5_reflstr: 0x4a3f
-  __TEXT.__swift5_assocty: 0x270
-  __TEXT.__swift5_fieldmd: 0x4480
-  __TEXT.__constg_swiftt: 0x3658
-  __TEXT.__swift5_builtin: 0xdc
-  __TEXT.__swift5_mpenum: 0x60
-  __TEXT.__swift5_capture: 0xd54
+  __TEXT.__swift5_typeref: 0x225e
+  __TEXT.__swift5_capture: 0xf38
+  __TEXT.__swift5_reflstr: 0x4de3
+  __TEXT.__swift5_assocty: 0x288
+  __TEXT.__swift5_fieldmd: 0x4908
+  __TEXT.__constg_swiftt: 0x388c
+  __TEXT.__swift5_builtin: 0xf0
+  __TEXT.__swift5_mpenum: 0x68
   __TEXT.__swift5_protos: 0x3c
-  __TEXT.__swift5_proto: 0x604
-  __TEXT.__swift5_types: 0x344
-  __TEXT.__unwind_info: 0x7cf0
-  __TEXT.__eh_frame: 0x6dbc
+  __TEXT.__swift5_proto: 0x630
+  __TEXT.__swift5_types: 0x398
+  __TEXT.__unwind_info: 0x8420
+  __TEXT.__eh_frame: 0x7ffc
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x986b8
+  __DATA_CONST.__const: 0x98808
   __DATA_CONST.__objc_classlist: 0x188
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x930
+  __DATA_CONST.__objc_selrefs: 0x938
   __DATA_CONST.__objc_superrefs: 0x10
   __DATA_CONST.__objc_arraydata: 0x2a8
-  __DATA_CONST.__got: 0x1dd8
-  __AUTH_CONST.__const: 0x10cf9
-  __AUTH_CONST.__cfstring: 0x608c0
+  __DATA_CONST.__got: 0x1e90
+  __AUTH_CONST.__const: 0x11c08
+  __AUTH_CONST.__cfstring: 0x60bc0
   __AUTH_CONST.__objc_const: 0x4228
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x240
   __AUTH_CONST.__objc_arrayobj: 0x1f8
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0x2810
+  __AUTH_CONST.__auth_got: 0x2890
   __AUTH.__objc_data: 0x520
-  __AUTH.__data: 0x30c0
+  __AUTH.__data: 0x3288
   __DATA.__objc_ivar: 0x3c
-  __DATA.__data: 0x14b8
-  __DATA.__bss: 0xc4f0
-  __DATA.__common: 0x4ac8
+  __DATA.__data: 0x1640
+  __DATA.__bss: 0xcaa0
+  __DATA.__common: 0x4b38
   __DATA_DIRTY.__objc_data: 0x50
   __DATA_DIRTY.__data: 0x2010
   __DATA_DIRTY.__bss: 0x568

   - /System/Library/Frameworks/Metal.framework/Versions/A/Metal
   - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/Frameworks/VideoToolbox.framework/Versions/A/VideoToolbox
+  - /System/Library/PrivateFrameworks/ASRKit.framework/Versions/A/ASRKit
   - /System/Library/PrivateFrameworks/AppleJPEG.framework/Versions/A/AppleJPEG
   - /System/Library/PrivateFrameworks/AppleJPEGXL.framework/Versions/A/AppleJPEGXL
   - /System/Library/PrivateFrameworks/ByteMatrixVerification.framework/Versions/A/ByteMatrixVerification

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 9699
-  Symbols:   8453
-  CStrings:  14008
+  Functions: 10148
+  Symbols:   8498
+  CStrings:  14198
 
Symbols:
+ _CMPhotoAIMarkerCopyBoxInformation
+ _CMPhotoAIMarkerCopyFileAndInsertAIMarker
+ _CMPhotoAIMarkerCopyFileAndModifyAIMarkerInfo
+ _CMPhotoAIMarkerCreateBox
+ _CMPhotoAIMarkerCreateContentHash
+ _CMPhotoAIMarkerCreateHash
+ _CMPhotoAIMarkerCreateHashComponents
+ _CMPhotoAIMarkerModifyBoxSignature
+ _CMPhotoAIMarkerVerify
+ _CMPhotoCompressionSessionAddAIMarker
+ _SecKeyCopyAttributes
+ _SecRandomCopyBytes
+ _asr_check_parser
+ _kCMPhotoAIMarkerBoxOption_CertificateChain
+ _kCMPhotoAIMarkerBoxOption_Description
+ _kCMPhotoAIMarkerBoxOption_PlaceholderSignature
+ _kCMPhotoAIMarkerBoxOption_SignatureAlgorithm
+ _kCMPhotoAIMarkerBoxOption_SigningTime
+ _kCMPhotoAIMarkerContentKind_Unknown
+ _kCMPhotoAIMarkerHashComponent_AIMarkerBoxHash
+ _kCMPhotoAIMarkerHashComponent_CombinedHash
+ _kCMPhotoAIMarkerHashComponent_ContentHash
+ _kCMPhotoAIMarkerHashComponent_SignatureInput
+ _kCMPhotoAIMarkerResult_AIMarkerBoxHash
+ _kCMPhotoAIMarkerResult_AllCodedItemsSigned
+ _kCMPhotoAIMarkerResult_CertificateChainData
+ _kCMPhotoAIMarkerResult_CertificateSecTrustVerified
+ _kCMPhotoAIMarkerResult_CertificateSecTrustVerifiedWithQASigningPolicy
+ _kCMPhotoAIMarkerResult_ContentHash
+ _kCMPhotoAIMarkerResult_ContentKind
+ _kCMPhotoAIMarkerResult_Description
+ _kCMPhotoAIMarkerResult_ListedItemIDs
+ _kCMPhotoAIMarkerResult_SignatureAlgorithmOID
+ _kCMPhotoAIMarkerResult_SignatureVerified
+ _kCMPhotoAIMarkerResult_SigningTime
+ _kCMPhotoAIMarkerResult_SpecVersion
+ _kCMPhotoAIMarkerResult_Verified
+ _kCMPhotoAIMarkerSignatureAlgorithm_CompositeMLDSA87RSA3072PSS
+ _kCMPhotoAIMarkerSignatureAlgorithm_ECDSAP256SHA384
+ _kCMPhotoAIMarkerSignatureAlgorithm_ECDSAP256SHA512
+ _kSecAttrKeySizeInBits
+ _kSecAttrKeyType
+ _kSecAttrKeyTypeECSECPrimeRandom
+ _kSecKeyAlgorithmECDSASignatureMessageX962SHA384
+ _kSecRandomDefault
CStrings:
+ "%{public}s: %d"
+ "1.2.840.10045.4.3.3"
+ "1.2.840.10045.4.3.4"
+ "1.3.6.1.5.5.7.6.52"
+ "6BEFF598-F635-480B-B213-D14F40790965"
+ "A file with provenance metadata cannot carry an AI Marker"
+ "AI Marker Box contents do not fit the box size"
+ "AI Marker Box does not map onto its segments"
+ "AI Marker Box field out of range"
+ "AI Marker Box instance number is used by another uuid box"
+ "AI Marker Box segments are not consecutive"
+ "AI Marker Box too large"
+ "AI Marker Box uses a 64-bit length"
+ "AI Marker description is not valid UTF-8"
+ "AI Marker error: %s"
+ "AI Marker functions take a CFData or a file CFURL"
+ "AIMarkerBoxHash"
+ "AllCodedItemsSigned"
+ "Box too large"
+ "CMByteStreamWrite failed: status=%d, wrote=%ld, expected=%ld"
+ "CMPhoto/CMPhotoAIMarker.swift"
+ "CMPhoto/CMPhotoAIMarkerBox.swift"
+ "CMPhoto/CMPhotoAIMarkerContainer.swift"
+ "CMPhotoAIMarkerCopyBoxInformation(_:_:_:)"
+ "CMPhotoAIMarkerCopyCarryOver(_:_:)"
+ "CMPhotoAIMarkerCopyFileAndInsertAIMarker(_:_:_:_:)"
+ "CMPhotoAIMarkerCopyFileAndModifyAIMarkerInfo(_:_:_:_:)"
+ "CMPhotoAIMarkerCreateBoxListingHEIFItems(_:_:_:)"
+ "CMPhotoAIMarkerCreateCarriedOverHEIFBox(_:_:_:)"
+ "CMPhotoAIMarkerCreateContentHash(_:_:_:_:)"
+ "CMPhotoAIMarkerCreateJPEGWithCarriedOverAIMarker(_:_:_:)"
+ "CMPhotoAIMarkerCreateJPEGWithoutAIMarker(_:_:)"
+ "CMPhotoAIMarkerGetJPEGSignedBoxes(_:_:_:)"
+ "CMPhotoAIMarkerModifyBoxSignature(_:_:_:_:)"
+ "CMPhotoAIMarkerVerify(_:_:_:)"
+ "Certificate is not a SEQUENCE"
+ "CertificateChain"
+ "Codec configuration of item is not available"
+ "Codec configuration too large"
+ "CodecConfigurations"
+ "Coded image item has no codec configuration"
+ "ContentKind"
+ "Could not copy the input for writing"
+ "Could not evaluate the certificate chain"
+ "Could not extract the public key of the signing certificate"
+ "Could not generate the AI Marker nonce"
+ "Could not get the length of the input"
+ "Could not open the input for reading"
+ "Could not parse the JPEG marker segments"
+ "Could not parse the signing certificate"
+ "Could not read the HEIF image items"
+ "Could not split the AI Marker Box into segments"
+ "Dropping the AI Marker Box: a listed item was changed or removed"
+ "Dropping the AI Marker Box: its items are too large to fingerprint"
+ "Dropping the AI Marker Box: the file carries provenance metadata"
+ "Dropping the AI Marker Box: the image data changed"
+ "Dropping the AI Marker Box: the rewritten items are too large to fingerprint"
+ "Extensions field does not hold exactly one SEQUENCE"
+ "Extents"
+ "File has more than one or an unreadable AI Marker Box"
+ "FirstSOSOffset"
+ "HEIF AI Marker Box must list at least one item"
+ "HEIF AI Marker carry-over does not match its box"
+ "HEIF AI Marker carry-over has no items"
+ "HEIF file does not start with ftyp"
+ "Input is neither HEIF nor JPEG"
+ "InsertionOffset"
+ "Invalid AI Marker carry-over"
+ "Invalid HEIF item description"
+ "Invalid HEIF item list"
+ "Invalid JFIF layout"
+ "Invalid JPEG-XT segment range"
+ "Invalid SignatureData: %s"
+ "Invalid SignatureParameters: %s"
+ "Invalid codec configuration"
+ "Item data is not available in the file"
+ "Item data too large"
+ "Item listed more than once"
+ "JPEG AI Marker Box must not list items"
+ "JPEG AI Marker carry-over has no Content Hash"
+ "JPEGXTSegmentRanges"
+ "Listed item does not exist"
+ "ListedItemIDs"
+ "ListedItemsByFingerprint"
+ "MP Entries out of bounds"
+ "MP Entry out of range"
+ "MPEntriesBigEndian"
+ "MPEntriesOffset"
+ "MPEntryCount"
+ "MPHeaderOffset"
+ "No AI Marker Box"
+ "No JPEG-XT instance number left"
+ "No JPEG-XT segments"
+ "No byte stream"
+ "No writable copy"
+ "Not a JPEG"
+ "Not an AI Marker Box"
+ "Option must be an integer"
+ "PlaceholderSignature"
+ "Range out of bounds"
+ "Signature algorithm %{public}s is no longer allowed by the AI Marker spec"
+ "Signature algorithm parameters are not supported"
+ "SignatureAlgorithm"
+ "SignatureAlgorithmOID"
+ "SignatureParameters must contain between 1 and 10 certificates"
+ "SignatureVerified"
+ "SigningTime"
+ "Skipping unreadable JPEG-XT segment: %s"
+ "SpecVersion"
+ "The AI Marker Box does not verify for this file"
+ "The AI Marker Box must be the same size as the one it replaces"
+ "The AI Marker Box must list items in a HEIF file and none in a JPEG file"
+ "The AI Marker Box to replace cannot be read"
+ "The AI Marker Box would be larger than 1 MiB"
+ "The Content Hash must be a 64-byte SHA-512"
+ "The file has no coded image item whose Content Hash is defined"
+ "The signature does not verify with the signing certificate"
+ "The signature must not be empty"
+ "Too many items to list in an AI Marker Box"
+ "Too many top-level boxes"
+ "Trailing bytes after SignatureData"
+ "Trailing bytes after SignatureParameters"
+ "Unexpected element in SignatureData"
+ "Unexpected element in SignatureParameters"
+ "Unsupported AI Marker spec_major %hu"
+ "Unsupported SignatureData version"
+ "Unsupported SignatureParameters version"
+ "Unsupported coded image item type"
+ "Unsupported signature algorithm"
+ "Verified"
+ "av01"
+ "avc1"
+ "byteStreamLength(_:)"
+ "certificateChain(options:)"
+ "codecConfiguration(of:)"
+ "com.apple.cmphoto.aimarker"
+ "com.apple.cmphoto.dicom"
+ "com.apple.cmphoto.heics"
+ "com.apple.cmphoto.heif"
+ "com.apple.cmphoto.jfif"
+ "com.apple.cmphoto.jpeg"
+ "com.apple.cmphoto.jpegxl"
+ "com.apple.cmphoto.slim"
+ "com.apple.cmphoto.videotoolbox"
+ "contentHash(byteStream:layout:box:)"
+ "contentHashParameter(_:)"
+ "createByteStreamForReading(_:)"
+ "createWritableCopy(of:)"
+ "data"
+ "descriptionField(options:)"
+ "doesNotFit"
+ "encode(certificates:algorithm:)"
+ "encode(rawSignature:)"
+ "free"
+ "ftyp"
+ "hashComponents(fileData:)"
+ "hashInput(of:byteStream:into:)"
+ "hvc1"
+ "init(byteStream:)"
+ "insertingAIMarkerBox(_:into:layout:)"
+ "insertingJPEGBox(_:into:layout:)"
+ "int64Option(_:_:)"
+ "itemIDsParameter(_:)"
+ "kCMPhotoAIMarkerBoxOption_CertificateChain must hold 1 to 10 certificates"
+ "kCMPhotoAIMarkerBoxOption_CertificateChain must hold DER certificates"
+ "kCMPhotoAIMarkerBoxOption_Description must be a string or data"
+ "kCMPhotoAIMarkerBoxOption_PlaceholderSignature must be non-empty data"
+ "kCMPhotoAIMarkerBoxOption_SignatureAlgorithm must be a kCMPhotoAIMarkerSignatureAlgorithm_* value"
+ "listedItemIDs lists an item more than once"
+ "listedItemIDs must hold 1 to 65535 item IDs"
+ "listedItemIDs must hold item IDs"
+ "listedItemIDs(of:)"
+ "notFound"
+ "publicKeyOfSigningCertificate(_:)"
+ "readWholeInput(_:)"
+ "serializedWithoutPadding(_:)"
+ "signatureAlgorithm(of:)"
+ "signatureAlgorithm(options:)"
+ "signedBoxData(_:rawSignature:contentHash:container:)"
+ "unsignedBox(options:algorithm:itemIDs:)"
+ "unsupportedAlgorithm"
+ "unsupportedSpecVersion"
+ "update(from:range:)"
+ "updateMPFEntries(_:in:entriesOffset:firstImageSizeChange:relativeOffsetChange:)"
+ "utf8"
+ "validateListedItemIDs(_:)"
+ "validatePlacement(of:box:layout:)"
+ "verifyECDSASignature: ECDSA X9.62 %{public}s algorithm not supported by key"
+ "verifyECDSASignature: Signature verification failed"
+ "verifyECDSASignature: Verification failed - %s (code: %ld)"
+ "verifySignature(box:boxData:contentHash:container:)"
+ "writeAIMarkerBox(_:into:byteStream:)"
+ "writeBytes(_:to:at:)"
- "CMPhotoVerifySEPSignature: ECDSA X9.62 SHA-256 algorithm not supported by key"
- "CMPhotoVerifySEPSignature: Signature verification failed"
- "CMPhotoVerifySEPSignature: Verification failed - %s (code: %ld)"
```
