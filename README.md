# MTFLASH UBL Snapdragon

<p align="center">
  <b>Professional Snapdragon bootloader unlock, firmware, EDL, Fastboot, and root assistant for Windows.</b><br>
  <b>Công cụ Windows hỗ trợ unlock bootloader, firmware, EDL, Fastboot và root cho thiết bị Snapdragon.</b>
</p>

<p align="center">
  <a href="https://github.com/tamm2904/MTFLASH_UBL_SNAPDRAGON/releases/tag/v1.1"><img alt="Version" src="https://img.shields.io/badge/version-v1.1-111111?style=for-the-badge"></a>
  <img alt="Windows" src="https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D4?style=for-the-badge">
  <img alt="Languages" src="https://img.shields.io/badge/language-English%20%2F%20Ti%E1%BA%BFng%20Vi%E1%BB%87t-2E7D32?style=for-the-badge">
</p>

<p align="center">
  <a href="https://github.com/tamm2904/MTFLASH_UBL_SNAPDRAGON/releases/latest"><b>Download Latest Release</b></a>
  &nbsp;|&nbsp;
  <a href="#english">English</a>
  &nbsp;|&nbsp;
  <a href="#ti%E1%BA%BFng-vi%E1%BB%87t">Tiếng Việt</a>
  &nbsp;|&nbsp;
  <a href="#supported-devices--thi%E1%BA%BFt-b%E1%BB%8B-h%E1%BB%97-tr%E1%BB%A3">Supported Devices</a>
</p>

---

## English

### Overview

MTFLASH UBL Snapdragon is a guided Windows tool for servicing selected Xiaomi, Redmi, POCO, ZTE, Nubia, RedMagic, and ASUS Snapdragon devices. It is built for technicians who need a clear workflow, live logs, device detection, firmware handling, and model-specific safety checks.

### Main Features

- Guided bootloader unlock workflows for supported Snapdragon devices.
- Xiaomi high-version unlock support for Snapdragon 8 Gen 3 and 8s Gen 3 security patches from `2026-02-01` and newer.
- Fastboot and EDL flash screens for supported brands.
- Firmware download manager with Mini EngFirmware, Full EngFirmware, China Fastboot, and China HyperTN options where available.
- Model detection through connected ADB/Fastboot devices.
- Root assistant for unlocked devices with supported Magisk, KernelSU, and SukiSU workflows.
- English and Vietnamese interface.
- Voice prompts, sound cues, progress logs, and guided confirmation dialogs.
- QR-based online authorization through App_MTFLASH.

### Download

