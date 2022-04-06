# kicad-library
KiCad symbol and footprint to share between projects.

## Install

1. In each project make sure you have a hardware folder, add this repository as a git submodule:

    ```sh
    git submodule add https://github.com/armercier/kicad-library.git hardware/library
    ```
2. Update the git submodule

    ```sh
    git submodule foreach git pull origin main   
    ```
