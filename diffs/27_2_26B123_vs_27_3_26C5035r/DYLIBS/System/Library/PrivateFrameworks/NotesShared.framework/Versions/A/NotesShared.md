## NotesShared

> `/System/Library/PrivateFrameworks/NotesShared.framework/Versions/A/NotesShared`

```diff

-3195.42.3.0.0
-  __TEXT.__text: 0x366c08
+3195.61.6.0.0
+  __TEXT.__text: 0x36e100
   __TEXT.__delay_stubs: 0x1c0
   __TEXT.__delay_helper: 0x6b0
-  __TEXT.__objc_methlist: 0x18454
-  __TEXT.__const: 0xdde0
-  __TEXT.__cstring: 0x19606
-  __TEXT.__gcc_except_tab: 0xf2a0
-  __TEXT.__oslogstring: 0x1e4b9
+  __TEXT.__objc_methlist: 0x185d4
+  __TEXT.__const: 0xde10
+  __TEXT.__cstring: 0x19a36
+  __TEXT.__gcc_except_tab: 0xf360
+  __TEXT.__oslogstring: 0x1eed9
   __TEXT.__ustring: 0x39a
+  __TEXT.__swift5_typeref: 0x45a6
   __TEXT.__constg_swiftt: 0x37d8
-  __TEXT.__swift5_typeref: 0x4596
-  __TEXT.__swift5_builtin: 0x208
   __TEXT.__swift5_reflstr: 0x2259
   __TEXT.__swift5_fieldmd: 0x2f8c
+  __TEXT.__swift5_builtin: 0x208
   __TEXT.__swift5_assocty: 0x7e0
   __TEXT.__swift5_proto: 0x994
   __TEXT.__swift5_types: 0x39c

   __TEXT.__swift_as_ret: 0x1bc
   __TEXT.__swift_as_cont: 0x3fc
   __TEXT.__swift5_mpenum: 0x74
-  __TEXT.__unwind_info: 0x12920
-  __TEXT.__eh_frame: 0x888c
+  __TEXT.__unwind_info: 0x12ab0
+  __TEXT.__eh_frame: 0x88bc
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_protolist: 0x238
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0xcc38
+  __DATA_CONST.__objc_selrefs: 0xcd60
   __DATA_CONST.__objc_protorefs: 0xc0
   __DATA_CONST.__objc_superrefs: 0x6d0
   __DATA_CONST.__objc_arraydata: 0x228
   __DATA_CONST.__got: 0x2190
-  __AUTH_CONST.__const: 0x129a0
-  __AUTH_CONST.__cfstring: 0xfc80
-  __AUTH_CONST.__objc_const: 0x22850
+  __AUTH_CONST.__const: 0x12c30
+  __AUTH_CONST.__cfstring: 0xff40
+  __AUTH_CONST.__objc_const: 0x22868
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__objc_intobj: 0x420
   __AUTH_CONST.__objc_arrayobj: 0x258

   __AUTH.__objc_data: 0x2e50
   __AUTH.__data: 0x1608
   __DATA.__objc_ivar: 0xd90
-  __DATA.__data: 0x4c00
+  __DATA.__data: 0x4c10
   __DATA.__objc_stublist: 0x20
   __DATA.__bss: 0x10060
   __DATA.__common: 0x188
   __DATA_DIRTY.__objc_data: 0x48d8
-  __DATA_DIRTY.__data: 0x1df8
-  __DATA_DIRTY.__bss: 0x2c40
+  __DATA_DIRTY.__data: 0x1de8
+  __DATA_DIRTY.__bss: 0x2c30
   __DATA_DIRTY.__common: 0x1f0
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 18805
-  Symbols:   23001
-  CStrings:  5327
+  Functions: 18894
+  Symbols:   23096
+  CStrings:  5387
 
Symbols:
+ +[ICAccount(CloudKit) ic_isNoteBlockedFromPushing:]
+ +[ICAccount(CloudKit) ic_notesOnOtherPushes:]
+ +[ICAccount(CloudKit) ic_recentlyDeletedPushWaitTimeout]
+ +[ICAccount(CloudKit) ic_waitForOtherPushesOfNotes:inContext:until:then:]
+ +[ICAccount(Management) ic_manageStorageMoveBatchSize]
+ +[ICAccount(Management) ic_moveAllOwnedContentToRecentlyDeletedForAccountIdentifier:context:before:deletingFolders:savedHandler:completionHandler:]
+ +[ICAppURLUtilities acAccountIDInURL:]
+ +[ICAppURLUtilities accountToMoveAllToRecentlyDeletedInURL:context:]
+ +[ICAppURLUtilities isManageStorageMoveAllToRecentlyDeletedURL:]
+ +[ICAppURLUtilities isPrivateSettingsURL:]
+ +[ICAppURLUtilities manageStorageMoveAllToRecentlyDeletedURLForACAccountID:]
+ +[ICNote(LocalRecovery) copyNote:intoLocalFolder:]
+ +[ICNote(LocalRecovery) recoverNote:intoLocalFolder:]
+ -[ICAccount(CloudKit) hasUnsyncedNotesInRecentlyDeleted]
+ -[ICAccount(CloudKit) ic_pushOwedRecentlyDeletedObjectsInContext:cloudContext:waitingUntil:completionHandler:]
+ -[ICAccount(CloudKit) ic_pushRecentlyDeletedNotesWithCloudContext:completionHandler:]
+ -[ICAccount(CloudKit) ic_pushRecentlyDeletedNotesWithCompletionHandler:]
+ -[ICAccount(CloudKit) ic_recentlyDeletedNotesOwingPushWithLimit:]
+ -[ICAccount(Management) ic_deleteAllOwnedCustomFoldersBefore:]
+ -[ICAccount(Management) ic_deleteOwnedCustomFolderTree:rescuedNoteCount:]
+ -[ICAccount(Management) ic_folderTreeHoldsSparedNote:before:includingBlockedNotes:]
+ -[ICAccount(Management) ic_moveAllOwnedContentToRecentlyDeletedBefore:deletingFolders:savedHandler:completionHandler:]
+ -[ICAccount(Management) ic_moveAllOwnedNotesToRecentlyDeletedBefore:error:]
+ -[ICAccount(Management) ic_ownedSharedRootObjectsBefore:includingFolders:]
+ -[ICCloudContext addCallbackBlocksToModifyRecordsOperation:rootRecordIDsByShareID:session:isResumedLongLivedOperation:]
+ -[ICCloudContext addResumedLongLivedModifyRecordsOperation:]
+ -[ICCloudContext adoptSharedOwnerFromUserSpecificRecordParser:forPlaceholder:]
+ -[ICCloudContext dropAdoptedOwnerFromPlaceholder:resolvedByRecord:]
+ -[ICNote(LocalRecovery) ic_wholeTextAttachmentCount]
+ -[ICQueryResultsController contains:]
+ GCC_except_table210
+ GCC_except_table211
+ GCC_except_table222
+ GCC_except_table241
+ GCC_except_table273
+ GCC_except_table282
+ GCC_except_table301
+ GCC_except_table332
+ GCC_except_table374
+ GCC_except_table408
+ GCC_except_table533
+ _ICManageStorageSparesNote
+ __OBJC_$_CLASS_METHODS_ICNote(ActivityEvents|AirDropDocument|CloudKit|Management|AttachmentManagement|LocalRecovery|SearchIndexableNote|NotesShared|NotesShared1)
+ __OBJC_$_INSTANCE_METHODS_ICNote(ActivityEvents|AirDropDocument|CloudKit|Management|AttachmentManagement|LocalRecovery|SearchIndexableNote|NotesShared|NotesShared1)
+ __OBJC_CLASS_PROTOCOLS_$_ICNote(ActivityEvents|AirDropDocument|CloudKit|Management|AttachmentManagement|LocalRecovery|SearchIndexableNote|NotesShared|NotesShared1)
+ ___110-[ICAccount(CloudKit) ic_pushOwedRecentlyDeletedObjectsInContext:cloudContext:waitingUntil:completionHandler:]_block_invoke
+ ___110-[ICAccount(CloudKit) ic_pushOwedRecentlyDeletedObjectsInContext:cloudContext:waitingUntil:completionHandler:]_block_invoke_2
+ ___118-[ICAccount(Management) ic_moveAllOwnedContentToRecentlyDeletedBefore:deletingFolders:savedHandler:completionHandler:]_block_invoke
+ ___118-[ICAccount(Management) ic_moveAllOwnedContentToRecentlyDeletedBefore:deletingFolders:savedHandler:completionHandler:]_block_invoke_2
+ ___119-[ICCloudContext addCallbackBlocksToModifyRecordsOperation:rootRecordIDsByShareID:session:isResumedLongLivedOperation:]_block_invoke
+ ___147+[ICAccount(Management) ic_moveAllOwnedContentToRecentlyDeletedForAccountIdentifier:context:before:deletingFolders:savedHandler:completionHandler:]_block_invoke
+ ___45+[ICAccount(CloudKit) ic_notesOnOtherPushes:]_block_invoke
+ ___52-[ICNote(LocalRecovery) ic_wholeTextAttachmentCount]_block_invoke
+ ___56-[ICAccount(CloudKit) hasUnsyncedNotesInRecentlyDeleted]_block_invoke
+ ___73+[ICAccount(CloudKit) ic_waitForOtherPushesOfNotes:inContext:until:then:]_block_invoke
+ ___73+[ICAccount(CloudKit) ic_waitForOtherPushesOfNotes:inContext:until:then:]_block_invoke_2
+ ___85-[ICAccount(CloudKit) ic_pushRecentlyDeletedNotesWithCloudContext:completionHandler:]_block_invoke
+ ___85-[ICAccount(CloudKit) ic_pushRecentlyDeletedNotesWithCloudContext:completionHandler:]_block_invoke_2
+ ___ICDuplicateNoteForRecovery_block_invoke
+ ___block_descriptor_40_e8_32s_e34_B32?0"NSManagedObjectID"8Q16^B24l
+ ___block_descriptor_41_e8_32bs_e23_v24?0"NSError"8B16B20l
+ ___block_descriptor_41_e8_32bs_e8_v12?0B8l
+ ___block_descriptor_49_e8_32s40bs_e17_v16?0"NSError"8l
+ ___block_descriptor_50_e8_32s40bs_e17_v16?0"NSError"8l
+ ___block_descriptor_56_e8_32s40s48w_e45_v32?0"CKRecordID"8"CKRecord"16"NSError"24l
+ ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48s56r64w_e41_v32?0"NSArray"8"NSArray"16"NSError"24l
+ ___block_descriptor_73_e8_32s40s48s56bs64bs_e5_v8?0l
+ ___block_descriptor_80_e8_32s40s48s56s64bs_e17_v16?0"NSError"8l
+ ___block_descriptor_81_e8_32s40s48s56bs64bs72r_e17_v16?0"NSError"8l
+ ___block_descriptor_81_e8_32s40s48s56s64bs72bs_e17_v16?0"NSError"8l
+ ___block_descriptor_88_e8_32s40s48s56s64s72bs_e5_v8?0l
+ ___block_descriptor_89_e8_32s40s48s56s64bs72bs80r_e5_v8?0l
+ ___block_descriptor_89_e8_32s40s48s56s64s72bs80bs_e5_v8?0l
+ ___copy_helper_block_e8_32s40s48s56b64b
+ ___copy_helper_block_e8_32s40s48s56b64b72r
+ ___copy_helper_block_e8_32s40s48s56s64b72b
+ ___copy_helper_block_e8_32s40s48s56s64b72b80r
+ ___copy_helper_block_e8_32s40s48s56s64s72b80b
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80r
+ _objc_msgSend$__swift_objectForKeyedSubscript:
+ _objc_msgSend$abstractAttachmentsInOrder
+ _objc_msgSend$acAccountIDInURL:
+ _objc_msgSend$addCallbackBlocksToModifyRecordsOperation:rootRecordIDsByShareID:session:isResumedLongLivedOperation:
+ _objc_msgSend$addResumedLongLivedModifyRecordsOperation:
+ _objc_msgSend$adoptSharedOwnerFromUserSpecificRecordParser:forPlaceholder:
+ _objc_msgSend$cloudContext:didExceedQuotaRecoveringFromTrashWithCount:noteIdentifiers:accountID:
+ _objc_msgSend$contains:
+ _objc_msgSend$copyNote:intoLocalFolder:
+ _objc_msgSend$deleteDataFiles
+ _objc_msgSend$deleteSharesForObjects:completionHandler:
+ _objc_msgSend$dropAdoptedOwnerFromPlaceholder:resolvedByRecord:
+ _objc_msgSend$ensureHashtagsExistInDestinationAccount
+ _objc_msgSend$ic_deleteAllOwnedCustomFoldersBefore:
+ _objc_msgSend$ic_deleteOwnedCustomFolderTree:rescuedNoteCount:
+ _objc_msgSend$ic_firstObjectMatchingPredicate:context:
+ _objc_msgSend$ic_firstObjectMatchingPredicate:sortDescriptors:context:
+ _objc_msgSend$ic_folderTreeHoldsSparedNote:before:includingBlockedNotes:
+ _objc_msgSend$ic_isNoteBlockedFromPushing:
+ _objc_msgSend$ic_manageStorageMoveBatchSize
+ _objc_msgSend$ic_moveAllOwnedContentToRecentlyDeletedForAccountIdentifier:context:before:deletingFolders:savedHandler:completionHandler:
+ _objc_msgSend$ic_moveAllOwnedNotesToRecentlyDeletedBefore:error:
+ _objc_msgSend$ic_notesOnOtherPushes:
+ _objc_msgSend$ic_ownedSharedRootObjectsBefore:includingFolders:
+ _objc_msgSend$ic_pushOwedRecentlyDeletedObjectsInContext:cloudContext:waitingUntil:completionHandler:
+ _objc_msgSend$ic_pushRecentlyDeletedNotesWithCloudContext:completionHandler:
+ _objc_msgSend$ic_pushRecentlyDeletedNotesWithCompletionHandler:
+ _objc_msgSend$ic_recentlyDeletedNotesOwingPushWithLimit:
+ _objc_msgSend$ic_recentlyDeletedPushWaitTimeout
+ _objc_msgSend$ic_waitForOtherPushesOfNotes:inContext:until:then:
+ _objc_msgSend$initWithObjectIdentifier:forPasteboard:
+ _objc_msgSend$predicateForVisibleCustomFolders
+ _objc_msgSend$pushCloudObjects:operationGroupName:completionHandler:
+ _objc_msgSend$searchableItemMarkdownContent
+ _objc_msgSend$setIc_markdownContent:
+ _objc_msgSend$setOriginalCloudIdentifier:
+ _objc_msgSend$setPreferredBackgroundType:
+ _objc_msgSend$systemUptime
+ _symbolic _____yS2SSgG s18_DictionaryStorageC
- -[ICCloudContext addCallbackBlocksToModifyRecordsOperation:rootRecordIDsByShareID:session:]
- GCC_except_table178
- GCC_except_table271
- GCC_except_table310
- GCC_except_table317
- GCC_except_table346
- GCC_except_table356
- GCC_except_table522
- GCC_except_table527
- GCC_except_table532
- __OBJC_$_CLASS_METHODS_ICNote(ActivityEvents|AirDropDocument|CloudKit|Management|AttachmentManagement|SearchIndexableNote|NotesShared|NotesShared1)
- __OBJC_$_INSTANCE_METHODS_ICNote(ActivityEvents|AirDropDocument|CloudKit|Management|AttachmentManagement|SearchIndexableNote|NotesShared|NotesShared1)
- __OBJC_CLASS_PROTOCOLS_$_ICNote(ActivityEvents|AirDropDocument|CloudKit|Management|AttachmentManagement|SearchIndexableNote|NotesShared|NotesShared1)
- ___36+[ICAuthenticationState sharedState]_block_invoke
- ___49+[ICCryptoConvergenceController sharedController]_block_invoke
- ___91-[ICCloudContext addCallbackBlocksToModifyRecordsOperation:rootRecordIDsByShareID:session:]_block_invoke
- ___block_descriptor_64_e8_32s40s48r56w_e41_v32?0"NSArray"8"NSArray"16"NSError"24l
- ___block_descriptor_64_e8_32s40s48r56w_e45_v32?0"CKRecordID"8"CKRecord"16"NSError"24l
- ___copy_helper_block_e8_32s40s48r56w
- ___destroy_helper_block_e8_32s40s48r56w
- ___swift_project_boxed_opaque_existential_1Tm
- _objc_msgSend$addCallbackBlocksToModifyRecordsOperation:rootRecordIDsByShareID:session:
- _objc_msgSend$cloudContext:didExceedQuotaRecoveringFromTrashWithCount:
- _sharedState.onceToken
CStrings:
+ "Account has no managed object context"
+ "Account vanished before its content could be moved"
+ "B32@?0@\"NSManagedObjectID\"8Q16^B24"
+ "Cannot password-protect note {originalNote: %@}"
+ "Duplicated note"
+ "Duplicating note… {originalNote: %@, folder: %@}%s:%d"
+ "Error copying values to note %@"
+ "Failed to copy note values — deleting duplicated note {originalNote: %@, duplicatedNote: %@}"
+ "Failed to count ICSearchIndexState entities: %@"
+ "Failed to save after duplicating note {originalNote: %@, duplicatedNote: %@}"
+ "Failed to save after moving content to Recently Deleted"
+ "Failed to save note data — deleting duplicated note {originalNote: %@, duplicatedNote: %@}"
+ "ICManageStorage"
+ "ICNote * _Nullable ICDuplicateNoteForRecovery(ICNote *__strong, ICFolder *__strong)"
+ "ICNote * _Nullable ICDuplicateNoteForRecovery(ICNote *__strong, ICFolder *__strong)_block_invoke"
+ "ManageStorageFetchBeforeMove"
+ "ManageStorageMoveAllToRecentlyDeleted"
+ "ManageStoragePushRecentlyDeleted"
+ "Move"
+ "Move to Recently Deleted (Manage Storage folder cleanup)"
+ "Move to Recently Deleted (Manage Storage)"
+ "No worker context available"
+ "Not an iCloud account"
+ "Placeholder from a user-specific record is another user's shared object {object: %@}"
+ "Placeholder is resolved by a record of ours; dropping the owner its user-specific record gave it {object: %@}"
+ "Promoted joined subfolder out of a deleted custom folder (Manage Storage)"
+ "Re-parented joined note out of a deleted custom folder (Manage Storage)"
+ "Recently Deleted still owes a push"
+ "Refusing a Manage Storage deeplink that names the local account"
+ "Refusing a Manage Storage deeplink that resolved to a non-iCloud account"
+ "Saved after duplicating note {originalNote: %@, duplicatedNote: %@}"
+ "Saved while duplicating note"
+ "Simulating quota exceeded, so not sending %@ with %lu trash recovery objects"
+ "Sync isn't ready"
+ "Timed out fetching before the move"
+ "[MSQFA] Account %@ has no managed object context; cannot move content to Recently Deleted"
+ "[MSQFA] Account %@ not found; nothing to move to Recently Deleted"
+ "[MSQFA] Account %@ vanished after unsharing; aborting"
+ "[MSQFA] Account %@: Manage Storage cleanup sync complete"
+ "[MSQFA] Account %@: Recently Deleted is fully pushed, so not failing the delete on that sync error"
+ "[MSQFA] Account %@: Recently Deleted still owes a push after pushing it {note: %@, error: %@}"
+ "[MSQFA] Account %@: another push has %lu Recently Deleted note(s) on the way; pushing again once it's done"
+ "[MSQFA] Account %@: couldn't delete %lu share(s) before pushing Recently Deleted: %@"
+ "[MSQFA] Account %@: deleting %lu custom folder(s) {keptForNotesLeftInPlace: %lu, joinedNotesMovedToDefaultFolder: %lu}"
+ "[MSQFA] Account %@: error unsharing owned shares (continuing with delete): %@"
+ "[MSQFA] Account %@: fetch before the move failed, moving what's local: %@"
+ "[MSQFA] Account %@: moved %lu note(s) to Recently Deleted, deleted %lu custom folder(s)"
+ "[MSQFA] Account %@: moving %lu note(s) to Recently Deleted {joined: %lu, blocked: %lu, madeOrMovedAfterCutoff: %lu, cutoff: %{public}@, newestMovedDate: %{public}@}"
+ "[MSQFA] Account %@: no worker context available; aborting"
+ "[MSQFA] Account %@: not pushing %lu Recently Deleted note(s) yet; sync isn't ready"
+ "[MSQFA] Account %@: pushing %lu Recently Deleted object(s) on their own"
+ "[MSQFA] Account %@: pushing Recently Deleted failed (syncing anyway): %@"
+ "[MSQFA] Account %@: save failed with %lu note(s) already in Recently Deleted: %@"
+ "[MSQFA] Account %@: saved local changes, starting sync"
+ "[MSQFA] Account %@: sync error: %@"
+ "[MSQFA] Account %@: unsharing %lu owned share(s)"
+ "[MSQFA] Refusing to move content to Recently Deleted for account %@: it isn't an iCloud account"
+ "account == %@ AND serverShareData != nil"
+ "applenotessettings"
+ "folder.account == %@ AND serverShareData != nil"
+ "manageStorageMoveAllToRecentlyDeleted"
+ "v24@?0@\"NSError\"8B16B20"
- "Failed to fetch ICSearchIndexState entities: %@"
- "Simulating quota exceeded for record recovering from trash: %@"
```
