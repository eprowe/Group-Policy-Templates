Group Policy Administrative Templates for Adobe Acrobat DC on 64-bit Windows.  Requires Adobe.adml and Adobe.admx files for proper operation.

The settings for Acrobat can be found here: https://www.adobe.com/devnet-docs/acrobatetk/tools/PrefRef/Windows/index.html

There is no plan to support older versions of Acrobat or 32-Bit Windows.

# 3D #
* b3DEnableContent - This is a preference, not a policy.  User's will have the ability to change the setting after configuring this on the administrative side.
* bEnable3D - Configuring this setting doesn't have the effect described in Adobe's documentation.  Setting the value to either 0 or 1 disables the checkbox in the UI.  It does not disable/enable 3D content and disable the UI as expected.  Properly controlling the rendering of 3D content requires a combination of both policy settings.
# Access (Accessibility)

# Previously Completed #
* IsAMTEnforced
* ADC4275034
* ADC4275035
* ADC4275035_ClickEdit
* ProtectOldExperience
* Shared_Action_Folder
* bFindMoreWorkflowsOnline
* bAcroSuppressOpenInReader
* bEnableContextualTips
* bEnableContextualToolbar
* bEnableSmartFind
* bOrganizePagesFromThumbnails
* BlockEMFParsing
* BlockXPSParsing
* bToggleFillSign
* bToggleSendACopy
* bAdobeSendPluginToggle
* bEnablePVCertificateBasedTrust
* bDisableOSTrustedSites
* bDisableTrustedFolders
* bDisableTrustedSites
* bSuppressSignOut
* bSuppressMessageBar
* DisableScannedDocumentEditing
* bEnhancedSecurityInBrowser
* bEnhancedSecurityStandalone
* bEnableFlash
* bIgnoreDataSchema
* bToggleFTE
* bToggleShareFeedback
* bToggleToDoList
* bToggleToDoTiles
* bAllowUserToChangeMsgPrefs
* bDontShowMsgWhenViewingDoc
* bShowMsgAtLaunch
* Disable_Repair
* DisableMaintenance
* bCrashReporterEnabled
* bMergeMenuBar
* bMixRecentFilesFeatureLockDown
* bShouldUseScalableCursor
* bWinCacheSessionHandles
* dSplitBySizeMaxSize
* bAllowPasswordSaving
* bDisablePDFRedirectionActions
* bDisablePDFHandlerSwitching
* bHasAcrobatConsent
* bTogglePDFOwnershipToasts
* Removing_Tools
* bDisableAcrobatShortcutCustomization