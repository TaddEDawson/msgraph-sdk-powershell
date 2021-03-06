---
external help file:
Module Name: Microsoft.Graph.Users.Functions
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.users.functions/invoke-mgcalendarusercalendargroupcalendareventcalendar
schema: 2.0.0
---

# Invoke-MgCalendarUserCalendarGroupCalendarEventCalendar

## SYNOPSIS
Invoke function allowedCalendarSharingRoles

## SYNTAX

### Calendar (Default)
```
Invoke-MgCalendarUserCalendarGroupCalendarEventCalendar -CalendarGroupId <String> -CalendarId <String>
 -EventId <String> -User <String> -UserId <String> [<CommonParameters>]
```

### CalendarViaIdentity
```
Invoke-MgCalendarUserCalendarGroupCalendarEventCalendar -InputObject <IUsersFunctionsIdentity>
 [<CommonParameters>]
```

## DESCRIPTION
Invoke function allowedCalendarSharingRoles

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

### -CalendarGroupId
key: calendarGroup-id of calendarGroup

```yaml
Type: System.String
Parameter Sets: Calendar
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -CalendarId
key: calendar-id of calendar

```yaml
Type: System.String
Parameter Sets: Calendar
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -EventId
key: event-id of event

```yaml
Type: System.String
Parameter Sets: Calendar
Aliases:

Required: True
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
Type: Microsoft.Graph.PowerShell.Models.IUsersFunctionsIdentity
Parameter Sets: CalendarViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
Dynamic: False
```

### -User
.

```yaml
Type: System.String
Parameter Sets: Calendar
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### -UserId
key: user-id of user

```yaml
Type: System.String
Parameter Sets: Calendar
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
Dynamic: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IUsersFunctionsIdentity

## OUTPUTS

### System.String

## ALIASES

## NOTES

### COMPLEX PARAMETER PROPERTIES
To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.

#### INPUTOBJECT <IUsersFunctionsIdentity>: Identity Parameter
  - `[CalendarGroupId <String>]`: key: calendarGroup-id of calendarGroup
  - `[CalendarId <String>]`: key: calendar-id of calendar
  - `[ContactFolderId <String>]`: key: contactFolder-id of contactFolder
  - `[EndDateTime <String>]`: 
  - `[EventId <String>]`: key: event-id of event
  - `[IncludePersonalNotebooks <Boolean?>]`: 
  - `[MailFolderId <String>]`: key: mailFolder-id of mailFolder
  - `[ManagedDeviceId <String>]`: key: managedDevice-id of managedDevice
  - `[NotebookId <String>]`: key: notebook-id of notebook
  - `[OnenotePageId <String>]`: key: onenotePage-id of onenotePage
  - `[OnenotePageId1 <String>]`: key: onenotePage-id of onenotePage
  - `[OnenoteSectionId <String>]`: key: onenoteSection-id of onenoteSection
  - `[RoomList <String>]`: 
  - `[SectionGroupId <String>]`: key: sectionGroup-id of sectionGroup
  - `[Skip <Int32?>]`: 
  - `[StartDateTime <String>]`: 
  - `[TimeZoneStandard <String>]`: 
  - `[Top <Int32?>]`: 
  - `[User <String>]`: 
  - `[UserId <String>]`: key: user-id of user

## RELATED LINKS

