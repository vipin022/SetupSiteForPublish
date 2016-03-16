# SetupSiteForPublish
Setup Site for Web Deploy - updated since included powershell scripts do os version checks. I added switch to skip it
Edited line 153 and added a new switch parameter called skipOSSkuCheck

& 'C:\Program Files\IIS\Microsoft Web Deploy V3\Scripts\SetupSiteForPublish.ps1' -siteName mywebsite -publishSettingSavePath c:\temp -publishSettingFileName mywebsite.publishsettings -deploymentUserName administrator -skipOSSkuCheck

This will not force OS sku checking in the powershell script
