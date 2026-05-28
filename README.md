# MTFLASH UBL Snapdragon

<p align="center">
  <b>Professional Snapdragon bootloader unlock, firmware, EDL, Fastboot, and root assistant for Windows.</b><br>
  <b>Công cụ Windows hỗ trợ unlock bootloader, firmware, EDL, Fastboot và root cho thiết bị Snapdragon.</b>
</p>

<p align="center">
  <a href="https://github.com/tamm2904/MTFLASH_UBL_SNAPDRAGON/releases/tag/v1.2"><img alt="Version" src="https://img.shields.io/badge/version-v1.2-111111?style=for-the-badge"></a>
  <img alt="Platform" src="https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D4?style=for-the-badge">
  <img alt="Language" src="https://img.shields.io/badge/language-English%20%2F%20Ti%E1%BA%BFng%20Vi%E1%BB%87t-2E7D32?style=for-the-badge">
  <img alt="Brands" src="https://img.shields.io/badge/brands-Xiaomi%20%7C%20ZTE%20%7C%20ASUS-B71C1C?style=for-the-badge">
</p>

<p align="center">
  <a href="https://github.com/tamm2904/MTFLASH_UBL_SNAPDRAGON/releases/latest"><b>Download Latest Release</b></a>
  &nbsp;|&nbsp;
  <a href="#english">English</a>
  &nbsp;|&nbsp;
  <a href="#tiếng-việt">Tiếng Việt</a>
  &nbsp;|&nbsp;
  <a href="#supported-devices--thiết-bị-hỗ-trợ">Supported Devices</a>
  &nbsp;|&nbsp;
  <a href="#contact--liên-hệ">Contact</a>
</p>

---

## English

### Overview

MTFLASH UBL Snapdragon is a guided Windows tool for selected Xiaomi, Redmi, POCO, ZTE, Nubia, RedMagic, and ASUS Snapdragon devices. It focuses on clear servicing workflows, model-aware checks, live logs, firmware handling, and step-by-step device operations for authorized users.

### Main Features

- Guided bootloader unlock workflows for supported Snapdragon models.
- Xiaomi high-version unlock support for Snapdragon 8 Gen 3 and 8s Gen 3 devices on security patch `2026-02-01` and newer.
- Model-specific Mini EngFirmware handling during supported high-version workflows.
- High-version unlock stops after `unlocked: yes` verification without wiping `misc` or rebooting automatically.
- Fastboot and EDL flashing screens for supported Xiaomi, ZTE/Nubia/RedMagic, and ASUS devices.
- EDL storage info check with UFS vendor/capacity detection and Kioxia/Toshiba flash blocking.
- Firmware download manager with Mini EngFirmware, Full EngFirmware, China Fastboot, and China HyperTN options where available.
- Device detection through ADB and Fastboot.
- Root assistant for unlocked devices using supported Magisk, KernelSU, and SukiSU workflows.
- English and Vietnamese interface with progress logs, sound cues, voice prompts, and confirmation dialogs.
- QR-based online authorization through App_MTFLASH.

### Download

