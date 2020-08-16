<h1 align="center">
<img width=75% src="https://github.com/mominaj/SpecX-bin/blob/master/media/logo.svg">
</h1>

<h4 align="center">Software Package for Electrical and Computer Studies</h4>

<h2 align="center">
<img width=65% src="https://github.com/mominaj/SpecX-bin/blob/master/media/distros.svg">
</h2>

<p align="center">
<a href="https://www.gnu.org/licenses/gpl-3.0">
    <img src="https://img.shields.io/badge/License-GPL%20v3-blue.svg">
</a>
<a href="https://github.com/mominaj/SpecX-bin/releases">
    <img src="https://img.shields.io/github/release/mominaj/SpecX-bin.svg">
</a>
<a href="https://github.com/mominaj/SpecX-bin/issues">
    <img src="https://img.shields.io/github/issues/mominaj/SpecX-bin.svg">
</a>
<a href="https://github.com/mominaj/SpecX-bin/search?l=shell">
    <img src="https://img.shields.io/github/languages/top/mominaj/SpecX-bin.svg">
</a>
</p>

<p align="center">
  <a href="#-installation">Installation</a> •
  <a href="#-distribution-and-architecture-support">Distribution and Architecture Support</a> •
  <a href="#-authors">Authors</a> •
  <a href="#-license">License</a> •
  <a href="#-docs">Docs</a> •
  <a href="#-revision-history">Revision History</a>
</p>

SpecX is a Linux based software package that facilitates easy download and installation of about 200+ tools related to Electrical and Computer Engineering Studies.

## 💾 Installation
First update your system with your relative command and restart (recommended):

```bash
# Ubuntu Distribution
$ sudo apt upgrade

# Fedora Distribution
$ sudo dnf update

# openSUSE Distribution
$ sudo zypper update
```
To clone and run this application, you'll need [Git](https://git-scm.com). From your command line:

```bash
# Clone this repository
$ git clone https://github.com/mominaj/SpecX-bin

# Go into the repository
$ cd SpecX-bin

# Start Installation
$ chmod +x SpecX_setup_enUS
$ ./SpecX_setup_enUS
```

Follow the on-screen dialogue boxes for installation.

## 📦 Distribution and Architecture Support

**Supported Architecture:**

SpecX currently support only **amd64 (64-bit)** architecture continue to maintain it and may add additional ones in the future.

**Supported Ubuntu versions:**

SpecX maintain Ubuntu distribution support for LTS releases as follows:.

* **Ubuntu 16.04 LTS** (Xenial Xerus)
* **Ubuntu 18.04 LTS** (Bionic Beaver)

**Supported Fedora versions:**

SpecX maintain Fedora distribution support as follows:

* **Fedora 30**
* **Fedora 31**

**Supported Fedora versions:**

SpecX maintain openSUSE distribution support for both Leap and Tumbleweed as follows:

* **openSUSE Leap 15.1**
* **openSUSE Tumbleweed**

**Windows Support:**

SpecX also provides a solution on Windows through virtualization. (See User Guide)

## 👦 Authors
 - Bilal Wajid
 - Momina Jamil
 - Hasan Iqbal
 - Imran Wajid
 - Khalid Waheed
 - Mustafa Kamal AlShawaqfeh
 - Ali Riza Ekti
 - Muhammad Atyab Imtaar
 - Ali Boyaci
 - Serhan Yarkan
 - Sabit Ekin

## 🔑 License
This project complies against license [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0).

## 📙 Docs
[User Guide](https://github.com/mominaj/SpecX-bin/blob/master/Docs/supplementary_user-guide.pdf)

## 📔 Revision History
**Version 3.2**
 - Major Bug Fixes

**Version 3.1**
 - Major Bug Fixes
 - Uninstall Support Added
 
**Version 3.0**
 - Major Bug Fixes
 - Added support for Fedora 3x
 - Added 208 Tools on Fedora
 - GUI Installation with Selection
 - Added Splash Screen and Install/Uninstall Window
 - Auto OS/Architecture detection
 - Sudo Password retrieval and parsing
 - Uninstall Support in v3.1 (Stay Updated)

**Version 2.0**
 - Minor Bug Fixes
 - Added support for openSUSE Leap 15.x and openSUSE Tumbleweed
 - Added 208 Tools on openSUSE
 - GUI Installation with Selection

 **Version 1.0**
 - SpecX initial release - alpha
 - Initial support for Ubuntu 18.04
 - Added 208 Tools on Ubuntu
 - GUI Installation with Selection
