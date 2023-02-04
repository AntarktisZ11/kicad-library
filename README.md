# kicad-library
 A library for custom symbols and footprints

Inspired by [hutscape/kicad-library](https://github.com/hutscape/kicad-library)


## Install

1. In each project, add this repository as a git submodule:

    ```sh
    git submodule add https://github.com/AntarktisZ11/kicad-library.git pcb/library
    ```
1. Update the git submodule

    ```sh
    git submodule update --remote pcb/library
    ```
## How to...

### Make a new symbol

1. Open Symbol Editor
2. File -> New Library...
3. Choose _Project_ and OK
4. Choose the name
5. Create new symbol
6. File -> Save Library As... and put in library/symbols

### Add symbol to project
1. Preferences -> Manage Symbol Libraries... -> Project Specific Libraries
2. Add existing library to table 📂, navigate to library/symbols and choose the one.
3. Make sure **Library Path** is ${KIPRJMOD}/library/symbols/**YOUR_SYMBOL**.kicad_sym
