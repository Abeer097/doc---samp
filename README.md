
# SAMPLauncher Project
## เกี่ยวกับ Launcher

- ชื่อโปรแกรม: SAMPLauncher
- ภาษาที่ใช้เขียน: [C#](https://www.w3schools.com/cs/index.php)
- IDE: [Visual Studio 2022](https://visualstudio.microsoft.com/vs/)
- .NET Framework Runtime: [4.8 ](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48)
- .NET Runtime: [6.0](https://dotnet.microsoft.com/en-us/download/dotnet/6.0)
## ความต้องการของระบบสำหรับผู้ใช้ (จำเป็น)

- Windows: Windows 10 หรือ Windows 11 64 บิต
- .NET Framework Runtime: [4.8 ](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48)
- .NET Runtime: [6.0](https://dotnet.microsoft.com/en-us/download/dotnet/6.0)
- DirectX: [D3DX9](https://www.microsoft.com/en-us/download/details.aspx?id=8109)
## ดาวน์โหลดสำหรับ DEV (จำเป็น)

- [ดาวน์โหลด Visual Studio 2022 Community](https://visualstudio.microsoft.com/vs/)
- [ดาวน์โหลด Inno Setup](https://jrsoftware.org/download.php/is.exe)
- [ดาวน์โหลด Visual Studio Code](https://code.visualstudio.com/download)
- [ดาวน์โหลด WinRAR](https://www.win-rar.com/start.html?&L=0)
## การติดตั้งสำหรับ DEV

- [การติดตั้ง Visual Studio 2022 Community](https://fujinons.web.app/howto/install-vs-2022.html)
- การติดตั้ง Inno Setup - ทำการติดตั้งโปรแกรม Inno Setup บนเครื่อง PC ของคุณตามปกติ
- การติดตั้ง Visual Studio Code - ทำการติดตั้งโปรแกรม Visual Studio Code บนเครื่อง PC ของคุณตามปกติ
- การติดตั้ง WinRAR - ทำการติดตั้งโปรแกรม WinRAR บนเครื่อง PC ของคุณตามปกติ
## วิธีตั้งค่าสำหรับ DEV
### ที่อยู่ไฟล์โปรเจค
- ให้ทำการดาวน์โหลดไฟล์และแตกไฟล์ "SAMPLauncher.zip" ด้วยโปรแกรม  Winrar ไปที่ ไดร์ `C` เท่านั้น! คุณควรจะได้ที่อยู่ของไฟล์แบบนี้
```
  C:\SAMPLauncher\
```

| ชื่อ ^ | ประเภท     |
| :-------- | :------- |
| `ConfigAutoUpdate` | `forder` |
| `FilesBuild_Installer` | `forder` |
| `FilesBuild_Launcher` | `forder` |
| `FileSetupForUser` | `forder` |
| `img` | `forder` |
| `KC_Start_LauncherV2` | `forder` |
| `obj` | `forder` |
| `Tool for Project` | `forder` |
| `App.xaml` | `file` |
| `App.xaml.cs` | `file` |
| `AssemblyInfo.cs` | `file` |
| `Config.cs` | `file` |
| `ConnectSAMPServer.cs` | `file` |
| `KC_Start_LauncherV2.sln` | `file` |
| `MainWindow.xaml` | `file` |
| `MainWindow.xaml.cs` | `file` |
| `QuerySAMP.cs` | `file` |
| `SampAPI.cs` | `file` |
| `SAMPLauncher.csproj` | `file` |
| `SAMPLauncher.csproj.user` | `file` |
| `SAMPLauncher.sln` | `file` |

### ตั้งค่า Package API
- เข้าไปที่ Path `C:\SAMPLauncher\Tool for Project\` และเปิดไฟล์ `Setting SAMP Launcher`
- ไปที่แท็บ `Save and Export to JSON` และกดปุ่ม Load save Settings
- ไปที่แท็บ `SAMP Launcher` และตั้งค่าให้เรียบร้อย

| ชื่อ | คำอธิบาย     | ตัวอย่าง     |
| :-------- | :------- | :------- |
| `Title` | `ชื่อ Launcher บนหน้าต่างโปรแกรม` | `SAMP Launcher Final Test` |
| `Title name server` | `ชื่อ Server บนหน้าต่างโปรแกรม` | `test rp` |
| `URL Discord` | `ลิ้งค์ Discord Server` | `https://discord.gg/39YvS7e` |
| `URL facebook` | `ลิ้งค์ facebook` | `https://discord.gg/39YvS7e` |
| `IP Server SAMP` | `ที่อยู่ IP Server` | `192.168.1.58` |
| `Port Server SAMP` | `ที่อยู่ PORT Server` | `ต้องเป็น 7777 เท่านั้น` |
| `Server Password` | `รหัสผ่าน Server` | `Fu*****Ns (หากไม่มี ให้ปล่อยว่าง)` |
| `CRON Password` | `รหัสผ่าน CRON Server` | `Fu*****Ns (หากไม่มี ให้ปล่อยว่าง)` |

- ไปที่แท็บ `Discord RPC`
- เข้าไปที่ `https://discord.com/developers/applications` และล็อกอินให้เรียบร้อย
- กดที่ปุ่ม `New Application`
- ตั้งชื่อ Application และยอมรับข้อตกลง จากนั้นกดที่ปุ่ม `Create`
- ในแท็บ General Information หัวข้อ `APP ICON` ให้กำหนด Icon ขนาด 1024x1024 ให้เรียบร้อย
- คัดลอก `APPLICATION ID` และนำไปใส่ในช่อง `Application ID` ของโปรแกรม `Setting SAMP Launcher`


| ชื่อ | คำอธิบาย     | ตัวอย่าง     |
| :-------- | :------- | :------- |
| `Application ID` | `APPLICATION ID ของ https://discord.com/developers/applications` | `766371391045894204` |
| `URL Button Download` | `ลิ้งค์สำหรับดาวน์โหลด Launcher บนหน้า Discord RPC` | `https://www.dropbox.com/s/ycd2teoj956393g/SAMP_Launcher_Setup.exe?dl=1` |
| `URL Button Discord` | `ลิ้งค์สำหรับ Discord บนหน้า Discord RPC` | `https://discord.gg/39YvS7e` |

- กลับมาที่หน้าเว็บ และไปที่แท็บ `Rich Presence` ตัวเลือก `Art Assets` จะเจอกับ `Rich Presence Art Assets`
- หัวข้อ `Rich Presence Invite Image` -> `COVER IMAGE` ให้กำหนด Icon ขนาด 1024x1024 ให้เรียบร้อย
- หัวข้อ `Rich Presence Assets` กดที่ปุ่ม Add Image(s) เพื่อเพิ่มรูปภาพที่จะแสดงในหน้า Discord RPC ขนาด  512x512 - 1024x1024 จำนวน 2 รูป
- กลับมาที่หน้าโปรแกรม `Setting SAMP Launcher` แท็บ `Discord RPC` -> `In Launcher` และกำหนดค่าให้เรียบร้อย

```
  แท็บ In Launcher
```
| ชื่อ | คำอธิบาย     | ตัวอย่าง     |
| :-------- | :------- | :------- |
| `Details` | `ข้อความขณะที่อยู่ใน Launcher` | `อยู่ใน Launcher` |
| `Large Image Key` | `ตีย์สำหรับรูปขนาดใหญ่ขณะที่อยู่ใน Launcher` | `logo1 (ชื่อไฟล์ที่อัพโหลดใน https://discord.com/developers/applications)` |
| `Large Image Text` | `ข้อความคำอธิบายสำหรับรูปขนาดใหญ่ขณะที่อยู่ใน Launcher` | `(Option หากไม่ใช้ ให้ปล่อยว่าง) Text logo1` |
| `Small Image Key` | `ตีย์สำหรับรูปขนาดเล็กขณะที่อยู่ใน Launcher` | `(Option หากไม่ใช้ ให้ปล่อยว่าง) logo2 (ชื่อไฟล์ที่อัพโหลดใน https://discord.com/developers/applications)` |
| `Small Image Text` | `ข้อความคำอธิบายสำหรับรูปขนาดเล็กขณะที่อยู่ใน Launcher` | `(Option หากไม่ใช้ ให้ปล่อยว่าง) Text logo2` |

```
  แท็บ In Game
```
| ชื่อ | คำอธิบาย     | ตัวอย่าง     |
| :-------- | :------- | :------- |
| `Details` | `ข้อความขณะที่อยู่ใน Game` | `อยู่ใน Grand Theft Auto San Andreas` |
| `Large Image Key` | `ตีย์สำหรับรูปขนาดใหญ่ขณะที่อยู่ใน Game` | `logo2 (ชื่อไฟล์ที่อัพโหลดใน https://discord.com/developers/applications)` |
| `Large Image Text` | `ข้อความคำอธิบายสำหรับรูปขนาดใหญ่ขณะที่อยู่ใน Game` | `(Option หากไม่ใช้ ให้ปล่อยว่าง) Text logo2` |
| `Small Image Key` | `ตีย์สำหรับรูปขนาดเล็กขณะที่อยู่ใน Game` | `(Option หากไม่ใช้ ให้ปล่อยว่าง) logo1` |
| `Small Image Text` | `ข้อความคำอธิบายสำหรับรูปขนาดเล็กขณะที่อยู่ใน Game` | `(Option หากไม่ใช้ ให้ปล่อยว่าง) Text logo1` |

- ไปที่แท็บ `Save and Export to JSON` และกดปุ่ม `Save and Export Packages`
- กดเปิดไฟล์ `kc_packages.json` ด้วยโปรแกรม `Visual Studio Code`
- เข้าไปที่ `https://www.npoint.io/` ให้สมัครและล็อกอินให้เรียบร้อย
- กดที่ปุ่ม `+ New` และตั้งชื่อฐานข้อมูลเป็น `Main - SAMP Launcher`
- ในโปรแกรม `Visual Studio Code` ที่เปิดไฟล์ `kc_packages.json`ค้างไว้ ให้คัดลอกข้อความทั้งหมด
- กลับมาที่หน้าเว็บ npoint.io -> `Main - SAMP Launcher` ให้วางข้อความที่คัดลอกมา แทนที่ข้อความเดิม และให้กดที่ปุ่ม `Save`

### Restore NuGet Packages และตั้งค่าโปรเจค Launcher และทดสอบ
- เข้าไปที่ Path `C:\SAMPLauncher\` และเปิดไฟล์ `SAMPLauncher.sln` ด้วย `Visual Studio 2022`
- คลิ๊กขวาที่ Solution 'SAMPLauncher' (หากคำว่า Restore NuGet Packages เป็นสีเท่า ให้คลิ๊กขวาที่ Solution 'SAMPLauncher' ใหม่อีกครั้ง จนกว่าข้อความ Restore NuGet Packages จะเป็นสีขาว )
- เลือก Restore NuGet Packages (รอสักครู่)
- คลิ๊กขวาที่ Solution 'SAMPLauncher' อีกครั้ง และเลือก Rebuild Solution (รอจนเสร็จ)
- คลิ๊กขวาที่ Solution 'SAMPLauncher' อีกครั้ง และเลือก Build Solution (รอจนเสร็จ)
- ไปที่ด้านล่างสุดของหน้าเว็บ npoint.io -> `Main - SAMP Launcher` จะเจอข้อความ `This bin is available at` ให้คัดลอกลิ้งค์ `https://api.npoint.io/????????????????????`
- ในไฟล์ `Config.cs` ช่อง `MainAPI` ให้นำลิ้งค์ที่คัดลอกมา ใส่ลงแทนที่ลิ้งค์เดิม และกดบันทึก
- คลิ๊กขวาที่ Solution 'SAMPLauncher' และเลือก Rebuild Solution (รอจนเสร็จ)
- คลิ๊กขวาที่ Solution 'SAMPLauncher' อีกครั้ง และเลือก Build Solution (รอจนเสร็จ)
- กดที่ปุ่ม  Satrt (หรือ F5) เพื่อทดสอบ Launcher เบื่องต้นว่าเปิดใช้งานได้หรือไม่ และเมื่อทดสอบเสร็จให้ออกจาก Launcher

### เพิ่มไฟล์ที่จำเป็นสำหรับ SAMPLauncher (รวมถึงไฟล์ที่ต้องการ Update)
#### เพิ่มไฟล์เกมและ SAMP
- คลิ๊กขวาที่ Solution 'SAMPLauncher' และเลือก `Open foder in File Explorer`
- เข้าไปที่ `C:\SAMPLauncher\FilesBuild_Launcher\Release\net6.0-windows\gamefiles\` ให้นำไฟล์เกมและ samp.exe รวมถึงไฟล์ Mod หรือไฟล์ที่จำเป็นในการเล่นต่างๆ ใส่ลงใน Forder `gamefiles`
#### เพิ่มไฟล์ภาพพื้นหลังและ Icon
- เข้าไปที่ `C:\SAMPLauncher\FilesBuild_Launcher\Release\net6.0-windows\img\`
##### เพิ่มไฟล์ภาพพื้นหลัง
###### (เตรียมไฟล์รูปสำหรับพื้นหลัง SAMPLauncher ขนาด `1920x1080` และตั้งชื่อไฟล์เป็น `bg.jpg` เท่านั้น!)
- นำไฟล์รูปสำหรับพื้นหลังที่ต้องการเปลี่ยนมาว่างทับไฟล์เดิม
##### เพิ่มไฟล์ Icon
###### (เตรียมไฟล์รูปสำหรับ Icon SAMPLauncher ขนาด `200x200` และตั้งชื่อไฟล์เป็น `icon.ico` เท่านั้น! หากคุณมีแค่ไฟล์ประเภท PNG คุณสามารถแปลงไฟล์ PNG เป็น ICO ได้ที่ `https://convertio.co/th/png-ico/`)
- นำไฟล์ Icon ที่ต้องการเปลี่ยนมาว่างทับไฟล์เดิม

### Pack ให้เป็นไฟล์ .zip สำหรับ Update SAMPLauncher
- เข้าไปที่ `C:\SAMPLauncher\FilesBuild_Launcher\Release\`
- คลิ๊กขวาที่ Forder `net6.0-windows` และเลือก `Add to archive...`
- หัวข้อ `Archive format` ให้เลือกเป็น `ZIP` เท่านั้น! และกดปุ่ม OK (รอจนเสร็จ)
- เมื่อได้ไฟล์ `net6.0-windows.zip` มาแล้ว ให้กดเปิดไฟล์ `net6.0-windows.zip` ด้วยโปรแกรม `WinRAR`
- จะเจอกับ Forder `net6.0-windows` ให้คลิ๊กขวา และเลือก `Rename` ให้เปลี่ยนชื่อเป็น `launcher` จากนั้นกดที่ปุ่ม Enter (รอจนเสร็จ)
- เมื่อรอจนเสร็จแล้ว ให้ปิด `net6.0-windows.zip`

### Upload ไฟล์ net6.0-windows.zip ขึ้น Cloud Dropbox
- เข้าไปที่ `https://www.dropbox.com/h` ให้สมัครและล็อกอินให้เรียบร้อย
- ใน Dropbox ให้สร้าง Forder ชื่อ `Files - SAMPLauncher` ขึ้นมา
- ให้นำไฟล์ `net6.0-windows.zip` ลากลงใน Forder `Files - SAMPLauncher` (รอจนเสร็จ)
- เมื่อ Upload เสร็จแล้วให้คัดลอกลิ้งค์ไฟล์เก็บไว้

### ตั้งค่า Package Update API
- กลับไปที่โปรแกรม `Setting SAMP Launcher` แท็บ `KC Auto Update 2.5`
- ให้วางลิ้งค์ที่คัดลอกมาลงในช่องของหัวข้อ `URL download file Update ( . zip only )` คุณจะได้ลิ้งค์แบบนี้ `https://www.dropbox.com/s/?????????/net6.0-windows.zip?dl=0`
- ให้แก้ไขตัวเลขด้านหลังลิ้งค์จาก `0` เป็น `1` (`https://www.dropbox.com/s/?????????/net6.0-windows.zip?dl=0` ->  `https://www.dropbox.com/s/?????????/net6.0-windows.zip?dl=1`)  และกำหนดค่าให้เรียบร้อย

| ชื่อ | คำอธิบาย     | ตัวอย่าง     |
| :-------- | :------- | :------- |
| `URL download file Update ( . zip only )` | `ลิ้งค์สำหรับดาวน์โหลดไฟล์ Update` | `https://www.dropbox.com/s/?????????/net6.0-windows.zip?dl=1` |
| `Version` | `Version ปัจจุบัน` | `1.0.0` |
| `MD5 file Launcher ( _launcher.exe )` | `Hash MD5 ของไฟล์ _launcher.exe` | `(โปรแกรมจะตรวจสอบให้อัตโนมัติ)` |

- ไปที่แท็บ `Save and Export to JSON` และกดปุ่ม `Save and Export Packages`
- กดเปิดไฟล์ `kc_packageupdate.json` ด้วยโปรแกรม `Visual Studio Code`
- เข้าไปที่ `https://www.npoint.io/` และล็อกอินให้เรียบร้อย
- กดที่ปุ่ม `+ New` และตั้งชื่อฐานข้อมูลเป็น `Update - SAMP Launcher`
- ในโปรแกรม `Visual Studio Code` ที่เปิดไฟล์ `kc_packageupdate.json`ค้างไว้ ให้คัดลอกข้อความทั้งหมด
- กลับมาที่หน้าเว็บ npoint.io -> `Update - SAMP Launcher` ให้วางข้อความที่คัดลอกมา แทนที่ข้อความเดิม และให้กดที่ปุ่ม `Save`

### Restore NuGet Packages และตั้งค่าโปรเจค KC_Start_LauncherV2
- เข้าไปที่ Path `C:\SAMPLauncher\` และเปิดไฟล์ `KC_Start_LauncherV2.sln` ด้วย `Visual Studio 2022`
- คลิ๊กขวาที่ `Solution 'KC_Start_LauncherV2'` (หากคำว่า Restore NuGet Packages เป็นสีเท่า ให้คลิ๊กขวาที่ Solution 'KC_Start_LauncherV2' ใหม่อีกครั้ง จนกว่าข้อความ Restore NuGet Packages จะเป็นสีขาว )
- เลือก Restore NuGet Packages (รอสักครู่)
- คลิ๊กขวาที่ `Solution 'KC_Start_LauncherV2'` อีกครั้ง และเลือก `Rebuild Solution` (รอจนเสร็จ)
- คลิ๊กขวาที่ `Solution 'KC_Start_LauncherV2'` อีกครั้ง และเลือก `Build Solution` (รอจนเสร็จ)
- ไปที่ด้านล่างสุดของหน้าเว็บ npoint.io -> `Update - SAMP Launcher` จะเจอข้อความ `This bin is available at` ให้คัดลอกลิ้งค์ `https://api.npoint.io/????????????????????`
- ในไฟล์ `ConfigAutoUpdate.cs` ช่อง `URLUpdateAPI` ให้นำลิ้งค์ที่คัดลอกมาใส่ลง `แทนที่ลิ้งค์เดิม` และกดบันทึก
- คลิ๊กขวาที่ `Solution 'KC_Start_LauncherV2'` และเลือก `Rebuild Solution` (รอจนเสร็จ)
- คลิ๊กขวาที่ `Solution 'KC_Start_LauncherV2'` อีกครั้ง และเลือก `Build Solution` (รอจนเสร็จ)

#### เปลี่ยน Icon
##### (เตรียมไฟล์รูปสำหรับ Icon SAMPLauncher ขนาด `200x200` และตั้งชื่อไฟล์เป็น `icon.ico` เท่านั้น! หากคุณมีแค่ไฟล์ประเภท PNG คุณสามารถแปลงไฟล์ PNG เป็น ICO ได้ที่ `https://convertio.co/th/png-ico/`)
- คลิ๊กขวาที่ `KC_Start_LauncherV2`
- เลือก `Add`
- เลือก `Existing Item...`
- เปลี่ยนจาก Visual C# Files เป็น `All Files`
- เลือกไฟล์ Icon ของคุณที่เป็นประเภท `ICO`
- คลิ๊ก Add จากนั้นคลิ๊กขวาที่ `KC_Start_LauncherV2`
- เลือก `Properties`
- เลือกหัวข้อ `Application`
- หัวข้อ Icon คลิ๊กที่ลูกศรชี้ลง `⇩`
- เลือกไฟล์ Icon ของคุณ
- คลิ๊กขวาที่ `Solution 'KC_Start_LauncherV2'` และเลือก `Rebuild Solution` (รอจนเสร็จ)
- คลิ๊กขวาที่ `Solution 'KC_Start_LauncherV2'` อีกครั้ง และเลือก `Build Solution` (รอจนเสร็จ)

#### เปลี่ยนภาพพื้นหลัง
##### (เตรียมไฟล์รูปสำหรับพื้นหลัง KC Start Launcher ขนาด `560x280` และตั้งชื่อไฟล์เป็น `app bg.jpg` เท่านั้น!)
- เข้าไปที่ `C:\SAMPLauncher\FilesBuild_Installer\resource`
- นำไฟล์รูปสำหรับพื้นหลังที่ต้องการเปลี่ยนมาว่างทับไฟล์เดิม

### สร้างไฟล์สำหรับติดตั้ง
- เข้าไปที่ `C:\SAMPLauncher\Tool for Project\`
- เปิดไฟล์ `Create file setup Launcher.iss` ด้วย `Inno Setup Compiler`
- ตั้งค่าไฟล์ Setup ของคุณ

| ชื่อ | คำอธิบาย     | ตัวอย่าง     |
| :-------- | :------- | :------- |
| `MyAppName` | `ชื่อโปรแกรม` | `SAMP_Launcher` |
| `MyAppVersion` | `เวอร์ชั่นของโปรแกรม (ไม่มีผลกับระบบ Auto Update)` | `1.0.0` |
| `MyAppPublisher` | `ชื่อเจ้าของ หรือ ผู้สร้าง` | `Fujino N's` |
| `MyAppIcon` | `ไอค่อนโปรแกรม` | `C:\SAMPLauncher\img\icon.ico` |
| `MyAppURL` | `ลิงค์ติดต่อ หรือ ลิงค์โปรแกรม` | `https://fujinons.web.app/credit/` |
| `MyFolderInstall` | `ชื่อโฟลเดอร์ในไดร์ C สำหรับติดตั้งไฟล์ Launcher` | `FujinoNs` |

- เมื่อตั้งค่าเสร็จให้กดปุ่ม Ctrl+S ที่ Keyboard
- กดปุ่ม Ctrl+F9 ที่ Keyboard
- รอจนขึ้นข้อความ `*** Finished. [??:??:??, ??:??.?? elapsed]` และกดปิดโปรแกรม Inno Setup Compiler
- ไฟล์สำหรับแจกจ่ายให้ผู้เล่นจะถูกเก็บไว้ใน `C:\SAMPLauncher\FileSetupForUser\`

## วิธีอัพเดตไฟล์ Launcher และไฟล์ Game
#### เมื่อมีการแก้ไขโค้ด Launcher เช่นการแก้บัค และต้องการอัพเดตไฟล์ Launcher หรือไฟล์ Game หรือ Mod ให้ทำตามนี้)
- ให้ทำตามขั้นตอน `เพิ่มไฟล์ที่จำเป็นสำหรับ SAMPLauncher (รวมถึงไฟล์ที่ต้องการ Update)` ถึงขั้นตอน `ตั้งค่า Package Update API` หัวข้อที่ `3`
- ในแท็บ `KC Auto Update 2.5` ช่อง `Version` ให้ปรับเลขเวอร์ชั่น จาก `1.0.0` เป็น `1.1.0`
- ไปที่เท็บ `Save and Export to JSON` และกดปุ่ม `Save and Export Packages`
- กดเปิดไฟล์ `kc_packageupdate.json` ด้วยโปรแกรม `Visual Studio Code`
- เข้าไปที่ `https://www.npoint.io/docs/`
- กดเข้าไปที่ฐานข้อมูล `Update - SAMP Launcher`
- ในโปรแกรม `Visual Studio Code` ที่เปิดไฟล์ `kc_packageupdate.json` ค้างไว้ ให้คัดลอกข้อความทั้งหมด
- กลับมาที่หน้าเว็บ npoint.io -> `Update - SAMP Launcher` ให้วางข้อความที่คัดลอกมา แทนที่ข้อความเดิม และให้กดที่ปุ่ม `Save`
- ระบบจะทำการอัพเดตอัตโนมัติหลังจากผู้ใช้เข้า Launcher ใหม่อีกครั้ง
## END
## FAQ
#### ไม่สามารถเข้าร่วม Server ได้
#### สำหรับ DEV
##### 1.โปรดตรวจสอบว่า IP,PORT,Server Password หรือ CRON Password ถูกต้อง
##### 2.โปรดอัพเดต SAMP Client หรือตัวเกม เป็นเวอร์ชั่นปัจจุบันให้ผู้เล่น
#### สำหรับผู้ใช้
##### 1.โปรดดาวน์โหลด Launcher เวอร์ชั่นล่าสุด หรืออัพเดต Launcher ให้เป็นเวอร์ชั่นล่าสุด
##### 2.ขอไฟล์ SAMP Client เวอร์ชั่น Setup จาก Admin มาติดตั้งทับไฟล์เดิมของ Launcher

#### ไม่สามารถอัพเดตเป็นเวอร์ชั่นล่าสุดได้
#### สำหรับ DEV
##### 1.โปรดตรวจสอบว่าลิ้งค์ในช่อง URL download file Update ( . zip only ) เป็น `https://www.dropbox.com/s/?????????/net6.0-windows.zip?dl=1` แล้วหรือไม่ หาก ?dl=0 ให้เปลี่ยน เป็น ?dl=1
#### สำหรับผู้ใช้
##### 1.โปรดลองใหม่อีกครั้ง
##### 2.โปรด Restart PC ของคุณ และลองใหม่อีกครั้ง

#### ไม่สามารถเปิดโปรแกรมได้
##### 1.โปรดตรวจสอบว่าคุณสมบัติของ PC คุณตรงกับความต้องการของระบบหรือไม่
##### 2.โปรด Restart PC ของคุณ และลองใหม่อีกครั้ง
##### 3.โปรดปิดโปรแกรม Antivirus และลองใหม่อีกครั้ง
