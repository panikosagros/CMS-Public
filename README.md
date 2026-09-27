# IP Configurator CMS

A Windows console tool for managing network adapters - IP addresses, DHCP, DNS,
routes, Wi-Fi profiles - plus optional modules for password generation, secure
notes, email, network scanning and system info.

## Download

Get the latest version from the **[Releases](https://github.com/panikosagros/CMS-Public/releases/latest)** page. Two options:

| File | What it is |
|------|------------|
| `IP-Configurator-CMS-<version>.msi` | Installer - installs to `C:\Program Files\IP-Configurator-CMS\` and adds a Start Menu shortcut |
| `CMS.exe` | Portable - a single file, nothing to install; settings are kept next to it |

Both ask for Administrator rights when started, because the tool changes
network settings. They are not code-signed, so Windows may show an
"unknown publisher" warning - choose **More info -> Run anyway**.

## First run

A disclaimer is shown - type `YES` to accept. Then choose **Quick Setup**
(pick the interfaces to manage, the rest uses defaults) or **Advanced Setup**
(answer every question yourself).

## Upgrading

- **Installer:** run the newer `.msi` - it replaces the current install in place.
- **Portable:** replace `CMS.exe` - the `settings` and `log` folders next to it are kept.

Contact: cms@nss.network
