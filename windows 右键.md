Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\Directory\Background\shell\WindowsTerminal]
"MUIVerb"="Windows Terminal"
"Icon"="C:\\Users\\lvswe\\AppData\\Local\\OpenHere\\WindowsTerminal\\Icon.ico"
"ExtendedSubCommandsKey"="Directory\\ContextMenus\\WindowsTerminal"

[HKEY_CLASSES_ROOT\Directory\ContextMenus\WindowsTerminal\shell\openWindowsTerminal]
"MUIVerb"="Open here"
"Icon"="C:\\Users\\lvswe\\AppData\\Local\\OpenHere\\WindowsTerminal\\Icon.ico"

[HKEY_CLASSES_ROOT\Directory\ContextMenus\WindowsTerminal\shell\openWindowsTerminal\command]
@="C:\\Users\\lvswe\\AppData\\Local\\Microsoft\\WindowsApps\\wt.exe -d ."

[HKEY_CLASSES_ROOT\Directory\ContextMenus\WindowsTerminal\shell\runas]
"MUIVerb"="Open here as Administrator"
"Icon"="C:\\Users\\lvswe\\AppData\\Local\\OpenHere\\WindowsTerminal\\Icon.ico"
"HasLUAShield"=""

[HKEY_CLASSES_ROOT\Directory\ContextMenus\WindowsTerminal\shell\runas\command]
@="C:\\WINDOWS\\system32\\WindowsPowerShell\\v1.0\\powershell.exe -noninteractive -noprofile -command Set-Location '%V';start-process wt -argumentList '-d .'"
