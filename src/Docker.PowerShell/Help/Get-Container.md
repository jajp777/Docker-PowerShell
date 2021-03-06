---
external help file: Docker.PowerShell.dll-Help.xml
schema: 2.0.0
---

# Get-Container
## SYNOPSIS
Get-Container \[-HostAddress \<string\>\] \[-CertificateLocation \<string\>\] \[\<CommonParameters\>\]
## SYNTAX

```
Get-Container [[-Id] <String[]>] [-HostAddress <String>] [-CertificateLocation <String>] [<CommonParameters>]
```

## DESCRIPTION
Returns a list of containers.
## EXAMPLES

### Example 1
```
PS C:\> Get-Container
```

Retrieves a list of containers. 
## PARAMETERS

### -CertificateLocation
The location of the X509 certificate file named "key.pfx" that will be used for authentication with the server.  (Note that certificate authorization work is still in progress and this is likely to change).





```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

### -HostAddress
The address of the docker daemon to connect to.





```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: 
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
{{Fill Id Description}}

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: Name

Required: False
Position: 0
Default value: 
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).
## INPUTS

### None

## OUTPUTS

### Docker.DotNet.Models.ContainerListResponse

## NOTES

## RELATED LINKS

[Online Version:]()






