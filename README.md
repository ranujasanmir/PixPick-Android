
![PixPick Logo](./img/pixpick.png)

# PixPick Android - A GUI Manga, Manhua, Manhwa and Comic Downloader For Android Devices

**Click here to Download Latest Version:**

[![Download Now](./img/dwn.png)](https://github.com/ranujasanmir/PixPick-Android/releases/download/V1.0/PixPick_Manga_Downloader_1.0.apk)

### Important Note

This app is a android version of original windows application. You can also download Windows Version [here.](https://github.com/ranujasanmir/PixPick).

#### Liability and License Notice
PixPick and its maintainers cannot be held liable for misuse of this application, as stated in the [MIT license](https://github.com/ranujasanmir/PixPick/blob/main/LICENSE).
The maintainers of PixPick do not in any way condone the use of this application in practices that violate the Terms of Service of web apps that allow to read comics (From now on we represent Manga, Manhua, Manhwa and any others using comics). The maintainers of this application call upon the personal responsibility of its users to use this application in a fair way, as it is intended to be used.
##

PixPick does not require Selenium or any other browser to be interface with web pages, it does so directly using a **http requests**. 
Also some web pages blocking http requests. So you cannot download content from that sites.
 
## Please Read

This is the only official repository for android app and is maintained by the community.
 **Contact the Main Developer [here](https://t.me/PixCap_Support)**

**_`PixPick Downloader` is a GUI software that allow users to download Manga, Manhua, Manhwa, Comics and etc for read offline on mobile_**

## Table of Contents

- [Installation](#installation)
- [Update](#update)
- [System Requirements](#system-requirements)
- [How To Use](#how-to-use)
  - [Home](#home)
  - [Features](#features)
  - [Templates](#templates)
    - [Create Your Own Templates](#create-templates)
- [Terms And Condition](#terms-and-condition)
- [License](#license)
- [About Us](#about-us)

## Installation

To download go to [release](https://github.com/ranujasanmir/PixPick-Android/releases) and select any version that suitable for your system(Recommended to download latest version):

You can install PixPick as installing other apps.

## Update

**How to Update:**

You can update PixPick by downloading and installing new version. Maybe in new versions GUI can be changed. But new versions have new features. So updating is at your own decision. Download latest application from [PixPick](https://github.com/ranujasanmir/PixPick-Android/releases).

## System Requirements

**Following system Requirements are used to test PixPick. Keep in mind that you can run PixPick even with the lower specs than these.**

> Android System : Android 7+ (Universal arch supporting)

> Architecture : All

> Others : You need good internet connection

## How To Use

**How to use:**

PixCap UI (In v1.0) :
![PixPick Home](./img/1.png)

![PixPick Templates](./img/2.png)

![PixPick While Downloading](./img/3.png)

To use PixPick you must have direct URLs to the each chapters. You can download chapter by chapter or can use bulk downloader.

Paste your URL inside the textbox at top of the application. You can also add mutiple URLs to it by seperating each one by comma.

```
https://example.com/manga-name/chapter-1, https://example.com/manga-name/chapter-2, https://example.com/manga-name/chapter-3
```

PixPick will automatically download images into the `Downloads/PixPick Downloader` and inside the specific folder for each manga and chapters.

If you give `Keywords`, PixPick will only download images with the keywords you have provided. For example:

Imagine that page has two images with following links,

```
https://example.com/wp-content/manga-images/image1.png
```
```
https://example.com/wp-content/images/logo.png
```

First link is one of image URL in manga chapter. But second one is web site logo. As you can see first link has keyword 'manga' inside it. But second image not have it. If you enable `Keywords`, and add 'manga' keywords PixPick only download images that has `manga` as a keywords.

**Keep in mind:**

Usually comic images has width more than 500 pixels in every comic sites. PixPick will automatically skipping images that has width lower than 500 pixels. In next Filtering option you can adjust the pixel limit according to the you likes. But make sure to check width and height in comic images before adding it.

Next is you can select image saving file format. If you select any of available optionPixPick will save all images in that file format.

### Features

**Easily download full chapters:**
PixPick allow you to download each chapter without Long-Click -> Save as Image in browser!

**Bulk download:**
No need to manually visit every page. Just paste all links to download seperated by comma, PixPick will download all chapters you entered!

**Filtering Options:**
PixPick give filtering options to adjust. So you don't miss any chapter images!

**Convert image format while downloading:**
PixPick saves downloaded images in the original format. But no worries. In android, you can open lot of image file formats in default.

### Templates

> Templates will allow you to simply setup filtering options for specific comic pages. If you select any template available you can download comics from that site without editing filtering options.

#### Create Templates

> You can also create your own templates and submit to us. Configuration for Templates are following:

```json
{
  "name": "example.com", // Add name of the site yu creating template for.
  "keywords": ["manga"], // Add keywords. These are the links keyword in <img src="#"> as mentioned earliar.
  "min_width": 600 // This is the minimum width of manga image.
},
{
  "name": "example.com",
  "keywords": [], // In this site it dosen't need keywords to download manga images. Its downloading all images that width higher than min_width.
  "min_width": 600
}
```

> We are glad to host your templates on our official server. Send your templates to us: [On Telegram](https://t.me/PixCap_Support)

## Terms And Condition

1. **User Responsibly**: PixPick is developed for only personal usage. For other usage you have to ask permission from comics sites maintainers.

2. **Security**: PixPick is 100% safe. It will only connect with our server and comic sites web servers only. No your data will be collected or shared. PixPick will automatically checking update by requesting our server. 

3. **Privacy Policy**: We didn't have privacy policy for PixPick for now. But you have to agree with comic sites privacy policies before download them.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/ranujasanmir/PixPick/LICENSE) file for details.

## About Us

We are PixCap Soft. We are from Sri Lanka! We are intended to build modern day solutions for make this world better...

**Copyright © 2020-2025 PixCap Soft.**
**All rights Reserved.**


