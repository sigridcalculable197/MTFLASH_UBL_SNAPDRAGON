# MTFLASH UBL Snapdragon

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/readme/hero-v13-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="docs/readme/hero-v13-light.svg">
  <img alt="MTFLASH UBL Snapdragon v1.4 premium unlock controls banner" src="docs/readme/hero-v13-dark.svg" width="100%">
</picture>

<p align="center">
  <a href="https://github.com/tamm2904/MTFLASH_UBL_SNAPDRAGON/releases/tag/v1.4"><img alt="Version" src="https://img.shields.io/badge/version-v1.4-111111?style=for-the-badge"></a>
  <img alt="Platform" src="https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D4?style=for-the-badge">
  <img alt="Language" src="https://img.shields.io/badge/language-English%20%2F%20Ti%E1%BA%BFng%20Vi%E1%BB%87t-2E7D32?style=for-the-badge">
  <img alt="Brands" src="https://img.shields.io/badge/brands-Xiaomi%20%7C%20ZTE%20%7C%20ASUS-B71C1C?style=for-the-badge">
</p>

<p align="center">
  <a href="https://github.com/tamm2904/MTFLASH_UBL_SNAPDRAGON/releases/latest"><b>Download Latest Release</b></a>
  &nbsp;·&nbsp;
  <a href="#overview">Overview</a>
  &nbsp;·&nbsp;
  <a href="#release">Release</a>
  &nbsp;·&nbsp;
  <a href="#feature-map">Features</a>
  &nbsp;·&nbsp;
  <a href="#supported-devices">Devices</a>
  &nbsp;·&nbsp;
  <a href="#contact">Contact</a>
</p>

<p align="center">
  <b>Professional Snapdragon servicing workspace for bootloader unlock, firmware handling, EDL/Fastboot flashing, storage safety, and root workflows.</b><br>
  <b>Công cụ Windows chuyên nghiệp cho unlock bootloader, xử lý firmware, flash EDL/Fastboot, kiểm tra storage an toàn và root thiết bị Snapdragon.</b>
</p>

---

## Overview

MTFLASH UBL Snapdragon is a guided Windows tool for selected Xiaomi, Redmi, POCO, ZTE, Nubia, RedMagic, and ASUS Snapdragon devices. It combines model-aware checks, QR-based authorization, live logs, firmware download support, device-mode guidance, and safety gates for high-risk EDL workflows.

MTFLASH UBL Snapdragon là công cụ Windows có hướng dẫn cho một số thiết bị Snapdragon thuộc Xiaomi, Redmi, POCO, ZTE, Nubia, RedMagic và ASUS. Công cụ tập trung vào kiểm tra đúng model, xác thực QR, log trực tiếp, hỗ trợ firmware, hướng dẫn chuyển chế độ thiết bị và các lớp an toàn cho thao tác EDL rủi ro cao.

## Release

