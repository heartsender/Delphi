# Delphi Coding Standards and Naming Conventions


| Object Name               | Notation   |  Begin |
|:--------------------------|:-----------|-------:|
| Unit name                 | PascalCase |        |
| Class name                | InfixCaps  |    T   |
| Constructor name          | PascalCase |        |
| Method name               | PascalCase |        |
| Method arguments          | PascalCase |        |
| Local variables           | PascalCase |        |
| Field name                | InfixCaps  |    F   |
| Properties name           | PascalCase |        |
| Enum type name            | Hungarian  |        |

'A' is for 'Argument'. Also, 'F' is for 'Field', 'T' is for 'Type', 'E' is for 'Exception', 'I' is for 'Interface'.
There is no rule when to add 'A' prefix and when not.
Modern VCL code uses L as a prefix for local variable

Ex: enum
TOperatingSystemType = (osWindows95, osWindows98, osWindows98SE, osWindowsME, osWindowsNT, osWindows2000, {osWindows2000Server,} osWindowsXP, osWindowsServer2003, osWindowsVista, osUnknown);
# Autosize columns for TListView
Use -1 setting to set the column header to the size of the largest subitem text in the column,
and a -2 setting to set the column header to the size of the text in the column header.
ListView1.Columns[0].Width := -1 or -2;
