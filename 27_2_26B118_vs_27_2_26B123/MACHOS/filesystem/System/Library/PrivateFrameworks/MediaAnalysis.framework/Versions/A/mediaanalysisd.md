## mediaanalysisd

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/Versions/A/mediaanalysisd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_proto`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`

```diff

-460.14.5.1.0
-  __TEXT.__text: 0x23d770
-  __TEXT.__auth_stubs: 0x35d0
-  __TEXT.__objc_stubs: 0x17a60
-  __TEXT.__objc_methlist: 0xb520
-  __TEXT.__gcc_except_tab: 0x35f18
-  __TEXT.__cstring: 0x14124
+460.14.5.2.0
+  __TEXT.__text: 0x2215c8
+  __TEXT.__auth_stubs: 0x3590
+  __TEXT.__objc_stubs: 0x17820
+  __TEXT.__objc_methlist: 0xb438
+  __TEXT.__gcc_except_tab: 0x34350
+  __TEXT.__cstring: 0xff64
   __TEXT.__const: 0x25a0
-  __TEXT.__objc_methname: 0x1fa7f
+  __TEXT.__objc_methname: 0x1f8cd
   __TEXT.__objc_classname: 0x2246
-  __TEXT.__objc_methtype: 0x3c5b
-  __TEXT.__oslogstring: 0x2f441
+  __TEXT.__objc_methtype: 0x3c4b
+  __TEXT.__oslogstring: 0x2e9d1
   __TEXT.__dlopen_cstrs: 0x1da
   __TEXT.__swift5_typeref: 0xa7a
   __TEXT.__constg_swiftt: 0xa2c

   __TEXT.__swift5_assocty: 0x48
   __TEXT.__swift5_builtin: 0x50
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x96f0
+  __TEXT.__unwind_info: 0x8a88
   __TEXT.__eh_frame: 0x2348
-  __DATA_CONST.__const: 0x8398
-  __DATA_CONST.__cfstring: 0x8aa0
+  __DATA_CONST.__const: 0x7fc8
+  __DATA_CONST.__cfstring: 0x8240
   __DATA_CONST.__objc_classlist: 0x800
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0xd0

   __DATA_CONST.__objc_arrayobj: 0x7c8
   __DATA_CONST.__objc_dictobj: 0xc8
   __DATA_CONST.__objc_doubleobj: 0x20
-  __DATA_CONST.__auth_got: 0x1b00
-  __DATA_CONST.__got: 0x2778
+  __DATA_CONST.__auth_got: 0x1ae0
+  __DATA_CONST.__got: 0x2770
   __DATA_CONST.__auth_ptr: 0x600
-  __DATA.__objc_const: 0x17a00
-  __DATA.__objc_selrefs: 0x6628
-  __DATA.__objc_ivar: 0x14b4
+  __DATA.__objc_const: 0x179e0
+  __DATA.__objc_selrefs: 0x65a8
+  __DATA.__objc_ivar: 0x14b0
   __DATA.__objc_data: 0x58e8
-  __DATA.__data: 0x1690
-  __DATA.__bss: 0x3a60
+  __DATA.__data: 0x1618
+  __DATA.__bss: 0x3900
   __DATA.__common: 0x50
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7019
-  Symbols:   2235
-  CStrings:  10077
+  Functions: 6412
+  Symbols:   2230
+  CStrings:  9855
 
Symbols:
- _NSSelectorFromString
- _OBJC_CLASS_$_NSInvocation
- _VCPMADGetReadableMemoryUsageInformation
- __os_crash
- _puts
CStrings:
+ "Daemon appears to be hung; self-terminating"
- "\nUsage:\n\t-f,--full-interval   Interval to schedule full background analysis at (seconds)\n\t-h,--help            Display this usage information and exit\n"
- "%@ --> rejected person %@"
- "%@ Add face %@ (%lu)"
- "%@ Adding FaceOnly to Gallery"
- "%@ Adding FaceTorso to Gallery"
- "%@ Adding TorsoOnly to Gallery"
- "%@ Adding observation without valid print"
- "%@ Client FaceCrop %@"
- "%@ Deleting unverified person %@ (%@)"
- "%@ Entity to update %ld"
- "%@ Face %@ confirms graph verified person %@"
- "%@ Face %@ confirms user verified person %@"
- "%@ Face %@ rejects %lu persons"
- "%@ Face %@ rejects person %@"
- "%@ Gallery indexed FaceCrop %@"
- "%@ Latest bookmark from VU %@"
- "%@ No face for observation %@"
- "%@ Orphan training face %@"
- "%@ Person not in Photos DB (should be according to bookmark %@)"
- "%@ Person not in Photos DB (should be according to bookmark) from bookmark %@ to bookmark %@"
- "%@ Unexpected person update with %lu VU, %lu PhotosDB from bookmark %@ to bookmark %@"
- "%@ Will merge person %@(%@)(VerifyType-%ld) to person %@(%@)(VerifyType-%ld)"
- "%@ changeBookmark changed from query %@ to store %@"
- "%@ failed to encode changeBookmark %@"
- "%@ failed to encode currentChangeBookmark %@"
- "%@ failed to encode previousChangeBookmark %@"
- "%@ missing observation: %@"
- "%@: %@"
- "%lu %@"
- "%lu-day scheduling history (%lu records) for background activity %@:"
- "(Forced) "
- "--full-interval"
- "--help"
- "-f"
- "-h"
- "./Utilities/CGUtilities.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/Home/MADHomePersonProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/MADPhotosFaceAssetProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/MADPhotosFaceFastPassProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/MADPhotosFullAssetProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/MADPhotosOCRAssetProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/MADPhotosPersonProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/MADPhotosVisualSearchAssetProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Filesystem/MADFilesystemProgressReportingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Filesystem/VCPMADFilesystemProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Filesystem/VCPMADFilesystemVideoProcessingTask.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/HomeKit/VCPHomeKitAnalysisServiceTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/MADPreheatingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/MADVUUtilities.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/MADVectorDatabaseUtilities.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/MediaAnalysisDaemon.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Moments/MADMomentsDeferredProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADFullAnalysisResultsSynchronizationTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADFullAssetBatch.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADImageRichCaptionAssetBatch.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADPhotosBackupAnalysisTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADPhotosBackupProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADPhotosDatabaseMigrationProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADPhotosLibraryRestoreTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADPhotosRestoreAnalysisTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADPhotosTelemetryProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADProgressManager.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADProgressReporterProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADRichCaptionLibraryProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADTUAssetBatch.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADTULibraryProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADVideoRichCaptionAssetBatch.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MediaAnalysisServiceTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/NSInputStream+VCPRestore.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/PHAssetResourceManager+InMemoryDownload.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/PHPhotoLibrary+MediaAnalysisDaemonAnalysisMigration.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPAssetAnalysisTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPBackgroundProcessingMetrics.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPBackupEntryHeader.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPBackupFileHeader.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPBatchAnalysisTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPEffectsAssetProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPFaceAssetProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPFaceLibraryProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPFaceProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPFailedAssetAnalysisTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADFullAssetProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADOCRAssetBatch.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADPECAssetBatch.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADPECLibraryProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADPECSingleRequestProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADPhotoAssetProcessingTask.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADPhotosFetchProcessingTask.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADPhotosLibraryProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADPhotosProcessingTask.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADQuickFaceIDAssetBatch.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADSceneAssetBatch.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADSceneLibraryProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADVisualSearchAssetBatch.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMediaTypeAnalysisTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPPausedAnalysis.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPPhotosAssetChangeManager.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPPhotosAssetProcessingTask.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPPhotosCaptureProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPPhotosCoreAnalytics.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPPhotosFaceIdentificationTask.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPPhotosMaintenanceProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPRestoreDatabaseTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPResumePausedAnalysisTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPSystemMonitor.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPUnifiedFullAnalysisTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Spotlight/MADSpotlightImageProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Spotlight/MADSpotlightMovieProcessingTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/VCPCompoundMADTask.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Service/VCPMADRemoteActivityTask.mm"
- "Add MAD_WATCHDOG_CRASH_CALLBACK_METHOD to your class - %@"
- "AllowStreaming"
- "AutoCounter "
- "Biome appears to be hung. Reported: %s. Began operation at %@"
- "BlurExposureRotationConcurrentQueueCount"
- "Compilation of the text encoder. Reported: %s. Began operation at %@"
- "Compilation of the visual encoder. Reported: %s. Began operation at %@"
- "ConcurrentAssetCountFullImage"
- "ConcurrentAssetCountFullLivePhoto"
- "ConcurrentAssetCountFullVideo"
- "ConcurrentFaceAnalysis"
- "ConcurrentPreAnalysis"
- "DAS cancellation %s via default"
- "Daemon appears to be hung (%@); self-terminating"
- "DisablePersonChangeBatching"
- "Dlib appears to be hung. Began operation at %@"
- "EnablePerFrameHomeKitAnalysis"
- "EnableRemoteActivity"
- "Error: This option is currently unsupported."
- "FaceAnalysisConcurrentQueueCount"
- "FaceClustering "
- "FaceCropProcessing "
- "FaceDetection "
- "FaceProcessingConcurrentQueueCount"
- "FaceStagingConcurrency"
- "ForceInitialScanNoResource"
- "FrequentProgressReporting"
- "IgnoreDASCancellation"
- "ImageRichCaptionBypassGating"
- "ImageRichCaptionMaxWordCound"
- "JITCameraFaceOnly"
- "Latest Watchdog petting at %s[%d]"
- "Long movie download timeout set to %0.2f via default"
- "LongMovieDownloadTimeout"
- "MAD_PET_SHARED_WATCHDOG_WITH_CALLBACK object deallocated - %@"
- "Maintenance"
- "Model initialization appears to be hung. Reported: %s. Began preheat at %@"
- "MomentsGracePeriod"
- "MomentsPriority"
- "No scheduling history for background activity %@ in database"
- "NoResultStrip"
- "ParseConcurrentAssetCount"
- "Per client scheduled request limit set to %d"
- "PerClientScheduledRequestLimit"
- "Persist full-range signals %@"
- "PersistFullRangeSignals"
- "Person promoting appears to be hung. Reported: %s. Began operation at %@"
- "PersonBuilding "
- "PersonPromoting "
- "Photos appears to be hung. Reported: %s. Began operation at %@"
- "ProcessCapturedFace"
- "QuickFaceID "
- "Remote DAS activity %s via default"
- "RichCaptionCapRatioImage"
- "RichCaptionCapRatioVideo"
- "SceneNetConcurrentQueueCount"
- "SceneProcessing "
- "Set ImageRichCaptionBypassGating to %d"
- "Set ImageRichCaptionMaxWordCound to %lu"
- "Set RichCaptionCapRatioImage to %f"
- "Set RichCaptionCapRatioVideo to %f"
- "Set VideoRichCaptionBypassGating to %d"
- "Set VideoRichCaptionMaxWordCound to %lu"
- "TextUnderstanding appears to be hung. Reported: %s. Began operation at %@"
- "Unknown option \"%@\" specified"
- "Unknown priority %@, default to Maintenance"
- "Utility"
- "VideoRichCaptionBypassGating"
- "VideoRichCaptionMaxWordCound"
- "Watchdog Timeout"
- "Watchdog disabled"
- "WatchdogTimeoutSeconds"
- "[%@] Concurrent asset count set via defaults (%d)"
- "[%@][PhotosCapture] Persisting matching face %@ with person %@"
- "[%@][PhotosCapture] Persisting unrecognized face %@"
- "[CoreAnalyticManager] %@ %@ days with since Version %llu created %@"
- "[CoreAnalyticManager] %@ invalid taskID %lu (%@); ignore"
- "[CoreAnalyticManager] %@: invalid allowed assets count %lu; ignore"
- "[CoreAnalyticManager] %@: invalid progress %lu%%; ignore"
- "[FaceCrop] Processed %lu facecrop for person %@"
- "[FaceLibraryProcessing] Running with: "
- "[GalleryUpdate] Person change batching %s via default"
- "[LOG_ERROR] %s[%d]: code %d\n"
- "[Perf] Memory usage before running the first task: %@"
- "[Perf] Memory usage on finishing all scheduled tasks: %@"
- "[Perf] Memory usage: %@"
- "[QuickFaceID][%@] Persisting matching face %@ with person %@"
- "[QuickFaceID][%@] Persisting unrecognized face %@"
- "[Scene] Defaults to fail initial scan with no resource"
- "[VisualSearch] Concurrent asset count set via default (%d)"
- "_memoryUsageMonitor"
- "base64EncodedStringWithOptions:"
- "captureCrashWithKnownTimeoutRisk:"
- "currentTimeoutRiskAndStartTime:"
- "disabled"
- "dumpBreadcrumps"
- "faceTorsoprint"
- "invocationWithMethodSignature:"
- "invoke"
- "methodSignatureForSelector:"
- "parseCommandLine:argv:"
- "printUsageAndExitWith:andMessage:"
- "setArgument:atIndex:"
- "setSelector:"
- "setTarget:"
- "stringWithCString:encoding:"
- "timeoutCrashWithMessage:"
- "unsignedLongValue"
- "v24@?0@\"NSUUID\"8^B16"
- "v24@?0@\"VUWGalleryEntityIdentifier\"8^B16"
- "v24@?0@8^B16"
- "v28@0:8i16r^*20"
- "v32@?0@\"NSNumber\"8@\"NSMutableSet\"16^B24"
```
