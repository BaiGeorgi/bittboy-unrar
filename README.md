**UnRAR for BittBoy or PocketGo (V1)**

This is UnRAR compilled for BittBoy/PocketGo.

Just copy unrar where you want and you are ready to use it.

Follow the steps to build newer version from scratch:

1. Download [toolchain.7z](https://github.com/steward-fu/miyoo/releases/download/v1.0/toolchain.7z) and extract the archive in "/opt/".
2. Download the [UnRAR source code](https://www.rarlab.com/rar_add.htm) and extract it.
3. Edit `makefile` and comment the part for `# Linux using GCC` (5 to 12 row) and uncomment
 `# Linux using arm-linux-g++` (107 to 113 row). Just use my makefile as example. 
4. Run `export.sh && make`
5. Copy unrar in the sd card.
