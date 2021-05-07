Group Policy Administrative Templates for Adobe Acrobat DC on 64-bit Windows.  Requires Adobe.adml and Adobe.admx files for proper operation.

There is no plan to support older versions of Acrobat or 32-Bit Windows.

Only supporting the lockable preferences documented here:
* https://www.adobe.com/devnet-docs/acrobatetk/tools/PrefRef/Windows/lockable.html
* https://www.adobe.com/devnet-docs/acrobatetk/tools/PrefRef/Windows/FeatureLockdown.html

# Lockable Preferences: #
* IsAMTEnforced : Please note this is a preference and not a policy.
* bPreviouslyEnabledSharePointInChromeExtn : Not included.  Flagged by Adobe as 'Not modifiable as the key is application or machine generated'.
## Actions (online resources) ##
* bFindMoreWorkflowsOnline
## Actions (shared folders) ##
* tDIPath
* tName
## AppContainer ##
* bEnableProtectedModeAppContainer : This policy is not supported by Adobe Acrobat Pro
## Bates numbering ##
* bBatesLogOriginalFileName
## Chrome Integration ##
* bAcroSuppressOpenInReader
* ENABLE_CHROMEEXT : This policy is not supported by Adobe Acrobat Pro
## Context menus, tips, tools
* bEnableContextualTips
* bEnableContextualToolbar
* bOrganizePagesFromThumbnails
## Create PDF ##
* bEnableFrictionlessInChromeExtn : This policy is not supported by Adobe Acrobat Pro
* BlockEMFParsing : Please note this is a preference and not a policy.
* BlockXPSParsing : Please note this is a preference and not a policy.
* ExportEntireTableContent : Not included.  Flagged by Adobe as 'Not modifiable as the key is application or machine generated'.
## DC Fill & Sign Integration ##
* bToggleFillSign
* bToggleSendACopy
## DC Send and Track ##
* bAdobeSendPluginToggle
## Digital Signature Certification ##
* bEnablePVCertificateBasedTrust
## Disabling Privileged Locations ##
* bDisableOSTrustedSites
* bDisableTrustedFolders
* bDisableTrustedSites
## Disabling Sign Out ##
* bSuppressSignOut
## Document Message Bar ##
* bSuppressMessageBar
## Editing Scanned PDFs ##
* DisableScannedDocumentEditing : Please note this is a preference and not a policy.
## Enhanced Security ##
* bEnhancedSecurityInBrowser
* bEnhancedSecurityStandalone
##  Flash ##
* bEnableFlash
## Form Preferences ##
* bAutoFill : Not included.  Only applicable to versions 8.0-9.0.
* bIgnoreDataSchema
## Home Screen and Startup ##
* bToggleFTE
* bToggleToDoList
* bToggleToDoTiles
## In Product Messaging ##
* bAllowUserToChangeMsgPrefs
* bDontShowMsgWhenViewingDoc
* bShowMsgAtLaunch
## Install details ##
* Disable_Repair : Please note this is a preference and not a policy.
* DisableMaintenance : Please note this is a preference and not a policy.
* Path : Not included.  Flagged by Adobe as 'Not modifiable as the key is application or machine generated'.
## Miscellaneous Features ##
* bCommercialPDF : Not included.  Only applicable to versions 8.0-11.x
* bCrashReporterEnabled
* bEnableAutoDockUndockHUD 
* bMergeMenuBar : Please note this is a preference and not a policy.
* bMixRecentFilesFeatureLockDown
* bRegisterProduct : Not included.  Only applicable to versions 6.0-9.x
* bShouldUseScalableCursor
* bShowAdsAllow : Not included.  Only applicable to versions 6.0-9.0
* bShowEbookMenu : Not included.  Only applicable to versions 9.0-11.x
* bToggleBillingIssue
* bWinCacheSessionHandles
* dSplitBySizeMaxSize
## Mobile Link ##
## Network and Protocol Access ##
Due to the poorly documented nature of the following settings I'm not going to include them in these template files.  The documentation is unclear on what these settings are, how they can be modified, or how each value should be configured.  For example, tSchemePerms has what appears to be a list of URI Schemes followed by a number, but there is no indication what the number value represents.  A search seems to indicate that a 3 restricts the user of the protocol, but nothing about what a 1 does.  Additionally, Adobe indicates that these values may be regulary updated so it may be best to leave them for Adobe to manage.
* cDefaultLaunchURLPerms
* tFlashContentSchemeWhiteList
* tSchemePerms
* tSponsoredContentSchemeWhiteList
## Password Caching ##
* bAllowPasswordSaving
## PDF Link Blocking ##
* bDisablePDFRedirectionActions
## PDF Ownership ##
* bDisablePDFHandlerSwitching
* bEnableAcrobatPromptForDocOpen : This policy is not supported by Adobe Acrobat Pro
* bHasAcrobatConsent
* bTogglePDFOwnershipToasts
## Protected Mode ##
* cJSEditor 
* cProtectedModeConfigFiles : Not implemented, yet.  https://www.adobe.com/devnet-docs/acrobatetk/tools/AppSec/index.html
## Removing Tools ##
Removing tools using these policies removes them from both the Tools tab and the right-hand pane as well.
* a(index)
* cDisabled
## Right-hand Tools Pane Customizations (DC) ##
* bDisableAcrobatShortcutCustomization
## Search ##
* bEnableAutoCompleteExactMatchLoader
* bEnableAutoCompleteNoExactMatchHeader
* bEnableAutoCompleteNoInternetConnectionHeader
* bEnableCloudPoweredSearch
* bEnableCloudPoweredSearchTokenCaching
## Send usage data to Adobe ##
* bEnableADMAnalytics
* bToggleShareFeedback
## Services (Acrobat.com: 11.x and earlier) ##
* bDisableADCFileStore
* bEnableADCFileStore
* bEnableBHCache
* bShowDistAcrobatDotCom
## Services (SharePoint-Office365) ##
* bDisableSharePointFeatures
## Services (Unified Share) ##
* bSendMailShareRedirection
* bToggleSendAndTrack
## Services-Adobe Sign (DC) ##
* bToggleAdobeSign
* bToggleFSSSignatureSaving
* bToggleManageSign
## Services-Cloud Storage (DC) ##
* bBoxConnectorEnabled
* bDropboxConnectorEnabled
* bGoogleDriveConnectorEnabled
* bOneDriveConnectorEnabled
* bToggleDocumentCloud
* bToggleWebConnectors
## Services-Master Switches (DC) ##
* bToggleAdobeDocumentServices
* bUpdater
## Services-Notifications (DC) ##
* bEnableBellButton
* bToggleNotifications
* bToggleNotificationToasts
## Services-Preference Synchronization (DC) ##
* bTogglePrefsSync
## Services-Reviews (DC) ##
* bEnableReviewPromote
* bToggleAdobeReview
## Services-Scan app integration (DC) ##
* bShowScanTabInHomeView
## Shared Reviews ##
* bDisableOnBehalfOfText
## Signature Clearing ##
* bEnableSignatureClear
## Signing: Format ##
* aSignFormat
## Signing: User Interface ##
* bEnableCEFBasedUI
## Starred files ##
* bFavoritesFeaturesLockDown
## Tool Sets (online resources) ##
* bFindMoreCustomizationsOnline
## Updater (basic settings) ##
* bUpdater
* Check
* Mode
## Updater Logging ##
* iLogLevel
## Upsell ##
* bAcroSuppressUpsell
* bEnableTrialistLaunchCard
* bPurchaseAcro
* bReaderRetentionExperiment
* bShowRhpToolSearch
* bToggleDCAppCenter
* bToggleSophiaWebInfra
## WebMail (Custom) ##
* iIMAPPort
* iIMAPSecurity
* iSMTPPort
* iSMTPSecurity
* tIMAPDraftsFolder
* tIMAPDraftsURL
* *tIMAPHostName
* tProfileID
* tSMTPHostName
## WebMail (Gmail) ##
* iClientType
* tProfileID
## WebMail (Yahoo) ##
* iClientType
* tProfileID
## Webmail Basics ##
* bDisableWebmail
* tDefaultProfile
## Windows Explorer Integration ##
* bDisableThumbnailPreviewHandler