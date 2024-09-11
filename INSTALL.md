# Installing Firux Linux (fxlx)

Firux Linux can be installed on any system that is compatible with Arch Linux.

## Installation Steps

### 1. Download the Base OS

Before installing Firux Linux, you'll need a base operating system that uses `pacman` as its package manager. You can choose any Arch-based distribution.

### 2. Install Firux Linux

Update your package list and install the Firux Linux package:

    sudo pacman -S fxlx_pak
    
For the `red` version targeted at programmers, use:

    sudo pacman -S fxlxred_pak

2. Follow the on-screen instructions to complete the installation.

### 3. Post-Installation

After installation, you can customize your system further using the `xsh` shell. Refer to the documentation for details on using `pakman`, `redpak`, and other commands.

## Uninstallation

To uninstall Firux Linux, run the following command:

    sudo pacman -R fxlx_pak

For the `red` version:

    sudo pacman -R fxlxred_pak
    
