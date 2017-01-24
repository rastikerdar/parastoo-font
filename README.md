<h1 id="parastoo-font">Parastoo Font</h1>
<p>A Persian (Farsi) Font</p>
<p dir="rtl">فونت (قلم) فارسی پرستو</p>
<p dir="rtl">
<a href="http://rastikerdar.github.io/parastoo-font/">نمایش فونت</a> <br />
<a href="https://github.com/rastikerdar/parastoo-font/releases">صفحه دریافت (دانلود) بسته فونت شامل فایل های ttf,woff,eot</a> <br />
</p>
<p dir="rtl">با تشکر از برنامه <a href="https://fontforge.github.io">FontForge</a></p>
<p dir="rtl">بر مبنای فونت <a href="http://rastikerdar.github.io/gandom-font/" dir="rtl">گندم</a></p>
<h2 id="-" dir="rtl">طریقه استفاده در صفحات وب:</h2>
<div lang="fa" dir="rtl">
کد زیر را در قسمت style یا فایل css وارد نمایید:
</div>


```css
@font-face {
  font-family: Parastoo;
  src: url('Parastoo.eot');
  src: url('Parastoo.eot?#iefix') format('embedded-opentype'),
       url('Parastoo.woff') format('woff'),
       url('Parastoo.ttf') format('truetype');
  font-weight: normal;
}

@font-face {
  font-family: Parastoo;
  src: url('Parastoo-Bold.eot');
  src: url('Parastoo-Bold.eot?#iefix') format('embedded-opentype'),
       url('Parastoo-Bold.woff') format('woff'),
       url('Parastoo-Bold.ttf') format('truetype');
  font-weight: bold;
}
```

## Install
####Arch Linux

Arch user's could use [parastoo-fonts](https://aur.archlinux.org/packages/parastoo-fonts/) package from [AUR](https://aur.archlinux.org/) repository to install parastoo font. Use your favourite [AUR helper](https://wiki.archlinux.org/index.php/AUR_helpers) like pacaur or yaourt for installing package:

```shell
pacaur -S parastoo-fonts
```
