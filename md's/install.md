# Installing FiruxLinux with FLUPI

Welcome to the FiruxLinux installation guide using the FLUPI method! This method simplifies the installation process. Instead of using a full ISO image, we will download the base operating system and then install the necessary packages.

## Requirements

- Internet connection.
- An existing Linux operating system (any distribution compatible with `pacman`).

## Installation Steps

1. **Prepare the Environment**

   Ensure your current operating system is up-to-date and that `pacman` is available. If you are using an Arch Linux-based distribution, `pacman` should already be installed.

2. **Download the FLUPI Installer**

   Download the FiruxLinux package from the official FiruxLinux repository. You can use `pacman` to do this:

       sudo pacman -S firux_package

3. **Configure the Installation**

   During installation, the script will prompt you to select some settings and options. Follow the on-screen instructions to configure your FiruxLinux installation.

4. **Install Additional Packages**

   To install additional packages, use `pakman` (PAcKage MANager):

       sudo pakman -i <package-name>

   Alternatively, you can use `pacman`:

       sudo pacman -S <package-name>

5. **Reboot the System**

   After completing the installation and configuration, reboot your system to apply the changes:

       sudo reboot

6. **First Boot**

   Upon rebooting, you should see the new FiruxLinux operating system. Log in with the credentials you configured during the installation.

## Common Issues

- **Cannot connect to the Internet**: Ensure that your internet connection is working properly and that your network is configured.
- **Errors during installation**: Check the error messages and ensure all steps have been completed correctly.

## Support

If you encounter any problems or have questions, feel free to contact FiruxLinux support via email: [firuxlinux@proton.me](mailto:firuxlinux@proton.me).

Thank you for choosing FiruxLinux!

