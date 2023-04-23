
# SAMP Launcher WebView2
## เกี่ยวกับ Launcher

- ชื่อโปรแกรม: SAMPLauncherWebView2
- ภาษาที่ใช้เขียน: [C#](https://www.w3schools.com/cs/index.php), [HTML](https://www.w3schools.com/html/default.asp), [CSS](https://www.w3schools.com/css/default.asp), [JavaScript](https://www.w3schools.com/js/default.asp), [PHP](https://www.w3schools.com/php/default.asp), [SQL](https://www.w3schools.com/sql/default.asp)
- IDE: [Visual Studio 2022](https://visualstudio.microsoft.com/vs/)
- IDE: [Visual Studio Code](https://code.visualstudio.com/)
- .NET Framework Runtime: [4.8 +](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48)
- Microsoft Edge WebView2 Runtime: [Evergreen Bootstrapper](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section)
## ความต้องการของระบบสำหรับผู้ใช้ (จำเป็น)

- Windows: Windows 10 หรือ Windows 11 64 บิต
- .NET Framework Runtime: [4.8 +](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48)
- Microsoft Edge WebView2 Runtime: [Evergreen Bootstrapper ( *จำเป็นต้องลงทุกคน* )](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section)
## ดาวน์โหลดสำหรับ DEV (จำเป็น)

- [ดาวน์โหลด Visual Studio 2022 Community](https://visualstudio.microsoft.com/vs/)
- [ดาวน์โหลด Inno Setup](https://jrsoftware.org/download.php/is.exe)
- [ดาวน์โหลด Visual Studio Code ( *บนเครื่อง Server VPS* )](https://code.visualstudio.com/download)
- [ดาวน์โหลด WinRAR](https://www.win-rar.com/start.html?&L=0)
- [ดาวน์โหลด Microsoft Edge WebView2 Runtime เวอร์ชั่น Evergreen Bootstrapper](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section)
- [ดาวน์โหลด XAMPP ( *บนเครื่อง Server VPS* )](https://www.apachefriends.org/download.html)
- [ดาวน์โหลด HeidiSQL ( *บนเครื่อง Server VPS* )](https://www.heidisql.com/download.php)
## การติดตั้งสำหรับ DEV

- [การติดตั้ง Visual Studio 2022 Community](https://fujinons.web.app/howto/install-vs-2022.html)
- การติดตั้ง Inno Setup - ทำการติดตั้งโปรแกรม Inno Setup บนเครื่อง PC ของคุณตามปกติ
- การติดตั้ง Visual Studio Code - ทำการติดตั้งโปรแกรม Visual Studio Code บนเครื่อง Server VPS ของคุณตามปกติ
- การติดตั้ง WinRAR - ทำการติดตั้งโปรแกรม WinRAR บนเครื่อง PC ของคุณตามปกติ
- การติดตั้ง Microsoft Edge WebView2 Runtime เวอร์ชั่น Evergreen Bootstrapper - ทำการติดตั้งโปรแกรม Microsoft Edge WebView2 Runtime เวอร์ชั่น Evergreen Bootstrapper บนเครื่อง PC ของคุณตามปกติ
- [การติดตั้ง XAMPP ( *บนเครื่อง Server VPS* )](https://fujinons.web.app/howto/install-xampp.html)
- [การติดตั้ง HeidiSQL ( *บนเครื่อง Server VPS* )](https://fujinons.web.app/howto/install-HeidiSQL.html)
## วิธีตั้งค่าสำหรับ DEV
### ที่อยู่ไฟล์โปรเจค
- ให้ทำการดาวน์โหลดไฟล์และแตกไฟล์ "SAMPLauncherWebView2.zip" ด้วยโปรแกรม  Winrar ไปที่ ไดร์ `C` เท่านั้น! คุณควรจะได้ที่อยู่ของไฟล์แบบนี้
```
  C:\SAMPLauncherWebView2\
```
![alt text](https://i.imgur.com/y0qBaXQ.png)

### ตั้งค่า SAMPLauncherWebView2_API
- เข้าไปที่ Path `C:\SAMPLauncherWebView2\ไฟลเสริม\`
![alt text](https://i.imgur.com/DewOTn4.png)
- คัดลอกโฟลเดอร์ `SAMPLauncherWebView2_API` ไปที่ `C:\xampp\htdocs` ( *บนเครื่อง Server VPS* )
![alt text](https://i.imgur.com/DiSJ5Kw.png)
- เข้าไปในโฟลเดอร์ `SAMPLauncherWebView2_API` และให้เปิดไฟล์ `config_db.php` ด้วยโปรแกรม Visual Studio Code
![alt text](https://i.imgur.com/RjHXGVi.png)
- ให้ตั้งค่าฐานข้อมูลตามนี้

| ชื่อ | คำอธิบาย     | ตัวอย่าง     |
| :-------- | :------- | :------- |
| `DBHOST` | `Server Host SQL` | `ให้กำหนดเป็น 127.0.0.1 หรือ localhost ( หรือหากมี Server Host SQL แยกต่างหาก ให้ใส่ที่อยู่ Host นั้นๆ )` |
| `DBUSER` | `ชื่อบัญชีผู้ใช้ที่สามารถเข้าถึงฐานข้อมูลได้` | `ค่าปกติจะเป็น root` |
| `DBPASS` | `รหัสผ่านบัญชีผู้ใช้ที่สามารถเข้าถึงฐานข้อมูลได้` | `ค่าปกติของ XAMPP จะเป็นค่าว่าง หรือหากเป็น AMPPS จะเป็นค่า mysql` |
| `DBNAME` | `ชือฐานข้อมูลที่ต้องการเข้าถึง` | `ให้กำหนดเป็น samplauncherwebview2_db` |

- เมื่อตั้งค่าเสร็จให้กดปุ่ม CTRL + S เพื่อบันทึก และปิดหน้าจอโปรแกรม Visual Studio Code

![alt text](https://i.imgur.com/J5ttZMi.png)

- ให้เปิดไฟล์ `SQL Config API.sql` ด้วยโปรแกรม HeidiSQL
![alt text](https://i.imgur.com/E0EpKGz.png)
- กดปุ่ม Open
![alt text](https://i.imgur.com/GS7CE6g.png)
- กดปุ่ม F9 หรือที่ Icon ▶
![alt text](https://i.imgur.com/8zpFAHr.png)
- หากมีหน้าต่างให้ยืนยัน ให้กด Yes
![alt text](https://i.imgur.com/Sv2hfHW.png)
- จากนั้นรอจนเสร็จ และเมื่อเสร็จจะขึ้นหน้าต่างขึ้นมา ให้กดปุ่ม OK
![alt text](https://i.imgur.com/l25nnuH.png)
- ให้กดปุ่ม F5 จากนั้นจะมี Database `samplauncherwebview2_db` เพิ่มขึ้นมา
![alt text](https://i.imgur.com/AlJK50y.png)
- ให้กดเข้าไปใน Database `samplauncherwebview2_db` และใน Database `samplauncherwebview2_db` จะมี Table

| ชื่อ | คำอธิบาย |
| :-------- | :------- |
| `autoupdate_config` | `จัดเก็บข้อมูลการตั้งค่า Auto Update` 
| `launcher_config` | `จัดเก็บข้อมูลการตั้งค่า Launcher` 
| `server_list` | `จัดเก็บข้อมูลการตั้งค่ารายการ Server` 

![alt text](https://i.imgur.com/IPAQOoB.png)

- เข้าไปใน Table `launcher_config` และกดที่แท็บ Data เพื่อแสดง COLUMN ทั้งหมด
![alt text](https://i.imgur.com/tDoIZDX.png)
- โดยใน COLUMN ต่างๆจะตั้งค่าดังนี้

| ชื่อ | คำอธิบาย     | ตัวอย่าง     |
| :-------- | :------- | :------- |
| `LauncherName` | `ชื่อโปรแกรม Launcher ที่จะให้แสดงบน Title bar ของโปรแกรม` | `LAUNCHER SAMP 2` |
| `LauncherUILauncherURL` | `ลิ้งค์หน้าเพจ UI Launcher ` | `http://ให้ใส่เลขที่อยู่_IP_เครื่อง_Server_VPS/SAMPLauncherWebView2_API/web_ui_launcher/` |
| `LauncherImageLoading` | ` ลิ้งค์รูปภาพหน้าโหลดเข้า Launcher (แนะนำขนาด 1280x720px)` | `https://i.imgur.com/NVhU3QQ.jpg` |
| `LauncherIcon` | `ลิ้งค์รูปภาพ Icon โปรแกรม Launcher (ICO,PNG,JPG แนะนำ ICO)` | `https://fujinons.web.app/resource/img/New-KC-Logo-200x200.ico` |

- กดที่ปุ่ม ENTER เพื่อบันทึกข้อมูล
- เข้าไปใน Table `server_list` (หากไม่มี COLUMN ไดแสดง ให้กดที่แท็บ Data เพื่อแสดง COLUMN ทั้งหมด)
![alt text](https://i.imgur.com/taf19Ut.png)
- โดยใน COLUMN ต่างๆจะตั้งค่าดังนี้

| ชื่อ | คำอธิบาย     | ตัวอย่าง     |
| :-------- | :------- | :------- |
| `serverId` | `ให้กำหนด ID ของ Server โดยที่อย่าให้ซ้ำกับ Server ไดๆที่อยู่ใน List` | `server1` |
| `bigbgserver` | `ลิ้งค์รูปภาพพื้นหลัง Server ที่แสดงบนการการเซิร์ฟเวอร์บน Launcher` | `https://cdn.discordapp.com/attachments/1013587792716103800/1039509176310841465/ISREAL_BOXING_SV1.gif` |
| `logoserver` | `ลิ้งค์รูปภาพ Logo Server ที่แสดงบนการการเซิร์ฟเวอร์บน Launcher` | `http://154.212.139.107/logo.png` |
| `serverIP` | `IP ของ Server SAMP` | `154.212.139.107` |
| `serverPort` | `Port ของ Server SAMP` | `7777` |
| `serverLabel` | ` ชื่อ Server ที่แสดงบน Launcher` | `GTA San Legend of RolePlay - Sv1` |
| `serverText` | `รายละเอียดของ Server ที่แสดงบน Launcher` | `RolePlay Server 1 เป็นเซิร์ฟเวอร์ RolePlay .... ` |
| `sampCRONPassword` | `	รหัสผ่าน CRON Server` | `(หากไม่มี ให้ปล่อยว่าง)` |
| `sampServerPassword` | `รหัสผ่าน Server` | `(หากไม่มี ให้ปล่อยว่าง)` |

- กดที่ปุ่ม ENTER เพื่อบันทึกข้่อมูล
- บนเครื่อง Server VPS ตอนนี้เสร็จแล้ว ให้กลับไปที่ PC ของคุณ

### ตั้งค่าโปรเจค Launcher
- เข้าไปที่ Path `C:\SAMPLauncherWebView2\` และเปิดไฟล์ `SAMPLauncherWebView2.sln` ด้วยโปรแกรม Visual Studio 2022
![alt text](https://i.imgur.com/xMFgMxO.png)

- เข้าไปใน `config.json.cs` จะเจอกับลิงค์ `http://127.0.0.1/SAMPLauncherWebView2_API/api/?id=mainconfig`
- ให้เปลี่ยน IP 127.0.0.1 ที่อยู่ในลิ้งค์เป็น IP เครื่อง Server VPS ที่มี SAMPLauncherWebView2_API อยู่
![alt text](https://i.imgur.com/74xwdkh.png)

- (Option คุณสามารถกดปุ่ม F5 เพื่อทดสอบโปรแกรม Launcher ได้)
- ให้คลิ๊กขวาที่ Solution 'SAMPLauncherWebView2'
- เลือก Rebuild Solution และรอจนเสร็จ
- คลิ๊กขวาที่ Solution 'SAMPLauncherWebView2'
- เลือก Build Solution และรอจนเสร็จ
- และออกจากโปรแกรม Visual Studio 2022 Community

### ตั้งค่าโปรเจค Auto Update

- เข้าไปที่ Path `C:\SAMPLauncherWebView2\` และเปิดไฟล์ `KC_Start_LauncherV2.sln` ด้วยโปรแกรม Visual Studio 2022
![alt text](https://i.imgur.com/e1KNiff.png)

- เข้าไปใน `ConfigAutoUpdate` -> `ConfigAutoUpdate.cs` จะเจอกับลิงค์ `http://localhost/SAMPLauncherWebView2_API/api/?id=autoupdate_config`
- ให้เปลี่ยน localhost ที่อยู่ในลิ้งค์เป็น IP เครื่อง Server VPS ที่มี SAMPLauncherWebView2_API อยู่
![alt text](https://i.imgur.com/rFa1KSh.png)

- คลิ๊กขวาที่ KC_Start_LauncherV2 และเลือก Properties
![alt text](https://i.imgur.com/Fag9OYC.png)
- กดที่ปุ่ม Browse...
![alt text](https://i.imgur.com/gC99Yrx.png)
- เลือกไฟล์ Ico ที่จะใช้เป็น Icon โปรแกรม จากนั้นให้กดปุ่ม Open
![alt text](https://i.imgur.com/V66F4VN.png)

- ให้คลิ๊กขวาที่ Solution 'KC_Start_LauncherV2'
- เลือก Rebuild Solution และรอจนเสร็จ
- คลิ๊กขวาที่ Solution 'KC_Start_LauncherV2'
- เลือก Build Solution และรอจนเสร็จ
- และออกจากโปรแกรม Visual Studio 2022 Community

#### (Option) เปลี่ยนรูปพื้นหลัง KC Start Launcher
- เข้าไปที่ Path `C:\SAMPLauncherWebView2\FilesBuild_Installer_for_SETUP_File\resource`
- นำไฟล์รูปพื้นหลังมาวางทับไฟล์เดิมโดยใช้ชื่อ `app bg.jpg` เท่านั้น
![alt text](https://i.imgur.com/xzD7nKI.png)

### ทำไฟล์ Setup สำหรับให้ผู้เล่นติดตั้งบน PC
- เข้าไปที่ Path `C:\SAMPLauncherWebView2\` และเปิดไฟล์ `Create file setup Launcher.iss` ด้วยโปรแกรม Inno Setup Compiler
![alt text](https://i.imgur.com/c2j5PvY.png)

- ตั้งค่าไฟล์ Setup ของคุณ
![alt text](https://i.imgur.com/qN67huu.png)
- เมื่อตั้งค่าเสร็จให้กดปุ่ม CTRL + F9 และรอจนเสร็จ
![alt text](https://i.imgur.com/SeqJlyd.png)
- เข้าไปที่ Path `C:\SAMPLauncherWebView2\FileSetupForUser` คุณจะเจอกับไฟล์ ที่ลงท้ายด้วย Setup.exe
- ( คุณสามารถแจกจ่ายไฟล์ Setup.exe ผู้เล่นคนอื่นๆได้แล้ว )
![alt text](https://i.imgur.com/e0Icc6q.png)

### เตรียมไฟล์สำหรับ Update
(ไฟล์ทุกอย่างที่อยู่ใน launcher.zip จะถูกอัพเดตให้ผู้เล่น)
- เข้าไปที่ Path `C:\SAMPLauncherWebView2\FilesBuild_Launcher_for_UPDATE_Pack\launcher`
- (Option) หากต้องการอัพเดตไฟล์เกม หรือไฟล์ต่างๆที่เกี่ยวกับตัวเกม ให้เข้าไปในโฟลเดอร์ `gamefiles` และจัดการในสิ่งที่คุณจะทำ
![alt text](https://i.imgur.com/ZzuSPxy.png)
- (Option) หากต้องการแก้ไขโค้ดโปรแกรมให้เข้าไปที่ Path `C:\SAMPLauncherWebView2\` และเปิดไฟล์ `KC_Start_LauncherV2.sln` ด้วยโปรแกรม Visual Studio 2022 และจัดการในสิ่งที่คุณจะทำ
![alt text](https://i.imgur.com/e1KNiff.png)
- เมื่อจัดการเสร็จสิ้น ให้เข้าไปที่ Path `C:\SAMPLauncherWebView2\FilesBuild_Launcher_for_UPDATE_Pack`
![alt text](https://i.imgur.com/dpTaxmS.png)
- ให้คลิ๊กขวาที่โฟลเดอร์ `launcher` และบีบอัดเป็นไฟล์ ZIP
![alt text](https://i.imgur.com/ELKfRIZ.png)
- เมื่อรอจนบีบอัดเป็นไฟล์ ZIP เสร็จ คุณจะได้ไฟล์ `launcher.zip` มา 1 ไฟล์
![alt text](https://i.imgur.com/tmNhY88.png)
- เข้าไปที่เครื่อง Server VPS
- ให้คัดลอกไฟล์ `launcher.zip`
![alt text](https://i.imgur.com/oC1Kavu.png)
- ให้เข้าไปที่ Path `C:\xampp\htdocs\SAMPLauncherWebView2_API\file_update` บนเครื่อง Server VPS และวางไฟล์ `launcher.zip` ลงใน โฟลเดอร์ `file_update`
![alt text](https://i.imgur.com/evImYl1.png)

### ตั้งค่าระบบ Auto Update
- เปิดหน้าเว็บ https://emn178.github.io/online-tools/md5_checksum.html
- คลิ๊กที่ข้อความ Drop File Here Path
- ให้ใส่ที่อยู่ `C:\SAMPLauncherWebView2\FilesBuild_Launcher_for_UPDATE_Pack\launcher\` และกดปุ่ม ENTER
![alt text](https://i.imgur.com/C4u0N9R.png)
- กดที่ปุ่ม Open และหน้าเว็บจะแสดง MD5 ของไฟล์ ให้ทำการคัดลอก MD5 ของไฟล์เก็บไว้
![alt text](https://i.imgur.com/grrbfqW.png)
- ให้เปิดโปรแกรม HeidiSQL ขึ้นมา และกด Open
![alt text](https://i.imgur.com/t9cQmNj.png)
- เข้าไปใน Database `samplauncherwebview2_db` -> Table `autoupdate_config` (หากไม่มี COLUMN ไดแสดง ให้กดที่แท็บ Data เพื่อแสดง COLUMN ทั้งหมด)
- ให้ตั้งค่าฐานข้อมูลตามนี้

| ชื่อ | คำอธิบาย     | ตัวอย่าง     |
| :-------- | :------- | :------- |
| `MD5Launcher` | `MD5 ไฟล์ _launcher.exe` | `นำ MD5 ของไฟล์ _launcher.exe ที่คัดลอกไว้มาใส่`  |
| `URLForUpdateLauncher` | `ลิ้งค์ที่อยู่ไฟล์อัพเดต` | `http://ให้ใส่เลขที่อยู่_IP_เครื่อง_Server_VPS/SAMPLauncherWebView2_API/file_update/launcher.zip` |
| `VersionLauncherCurrent` | `เวอร์ชั่นปัจจุบัน` | `2.0.0` |

- (ระบบจะอัพเดตให้ผู้เล่น เมื่อออกและเข้าโปรแกรม Launcher ใหม้อีกครั้ง)
![alt text](https://i.imgur.com/b5O9FUm.png)

### หากเปิดปัญหา หรือติดปัญหา โปรดติดต่อผู้สร้างโปรแกรมนี้
[ติดต่อฉัน](https://fujinons.web.app/contact/)
