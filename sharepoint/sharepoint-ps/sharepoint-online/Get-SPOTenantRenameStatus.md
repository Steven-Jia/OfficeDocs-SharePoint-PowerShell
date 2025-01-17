---
external help file: sharepointonline.xml
Module Name: Microsoft.Online.SharePoint.PowerShell
online version: https://docs.microsoft.com/powershell/module/sharepoint-online/get-spotenantrenamestatus
applicable: SharePoint Online
title: Get-SPOTenantRenameStatus
schema: 2.0.0
author: WayneEwington
ms.author: waynewin
ms.reviewer:
---

# Get-SPOTenantRenameStatus

## SYNOPSIS

> [!IMPORTANT]
> - This feature is available only for customers who have been accepted into the Private Preview program. [Request to join the Private Preview](https://aka.ms/SPOTenantRenameNomination). Note that submitting a nomination does not guarantee acceptance into the program. We review the nominations on a case-by-case basis and will contact you if you're accepted.
> - This feature is not available for organizations that have set up multi-geo.

Get the status of the job to change the SharePoint domain name for your organization in Microsoft 365.

## SYNTAX

```Powershell
Get-SPOTenantRenameStatus [<CommonParameters>]
```

## DESCRIPTION

This command gets the status of the job to rename the SharePoint domain name for your organization.

## EXAMPLES

### EXAMPLE 1

```powershell
Get-SPOTenantRenameStatus
```

Gets the status of the job to rename your SharePoint domain name.

## PARAMETERS

### CommonParameters

This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/?LinkID=113216).

## RELATED LINKS

[Getting started with SharePoint Online Management Shell](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)

[Rename your SharePoint domain](https://aka.ms/SPOTenantRename)

[Start-SPOTenantRename](Start-SPOTenantRename.md)

[Stop-SPOTenantRename](Stop-SPOTenantRename.md)

[Get-SPOSiteRenameState](Get-SPOSiteRenameState.md)
