# macos setup script

Automates the installation and configuration.
- Installs utilities from brew and the appstore
- Configures system settings for more convenient use
- Customizes the Dock with preferred applications
- Sets up keyboard layout (ABC, Russian PC)

## 1. install task
```sh
sh -c "$(curl --location https://taskfile.dev/install.sh)" -- -d -b /usr/local/bin
```

## 2. run
```sh
task run
```

## 3. reboot
```sh
sudo reboot
```