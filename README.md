# Parastoo-Font
A Persian (Farsi) Font

فونت فارسی پرستو  
[نمایش فونت - صفحه رسمی پروژه](http://rastikerdar.github.io/parastoo-font/)  
[صفحه دریافت (دانلود) بسته فونت شامل فایل های ttf,woff,eot](https://github.com/rastikerdar/parastoo-font/releases)  
با تشکر از برنامه [FontForge](https://fontforge.github.io)  
نسخه‌های مخصوص چاپ، بدون حروف لاتین و تمام ارقام فارسی درون بسته فشرده موجود می‌باشد.  
فرآیند تولید بسته نهایی شامل انواع نسخه‌ها و فرمت‌ها توسط ابزار [fontbuilder](https://github.com/rastikerdar/fontbuilder) انجام می‌شود.

## نمونه متن Sample:
![Parastoo font sample](./sample.png)

## طریقه استفاده در صفحات وب:
<div lang="fa" dir="rtl">
کد زیر را در قسمت style یا فایل css وارد نمایید:
</div>


```css
@font-face {
  font-family: Parastoo;
  src: url('Parastoo.eot');
  src: url('Parastoo.eot?#iefix') format('embedded-opentype'),
       url('Parastoo.woff2') format('woff2'),
       url('Parastoo.woff') format('woff'),
       url('Parastoo.ttf') format('truetype');
  font-weight: normal;
}

@font-face {
  font-family: Parastoo;
  src: url('Parastoo-Bold.eot');
  src: url('Parastoo-Bold.eot?#iefix') format('embedded-opentype'),
       url('Parastoo-Bold.woff2') format('woff2'),
       url('Parastoo-Bold.woff') format('woff'),
       url('Parastoo-Bold.ttf') format('truetype');
  font-weight: bold;
}
```

## Install
#### Arch Linux

Arch user's could use [parastoo-fonts](https://aur.archlinux.org/packages/parastoo-fonts/) package from [AUR](https://aur.archlinux.org/) repository to install parastoo font. Use your favourite [AUR helper](https://wiki.archlinux.org/index.php/AUR_helpers) like pacaur or yaourt for installing package:

```shell
pacaur -S parastoo-fonts
```

2016 Saber Rastikerdar ([@rastikerdar](https://github.com/rastikerdar)). See the `LICENSE` file.