**Latest:** [MTFLASH UBL Tool v1.4](https://github.com/tamm2904/MTFLASH_UBL_SNAPDRAGON/releases/tag/v1.4)

- **Artifact:** `UBL-Snapdragon.exe`
- **Size:** `118,000,280` bytes
- **SHA256:** <code>43457E45B96B3459C87F3C7311FD2B3A0397<wbr>621922DD0044C82AD204B5D63163</code>

**v1.4 focus:** premium compact unlock-header controls with Driver, Reboot, Brand, and Chip dropdowns; ADB/Fastboot reboot actions matched to MTFLASH TOOL; and elevated Xiaomi USB / Qualcomm 9008 driver installation from verified server packages.

**Trọng tâm v1.4:** cụm điều khiển màn hình unlock gọn, cao cấp với dropdown Cài Driver, Khởi động, Brand và Chip; thao tác reboot ADB/Fastboot đồng bộ với MTFLASH TOOL; cài Driver USB Xiaomi / Qualcomm 9008 bằng quyền admin từ gói tải chính thức của server.

## Feature Map

<details open>
<summary><b>English</b></summary>

- **Guided unlock:** step-based bootloader unlock flows for supported Snapdragon models.
- **High-version Xiaomi:** Xiaomi 8 Gen 3 and 8s Gen 3 high-version paths for security patch `2026-02-01` and newer where mapped.
- **Firmware:** Mini EngFirmware, Full EngFirmware, China Fastboot, and China HyperTN download handling where available.
- **EDL Flash:** ROM/XML selection, partition filtering, progress tracking, logs, and post-step cleanup.
- **Storage safety:** full UFS info check with vendor, product, capacity, LUN, firmware, and serial parsing.
- **Fastboot Flash:** queue-based flash/erase/reboot workflows with validation and status tracking.
- **Unlock quick utilities:** compact Driver and Reboot dropdowns on the unlock screen for ADB/Fastboot reboot targets and elevated driver installs.
- **Root assistant:** supported Magisk, KernelSU, KernelSU Next, and SukiSU workflows for unlocked devices.
- **Authorization:** QR and short-code authorization through App_MTFLASH before protected workflows.

</details>

<details>
<summary><b>Tiếng Việt</b></summary>

- **Unlock có hướng dẫn:** quy trình unlock bootloader theo từng bước cho model Snapdragon được hỗ trợ.
- **Xiaomi high-version:** nhánh Xiaomi 8 Gen 3 và 8s Gen 3 cho security patch từ `2026-02-01` trở lên nếu model đã có mapping.
- **Firmware:** xử lý tải Mini EngFirmware, Full EngFirmware, China Fastboot và China HyperTN khi model có dữ liệu.
- **EDL Flash:** chọn ROM/XML, lọc partition, theo dõi tiến trình, log và dọn dẹp sau thao tác.
- **Storage safety:** kiểm tra đầy đủ thông tin UFS gồm vendor, mã chip, dung lượng, LUN, firmware và serial.
- **Fastboot Flash:** flash/erase/reboot bằng queue, có kiểm tra hợp lệ và theo dõi trạng thái.
- **Tiện ích nhanh trong Unlock:** dropdown Cài Driver và Khởi động ngay trên màn hình unlock cho reboot ADB/Fastboot và cài driver bằng quyền admin.
- **Root assistant:** hỗ trợ Magisk, KernelSU, KernelSU Next và SukiSU cho thiết bị đã unlock.
- **Authorization:** xác thực bằng QR hoặc mã ngắn qua App_MTFLASH trước khi dùng workflow bảo vệ.

</details>

## EDL Storage Safety

The EDL Flash screen includes a dedicated **Check Storage** action and also performs an automatic storage check before flashing. A confirmed Kioxia/Toshiba UFS result blocks the flash before any partition write starts.

Màn hình EDL Flash có nút **Kiểm tra Storage** riêng và cũng tự động kiểm tra storage trước khi flash. Nếu xác nhận UFS Kioxia/Toshiba, công cụ sẽ chặn flash trước khi bắt đầu ghi partition.

| Vendor | Manufacturer ID | Behavior |
|---|---:|---|
| Kioxia/Toshiba | `0x198` / `408` | Block EDL flash |
| Samsung | `0x1CE` / `462` | Allow when other checks pass |
| SK hynix | `0x1AD` / `429` | Allow when other checks pass |
| Micron | `0x12C` / `300` | Allow when other checks pass |
| WDC/SanDisk | `0x145` / `325` | Allow when other checks pass |

If Firehose returns incomplete storage data, the tool warns instead of guessing. Only a definitive Kioxia/Toshiba match blocks the flash.

Nếu Firehose trả dữ liệu storage không đầy đủ, công cụ sẽ cảnh báo thay vì đoán. Chỉ kết quả Kioxia/Toshiba rõ ràng mới bị chặn flash.

## Basic Workflow

1. Download `UBL-Snapdragon.exe` from the latest release.
2. Install the correct USB driver for the device, or use the unlock-screen **Drivers** dropdown for Xiaomi USB / Qualcomm 9008 packages.
3. Run the tool on Windows 10 or Windows 11.
4. Authorize with App_MTFLASH by scanning the QR code or entering the short code.
5. Connect the device in the requested mode: Android, Fastboot, FastbootD, or EDL.
6. Select the correct brand, chip, and model, or use device detection when available.
7. Read the live log and follow each confirmation prompt before continuing.
8. Do not disconnect the device during unlock, flash, erase, firmware, root, or reboot operations.

## Safety Rules

| Rule | Why it matters |
|---|---|
| Match the exact model and codename. | Wrong firmware or layout can brick the device. |
| Back up data first. | Unlock, wipe, root, and flash operations can erase user data. |
| Keep cable, battery, and USB port stable. | Interrupted EDL/Fastboot operations can leave the device unbootable. |
| Do not bypass Kioxia/Toshiba blocking. | Unsupported Firehose writes are blocked intentionally. |
| Use authorized workflows only. | The tool is designed for devices and accounts with valid permission. |

## Requirements

- Windows 10 or Windows 11.
- Qualcomm / OEM USB drivers for ADB, Fastboot, FastbootD, and Qualcomm HS-USB QDLoader 9008.
- Internet access for authorization and online firmware options.
- Active App_MTFLASH account with permission for this product.
- Device battery and USB connection stable enough for servicing operations.

## Supported Devices

Support is model-specific. Always confirm the exact model, codename, chip family, storage variant, and security patch before running a workflow.

<details>
<summary><b>Xiaomi / Redmi / POCO</b></summary>

#### Snapdragon 8 Elite

- Xiaomi 15 (`dada`)
- Xiaomi 15 Pro (`haotian`)
- Xiaomi 15 Ultra (`xuanyuan`)
- Redmi K80 Pro (`miro`)
- Redmi K90 (`annibale`)
- POCO F8 Pro (`annibale`)
- MIX Flip 2 (`bixi`)
- Pad 8 Pro (`piano`)

#### Snapdragon 8 Elite Gen 5

- Xiaomi 17 (`pudding`)
- Xiaomi 17 Pro (`pandora`)
- Xiaomi 17 Pro Max (`popsicle`)
- Xiaomi 17 Ultra (`nezha`)
- REDMI K90 Pro Max (`myron`)

#### Snapdragon 8 Gen 2

- Xiaomi 13 (`fuxi`)
- Xiaomi 13 Pro (`nuwa`)
- Xiaomi 13 Ultra (`ishtar`)
- Xiaomi MIX Fold 3 (`babylon`)
- Redmi K60 Pro (`socrates`)
- Redmi K70 (`vermeer`)
- POCO F6 Pro (`vermeer`)
- Xiaomi Pad 6S Pro (`sheng`)

#### Snapdragon 8 Gen 3

- Xiaomi 14 (`houji`)
- Xiaomi 14 Pro (`shennong`)
- Xiaomi 14 Ultra (`aurora`)
- Redmi K70 Pro (`manet`)
- Redmi K80 (`zorn`)
- MIX Flip (`ruyi`)
- MIX Fold 4 (`goku`)

#### Snapdragon 8s Gen 3

- Xiaomi Civi 4 Pro / 14 Civi (`chenfeng`)
- POCO F6 / Redmi Turbo 3 (`peridot`)
- Xiaomi Pad 7 Pro (`muyu`)
- Xiaomi Pad 7 (`uke`)

#### Snapdragon 8s Gen 4

- Xiaomi Civi 5 Pro (`luming`)
- Xiaomi Pad 8 (`yupei`)
- Redmi Turbo 4 Pro / POCO F7 (`onyx`)

</details>

<details>
<summary><b>ZTE / Nubia / RedMagic</b></summary>

#### Snapdragon 8 Elite

- RedMagic 10 Series (`NX789J`)
- RedMagic 11 Air (`NX799J`)
- RedMagic Pad 3 Pro / Astra (`NP05J`, `PQ84P01`)
- Nubia Z70 Ultra (`NX733J`)
- Nubia Z70 Ultra (`NX736J`)

#### Snapdragon 8 Elite Gen 5

- RedMagic 11 Series (`NX809J`)
- Nubia Z80 Ultra (`NX741J`)

</details>

<details>
<summary><b>ASUS ROG</b></summary>

#### Snapdragon 8 Elite

- ROG Phone 9 / 9 Pro (`AI2501`)
- ROG Phone 9 Global (`ASUS_AI2501_A`)
- ROG Phone 9 JP/TW (`ASUS_AI2501_B`)
- ROG Phone 9 Pro WW (`ASUS_AI2501_C`)
- ROG Phone 9 Pro US (`ASUS_AI2501_D`)
- ROG Phone 9 Pro Edition US (`ASUS_AI2501_E`)
- ROG Phone 9 Pro JP/TW (`ASUS_AI2501_F`)

</details>

## Authorization

| English | Tiếng Việt |
|---|---|
| The tool requires an active App_MTFLASH account with permission for this product. | Công cụ cần tài khoản App_MTFLASH còn hiệu lực và có quyền sử dụng sản phẩm này. |
| Scan the QR code or enter the short code shown in the Windows app. | Quét mã QR hoặc nhập mã ngắn hiển thị trong ứng dụng Windows. |
| Device workflows are available only after authorization is approved. | Chỉ có thể dùng workflow thiết bị sau khi xác thực được chấp thuận. |
| Internet access to the MTFLASH/APMPro service is required. | Cần internet để kết nối dịch vụ MTFLASH/APMPro. |

## Contact

| Channel | Link |
|---|---|
| Website | [mtflash.com](https://mtflash.com) |
| Contact page | [mtflash.com/lien-he.html](https://mtflash.com/lien-he.html) |
| Firmware portal | [file.mtflash.com](https://file.mtflash.com) |
| Email | [support@mtflash.com](mailto:support@mtflash.com) |
| Phone / Zalo | [0975904043](https://zalo.me/0975904043) |
| WhatsApp | [+84 975 904 043](https://wa.me/84975904043) |
| Telegram | [@bunnyVN888](https://t.me/bunnyVN888) |
| Facebook | [facebook.com/play29.mt](https://www.facebook.com/play29.mt) |
| YouTube | [youtube.com/@phoneauth](https://youtube.com/@phoneauth?si=2-qHa6n4kbLMeBG5) |

---

<p align="center">
  <b>MTFLASH UBL Snapdragon</b><br>
  Compact, model-aware, safety-first Snapdragon servicing for authorized users.
</p>
