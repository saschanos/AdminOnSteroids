Admin On Steroids
========================

Various admin hacks to enhance ProcessWire admin.


## Install

1. Install the module as usual (see help [here](http://modules.processwire.com/install-uninstall/)).

1. Enable or disable submodules and tweak their settings.

1. Save the module to apply settings.

To uninstall follow the uninstall instructions on the link above.


## Submodules



###AutosizeTextareas

*Autosize textareas according to content*

Adds auto-grow functionality to fit textarea to its content. The submodule has no settings to configure.



###HoverSaveDropdown

*Show save dropdown on hover instead on click*

Hovering on the Save button in the page editor shows the dropdown menu instantly instead on click.



###DeselectRadios

*Enable clearing checked radio buttons*

Once checked, a radio button can't be cleared. This submodule removes this limitation.

By default required fields can't be deselected but it can be enabled tweaking the submodule's settings.

####Settings

- **Only for SuperUsers**: disable the feature for non-SuperUsers
- **Allow also for required fields**: enable unchecking for required fields too



###FocusInputOnLangTabSwitch

*Focus input on switching language tabs*

Saves an extra click to activate text input, textarea or CKEditor when switching on language tabs.

####Settings

- **Focus**: activates the target input so the previous cursor position is restored
- **Move cursor to the end**: sets the cursor to the end of the input's content
- **Select all**: selects all content of the target input
- **Do nothing**: disables setting focus for the current field type

Settings can be configured separately for CKEditor settings.

**Bonus**: ctrl+clicking on a language tab will activate all the language tabs of the same language on current page. This can be handy for quickly checking content of other languages.



###LangTabHotkeySwitcher

*Switch language tabs on ctrl+arrow keys*

Enables switching language tabs on multilanguage fields using ctrl+right, ctrl+left hotkeys. Also adds ctrl+up, ctrl+down hotkeys to collapse/expand language fields. The latter doesn't work on CKEditor fields.



###LoadCollapsedModuleInfos

*Load module info fields collapsed*

When entering a module page in the admin the info field may occupy much of the screen. Checking this tweak will load them collapsed so more of their configuration fields will be visible.



###Prevent page jump when the scrollbar appears

*Prevent page jump when scrollbar appears*

Disable page jump and elements repositioning when the height of the page changes and the scrollbar appears or disappears.



###LongClickDuration

*Custom long-click action duration*

Long-clicking on Edit or View links on the Page tree opens a modal to edit/view the page. The default value is 600 milliseconds which you can modify here. Note that you can add only greater value than the default.



###AdminTweaks

*Apply default admin theme tweaks*

A few usability mods targetting the default admin theme.

- **Make header sticky**: stick the header to the top of the browser window so it stays in place when scrolling down



###RenoTweaks

*Apply Reno theme tweaks*

A few usability mods targetting the Reno admin theme.

- **Make header sticky**: stick the header to the top of the browser window so it stays in place when scrolling down
- **Make sidebar sticky**: stick the sidebar to the top to make it always visible
- **Auto hide sidebar on left**: auto hide the sidebar so it's accessible by moving the mouse to the left side of the screen
- **Always show sidebar items (disable accordion)**: make sidebar submenus more compact and do not hide them
- **Single click sidebar headers**: by default the sidebar header links need double-click to open the corresponding menu page because single click is used by the accordion. This tweak will remove this limitation. It's available only if "Always show sidebar items" tweak is on.
- **Place header button next to the main title**: moves the top (cloned) main button next to the title to make it easier to reach
- **Hide sidebar quick links (flash icons)**: this will hide the quicklink icons from the sidebar. Use this if you don't use this feature and/or you would like to make easier to click on submenu items
- **One-line sidebar submenus (only with autoHideSidebar)**: if AutoHideSidebar setting is on, using this will force the sidebar submenu items to be in one row (the sidebar width will grow)
- **Move notice close buttons to the left**: put the close button of the notice message to the left for easier access