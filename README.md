# Weave2-Installer

Official Windows installer for Weave2, a local version control system developed in C++.

## Features

- Installs `Weave2.exe` into __`C:\Program Files\Weave2\bin`__.
- Automatically adds installation directory to system PATH.
- Acessable from any command-line terminal, no desktop shortcut or launch application.
- No manual configuration required.
- Supports clean uninstallation, including removal of PATH entry.

## Requirements

- Windows 10 or Windows 11 (64-bit).
- Administrator privellages.

## Installation

1. Download the latest `Weave2Setup.exe`.
2. Run the installer.
3. Approve administrator permission prompt.
4. Complete installation.

Weave2 should now be accesable from any directory.

Once installed, to find documentation, open a new terminal and run:
```
Weave2 help
```

The installer does not initialise Weave2 application data, this alongside config files are generated when required during command execution.

Application data is stored separately from the installation directory, allowing it to persist independently of the installed executable.

## Uninstallation

1. Open __Settings -> Apps -> Installed Apps__
2. Search for "Weave2"
3. Select __More Options -> Uninstall__ and uninstall the program.

Uninstallation will cleanly remove the installed executable and all associated installation files, alongside the added PATH entry.

Repository data is stored seperately at __`C:\Users\mrble\AppData\Local\Weave2`__ and will __NOT__ deleted during uninstallation. 

## Related Project

[Weave2](https://github.com/BradCp2/Weave2) - The main Weave2 source code repository.

## Licence

This project is licensed under the MIT license. See the [LICENSE](https://github.com/BradCp2/Weave2_Installer/blob/main/LICENSE) for details.



