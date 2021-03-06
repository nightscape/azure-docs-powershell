---
external help file: Microsoft.Azure.Commands.SiteRecovery.dll-Help.xml
ms.assetid: AF3CACE3-632E-4901-8C2D-5B23C0F5C73E
online version: 
schema: 2.0.0
---

# Get-AzureRmSiteRecoveryNetworkMapping

## SYNOPSIS
Gets information about Site Recovery network mappings for the current vault.

## SYNTAX

### Default (Default)
```
Get-AzureRmSiteRecoveryNetworkMapping [<CommonParameters>]
```

### EnterpriseToEnterprise
```
Get-AzureRmSiteRecoveryNetworkMapping -PrimaryServer <ASRServer> -RecoveryServer <ASRServer>
 [<CommonParameters>]
```

### EnterpriseToAzure
```
Get-AzureRmSiteRecoveryNetworkMapping -PrimaryServer <ASRServer> [-Azure] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmSiteRecoveryNetworkMapping** cmdlet gets information about Azure Site Recovery network mappings for the current Site Recovery vault.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -Azure
Indicates that the command gets a list of network mappings for networks on the primary server mapped to Azure virtual networks.

```yaml
Type: SwitchParameter
Parameter Sets: EnterpriseToAzure
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PrimaryServer
```yaml
Type: ASRServer
Parameter Sets: EnterpriseToEnterprise, EnterpriseToAzure
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -RecoveryServer
```yaml
Type: ASRServer
Parameter Sets: EnterpriseToEnterprise
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[New-AzureRmSiteRecoveryNetworkMapping](./New-AzureRmSiteRecoveryNetworkMapping.md)

[Remove-AzureRmSiteRecoveryNetworkMapping](./Remove-AzureRmSiteRecoveryNetworkMapping.md)


