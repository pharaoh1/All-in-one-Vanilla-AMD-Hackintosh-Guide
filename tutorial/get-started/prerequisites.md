# Prerequisites

{% hint style="danger" %}
_**Please READ everything below CAREFULLY!**_
{% endhint %}

## General

* An 8GB+ USB flash drive for the installer
* Kexts for your system \([Gathering Kexts](gathering-kexts.md)\)

### **The config file for Clover:**

#### **General**

* **PLEASE READ THE PLIST BASICS OVER** [**HERE**](https://hackintosh.gitbook.io/-r-hackintosh-vanilla-desktop-guide/config.plist-basics) **AND MAKE YOUR OWN config.plist with Clover Configurator** \(On macOS\)**,** [**Clover Cloud Editor**](http://cloudclovereditor.altervista.org/cce/index.php) ****\(On Windows\) **or ProperTree config editor** \(Cross Platform Plist Editor, but difficult for people without any basis at programming\)**.**
  * _**DO NOT GET THE SAMPLE CONFIG.**_

#### **For Intel:**

* **Continue to read the plist guide to make you own config.plist**

#### **For AMD:**

* **After reading the plist basics guide, go to** [**this page**](../amd-clover-config.plist/) **to make your own config.plist**.

## Some more important things

{% hint style="danger" %}
You'll need to have **LAN \(Ethernet\) connection** if you are making a **Network Installer**. If you do _**NOT**_ have one, please make an **Offline Installer** instead.
{% endhint %}

### Offline Installer Prerequisites

#### Preparation for making an Offline Installer from macOS

* [Clover install package](https://sourceforge.net/projects/cloverefiboot/)
* [Clover Configurator](https://mackie100projects.altervista.org/download-clover-configurator/) \(for editing the config\)
* \*\*\*\*[**macOS Install Mojave.app**](https://drive.google.com/open?id=1fp7cBfkWZcyCnt0gy6zIxf6uN_nD-v1G) **\(10.14.1 18B75\),** [**macOS Install High Sierra.app**](https://drive.google.com/file/d/17U2GMCfIbLPN8SOfGoKl40vuIDZp3rt7/view) **\(10.13.6 17G65\) or** [**macOS Install Mojave.app**](https://drive.google.com/file/d/1BSp_lFlEVoSGleDpZxsVA9MJP6njUtCq/view?usp=sharing) **\(10.14.5 18F132\).** Please read the [Requirements](prerequisites.md#requirements) part below to know which version of macOS is compatible for your computer.
  * You can also use your own Installer **but you need to check if it is compatible for AMD if you are installing it to AMD System.** I'm not going to specify the steps here, Google it.
* **\[OPTIONAL\]** Fast Internet Speed

#### Preparation for making an Offline installer in Windows

* [Boot Disk Utility](http://cvad-mac.narod.ru/index/bootdiskutility_exe/0-5) \(BDUtitlity\)
* [**macOS Install Mojave.app**](https://drive.google.com/open?id=1fp7cBfkWZcyCnt0gy6zIxf6uN_nD-v1G) **\(10.14.1 18B75\) or** [**macOS Install High Sierra.app**](https://drive.google.com/file/d/17U2GMCfIbLPN8SOfGoKl40vuIDZp3rt7/view) **\(10.13.6 17G65\).** \(**Only if you want to make an Offline Installer**. More explanation [here](../preparing-the-installer-part-2/from-macos.md#youll-need-ethernet-connection-while-installing-macos-if-you-dont-have-a-ethernet-connection-go-to-the-next-page-for-offline-installation). The installer provided is a pure zip file of the installer. It is compatible for AMD.\)
* \*\*\*\*[TransMac](https://www.acutesystems.com/scrtm.htm)\*\*\*\*
* [Paragon Hard Disk Manager](https://www.paragon-software.com/free/pm-express/#)
* **\[OPTIONAL\]** Fast Internet Speed

### Network Installer Prerequisites

#### Preparation for making an Offline Installer from macOS

* A clone of [gibMacOS](https://github.com/corpnewt/gibMacOS)
* [Clover install package](https://sourceforge.net/projects/cloverefiboot/)
* [Clover Configurator](https://mackie100projects.altervista.org/download-clover-configurator/) \(for editing the config\)
* You **MUST** have fast Internet Speed \(at least 20 Mbps\). If your Internet Speed is slow, make an Offline Installer instead as the Installer might be locked while installing.

#### Preparation for making an Network Installer from Windows

* A clone of [gibMacOS](https://github.com/corpnewt/gibMacOS)
* You **MUST** have fast Internet Speed \(at least 20 Mbps\). If your Internet Speed is slow, make an Offline Installer instead as the Installer might be locked while installing.

### Notes

**\[Windows\] You'll need** [**7-zip**](https://www.7-zip.org/) for extracting the macOS Installer zip file I have provided above.

## Requirements

* **Intel \(Core, Xeon or Pentium series\) or AMD \(FX, Ryzen or Zen Athlon\) CPUs**
* **Intel iGPU or a dedicated GPU.** _**Remember that the iGPU of AMD CPUs is not supported.**_ Either NVidia or AMD will work. **AMD GPUs are recommended** because of the native support from macOS Mojave. **Most of the NVidia GPUs can only goes up to macOS High Sierra** \(only Kepler GPUs are supported in Mojave\). [_**Here**_](https://www.reddit.com/r/hackintosh/comments/b91vf5/mojave_gpu_buyers_guide/) is a compatible GPU list. _**Remember the highest supported version.**_
* As I haven't finished the Configuring Legacy Clover Part yet, this guide **requires a motherboard which support UEFI.** Sorry for keeping Legacy booting user waiting.
