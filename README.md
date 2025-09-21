# ohmyautoinstaller

> Automated Ubuntu installer for DevOps/Programmers.

**ohmyautoinstaller** automates Ubuntu installations with LUKS encryption, LVM partitioning, and essential tools like Git, Chrome, VS Code, PHP, Golang, Throne, and Telegram.  
You can provide the `autoinstall.yaml` file either via a **raw URL** during installation or as a **local file**.

For more information about Ubuntu auto installation, check out the [Subiquity documentation](https://canonical-subiquity.readthedocs-hosted.com/en/latest/intro-to-autoinstall.html).

⚠️ **WARNING**: This installer is not designed for dual-boot setups or systems with multiple disks. Using it in such environments may lead to data loss or system configuration issues.

## Usage
- **URL**: Use this raw URL: [autoinstall.yaml](https://raw.githubusercontent.com/ohmydevops/ohmyautoinstaller/refs/heads/master/autoinstall.yaml)
- **File**: copy it to the installation media.