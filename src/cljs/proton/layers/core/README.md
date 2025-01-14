## Core configuration layer

This layer contains the base functionality of proton.

### Install

The core layer should get included by default. No installation needed.

### Configuration

| Name                              | Default        | Type        | Description                                                                                |
|-----------------------------------|----------------|-------------|--------------------------------------------------------------------------------------------|
| `proton.core.showTabBar`          | false          | __boolean__ | whether the tab bar should be visible by default                                           |
| `proton.core.relativeLineNumbers` | false          | __boolean__ | whether to use relative line numbers instead of absolute ones                              |
| `proton.core.quickOpenProvider`   | :normal        | __keyword__ | which quickOpen to use. Possible options are `:normal` and `:nuclide`                      |
| `proton.core.vim-provider`        | :vim-mode-plus | __keyword__ | which vim emulation provider to use. Possible options are `:vim-mode-plus` and `:vim-mode` |

### Key Bindings

#### Root

Key Binding        | Description
-------------------|------------------------
<kbd>SPC 0</kbd>   | focus tree view
<kbd>SPC j</kbd>   | go to pane below
<kbd>SPC k</kbd>   | go to pane above
<kbd>SPC l</kbd>   | go to pane on the left
<kbd>SPC h</kbd>   | go to pane on the right
<kbd>SPC tab</kbd> | visit last used buffer

#### Files

Key Binding            | Description
-----------------------|----------------------
<kbd> SPC f f </kbd>   | open / create file
<kbd> SPC f e d </kbd> | open proton dotfile
<kbd> SPC f e s </kbd> | open atom stylesheet
<kbd> SPC f e i </kbd> | open atom init script
<kbd> SPC f e p </kbd> | open atom snippets

#### Window

Key Binding          | Description
---------------------|--------------------------------
<kbd> SPC w d </kbd> | Destroy current window / pane
<kbd> SPC w v </kbd> | Split vertically
<kbd> SPC w h </kbd> | Split horizontally
<kbd> SPC w V </kbd> | Split vertically and focus left
<kbd> SPC w H </kbd> | Split horizontally and focus up

#### Buffer

Key Binding          | Description
---------------------|--------------------------------
<kbd> SPC b b </kbd> | Browse buffers
<kbd> SPC b K </kbd> | Kill other buffers
<kbd> SPC b d </kbd> | Delete / destroy current buffer

#### Project

Key Binding          | Description
---------------------|--------------------------
<kbd> SPC p p </kbd> | Switch project
<kbd> SPC p s </kbd> | Save project
<kbd> SPC p e </kbd> | Edit project 
<kbd> SPC p b </kbd> | Find project buffer
<kbd> SPC p t </kbd> | Toggle tree view
<kbd> SPC p f </kbd> | Open project file
<kbd> SPC p r </kbd> | Open recently opened file

#### Toggles

Key Binding          | Description
---------------------|-----------------------------
<kbd> SPC t t </kbd> | Toggle tab bar
<kbd> SPC t g </kbd> | Toggle line gutter
<kbd> SPC t f </kbd> | Toggle fullscreen
<kbd> SPC t n </kbd> | Toggle relative line numbers


#### Meta

Key Binding          | Description
---------------------|--------------------
<kbd> SPC _ d </kbd> | Find proton dotfile
<kbd> SPC _ R </kbd> | Reload atom
<kbd> SPC _ c </kbd> | Toggle dev tools
