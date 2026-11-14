---
layout: default
title: Open-source Software
---
# Open-source Software

Ommalux includes libusb under the GNU Lesser General Public License, version 2.1 or later.

## libusb source and replacement

[Download the source package for Ommalux 0.1 (Beta)]({{ '/downloads/Ommalux-0.1-Beta-libusb-source.zip' | relative_url }})

The package contains the Android libusb 1.0.25 fork from UVCAndroid 1.0.13, its license and Android build inputs, reference library hashes, and instructions for building and using a modified library. It includes helpers for rebuilding all four supported ABIs and creating an APK copy with replacement libraries.

Read the included README before changing an installation. A replacement APK must be signed with your own key. Android installation and data-handling requirements apply. The workflow has passed build, packaging and signing checks. Execution with a modified library on an Android device remains unverified.

Source archive SHA-256

`d1b829fb99786d24b624f069a856cfd6cccef65e10caae50c12d54dd9ac34743`

[Read the libusb license](https://raw.githubusercontent.com/libusb/libusb/v1.0.25/COPYING)

Additional third-party license notices are included in Ommalux's distributed application assets.
