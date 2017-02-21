# Notepad++ Macro Creator

Convert a pre-written text/code to macro (XML).

## Example output

`"Hello, World!"` becomes:

```xml
<Macro name="" Ctrl="no" Alt="no" Shift="no" Key="0">
    <Action type="1" message="2170" wParam="0" lParam="0" sParam="H" />
    <Action type="1" message="2170" wParam="0" lParam="0" sParam="e" />
    <Action type="1" message="2170" wParam="0" lParam="0" sParam="l" />
    <Action type="1" message="2170" wParam="0" lParam="0" sParam="l" />
    <Action type="1" message="2170" wParam="0" lParam="0" sParam="o" />
    <Action type="1" message="2170" wParam="0" lParam="0" sParam="," />
    <Action type="1" message="2170" wParam="0" lParam="0" sParam=" " />
    <Action type="1" message="2170" wParam="0" lParam="0" sParam="W" />
    <Action type="1" message="2170" wParam="0" lParam="0" sParam="o" />
    <Action type="1" message="2170" wParam="0" lParam="0" sParam="r" />
    <Action type="1" message="2170" wParam="0" lParam="0" sParam="l" />
    <Action type="1" message="2170" wParam="0" lParam="0" sParam="d" />
    <Action type="1" message="2170" wParam="0" lParam="0" sParam="!" />
</Macro>
```

## shortcuts.xml

```xml
<NotepadPlus>
    <InternalCommands>
		<!-- Shortcut -->
    </InternalCommands>
    <Macros>
        <!-- Insert Macro Here -->
    </Macros>
    <UserDefinedCommands>
        <!-- Command -->
    </UserDefinedCommands>
    <PluginCommands />
    <ScintillaKeys />
</NotepadPlus>
```