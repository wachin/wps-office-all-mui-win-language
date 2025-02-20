# wps-office-all-mui-win-language

In 2023, the Chinese software company Kingsoft Office, which developed WPS Office, released an update with many improvements for Linux available for 64-bit computers; These are the steps to install it (Also at the end are the steps for the latest version 11.1.0.8392 for 32 and 64 bit). You can ask me any questions by email: wachin.id@gmail.com.

## Tutorial en español

Este tutorial está disponible en español aquí:

**WPS Office 2019 versión 11.1.0.11711 actualización 2023 para Linux**   
🔗 [https://facilitarelsoftwarelibre.blogspot.com/2023/11/wps-office-2019-version-11.1.0.11704-actualizacion-2023.html.html](https://facilitarelsoftwarelibre.blogspot.com/2023/11/wps-office-2019-version-11.1.0.11704-actualizacion-2023.html.html)

---

# How to Install WPS Office version 11.1.0.xxxxx on Linux Linux (64 bit)
This is an tutorial to install the 11.1.0.xxxxx on Linux only 64 bit

## Tested WPS Office 11.1.0.xxxxx in the following Linux
Tested in:

**Abbreviations:**
MX = MX Linux  
Deb = Debian  
Mint 21 = Linux Mint 21 Vanessa  
✔ = Working Fine  
❌ = Not Working  

| WPS version  | Release | MX 23(Deb 12) | MX 21(Deb 11) | Mint 21 | Ubuntu |
| ------------ | ------- | ------------- | ------------- | ------- | ------ |
| 11.1.0.10702 | ?       | ❌            |               |         |        |
| 11.1.0.11704 | ©2023   | ✔             |               | ✔       |        |
| 11.1.0.11711 | ©2023   | ✔             | ✔             | ✔       |        |
| 11.1.0.11723 | ©2024   | ✔             |               |         |        |

---

WPS Office 11.1.0.xxxxx brings the four programs:

- **Writer** (Procesador de textos)  
- **Presentation** (Presentaciones)  
- **Spreadsheet** (Hojas de cálculo)  
- **PDF**  

In 11.1.0.11711 version WPS Office have the programs in same window:

![](vx_images/20240212-080056-WPS-Office-11.1.0.11711-amd64.png)

---

## WPS Office Chinese version has language selector button 

You must download the Chinese version 11.1.0.xxxxx because it has the language switcher button enabled:

![](vx_images/20231030-223216-WPS-Office-button-in-11.1.0.11704.png)

---

## Doesn`t use WPS Office 12.1.0.xxxxx versión

WPS Office Linux 12.1.0.xxxxx have problems with language switcher button because is missing, not download from there:  

🔗 [https://www.wps.cn/product/wpslinux](https://www.wps.cn/product/wpslinux)

At this time 2025-01 not working the language switcher button, tested in 12.1:

- **wps-office_12.1.0.17881_amd64.deb**  
- **wps-office_12.1.0.17900_amd64.deb**  

perhaps later working. 

**Note:** The program was previously available there at [www.wps.cn](www.wps.cn) but is no longer available.

---

## Download from Mirror web
There is some WPS version in the web in the following mirror, but I don't know when the link will go down:

🔗 [https://mirrors.163.com/ubuntukylin/pool/partner/](https://mirrors.163.com/ubuntukylin/pool/partner/) 

![](vx_images/20240211-224433-Varias-versiones-de-WPS-Office-en-ubuntukylin.com.png)

Additionally, if you wish to use the WPS Office Linux version 11.1.0.11704, which has each program separately, as shown in the following screenshot:

![](vx_images/20231116_WPS_Office_Linux_11.1.0.11704_Portada.png)

This is other snapshot:

![](vx_images/20231030-233430-wps-office-11.1.0.11704-Update-2023-working-in-mint-21.png)


you can download it:

![](vx_images/20250129-083708-mirror.163.com-WPS-Office-11.1.0.11704.png)

---

## Download from MEGA
The following link is a mirror that I have uploaded in my own MEGA account in case the other downloads fail, this has some versions:

📥 From **MEGA**  
🔗 [https://mega.nz/folder/s6AQHSzC#Kd8qbA-Z7yeTa2P5qcVG3w](https://mega.nz/folder/s6AQHSzC#Kd8qbA-Z7yeTa2P5qcVG3w)

---

## Download from Telegram

📥 In **Telegram** I have some versions:  
🔗 [https://t.me/c/1343202595/14](https://t.me/c/1343202595/14)

---

## About the warning "This type of file can damage your computer. Do you want to download ... deb anyway?"

That message is a general warning that appears when downloading executable files, such as `.deb` files on Linux systems. `.deb` files contain installable packages, and if they come from untrusted sources, they could potentially contain malicious software that could damage your system or compromise its security.

The warning does not necessarily mean that the file you are downloading is dangerous, but rather that you should be careful and make sure it comes from a trusted source. It is important to verify the authenticity and provenance of the file before installing it, especially if you are not downloading it from the official repositories of your Linux distribution.

You can also upload it to to check its Reliability to:

🔍 [https://virustotal.com](https://virustotal.com) 

---

## 1.) Install deb with right clic
When you right click on the **deb** you should see an option in your file manager to install deb, this on **MX Linux**, **Debian**, **Ubuntu**, but if not in your distro, search on the web how to install **deb** files.

---

## 2.) Install ttf-wps-fonts

These are the symbol fonts required by wps-office. They are used to display math formulas. Since the official download is no longer available I uploaded the file to GitHub:

🔹 **For debian based Linux:**  
🔗 [https://github.com/wachin/ttf-wps-fonts/releases/download/1.0/ttf-wps-fonts_1.0_all.deb](https://github.com/wachin/ttf-wps-fonts/releases/download/1.0/ttf-wps-fonts_1.0_all.deb)

🔹 **For rpm**  
🔗 [https://github.com/wachin/ttf-wps-fonts/releases/download/1.0/ttf-wps-fonts-1.0_all.rpm](https://github.com/wachin/ttf-wps-fonts/releases/download/1.0/ttf-wps-fonts-1.0_all.rpm)

🔹 **For others Linux**  
🔗 [https://github.com/wachin/ttf-wps-fonts/releases/download/1.0/ttf-wps-fonts_1.0.tar.gz](https://github.com/wachin/ttf-wps-fonts/releases/download/1.0/ttf-wps-fonts_1.0.tar.gz)

download the **tar.gz** file and extract it with right clic "**Extract here"**, then copy the folder to:  

📂 .fonts  

If this folder does not exist create it. To see hit Ctrl + H to show hidden directories.

---

## 3.) Install Chinese fonts

To work fine this WPS Office Chinese version neet the following fonts:  

- **batang.ttc**  
- **gulim.ttc**  
- **simfang.ttf**  
- **simhei.ttf**  
- **simkai.ttf**  
- **simsun.ttc**  
- **simsunb.ttf**  

📥 **Download it from GitHub:**  
🔗 [https://github.com/wachin/wps-office-all-mui-win-language/releases/download/v11.1.0.11704/wps-office-cn-fonts.7z](https://github.com/wachin/wps-office-all-mui-win-language/releases/download/v11.1.0.11704/wps-office-cn-fonts.7z)  

download the **.7z** file and extract it with right clic **"Extract here"**, then copy the folder to:  

📂 **~/.fonts** 

If this folder does not exist create it. To see hit **Ctrl + H** to show hidden directories.

---

## 4.) Install ibus  

This is necessary for special characters like accent marks on Spanish language to can be written, If you need, install with:

```bash
sudo apt install im-config ibus ibus-gtk ibus-gtk3
```

In some more modern Linux the following package goes 

```bash
ibus-gtk4
```

📌  After installed: **RESTART YOUR COMPUTER**

⚠️**Note**: If you don't start it it doesn't work.

---

## 5.) Install MUI (Multilingual User Interface)

The **MUI (Multilingual User Interface)** allows you to change the language of  **WPS Office Linux**

📥 **Download from GitHub:**  
🔗 [https://github.com/wachin/wps-office-all-mui-win-language/releases/download/v11.1.0.11704/mui.7z](https://github.com/wachin/wps-office-all-mui-win-language/releases/download/v11.1.0.11704/mui.7z)

After downloading the **.7z** file, unzip it and copy it to the following location:

📂 **~/.local/share/Kingsoft/office6**  

This folder is hidden. To show it, press **Ctrl + H** in your file explorer.  

⚠️ **Important:** The **Kingsoft/office6** folder will only appear after you have opened **WPS Office** for the first time. If you have just installed it and do not see the folder, **open and close the program** so that it is automatically generated.

📌 **This MUI contains:**

```
    Chinese (China)
    English (USA)
    English (United Kingdom)
    French
    French (Canada)
    German (Germany)
    Indonesian
    Japanese (Japan)
    Polish (Poland)
    Portuguese (Brazil)
    Portuguese (Portugal)
    Russian (Russian Federation)
    Spanish (Mexico)
    Spanish (Spain)
```

## 7.) Install spell checking dictionaries

📥 **Download from GitHub**:  
🔗 [https://github.com/wachin/wps-office-all-mui-win-language/releases/download/v11.1.0.11704/dicts.7z](https://github.com/wachin/wps-office-all-mui-win-language/releases/download/v11.1.0.11704/dicts.7z)

After downloading the **.7z** file, unzip it and copy it to the following location:

📂 **~/.local/share/Kingsoft/office6**  

⚠️ **Remember** This folder is hidden (hit **"Ctrl + H"** to see) and appear from the first time when you open **WPS Office Linux**, If you have just installed it and have not opened it, open and close it, then the hidden folder appear

📌 **This dicts contains the follow languages:**

```bat
af_ZA    African (South Africa)
be_BY    Belarusian (Belarus)
bg_BG    Bulgarian (Bulgaria)
bn_BD    Bengali (Bangladesh)
bs_BA    Bosnian (Bosnia and Herzegovina)
ca_ES    Catalan (Catalonia)
cs_CZ    Czech (Czech)
da_DK    Danish (Denmark)
de_DE    German (Germany)
el_GR    Greek (Greece)
en_AU    English (Australia)
en_GB    English (United Kingdom)
en_US    English (United States)
es_AR    Spanish (Argentina)
es_BO    Spanish (Bolivia)
es_CL    Spanish (Chile)
es_CO    Spanish (Colombia)
es_ES    Spanish (Spain)
es_MX    Spanish (Mexico)
es_PR    Spanish (Puerto Rico)
fr_FR    French (France)
gd_GB    Scots Gaelic (Great Britain)
gl       Galician (strict Volga)
gu_IN    Gujarati (India)
hi_IN    Hindi (India)
hr_HR    Croatian (Croatia)
hu_HU    Hungarian (Hungary)
id_ID    Indonesian
is       Icelandic
it_IT    Italian (Italy)
km_KH    Khmer (Cambodia)
lt_LT    Lithuanian (Lithuania)
ms_MY    Malay (Malaysia)
nb_NO    Norwegian (Norway)
ne_NP    Nepali (Nepal)
nl_NL    Dutch
pl_PL    Polish
pt_BR    Portuguese (Brazil)
pt_PT    Portuguese
qu_EC    Kichwa (Ecuador)
ro_RO    Romanian (Romania)
ru_RU    Russian (Russia)
sk_SK    Slovak (Slovakia)
sl_SI    Slovenian (Slovenia)
sq_AL    Albanian (Albania)
sr       Serbio
sv_SE    Swedish (Sweden)
sw_TZ    Swahili (Tanzania)
tr_TR    Turkish (Turkey)
uk_UA    Ukrainian (Ukraine)
vi_VN    Vietnamese (Vietnam)
```

---

Checking the button to change the language of WPS Office:

1. **Open WPS Office**
2. Click **"New Tab"**

![](vx_images/20231030-225131-WPS-Office-clic-create-new-tab.png)

3. Create a new document (Presentation, Excel or Document)

![](vx_images/20231030-225431-Create-a-new-empty-document.png)

4. The first time when you open the language switcher there is only two available:

![](vx_images/20231030-230201-the-first-time-when-you-open-the-language-switcher-there-is-only-two-available.png)

---

## 6.) Install the Fix language selector

The program has a file with incomplete code in:  

📂 **/opt/kingsoft/wps-office/office6/mui/lang_list/lang_list_community.json**  

To fix this, first backup the original file with the following command in the terminal:

```bash
sudo cp /opt/kingsoft/wps-office/office6/mui/lang_list/lang_list_community.json /opt/kingsoft/wps-office/office6/mui/lang_list/lang_list_community.json.backup
```

then replace the file with the one with the complete code:

```
wget -c https://github.com/wachin/wps-office-all-mui-win-language/releases/download/v11.1.0.11704/lang_list_community.json && sudo cp lang_list_community.json /opt/kingsoft/wps-office/office6/mui/lang_list/
```

📌 **What does this command do?**
1. Download the corrected file to your **HOME** folder.
2. Then, it will ask you for **superuser** permissions to copy it to the correct location within the system.

If you want to review its content before installing it, copy the line before && and paste it into a terminal and the file will be downloaded and you can open it with a text editor to review it, then use the full line.

For this fix to be visible it is necessary to restart WPS Office, but do not restart it yet, instead continue with the installation of the spell checking dictionaries and then restart it.

![](vx_images/20231030-231301-now-all-the-mui-are-present-to-switch-it.png)

⚠️ **Note:** When there is an update to the program and you have installed it, you must reapply the fix.

---



## 8.) Fix WPS Office fails to save as PDF

On some Linux distributions that use libtiff6 instead of libtiff5, such as:

**MX Linux 23 (Debian 12 based)**  
🔗 [packages.debian.org/libtiff6](packages.debian.org/libtiff6)

**Ubuntu 24.04**  
🔗 [packages.ubuntu.com/libtiff6](packages.ubuntu.com/libtiff6)

to save to PDF check if you has the package `libtiff6`, and if this is not true, install this with:
```
sudo apt install libtiff6
```
and is necesary create a symbolic link to simulate that this versión is libtiff5, to do that copy and paste in a terminal:

```
sudo ln -s /usr/lib/x86_64-linux-gnu/libtiff.so.6 /usr/lib/x86_64-linux-gnu/libtiff.so.5 
```
give Enter and Restart WPS Office, and try again.  

📌 **Why is this step necessary?**
WPS Office looks for version **libtiff5**, but on newer versions of Linux, only **libtiff6** is available. This command creates a **symlink** that makes the system "trick" WPS Office into using the available version.

---

## Origin of Dictionaries and MUI files
If any of you are wondering where I got the **dictionaries** and **MUI** from, it is in the following explanation, which although it has images in Spanish I think you should be able to understand it:

**Where is the files under PlayOnLinux**  
🔗 [https://github.com/wachin/wps-office-all-mui-win-language/blob/master/src/PlayOnLinux's%20virtual%20drives/Where%20is%20the%20files%20under%20PlayOnLinux.md](https://github.com/wachin/wps-office-all-mui-win-language/blob/master/src/PlayOnLinux's%20virtual%20drives/Where%20is%20the%20files%20under%20PlayOnLinux.md)

and read:

**Where is the files on Windows 8.1**  
🔗 [https://github.com/wachin/wps-office-all-mui-win-language/blob/master/src/C_Windows8.1/Where%20is%20the%20files%20on%20Windows%208.1.md](https://github.com/wachin/wps-office-all-mui-win-language/blob/master/src/C_Windows8.1/Where%20is%20the%20files%20on%20Windows%208.1.md)

---

# How to install WPS Office 2019 Linux 11.1.0.8392 (32 y 64 bit)
This version is possible not working on Linux from 2024, I tested fine in:

- **MX Linux 17 (Debian 9 Stretch)**  
- **MX Linux 19 (Debian 10 Buster)**  
- **MX Linux 21 (Debian 11 Bullseye)**  

📌 **Note**: Mx Linux is based on Debian. 

you can see the debian releases time in:  

🔗 [https://www.debian.org/releases/](https://www.debian.org/releases/)

📌 **Note:** WPS Office 2019 Linux 11.1.0.8392 (64 bit) also would be working fine in:  
- **Ubuntu 18.04**  
- **Ubuntu 20.04**  

---

## Download from MEGA:

📥 **WPS Office 64** y **32** bit + **ttf-wps-fonts**  
🔗 [https://mega.nz/folder/WhdGUCbD#AScUhE8HB_GI457CW2n3FQ](https://mega.nz/folder/WhdGUCbD#AScUhE8HB_GI457CW2n3FQ)

---

## Download from Telegram:

📥 **64 bits**  
🔗 [https://t.me/PFSLEE/10](https://t.me/PFSLEE/10)

📥 **32 bits**  
🔗 [https://t.me/PFSLEE/11](https://t.me/PFSLEE/11)

📥 **ttf-wps-fonts**  
🔗 [https://t.me/PFSLEE/13](https://t.me/PFSLEE/13)

📌 **Note:** You need extract the content with right clic and then extract here.  

---

## Follow only the next steps
To install WPS Office 11.1.0.8392 (32 or 64 bit) this working fine en:

📌 **is compatible with:**  
- **MX Linux 19 y 21**  
- **Debian 10 y 11**  
- **Ubuntu 20.04**  

⚠️ **But in the New versions of Linux is possible not working**  

To install it you need to follow some of the steps mentioned above:

```plaintext
## 2.) Install ttf-wps-fonts
## 3.) Install Chinese fonts
## 5.) Install MUI (Multilingual User Interface)
## 6.) Install the Fix language selector
## 7.) Install spell checking dictionaries
```

---

## ¡God Bless You!

---

# References

**I18n ibus**  
[https://wiki.debian.org/I18n/ibus](https://wiki.debian.org/I18n/ibus)

**WPS Converting to PDF error**  
[https://www.reddit.com/r/Ubuntu/comments/17ehukn/wps_converting_to_pdf_error/](https://www.reddit.com/r/Ubuntu/comments/17ehukn/wps_converting_to_pdf_error/)

**Wps Converting to pdf error**  
[https://www.reddit.com/r/Ubuntu/comments/17ehukn/wps_converting_to_pdf_error/](https://www.reddit.com/r/Ubuntu/comments/17ehukn/wps_converting_to_pdf_error/)

---