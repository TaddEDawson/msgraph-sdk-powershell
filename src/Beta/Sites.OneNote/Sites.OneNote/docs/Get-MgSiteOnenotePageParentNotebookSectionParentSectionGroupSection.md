---
external help file:
Module Name: Microsoft.Graph.Sites.OneNote
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.sites.onenote/get-mgsiteonenotepageparentnotebooksectionparentsectiongroupsection
schema: 2.0.0
---

# Get-MgSiteOnenotePageParentNotebookSectionParentSectionGroupSection

## SYNOPSIS
Get sections from sites

## SYNTAX

### List (Default)
```
Get-MgSiteOnenotePageParentNotebookSectionParentSectionGroupSection -OnenotePageId <String>
 -OnenoteSectionId <String> -SiteId <String> [-Count] [-Expand <String[]>] [-Filter <String>]
 [-Orderby <String[]>] [-Search <String>] [-Select <String[]>] [-Skip <Int32>] [-Top <Int32>]
 [<CommonParameters>]
```

### Get
```
Get-MgSiteOnenotePageParentNotebookSectionParentSectionGroupSection -OnenotePageId <String>
 -OnenoteSectionId <String> -OnenoteSectionId1 <String> -SiteId <String> [-Expand <String[]>]
 [-Select <String[]>] [<CommonParameters>]
```

### GetViaIdentity
```
Get-MgSiteOnenotePageParentNotebookSectionParentSectionGroupSection -InputObject <ISitesOneNoteIdentity>
 [-Expand <String[]>] [-Select <String[]>] [<CommonParameters>]
```

## DESCRIPTION
Get sections from sites

## EXAMPLES

### Example 1: {{ Add title here }}
```powershell
PS C:\> {{ Add code here }}

{{ Add output here }}
```

{{ Add description here }}

### Example 2: {{ Add title here }}
```powershell
PS C:\> {{ Add code here }}

{{ Add output here }}
```

{{ Add description here }}

## PARAMETERS

### -Count
Include count of items

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: List
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -Expand
Expand related entities

```yaml
Type: System.String[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -Filter
Filter items by property values

```yaml
Type: System.String
Parameter Sets: List
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.ISitesOneNoteIdentity
Parameter Sets: GetViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
Dynamic: False
```

### -OnenotePageId
key: onenotePage-id of onenotePage

```yaml
Type: System.String
Parameter Sets: Get, List
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -OnenoteSectionId
key: onenoteSection-id of onenoteSection

```yaml
Type: System.String
Parameter Sets: Get, List
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -OnenoteSectionId1
key: onenoteSection-id of onenoteSection

```yaml
Type: System.String
Parameter Sets: Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -Orderby
Order items by property values

```yaml
Type: System.String[]
Parameter Sets: List
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -Search
Search items by search phrases

```yaml
Type: System.String
Parameter Sets: List
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -Select
Select properties to be returned

```yaml
Type: System.String[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -SiteId
key: site-id of site

```yaml
Type: System.String
Parameter Sets: Get, List
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -Skip
Skip the first n items

```yaml
Type: System.Int32
Parameter Sets: List
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -Top
Show only the first n items

```yaml
Type: System.Int32
Parameter Sets: List
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.ISitesOneNoteIdentity

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphOnenoteSection

## ALIASES

## NOTES

### COMPLEX PARAMETER PROPERTIES
To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.

#### INPUTOBJECT <ISitesOneNoteIdentity>: Identity Parameter
  - `[NotebookId <String>]`: key: notebook-id of notebook
  - `[OnenoteOperationId <String>]`: key: onenoteOperation-id of onenoteOperation
  - `[OnenotePageId <String>]`: key: onenotePage-id of onenotePage
  - `[OnenotePageId1 <String>]`: key: onenotePage-id of onenotePage
  - `[OnenoteResourceId <String>]`: key: onenoteResource-id of onenoteResource
  - `[OnenoteSectionId <String>]`: key: onenoteSection-id of onenoteSection
  - `[OnenoteSectionId1 <String>]`: key: onenoteSection-id of onenoteSection
  - `[SectionGroupId <String>]`: key: sectionGroup-id of sectionGroup
  - `[SectionGroupId1 <String>]`: key: sectionGroup-id of sectionGroup
  - `[SiteId <String>]`: key: site-id of site

## RELATED LINKS

