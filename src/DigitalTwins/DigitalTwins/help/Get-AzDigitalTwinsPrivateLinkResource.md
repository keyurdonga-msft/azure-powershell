---
external help file:
Module Name: Az.DigitalTwins
online version: https://learn.microsoft.com/powershell/module/az.digitaltwins/get-azdigitaltwinsprivatelinkresource
schema: 2.0.0
---

# Get-AzDigitalTwinsPrivateLinkResource

## SYNOPSIS
Get the specified private link resource for the given Digital Twin.

## SYNTAX

### List (Default)
```
Get-AzDigitalTwinsPrivateLinkResource -ResourceGroupName <String> -ResourceName <String>
 [-SubscriptionId <String[]>] [-DefaultProfile <PSObject>] [<CommonParameters>]
```

### Get
```
Get-AzDigitalTwinsPrivateLinkResource -ResourceGroupName <String> -ResourceId <String> -ResourceName <String>
 [-SubscriptionId <String[]>] [-DefaultProfile <PSObject>] [<CommonParameters>]
```

### GetViaIdentity
```
Get-AzDigitalTwinsPrivateLinkResource -InputObject <IDigitalTwinsIdentity> [-DefaultProfile <PSObject>]
 [<CommonParameters>]
```

## DESCRIPTION
Get the specified private link resource for the given Digital Twin.

## EXAMPLES

### Example 1: Get the specified private link resource for the given Digital Twin.
```powershell
Get-AzDigitalTwinsPrivateLinkResource -ResourceGroupName azps_test_group -ResourceName azps-digitaltwins-instance
```

```output
GroupId Name ResourceGroupName
------- ---- -----------------
API     API  azps_test_group
```

Get the specified private link resource for the given Digital Twin.

### Example 2: Get the specified private link resource for the given Digital Twin.
```powershell
Get-AzDigitalTwinsPrivateLinkResource -ResourceGroupName azps_test_group -ResourceName azps-digitaltwins-instance -ResourceId API
```

```output
GroupId Name ResourceGroupName
------- ---- -----------------
API     API  azps_test_group
```

Get the specified private link resource for the given Digital Twin.

## PARAMETERS

### -DefaultProfile
The credentials, account, tenant, and subscription used for communication with Azure.

```yaml
Type: System.Management.Automation.PSObject
Parameter Sets: (All)
Aliases: AzureRMContext, AzureCredential

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.DigitalTwins.Models.IDigitalTwinsIdentity
Parameter Sets: GetViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ResourceGroupName
The name of the resource group that contains the DigitalTwinsInstance.

```yaml
Type: System.String
Parameter Sets: Get, List
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceId
The name of the private link resource.

```yaml
Type: System.String
Parameter Sets: Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceName
The name of the DigitalTwinsInstance.

```yaml
Type: System.String
Parameter Sets: Get, List
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SubscriptionId
The subscription identifier.

```yaml
Type: System.String[]
Parameter Sets: Get, List
Aliases:

Required: False
Position: Named
Default value: (Get-AzContext).Subscription.Id
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Azure.PowerShell.Cmdlets.DigitalTwins.Models.IDigitalTwinsIdentity

## OUTPUTS

### Microsoft.Azure.PowerShell.Cmdlets.DigitalTwins.Models.Api20220531.IGroupIdInformation

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`INPUTOBJECT <IDigitalTwinsIdentity>`: Identity Parameter
  - `[EndpointName <String>]`: Name of Endpoint Resource.
  - `[Id <String>]`: Resource identity path
  - `[Location <String>]`: Location of DigitalTwinsInstance.
  - `[PrivateEndpointConnectionName <String>]`: The name of the private endpoint connection.
  - `[ResourceGroupName <String>]`: The name of the resource group that contains the DigitalTwinsInstance.
  - `[ResourceId <String>]`: The name of the private link resource.
  - `[ResourceName <String>]`: The name of the DigitalTwinsInstance.
  - `[SubscriptionId <String>]`: The subscription identifier.
  - `[TimeSeriesDatabaseConnectionName <String>]`: Name of time series database connection.

## RELATED LINKS

