Group Policy Administrative Templates for Adobe Acrobat Reader DC on 64-bit Windows.  Requires Adobe.adml and Adobe.admx files for proper operation.

The settings for Acrobat Reader can be found here: https://www.adobe.com/devnet-docs/acrobatetk/tools/PrefRef/Windows/index.html

There is no plan to support older versions of Acrobat Reader or 32-bit Windows.

# Lockable Preferences: #
Lockable preferences supported by Adobe Acrobat Reader as documented here: https://www.adobe.com/devnet-docs/acrobatetk/tools/PrefRef/Windows/lockable.html
* bPreviouslyEnabledSharePointInChromeExtn - Flagged as 'Not modifiable as the key is application or machine generated.'
## Actions (online resources) ##
* bFindMoreWorkflowsOnline : In my testing I have been unable to identify what changes, if any, this setting changes once enabled.
## Actions (shared folders) ##
* tDIPath
* tName
## AppContainer ##
* bEnableProtectedModeAppContainer - This policy is intended for Adobe Acrobat Reader
## Chrome Integration ##
* bAcroSuppressOpenInReader
* ENABLE_CHROMEEXT - This policy is intended for Adobe Acrobat Reader
## Context menus, tips, tools
* bEnableContextualTips - In my testing I could not find any discernable difference if this policy was or wasn't enabled.
* bEnableContextualToolbar
## Create PDF ##
* bEnableFrictionlessInChromeExtn
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
* DisableScannedDocumentEditing
## Enhanced Security ##
* bEnhancedSecurityInBrowser
* bEnhancedSecurityStandalone
##  Flash ##
* bEnableFlash
## Form Preferences ##
* bAutoFill - Version 8.0-9.0
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
* Disable_Repair
* DisableMaintenance
* Path - Not modifiable as the key is application or machine generated.
## Miscellaneous Features ##
* bCommercialPDF - Version 8.0-11.x
* bEnableAutoDockUndockHUD
* bMergeMenuBar
* bMixRecentFilesFeatureLockDown
* bRegisterProduct - Version 6.0-9.x
* bShouldUseScalableCursor
* bShowAdsAllow - Version 6.0-9.0
* bShowEbookMenu - Version 9.0-11.x
* bWinCacheSessionHandles
## Mobile Link ##
## Network and Protocol Access ##
Due to the poorly documented nature of the following settings I'm not going to include them in these template files.  The documentation is unclear on what these settings are, how they can be modified, or what each value should be configured as.  For example, tSchemePerms has what appears to be a list of URI Schemes followed by a number, but there is no indication what the number value represents.  A search seems to indicate that a 3 restricts the user of the protocol, but nothing about what a 1 does.  Additionally, Adobe indicates that these values may be regulary updated so it may be best to leave them for Adobe to manage.
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
* bEnableAcrobatPromptForDocOpen - This policy is intended for Adobe Acrobat Reader
* bHasAcrobatConsent
* bTogglePDFOwnershipToasts
## Protected Mode ##
* cProtectedModeConfigFiles
## Protected View ##
* bEnablePVSwitchoutShortcut
## Removing Tools ##
* a(index)
* cDisabled
## Right-hand Tools Pane Customizations (DC) ##
* a(index)
* bDisableAcrobatShortcutCustomization
* cFavorites
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
* bDisableThirdPartyPluginNotif
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
## Sharepoint Integration ##
* bEnableSharePointInChromeExtn
* tSharePointUrls
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
* bLimitPromptsFeatureKey
* bPurchaseAcro
* bReaderRetentionExperiment
* bShowRhpToolSearch
* bToggleDCAppCenter
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