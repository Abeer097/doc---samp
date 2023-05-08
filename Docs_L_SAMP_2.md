
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
- ให้ทำการดาวน์โหลดไฟล์และแตกไฟล์ "SAMPLauncherWebView2.zip" ด้วยโปรแกรม Winrar ไปที่ ไดร์ `C` (หรือไดร์อื่น หากไดร์ C ไม่มีพื้นที่ว่าง) ตำแหน่ง `Root Directory` เท่านั้น!
*ภาพตัวอย่างวิธีแตกไฟล์ SAMPLauncherWebView2.zip*

![alt text](https://i.imgur.com/RGlQ1m7.png)

*ภาพตัวอย่างหลังแตกไฟล์เสร็จ*

![alt text](https://i.imgur.com/aj4xU9A.png)

- เพื่อให้แน่ใจว่าโฟลเดอร์ `SAMPLauncherWebView2` ที่แตกไฟล์มาจาก `SAMPLauncherWebView2.zip` เป็นโฟลเดอร์ที่ถูกต้อง โดยให้เข้าไปในโฟลเดอร์ `SAMPLauncherWebView2` และสังเกตว่า ตำแหน่งและไฟล์หรือโฟลเดอร์ย่อยต่างๆ เหมือนกับภาพตัวอย่างหรือไม่

*ภาพตัวอย่างที่ถูกต้อง*

![alt text](https://i.imgur.com/H1rQFKB.png)

### ตั้งค่า SAMPLauncherWebView2_API ( คำแนะนำ โปรดเปิดใช้งาน Service Apache และ MySQL บนโปรแกรม XAMPP ให้เรียบร้อย )
- ให้แตกไฟล์ "SAMPLauncherWebView2_API.zip" ด้วยโปรแกรม Winrar

*ภาพตัวอย่างวิธีแตกไฟล์ SAMPLauncherWebView2_API.zip*

![alt text](https://i.imgur.com/LlJXTou.png)

- เมื่อแตกไฟล์เสร็จ ให้ทำการคัดลอกโฟลเดอร์ `SAMPLauncherWebView2_API`
*ภาพตัวอย่างวิธีคัดลอกโฟลเดอร์ SAMPLauncherWebView2_API*

![alt text](https://i.imgur.com/WAnkG5Z.png)

- ให้เข้าไปในตำแหน่ง `C:\xampp\htdocs\` บนเครื่อง Server VPS ของคุณ และให้วางโฟลเดอร์ `SAMPLauncherWebView2_API` ที่คัดลอกมาจาก PC ของคุณ

*ภาพตัวอย่างวิธีวางโฟลเดอร์ SAMPLauncherWebView2_API*

![alt text](https://i.imgur.com/A9Mnfs0.png)


*ภาพตัวอย่างหลังวางโฟลเดอร์ SAMPLauncherWebView2_API แล้ว*

![alt text](https://i.imgur.com/cXH1iKn.png)

- ให้เปิดเข้าไปในโฟลเดอร์ `SAMPLauncherWebView2_API` และเปิดไฟล์ `DB  Config.sql` ด้วยโปรแกรม HeidiSQL

*ภาพตัวอย่างวิธีเปิดไฟล์ DB  Config.sql*

![alt text](https://i.imgur.com/4QG3tXk.png)

- กดปุ่ม Open

![alt text](https://i.imgur.com/KkSq63o.png)

- กดปุ่ม F9 หรือที่ Icon ▶

![alt text](https://i.imgur.com/ufaOkaA.png)

- หากมีหน้าต่างให้ยืนยัน ให้กด Yes

![alt text](https://i.imgur.com/vqCqiV3.png)

- จากนั้นรอจนเสร็จ และเมื่อเสร็จจะขึ้นหน้าต่างขึ้นมา ให้กดปุ่ม OK

![alt text](https://i.imgur.com/jZcTjOO.png)

- ให้กดปุ่ม F5 จากนั้นจะมี Database `samplauncherwebview2_db` เพิ่มขึ้นมา จากนั้นให้ออกจากโปรแกรม HeidiSQL

![alt text](https://i.imgur.com/EmsfZS1.png)


- กลับมาที่โฟลเดอร์ `SAMPLauncherWebView2_API` และให้เปิดไฟล์ `config_db.php` ด้วยโปรแกรม Visual Studio Code

*ภาพตัวอย่างวิธีเปิดไฟล์ config_db.php*
![alt text](https://i.imgur.com/XkUtPvL.png)

- ให้ตั้งค่าฐานข้อมูลตามนี้

| ชื่อ | คำอธิบาย     | ตัวอย่าง     |
| :-------- | :------- | :------- |
| `DBHOST` | `Server Host SQL` | `ให้กำหนดเป็น 127.0.0.1 หรือ localhost ( หรือหากมี Server Host SQL แยกต่างหาก ให้ใส่ที่อยู่ Host นั้นๆ )` |
| `DBUSER` | `ชื่อบัญชีผู้ใช้ที่สามารถเข้าถึงฐานข้อมูลได้` | `ค่าปกติจะเป็น root` |
| `DBPASS` | `รหัสผ่านบัญชีผู้ใช้ที่สามารถเข้าถึงฐานข้อมูลได้` | `ค่าปกติของ XAMPP จะเป็นค่าว่าง หรือหากเป็น AMPPS จะเป็นค่า mysql` |
| `DBNAME` | `ชือฐานข้อมูลที่ต้องการเข้าถึง` | `ให้กำหนดเป็น samplauncherwebview2_db` |

- เมื่อตั้งค่าเสร็จให้กดปุ่ม CTRL + S เพื่อบันทึก และปิดหน้าจอโปรแกรม Visual Studio Code

![alt text](https://i.imgur.com/J5ttZMi.png)

- ตอนนี้บนเครื่อง Server VPS ตอนนี้เสร็จแล้ว ให้กลับไปที่ PC ของคุณ

### ตั้งค่าโปรเจค SAMPLauncherWebView2
- เข้าไปที่ Path `C:\SAMPLauncherWebView2\` และเปิดไฟล์ `SAMPLauncherWebView2.sln` ด้วยโปรแกรม Visual Studio 2022

*ภาพตัวอย่างวิธีเปิดไฟล์ SAMPLauncherWebView2.sln*

![alt text](https://i.imgur.com/BDe7eNb.png)

- เข้าไปใน `config.json.cs` ให้คัดลอกลิงค์นี้ `http://127.0.0.1/SAMPLauncherWebView2_API/api/?id=mainconfig` ไปแทนที่ลิ้งค์เดิม

*ภาพตัวอย่างลิ้งค์เดิม*

![alt text](https://i.imgur.com/rYyiVD4.png)

- และให้เปลี่ยน IP 127.0.0.1 ที่อยู่ในลิ้งค์เป็น IP เครื่อง Server VPS ที่มี SAMPLauncherWebView2_API อยู่

*ภาพตัวอย่างลิ้งค์ใหม่*

![alt text](https://i.imgur.com/4tKFAvL.png)


- กดปุ่ม F5 เพื่อทดสอบโปรแกรม Launcher ว่าสามารถเชื่อมต่อกับ Server API ได้หรือไม่

*ภาพตัวอย่างหากเชื่อมต่อกับ Server API ได้ปกติ*

![alt text](https://i.imgur.com/9uxC6oG.png)

### ( Option ) วิธีเปลี่ยนรูป Icon ไฟล์โปรแกรม Launcher

- คลิ๊กขวาที่ SAMPLauncherWebView2 และเลือก Properties

![alt text](https://i.imgur.com/x4RUb6g.png)

- กดที่ปุ่ม Browse... เพื่อเลือกไฟล์ Ico สำหรับใช้เป็น Icon ไฟล์โปรแกรม

![alt text](https://i.imgur.com/jLwrQYX.png)


### ทำไฟล์ Setup สำหรับให้ผู้เล่นติดตั้งบน PC

- คลิ๊กขวาที่ SAMPLauncherWebView2 และเลือก Properties

![alt text](https://i.imgur.com/x4RUb6g.png)

- กดที่ปุ่ม `Assembly Information...`
- ให้กำหนดเลข `Assembly version` ใหม่ เช่น `1.0.0.0` ( หากมีการแก้ไขโค้ด หรืออื่นๆเกี่ยวกับโปรเจค SAMPLauncherWebView2 และต้องการอัพเดตให้ผู้เล่น ให้กำหนดเลข `Assembly version` ใหม่ เช่น `1.0.1.0`  )

- ให้กำหนดเลข `File version` ให้ตรงกับ `Assembly version`

- ให้คลิ๊กขวาที่ Solution 'SAMPLauncherWebView2'
- เลือก Rebuild Solution และรอจนเสร็จ
- คลิ๊กขวาที่ Solution 'SAMPLauncherWebView2'
- เลือก Build Solution และรอจนเสร็จ

![alt text](https://i.imgur.com/yswNvMP.png)

- เข้าไปที่ Path `C:\SAMPLauncherWebView2\bin\Release\` จากนั้นให้ลบโฟลเดอร์ `gamefiles` และ `Launcher.exe.WebView2` ทิ้งก่อน

![alt text](https://i.imgur.com/gVVBYjq.png)

- เข้าไปที่ Path `C:\SAMPLauncherWebView2\` และเปิดไฟล์ `Setup Install exe.iss` ด้วยโปรแกรม Inno Setup Compiler

![alt text](https://i.imgur.com/NXhKfwS.png)

- ตั้งค่าไฟล์ Setup ของคุณ

![alt text](https://i.imgur.com/ZcfLnSR.png)

- เมื่อตั้งค่าเสร็จให้กดปุ่ม CTRL + F9 และรอจนเสร็จ

![alt text](https://i.imgur.com/jAAX21o.png)

- เข้าไปที่ Path `C:\SAMPLauncherWebView2\setup` คุณจะเจอกับไฟล์ ที่ลงท้ายด้วย Setup.exe
- ( คุณสามารถแจกจ่ายไฟล์ Setup.exe ผู้เล่นคนอื่นๆได้แล้ว )
![alt text](https://i.imgur.com/1k5LFAZ.png)

### การตั้งค่า Launcher และตั้งค่าอื่นๆ
- คัดลอกลิ้งค์นี้ `http://YOU_SERVER_IP/SAMPLauncherWebView2_API/panel/index.php` ไปเปิดบนเบราว์เซอร์ของคุณ
- ให้เข้าสูระบบด้วยบัญชีค่าเริ่มต้น Username: `adminpanel` และ Password: `3X8s5ml0yXvT` (คำเตือน! โปรดเปลี่ยน Username และ Password ทันที ที่ `เครื่อง Server VPS -> HeidiSQL -> samplauncherwebview2_db -> admin_account` เมื่อคุณตั้งค่าเริ่มต้นเสร็จสิ้น)

![alt text](https://i.imgur.com/NjX5zSB.png)

#### การตั้งค่า Launcher

![alt text](https://i.imgur.com/RLtWS8C.png)

- ให้ตั้งค่าฐานข้อมูลตามนี้

| ชื่อ | คำอธิบาย     | ตัวอย่าง     |
| :-------- | :------- | :------- |
| `ชื่อโปรแกรม` | `ชื่อโปรแกรม Launcher ที่จะให้แสดงบน Title bar ของโปรแกรม` | `Launcher SAMP 2` |
| `Url หน้าเว็บไซต์ UI` | `ลิ้งค์หน้าเพจ UI Launcher` | `ให้กำหนดเป็น http://YOU_SERVER_IP/SAMPLauncherWebView2_API/web_ui_launcher/index.html` |
| `Url รูปภาพหน้าโหลดระบบ Webview2` | `ลิ้งค์รูปภาพหน้าโหลดเข้า Launcher (แนะนำขนาด 1280x720px)` | `https://i.imgur.com/NVhU3QQ.jpg` |
| `Url รูปภาพไอค่อนโปรแกรม` | `ลิ้งค์รูปภาพ Icon โปรแกรม Launcher (ICO,PNG,JPG แนะนำ ICO)` | `https://fujinons.web.app/resource/img/New-KC-Logo-200x200.ico` |
| `Url รูปภาพพื้นหลัง Launcher` | `ลิ้งค์รูปภาพพื้นหลัง Launcher (แนะนำขนาด 1280x720px)` | `https://i.imgur.com/twmXJX4.jpg` |
| `Youtube Video ID` | `ID Video จา่ก Youtube ที่จะให้แสดงบน Launcher` | `https://www.youtube.com/watch?v=`Jg6zvjYzXHE |

- เมื่อเสร็จแล้วให้กดปุ่ม บันทึกการตั้งค่า

#### การตั้งค่าปุ่มเมนู

![alt text](https://i.imgur.com/wY7jynC.png)

- สำหรับเพิ่มปุ่มใหม่ ให้ตั้งค่าฐานข้อมูลตามนี้

| ชื่อ | คำอธิบาย     | ตัวอย่าง     |
| :-------- | :------- | :------- |
| `กำหนดชื่อปุ่ม` | `ตั้งชื่อปุ่มตามที่ต้องการ` | `Facebook` |
| `Url รูปภาพไอค่อนของปุ่ม` | `ลิ้งค์รูปภาพที่จะใช้เป็น Icon ของปุ่ม` | `https://cdn1.iconfinder.com/data/icons/logotypes/32/square-facebook-256.png` |
| `สีของฟอนต์` | `สีของข้อความ` | `255 255 255` |
| `สีของพื้นหลัง` | `สีของพื้นหลัง` | `0 163 221` |
| `ลิ้งค์` | `เมื่อผู้ใช้กดปุ่ม จะให้ลิ้งค์ไปที่ไหน` | `https://www.facebook.com/fujinolive` |

- เมื่อเสร็จแล้วให้กดปุ่ม เพิ่มรายการปุ่มเมนู

- สำหรับแก้ไขปุ่มเดิม ให้กดที่ปุ่ม `เลือก` เมื่อแก้ไขเสร็จสิ้น ให้กดที่ปุ่ม `อัพเดตปุ่มเมนู` หรือหากต้องการยกเลิกการเลือก ให้กดปุ่ม `ยกเลิก` 

![alt text](https://i.imgur.com/90V4arO.png)

#### การตั้งค่าประชาสัมพันธ์

![alt text](https://i.imgur.com/CW8c2NW.png)

- สำหรับเพิ่มรายการประชาสัมพันธ์ใหม่ ให้ตั้งค่าฐานข้อมูลตามนี้

| ชื่อ | คำอธิบาย     | ตัวอย่าง     |
| :-------- | :------- | :------- |
| `กำหนดประเภท` | `ประเภทของการสื่อสาร` | `ข่าวสาร` |
| `สีของพื้นหลังข้อความ ประเภท` | `กำหนดสีให้สำหรับประเภทนั้นๆ` | `0 183 96` |
| `กำหนดหัวเรื่องของลิ้งค์` | `ชื่อหัวเรื่อง` | `7-5-2022 ทดสอบระบบ Launcher` |
| `ลิ้งค์สำหรับอ่านต่อ` | `สีของพื้นหลัง` | `0 163 221` |
| `ลิ้งค์` | `เมื่อผู้ใช้กดที่หัวเรื่อง จะให้ลิ้งค์ไปที่ไหน` | `https://www.facebook.com/fujinolive` |

- เมื่อเสร็จแล้วให้กดปุ่ม เพิ่มรายการประชาสัมพันธ์ใหม่

- สำหรับแก้ไขรายการประชาสัมพันธ์เดิม ให้กดที่ปุ่ม `เลือก` เมื่อแก้ไขเสร็จสิ้น ให้กดที่ปุ่ม `อัพเดตประชาสัมพันธ์` หรือหากต้องการยกเลิกการเลือก ให้กดปุ่ม `ยกเลิก` 

![alt text](https://i.imgur.com/OmIdbi8.png)

#### การตั้งค่ารายการ Server

![alt text](https://i.imgur.com/mkb8Nym.png)

- สำหรับเพิ่มรายการ Server ใหม่ ให้ตั้งค่าฐานข้อมูลตามนี้

| ชื่อ | คำอธิบาย     | ตัวอย่าง     |
| :-------- | :------- | :------- |
| `ชื่อ Server` | `ชื่อ Server ที่แสดงบน Launcher` | `GTA San Legend of RolePlay - Sv1` |
| `กำหนด Server ID` | `ให้กำหนด ID ของ Server โดยที่อย่าให้ซ้ำกับ Server ไดๆที่อยู่ใน List` | `server1` |
| `IP Server` | `IP ของ Server SAMP` | `154.212.139.107` |
| `Port Server` | `Port ของ Server SAMP` | `7777` |
| `Url รูปภาพ Logo Server` | `ลิ้งค์รูปภาพ Logo Server ที่แสดงบนการการเซิร์ฟเวอร์บน Launcher` | `https://fujinons.web.app/resource/img/New-KC-Logo-200x200.ico` |
| `รหัสผ่าน RCon` | `รหัสผ่าน RCON Server` | `(หากไม่มี ให้ปล่อยว่าง)` |
| `รหัสผ่าน Server` | `รหัสผ่าน Server` | `(หากไม่มี ให้ปล่อยว่าง)` |

- เมื่อเสร็จแล้วให้กดปุ่ม เพิ่มเซิร์ฟเวอร์

- สำหรับแก้ไขรายการ Server เดิม ให้กดที่ปุ่ม `เลือก` เมื่อแก้ไขเสร็จสิ้น ให้กดที่ปุ่ม `อัพเดตการตั้งค่า` หรือหากต้องการยกเลิกการเลือก ให้กดปุ่ม `ยกเลิก` 

![alt text](https://i.imgur.com/YYLWwkC.png)

#### การตั้งค่าเวอร์ชั่น Launcher ( อัพเดต Launcher )

- ทุกครั้งที่มีการแก้ไขโค้ด หรืออื่นๆเกี่ยวกับโปรเจค `SAMPLauncherWebView2` ให้ทำตามขั้นตอน `ทำไฟล์ Setup สำหรับให้ผู้เล่นติดตั้งบน PC` ก่อน

- ไปที่ Path `C:\SAMPLauncherWebView2\setup\` บนเครื่อง PC ของคุณ และคัดลอกไฟล์ `ชื่อไฟล์ Setup.exe`

![alt text](https://i.imgur.com/fEX3jNj.png)

- เข้าไป Path `C:\xampp\htdocs\SAMPLauncherWebView2_API\file_update\` บนเครื่อง Server VPS ของคุณ 

![alt text](https://i.imgur.com/ti3aKhL.png)

- วางไฟล์ `ชื่อไฟล์ Setup.exe` ที่คัดลอกมาจาก PC ของคุณ

*ภาพตัวอย่างก่อนวางไฟล์ `ชื่อไฟล์ Setup.exe`*

![alt text](https://i.imgur.com/nKGdB14.png)

*ภาพตัวอย่างหลังจากวางไฟล์ `ชื่อไฟล์ Setup.exe`*

![alt text](https://i.imgur.com/4hwmSwI.png)

- ให้เปิดลิ้งค์นี้ `http://YOU_SERVER_IP/SAMPLauncherWebView2_API/file_update/` ในเบราว์เซอร์บนเครื่อง Server VPS ของคุณ
- ให้คลิ๊กขวาที่ไฟล์ `ชื่อไฟล์ Setup.exe` และเลือก `คัดลอกที่อยู่ลิงก์`

![alt text](https://i.imgur.com/8cEUncL.png)

- กลับมาที่เว็บ L-SAMP-2 Panel แท็บ `ตั้งค่าเวอร์ชั่น` และวางลิ้งค์ที่คัดลอกมาลงในช่อง `ลิ้งค์ที่อยู่ไฟล์ Setup.exe เวอร์ชั่นใหม่`

![alt text](https://i.imgur.com/ux6RrHZ.png)

- เข้าไปที่ Path `C:\SAMPLauncherWebView2\` บนเครื่อง PC ของคุณ และเปิดไฟล์ `SAMPLauncherWebView2.sln` ด้วยโปรแกรม Visual Studio 2022

![alt text](https://i.imgur.com/MeboMVh.png)

- คลิ๊กขวาที่ SAMPLauncherWebView2 และเลือก Properties

![alt text](https://i.imgur.com/x4RUb6g.png)

- กดที่ปุ่ม `Assembly Information...`
- เปิดหน้าเว็บ L-SAMP-2 Panel แท็บ `ตั้งค่าเวอร์ชั่น` และกรอก `เวอร์ชั่น Launcher` ให้ตรงกับ `Assembly version` ของโปรแกรม
- เมื่อเสร็จแล้วให้กดปุ่ม บันทึกการตั้งค่า
- ระบบจะอัพเดตให้ผู้เล่นอัตโนมัติ เมื่อผู้เล่นเข้า Launcher ใหม่อีกครั้ง

![alt text](https://i.imgur.com/ebYPLlS.png)


#### การตั้งค่าเวอร์ชั่น Game ( อัพเดตไฟล์ Game )

- ทุกครั้งที่มีการแก้ไขโค้ด หรืออื่นๆเกี่ยวกับโปรเจค `SAMPLauncherWebView2` ให้ทำตามขั้นตอน `ทำไฟล์ Setup สำหรับให้ผู้เล่นติดตั้งบน PC` ก่อน

- เข้าไป Path `C:\xampp\htdocs\SAMPLauncherWebView2_API\file_update\` บนเครื่อง Server VPS ของคุณ

- และให้สร้างโฟล์เดอร์ชื่อ `gamefiles` ขึ้นมา ( หากเป็นการอัพเดตไฟล์เกม ให้ลบโฟลเดอร์ gamefiles เดิมทิ้งก่อน )

![alt text](https://i.imgur.com/Lujhq1U.png)

- เข้าไปโฟล์เดอร์ `gamefiles` และให้นำไฟล์ Game พร้อม SAMP.exe และ Mods ที่เตรียมไว้ให้กับผู้เล่นสำหรับใช้เข้าเล่นบน Server ใส่ในโฟลเดอร์ `gamefiles`

![alt text](https://i.imgur.com/QjsGBXx.png)

*ภาพตัวอย่างหลังจากนำไฟล์ Game ใส่ลงในโฟลเดอร์* `gamefiles`

![alt text](https://i.imgur.com/6YC6Yfr.png)

- กลับไปที่โฟลเดอร์ `file_update` 

![alt text](https://i.imgur.com/tTehCT0.png)


- ให้คลิ๊กขวาที่โฟลเดอร์ `gamefiles` และบีบให้เป็นไฟล์ `ZIP` เท่านั้น! ด้วยโปรแกรม WinRAR และรอจนเสร็จ ( หากเป็นการอัพเดตไฟล์เกม ให้ลบไฟล์ gamefiles.zip เดิมทิ้งก่อน )

![alt text](https://i.imgur.com/SI97Xft.png)

- เมื่อบีบไฟล์เสร็จ คุณจะได้ไฟล์ `gamefiles.zip` มา 1 ไฟล์

![alt text](https://i.imgur.com/NYBv9MW.png)

- ให้เปิดลิ้งค์นี้ `http://YOU_SERVER_IP/SAMPLauncherWebView2_API/file_update/` ในเบราว์เซอร์บนเครื่อง Server VPS ของคุณ
- ให้คลิ๊กขวาที่ไฟล์ `gamefiles.zip` และเลือก `คัดลอกที่อยู่ลิงก์`

![alt text](https://i.imgur.com/jIzkNGW.png)

- กลับมาที่เว็บ L-SAMP-2 Panel แท็บ `ตั้งค่าเวอร์ชั่น` และวางลิ้งค์ที่คัดลอกมาลงในช่อง `ลิ้งค์ที่อยู่ไฟล์ gamefiles.zip สำหรับอัพเดท`

![alt text](https://i.imgur.com/xoiYyMq.png)

- ในช่อง `เวอร์ชั่นแพทช์ไฟล์ Game` ให้กำหนดเลขเวอร์ชั่น เช่น จากเดิมเวอร์ชั่น `1.0.0` ให้เปลี่ยนเป็น `1.0.1`

![alt text](https://i.imgur.com/9mo93Hx.png)

- เมื่อเสร็จแล้วให้กดปุ่ม บันทึกการตั้งค่า

### หากเปิดปัญหา หรือติดปัญหา โปรดติดต่อผู้สร้างโปรแกรมนี้