Latest release: [MTFLASH UBL Tool v1.2](https://github.com/tamm2904/MTFLASH_UBL_SNAPDRAGON/releases/tag/v1.2)

| File | Size | SHA256 |
|---|---:|---|
| `UBL-Snapdragon.exe` | `117,763,134` bytes | `069F31DF524B8EA48500193266D03D029E1AB0767B1A7221207605E2FF155EAF` |

### Basic Usage

1. Download `UBL-Snapdragon.exe` from the release page.
2. Install the correct USB driver for your device.
3. Run the tool on Windows 10 or Windows 11.
4. Authorize the session with App_MTFLASH by scanning the QR code or entering the short code.
5. Connect the device in the mode requested by the selected workflow: Android, Fastboot, FastbootD, or EDL.
6. Select the correct brand, chip, and model, or use device detection when available.
7. Follow each on-screen step and read the live log before confirming the next action.
8. Do not disconnect the device during unlock, flash, erase, firmware, or reboot operations.

### Safety Notes

- Use only the model that matches the connected device.
- Back up important data before unlock, root, wipe, or firmware operations.
- A locked bootloader, unsupported security patch, unstable cable, weak battery, or wrong model selection can interrupt the workflow.
- Some workflows require manual key combinations or switching between Android, Fastboot, FastbootD, and EDL.
- Internet access is required for authorization and online firmware options.

---

## Tiếng Việt

### Tổng Quan

MTFLASH UBL Snapdragon là công cụ Windows có hướng dẫn cho một số thiết bị Snapdragon thuộc Xiaomi, Redmi, POCO, ZTE, Nubia, RedMagic và ASUS. Công cụ tập trung vào quy trình thao tác rõ ràng, kiểm tra theo đúng model, log trực tiếp, xử lý firmware và các bước thao tác thiết bị dành cho người dùng đã được cấp quyền.

### Tính Năng Chính

- Hỗ trợ quy trình unlock bootloader có hướng dẫn cho các model Snapdragon được hỗ trợ.
- Hỗ trợ Xiaomi high-version cho Snapdragon 8 Gen 3 và 8s Gen 3 với security patch từ `2026-02-01` trở lên.
- Xử lý Mini EngFirmware theo từng model trong các workflow high-version được hỗ trợ.
- Nhánh high-version dừng sau khi verify `unlocked: yes`, không wipe `misc` và không tự reboot.
- Màn hình Fastboot và EDL cho các thiết bị Xiaomi, ZTE/Nubia/RedMagic và ASUS được hỗ trợ.
- Màn hình EDL có kiểm tra đầy đủ thông tin UFS, nhận diện vendor/dung lượng và chặn flash khi phát hiện UFS Kioxia/Toshiba.
- Trình tải firmware với Mini EngFirmware, Full EngFirmware, China Fastboot và China HyperTN nếu model có dữ liệu tương ứng.
- Nhận diện thiết bị qua ADB và Fastboot.
- Hỗ trợ root cho thiết bị đã unlock bằng các workflow Magisk, KernelSU và SukiSU tương thích.
- Giao diện tiếng Anh và tiếng Việt, có log tiến trình, âm báo, giọng nói hướng dẫn và hộp thoại xác nhận.
- Xác thực online bằng QR thông qua App_MTFLASH.

### Tải Xuống

Phiên bản mới nhất: [MTFLASH UBL Tool v1.2](https://github.com/tamm2904/MTFLASH_UBL_SNAPDRAGON/releases/tag/v1.2)

| File | Dung lượng | SHA256 |
|---|---:|---|
| `UBL-Snapdragon.exe` | `117,763,134` bytes | `069F31DF524B8EA48500193266D03D029E1AB0767B1A7221207605E2FF155EAF` |

### Cách Sử Dụng Cơ Bản

1. Tải `UBL-Snapdragon.exe` từ trang Release.
2. Cài đúng USB driver cho thiết bị.
3. Mở công cụ trên Windows 10 hoặc Windows 11.
4. Xác thực phiên làm việc bằng App_MTFLASH qua mã QR hoặc mã ngắn.
5. Kết nối thiết bị đúng chế độ mà workflow yêu cầu: Android, Fastboot, FastbootD hoặc EDL.
6. Chọn đúng thương hiệu, chip và model, hoặc dùng nhận diện thiết bị nếu có.
7. Thực hiện đúng từng bước trên màn hình và đọc log trước khi xác nhận bước tiếp theo.
8. Không rút cáp khi công cụ đang unlock, flash, erase, xử lý firmware hoặc reboot thiết bị.

### Lưu Ý An Toàn

- Chỉ thao tác với đúng model trùng với thiết bị đang kết nối.
- Sao lưu dữ liệu quan trọng trước khi unlock, root, wipe hoặc xử lý firmware.
- Bootloader đang khóa, security patch chưa hỗ trợ, cáp chập chờn, pin yếu hoặc chọn sai model đều có thể làm gián đoạn quy trình.
- Một số workflow yêu cầu giữ phím thủ công hoặc chuyển đổi giữa Android, Fastboot, FastbootD và EDL.
- Cần internet để xác thực và sử dụng các tùy chọn firmware online.

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
| The tool requires an active App_MTFLASH account with permission for this product. | Công cụ cần tài khoản App_MTFLASH còn hiệu lực và có quyền sử dụng sản phẩm này. |
| Scan the QR code or enter the short code shown in the Windows app. | Quét mã QR hoặc nhập mã ngắn hiển thị trên ứng dụng Windows. |
| Device workflows are available only after authorization is approved. | Chỉ có thể sử dụng workflow thiết bị sau khi xác thực được chấp thuận. |
| Internet access to the MTFLASH/APMPro service is required. | Cần internet để kết nối dịch vụ MTFLASH/APMPro. |

---

## Contact / Liên Hệ

Official contact channels are listed on the MTFlash contact page.

Các kênh liên hệ chính thức được lấy từ trang liên hệ MTFlash.

| Channel | Contact |
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

## Support / Hỗ Trợ

For access, account, supported model, and workflow support, contact MTFLASH through the official service channel.

Để được hỗ trợ về tài khoản, quyền truy cập, model hỗ trợ và quy trình sử dụng, vui lòng liên hệ MTFLASH qua kênh dịch vụ chính thức.
