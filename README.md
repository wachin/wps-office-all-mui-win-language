# wps-office-all-mui-win-language

In 2023, the Chinese software company Kingsoft Office, which developed WPS Office, released an update with many improvements for Linux available for 64-bit computers; These are the steps so you can install it. You can ask me any questions by email: wachin.id@gmail.com

## Tutorial en español

Este tutorial está disponible en español aquí:

**WPS Office 2019 versión 11.1.0.11711 actualización 2023 para Linux**   
https://facilitarelsoftwarelibre.blogspot.com/2023/11/wps-office-2019-version-11.1.0.11704-actualizacion-2023.html.html

# This tutorial working in WPS Office 2019 Linux version 11.1.0.11711 Update 2023

This tutorial works on WPS Office 2019 Linux version 11.1.0.11711 update 2023 that brings the four programs:

Writer
Presentation
Spreadsheet
PDF

in the same window:

![](vx_images/20240212-080056-WPS-Office-11.1.0.11711-amd64.png)

Tested in:

- [Linux Mint 21 Vanessa](https://linuxmint.com/edition.php?id=299) ([base Ubuntu 22.04 Jammy](https://www.linuxmint.com/mirrors.php))
- [Q4OS 4 Gemini](https://www.q4os.org/downloads3.html), Trinity (64 bit, base [Debian 11 Buslleye](https://packages.debian.org/bullseye/))
- [MX Linux 21](https://mxlinux.org/) (64 bit, base [Debian 11 Buslleye](https://packages.debian.org/bullseye/)) 

# DOWNLOAD

You must download the Chinese version because it has the language switcher button enabled:

![](vx_images/20231030-223216-WPS-Office-button-in-11.1.0.11704.png)



**WPS Linux 12.1 problems with language switcher button missing:**   

[https://www.wps.cn/product/wpslinux](https://www.wps.cn/product/wpslinux)

At this time 2024-12-19 not working the language switcher button  in 12.1 WPS Linux version, but the previous version does work



# Mirror for Download WPS Office Linux 11 versions

**Ubuntukylin Archive mirror**  

[https://mirrors.163.com/ubuntukylin/pool/partner/](https://mirrors.163.com/ubuntukylin/pool/partner/) 

![](vx_images/20240211-224433-Varias-versiones-de-WPS-Office-en-ubuntukylin.com.png)

Additionally, if you wish to use the WPS Office 2019 Linux version 11.1.0.11704, which has each program separately, as shown in the following screenshot:

![](vx_images/20231116_WPS_Office_Linux_11.1.0.11704_Portada.png)

In that list of Ubuntu Kylin above you can download it:

![](vx_images/20240211-224433-WPS-Office-2019-Linux-version-11.1.0.11704-ubuntukylin.com.png)



and I have also uploaded the deb to my accounts at:

**MEGA**  
The following link is a mirror that I have uploaded in case the other downloads fail:

https://mega.nz/folder/s6AQHSzC#Kd8qbA-Z7yeTa2P5qcVG3w

**Telegram** 

https://t.me/c/1343202595/14


# ttf-wps-fonts

These are the symbol fonts required by wps-office. They are used to display math formulas. 

**Download**

**From Deepin Linux Packages:**

https://packages.deepin.com/deepin/pool/non-free/t/ttf-wps-fonts/

download the deb file ans install it.

Or from a backup that I made:

**For debian based Linux:**  
https://github.com/wachin/ttf-wps-fonts/releases/download/1.0/ttf-wps-fonts_1.0_all.deb

**For rpm**  
https://github.com/wachin/ttf-wps-fonts/releases/download/1.0/ttf-wps-fonts-1.0_all.rpm

**For others Linux**  
https://github.com/wachin/ttf-wps-fonts/releases/download/1.0/ttf-wps-fonts_1.0.tar.gz

download the tar.gz file and extract it with right clic "Extract here", then copy the folder to:  

.fonts  

If this folder does not exist create it. To see hit Ctrl + H to show hidden directories.

# About the warning "This type of file can damage your computer. Do you want to download ... deb anyway?"
That message is a general warning that appears when downloading executable files, such as `.deb` files on Linux systems. `.deb` files contain installable packages, and if they come from untrusted sources, they could potentially contain malicious software that could damage your system or compromise its security.

The warning does not necessarily mean that the file you are downloading is dangerous, but rather that you should be careful and make sure it comes from a trusted source. It is important to verify the authenticity and provenance of the file before installing it, especially if you are not downloading it from the official repositories of your Linux distribution.

You can also upload it to: https://virustotal.com to check its Reliability


# Chinese fonts

To work fine this WPS Office Chinese version neet the following fonts:  

batang.ttc  
gulim.ttc  
simfang.ttf  
simhei.ttf  
simkai.ttf  
simsun.ttc  
simsunb.ttf    


Download it from:  

https://github.com/wachin/wps-office-all-mui-win-language/releases/download/v11.1.0.11704/wps-office-cn-fonts.7z  

download the .7z file and extract it with right clic "Extract here", then copy the folder to:  

.fonts  

If this folder does not exist create it. To see hit Ctrl + H to show hidden directories.

# Install ibus  

This is necessary for special characters like accent marks on Spanish language to can be written in this version 11.1.0.11704, If you need, install with:

	sudo apt install im-config ibus ibus-gtk ibus-gtk3

In some more modern Linux the following package goes 

```
 ibus-gtk4
```

after installed:

**RESTART YOUR COMPUTER**

**Note**: If you don't start it it doesn't work.



# Install MUI
MUI (Multilingual User Interface) for WPS Office Linux version 2019

Download from:

https://github.com/wachin/wps-office-all-mui-win-language/releases/download/v11.1.0.11704/mui.7z

and paste to:

.local/share/Kingsoft/office6

This folder is hidden (hit "Ctrl + H" to see) and appear from the first time when you open WPS Office Linux, If you have just installed it and have not opened it, open and close it, then the hidden folder appear

then extract there with right clic

This MUI contains:

```bat
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
<br />

to see the button to switch language, when you open WPS Office give clic in:

**New tab**

![](vx_images/20231030-225131-WPS-Office-clic-create-new-tab.png)

then create a new empty document: Presentation, Excel or Document:

![](vx_images/20231030-225431-Create-a-new-empty-document.png)

the first time when you open the language switcher there is only two available:

![](vx_images/20231030-230201-the-first-time-when-you-open-the-language-switcher-there-is-only-two-available.png)

# Install the Fix language selector

The program has a file with incomplete code in:  

/opt/kingsoft/wps-office/office6/mui/lang_list/lang_list_community.json  

To fix it, firt create a backup of that file with:


```
sudo cp /opt/kingsoft/wps-office/office6/mui/lang_list/lang_list_community.json /opt/kingsoft/wps-office/office6/mui/lang_list/lang_list_community.json.backup
```

then replace the file with the one with the complete code:

```
wget -c https://github.com/wachin/wps-office-all-mui-win-language/releases/download/v11.1.0.11704/lang_list_community.json && sudo cp lang_list_community.json /opt/kingsoft/wps-office/office6/mui/lang_list/
```

What that line does is download the file that I have prepared to your HOME and from there it will ask you to be a super user to copy it to the corresponding place in WPS Office in the system, if you want to review its content there it will be downloaded to your HOME, you can open with a text editor.

when you restart WPS Office (don't do it yet until you install the spell checking dictionaries), repeat the steps to open the language switcher, then working:

![](vx_images/20231030-231301-now-all-the-mui-are-present-to-switch-it.png)

**Note:** When there is an update to the program and you have installed it, you must reapply the fix, the instruction in the 2nd step. (Well, in the future, at some point of the program code development it may change and this tutorial will no longer be useful, but up to version 11.1.0.11711 works)


# Install spell checking dictionaries

Download from:

https://github.com/wachin/wps-office-all-mui-win-language/releases/download/v11.1.0.11704/dicts.7z

and paste to:

.local/share/Kingsoft/office6

This folder is hidden (hit "Ctrl + H" to see) and appear from the first time when you open WPS Office Linux, If you have just installed it and have not opened it, open and close it, then the hidden folder appear

then extract there with right clic

This dicts contains the follow languages:

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

<br />

## Origin of Dictionaries and MUI files
If any of you are wondering where I got the dictionaries from, it is in the following explanation, which although it has images in Spanish I think you should be able to understand it:

**Where is the files under PlayOnLinux**
https://github.com/wachin/wps-office-all-mui-win-language/blob/master/src/PlayOnLinux's%20virtual%20drives/Where%20is%20the%20files%20under%20PlayOnLinux.md

and read:

**Where is the files on Windows 8.1**
https://github.com/wachin/wps-office-all-mui-win-language/blob/master/src/C_Windows8.1/Where%20is%20the%20files%20on%20Windows%208.1.md

# WPS Office 2019 Linux version 11.1.0.8392 (32 y 64 bit)

You can download it for older machines from:

**packages.deepin.com**

http://packages.deepin.com/deepin/pool/non-free/w/wps-office-2019/

![](vx_images/20231030-231929-download-wps-office-2019-11.1.0.8392-from-packages-deepin.com.png)


https://packages.deepin.com/deepin/pool/non-free/w/wps-office-2019/

Also mirrors I upload: 

**MEGA:**

**WPS Office 64** y **32** bit + **ttf-wps-fonts**
https://mega.nz/folder/WhdGUCbD#AScUhE8HB_GI457CW2n3FQ

**Download from Telegram:**

64 bits
**https://t.me/PFSLEE/10**

32 bits
**https://t.me/PFSLEE/11**

ttf-wps-fonts
**https://t.me/PFSLEE/13**

**Note:** You need extract the content with right clic and then extract here.

# The WPS Office working (screenshot)

Working:

![](vx_images/20231030-233430-wps-office-11.1.0.11704-Update-2023-working-in-mint-21.png)

God Bless You


### References

**I18n ibus**  
https://wiki.debian.org/I18n/ibus