Latest version: [MTFLASH UBL Tool v1.1](https://github.com/tamm2904/MTFLASH_UBL_SNAPDRAGON/releases/tag/v1.1)

Release asset:

- `UBL-Snapdragon.exe`
- SHA256: `1EE93F228A59825889B7FC011B6960558326F1A3491B57AF04D25B26AC3C0633`

### Basic Usage

1. Download `UBL-Snapdragon.exe` from the release page.
2. Install the correct USB driver for your device.
3. Open the tool on Windows 10 or Windows 11.
4. Authorize the session using App_MTFLASH by scanning the QR or entering the short number.
5. Connect the device in the requested mode: Android, Fastboot, FastbootD, or EDL.
6. Select the correct brand, chip, and model, or use device detection when available.
7. Follow the on-screen steps exactly. Read the log before continuing at each confirmation.
8. Do not disconnect the device while a flash, unlock, erase, or reboot step is running.

### Safety Notes

- Use only the model that matches the connected device.
- Backup important data before any unlock, root, wipe, or firmware workflow.
- A locked bootloader, unsupported security patch, wrong model, unstable cable, or weak battery can interrupt the process.
- The tool may request Fastboot, FastbootD, EDL, or manual key combinations depending on the model.
- Internet is required for QR authorization and online firmware options.

---

## Tiếng Việt

### Tổng Quan

MTFLASH UBL Snapdragon là công cụ Windows hướng dẫn thao tác kỹ thuật cho các thiết bị Snapdragon được hỗ trợ thuộc Xiaomi, Redmi, POCO, ZTE, Nubia, RedMagic và ASUS. Công cụ tập trung vào quy trình rõ ràng, log trực tiếp, nhận diện thiết bị, xử lý firmware và kiểm tra an toàn theo từng model.

### Tính Năng Chính

- Hỗ trợ quy trình unlock bootloader có hướng dẫn cho các thiết bị Snapdragon tương thích.
- Hỗ trợ Xiaomi high-version cho Snapdragon 8 Gen 3 và 8s Gen 3 từ bản vá bảo mật `2026-02-01` trở lên.
- Màn hình Fastboot và EDL cho các thương hiệu được hỗ trợ.
- Trình tải firmware với Mini EngFirmware, Full EngFirmware, China Fastboot và China HyperTN nếu model có dữ liệu tương ứng.
- Nhận diện model qua thiết bị đang kết nối ở ADB/Fastboot.
- Hỗ trợ root cho thiết bị đã unlock bằng các workflow Magisk, KernelSU và SukiSU tương thích.
- Giao diện tiếng Anh và tiếng Việt.
- Có giọng nói hướng dẫn, âm báo, log tiến trình và hộp thoại xác nhận theo từng bước.
- Xác thực online bằng QR thông qua App_MTFLASH.

### Tải Xuống

Phiên bản mới nhất: [MTFLASH UBL Tool v1.1](https://github.com/tamm2904/MTFLASH_UBL_SNAPDRAGON/releases/tag/v1.1)

Tệp phát hành:

- `UBL-Snapdragon.exe`
- SHA256: `1EE93F228A59825889B7FC011B6960558326F1A3491B57AF04D25B26AC3C0633`

### Cách Sử Dụng Cơ Bản

1. Tải `UBL-Snapdragon.exe` từ trang Release.
2. Cài đúng USB driver cho thiết bị.
3. Mở công cụ trên Windows 10 hoặc Windows 11.
4. Xác thực phiên làm việc bằng App_MTFLASH qua mã QR hoặc mã ngắn.
5. Kết nối thiết bị đúng chế độ được yêu cầu: Android, Fastboot, FastbootD hoặc EDL.
6. Chọn đúng thương hiệu, chip và model, hoặc dùng chức năng nhận diện thiết bị nếu có.
7. Làm đúng theo từng bước trên màn hình. Đọc log trước khi bấm xác nhận tiếp tục.
8. Không rút cáp khi công cụ đang flash, unlock, erase hoặc reboot thiết bị.

### Lưu Ý An Toàn

- Chỉ thao tác với đúng model trùng với thiết bị đang kết nối.
- Sao lưu dữ liệu quan trọng trước khi unlock, root, wipe hoặc chạy firmware.
- Bootloader đang khóa, bản vá chưa hỗ trợ, chọn sai model, cáp chập chờn hoặc pin yếu đều có thể làm gián đoạn quy trình.
- Tùy model, công cụ có thể yêu cầu vào Fastboot, FastbootD, EDL hoặc giữ phím thủ công.
- Cần internet để xác thực QR và dùng các tùy chọn firmware online.

---

## Supported Devices / Thiết Bị Hỗ Trợ

### Xiaomi / Redmi / POCO

| Chip | Supported models / Model hỗ trợ |
|---|---|
| Snapdragon 8 Elite | Xiaomi 15 (`dada`)<br>Xiaomi 15 Pro (`haotian`)<br>Xiaomi 15 Ultra (`xuanyuan`)<br>Redmi K80 Pro (`miro`)<br>Redmi K90 (`annibale`)<br>POCO F8 Pro (`annibale`)<br>MIX Flip 2 (`bixi`)<br>Pad 8 Pro (`piano`) |
| Snapdragon 8 Elite Gen 5 | Xiaomi 17 (`pudding`)<br>Xiaomi 17 Pro (`pandora`)<br>Xiaomi 17 Pro Max (`popsicle`)<br>Xiaomi 17 Ultra (`nezha`)<br>REDMI K90 Pro Max (`myron`) |
| Snapdragon 8 Gen 2 | Xiaomi 13 (`fuxi`)<br>Xiaomi 13 Pro (`nuwa`)<br>Xiaomi 13 Ultra (`ishtar`)<br>Xiaomi MIX Fold 3 (`babylon`)<br>Redmi K60 Pro (`socrates`)<br>Redmi K70 (`vermeer`)<br>POCO F6 Pro (`vermeer`)<br>Xiaomi Pad 6S Pro (`sheng`) |
| Snapdragon 8 Gen 3 | Xiaomi 14 (`houji`)<br>Xiaomi 14 Pro (`shennong`)<br>Xiaomi 14 Ultra (`aurora`)<br>Redmi K70 Pro (`manet`)<br>Redmi K80 (`zorn`)<br>MIX Flip (`ruyi`)<br>MIX Fold 4 (`goku`) |
| Snapdragon 8s Gen 3 | Xiaomi Civi 4 Pro / 14 Civi (`chenfeng`)<br>POCO F6 / Redmi Turbo 3 (`peridot`)<br>Xiaomi Pad 7 Pro (`muyu`)<br>Xiaomi Pad 7 (`uke`) |
| Snapdragon 8s Gen 4 | Xiaomi Civi 5 Pro (`luming`)<br>Xiaomi Pad 8 (`yupei`)<br>Redmi Turbo 4 Pro / POCO F7 (`onyx`) |

### ZTE / Nubia / RedMagic

| Chip | Supported models / Model hỗ trợ |
|---|---|
| Snapdragon 8 Elite | RedMagic 10 Series (`NX789J`)<br>RedMagic 11 Air (`NX799J`)<br>RedMagic Pad 3 Pro / Astra (`NP05J`, `PQ84P01`)<br>Nubia Z70 Ultra (`NX733J`)<br>Nubia Z70 Ultra (`NX736J`) |
| Snapdragon 8 Elite Gen 5 | RedMagic 11 Series (`NX809J`)<br>Nubia Z80 Ultra (`NX741J`) |

### ASUS ROG

| Chip | Supported models / Model hỗ trợ |
|---|---|
| Snapdragon 8 Elite | ROG Phone 9 / 9 Pro (`AI2501`)<br>ROG Phone 9 Global (`ASUS_AI2501_A`)<br>ROG Phone 9 JP/TW (`ASUS_AI2501_B`)<br>ROG Phone 9 Pro WW (`ASUS_AI2501_C`)<br>ROG Phone 9 Pro US (`ASUS_AI2501_D`)<br>ROG Phone 9 Pro Edition US (`ASUS_AI2501_E`)<br>ROG Phone 9 Pro JP/TW (`ASUS_AI2501_F`) |

---

## Authorization / Xác Thực

| English | Tiếng Việt |
|---|---|
| The tool requires an active App_MTFLASH account with permission for this tool. | Công cụ cần tài khoản App_MTFLASH còn hiệu lực và có quyền sử dụng tool này. |
| Scan the QR or enter the short number shown on the Windows app. | Quét mã QR hoặc nhập mã ngắn hiển thị trên ứng dụng Windows. |
| Approval is required before device workflows can be used. | Cần xác nhận trước khi sử dụng các quy trình thao tác thiết bị. |
| Internet access to the MTFLASH/APMPro service is required. | Cần internet để kết nối dịch vụ MTFLASH/APMPro. |

---

## Support / Hỗ Trợ

For access, account, model support, and workflow support, contact MTFLASH through the official service channel.

Để được hỗ trợ về tài khoản, quyền truy cập, model hỗ trợ và quy trình sử dụng, vui lòng liên hệ MTFLASH qua kênh dịch vụ chính thức.
