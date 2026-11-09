<div align="center">

# Awesome Iran Dev [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p><b>A curated toolbox for building software for Iranian and Persian-speaking users.</b></p>

<p>Jalali dates, Persian text, RTL UI, fonts, local payment gateways, SMS, maps, cloud and mirrors, and Persian AI, organized by language.</p>

[![Link check](https://github.com/meyshad/awesome-iran-dev/actions/workflows/links.yml/badge.svg)](https://github.com/meyshad/awesome-iran-dev/actions/workflows/links.yml)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)

**English** · [فارسی](#farsi)

</div>

Building a product for Iran means solving the same problems again and again: Shamsi calendars, `ي` vs `ی`, right-to-left layouts, Shaparak payment gateways, SMS OTP providers, local maps, and reaching package registries from inside the country. This list collects maintained, open-source, battle-tested solutions for each of them, so you can ship instead of reinventing.

Every entry is checked before it is added. Archived and abandoned projects are left out.

## Contents

- [Date and Calendar (Jalali / Shamsi)](#date-and-calendar-jalali--shamsi)
  - [JavaScript and TypeScript](#javascript-and-typescript)
  - [Date Pickers](#date-pickers)
  - [Python](#python)
  - [PHP and Laravel](#php-and-laravel)
  - [Go](#go)
  - [.NET](#net)
  - [Android](#android)
  - [Dart and Flutter](#dart-and-flutter)
- [Persian Text and Localization](#persian-text-and-localization)
- [RTL and UI](#rtl-and-ui)
- [Fonts](#fonts)
- [Payment Gateways](#payment-gateways)
- [Banking](#banking)
- [SMS and OTP](#sms-and-otp)
- [Maps and Geographic Data](#maps-and-geographic-data)
- [Cloud, Hosting and Mirrors](#cloud-hosting-and-mirrors)
- [AI and NLP](#ai-and-nlp)
- [Desktop and Daily Tools](#desktop-and-daily-tools)
- [Learning](#learning)

## Date and Calendar (Jalali / Shamsi)

### JavaScript and TypeScript

- [moment-jalaali](https://github.com/jalaali/moment-jalaali) - Jalaali calendar plugin for Moment.js.
- [jalali-moment](https://github.com/fingerpich/jalali-moment) - Parse, validate, manipulate and convert Jalali dates on top of Moment.js.
- [jalaali-js](https://github.com/jalaali/jalaali-js) - Tiny, dependency-free functions for converting between Jalaali and Gregorian.
- [date-fns-jalali](https://github.com/date-fns-jalali/date-fns-jalali) - The date-fns utility library adapted to the Jalali calendar.
- [jalaliday](https://github.com/alibaba-aero/jalaliday) - Jalali plugin for Day.js.
- [PersianDate](https://github.com/babakhani/PersianDate) - Parse, validate, manipulate and format Persian dates.

### Date Pickers

- [react-multi-date-picker](https://github.com/shahabyazdi/react-multi-date-picker) - React date picker with Persian, Arabic and Gregorian calendars, ranges and multiple selection.
- [react-modern-calendar-datepicker](https://github.com/Kiarash-Z/react-modern-calendar-datepicker) - Modern, customizable React date picker with Persian support.
- [react-native-ui-datepicker](https://github.com/farhoudshapouran/react-native-ui-datepicker) - Customizable React Native date picker with Jalali support.
- [vue3-persian-datetime-picker](https://github.com/talkhabi/vue3-persian-datetime-picker) - Jalali date and time picker for Vue 3.
- [ng-persian-datepicker](https://github.com/SaeedDev94/ng-persian-datepicker) - Persian date picker for modern Angular.
- [JalaliDatePicker](https://github.com/majidh1/JalaliDatePicker) - Lightweight, dependency-free Jalali date picker for any web page.
- [pwt.datepicker](https://github.com/babakhani/pwt.datepicker) - Jalaali date picker widget for jQuery.
- [MD.BootstrapPersianDateTimePicker](https://github.com/Mds92/MD.BootstrapPersianDateTimePicker) - Persian and Gregorian date time picker for Bootstrap.

### Python

- [jdatetime](https://github.com/slashmili/jdatetime) - Jalali calendar binding based on Python's `datetime` module.
- [persiantools](https://github.com/majiidd/persiantools) - Jalali dates plus Persian digit and character conversion.
- [khayyam](https://github.com/pylover/khayyam) - Jalali date and time library with time zone and DST support.
- [django_jalali](https://github.com/slashmili/django_jalali) - Jalali `DateField` and `DateTimeField` for Django models.
- [django-jalali-date](https://github.com/a-roomana/django-jalali-date) - Jalali date widgets and conversion for Django forms and admin.

### PHP and Laravel

- [morilog/jalali](https://github.com/morilog/jalali) - Work with Jalali dates in PHP and Laravel, Carbon style.
- [Verta](https://github.com/hekmatinasser/verta) - Jalali date toolkit for Laravel with validation and Carbon interop.

### Go

- [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - Persian (Solar Hijri) calendar implementation for Go.

### .NET

- [MD.PersianDateTime](https://github.com/Mds92/MD.PersianDateTime) - Use the Persian calendar as easily as `DateTime` in C#.
- [DNTPersianUtils.Core](https://github.com/VahidN/DNTPersianUtils.Core) - Persian date, number and text extension methods for .NET.

### Android

- [PersianDate](https://github.com/samanzamani/PersianDate) - Persian date library for Android.
- [PersianMaterialDateTimePicker](https://github.com/mohamad-amin/PersianMaterialDateTimePicker) - Material Design Shamsi date and time picker for Android.
- [Persian-Date-Picker-Dialog](https://github.com/aliab/Persian-Date-Picker-Dialog) - Persian date picker dialog for Android.

### Dart and Flutter

- [shamsi_date](https://github.com/FatulM/shamsi_date) - Jalali calendar conversion and formatting for Dart and Flutter.
- [persian-datetime-picker](https://github.com/M-amir-M/persian-datetime-picker) - Persian date and time picker for Flutter.
- [persian_number_utility](https://github.com/mehdi-nemati/persian_number_utility) - Number to Persian words, digit conversion and Jalali formatting for Dart.

## Persian Text and Localization

- [persian.js](https://github.com/usablica/persian.js) - Persian localization helpers: digits, Arabic characters, half-spaces and more.
- [virastar](https://github.com/brothersincode/virastar) - Clean up and normalize Persian text typography in JavaScript.
- [virastar.py](https://github.com/JKhakpour/virastar.py) - Python port of Virastar for Persian text normalization.
- [persian](https://github.com/mavihq/persian) - String and digit utilities for Persian text in Go.
- [PersianTools.Core](https://github.com/naeemaei/PersianTools.Core) - Shamsi dates, number to words, national code and bank card validation for .NET.
- [persian-tools-rs](https://github.com/rustland-fa/persian-tools-rs) - Collection of Persian language tools for Rust.
- [num2fawords](https://github.com/5j9/num2fawords) - Convert numbers to Persian words in Python.

## RTL and UI

- [RTLCSS](https://github.com/MohammadYounes/rtlcss) - Transform left-to-right CSS into right-to-left automatically.
- [postcss-rtlcss](https://github.com/elchininet/postcss-rtlcss) - PostCSS plugin that builds a single stylesheet with both LTR and RTL rules.
- [tailwindcss-rtl](https://github.com/20lives/tailwindcss-rtl) - Bidirectional utilities for Tailwind CSS.
- [stylis-plugin-rtl](https://github.com/styled-components/stylis-plugin-rtl) - RTL plugin for styled-components and Emotion, used for MUI RTL setups.
- [RTLTMPro](https://github.com/pnarimani/RTLTMPro) - Persian and Arabic RTL text for Unity TextMesh Pro.

## Fonts

- [Vazirmatn](https://github.com/rastikerdar/vazirmatn) - The most popular open-source Persian font, variable weights, OFL licensed.
- [Estedad](https://github.com/aminabedi68/Estedad) - Sans-serif Arabic-Latin typeface for UI and text.
- [Sahel](https://github.com/rastikerdar/sahel-font) - Clean Persian font for interfaces.
- [Mikhak](https://github.com/aminabedi68/Mikhak) - Mono-width, semi-handwritten Arabic-Latin typeface.
- [Lalezar](https://github.com/BornaIz/Lalezar) - Bold multi-script display typeface for headlines.
- [next-persian-fonts](https://github.com/amiryxe/next-persian-fonts) - Persian fonts packaged for `next/font`.
- [persian-fonts-linux](https://github.com/fzerorubigd/persian-fonts-linux) - Installer for Persian fonts on Linux.

## Payment Gateways

Shaparak IPG integrations for ZarinPal, IDPay, Mellat, Saman, Pasargad and others.

- [shetabit/payment](https://github.com/shetabit/payment) - Multi-driver payment package for Laravel.
- [shetabit/multipay](https://github.com/shetabit/multipay) - Framework-agnostic multi-driver payment package for PHP.
- [larabook/gateway](https://github.com/larabook/gateway) - Laravel package for connecting to Iranian bank gateways.
- [PoolPort](https://github.com/PoolPort/PoolPort) - PHP library that connects to Iranian payment gateways.
- [laravel-toman](https://github.com/evryn/laravel-toman) - Elegant IDPay and ZarinPal gateway for Laravel.
- [az-iranian-bank-gateways](https://github.com/ali-zahedi/az-iranian-bank-gateways) - Iranian bank gateways for Django.
- [Parbad](https://github.com/Sina-Soltani/Parbad) - Extensible library that connects ASP.NET apps to Iranian payment gateways.
- [monopay](https://github.com/cerpinn/monopay) - Node.js package for transactions across multiple Iranian gateways.
- [zarinpal-checkout](https://github.com/siamak/zarinpal-checkout) - JavaScript implementation of the ZarinPal API.
- [paygap](https://github.com/GoFarsi/paygap) - Go SDK for ZarinPal, IDPay, Pay.ir and more.
- [ZarinPal](https://www.zarinpal.com) - Widely used payment provider with developer APIs.

## Banking

- [az-iranian-bank-intro](https://github.com/ali-zahedi/az-iranian-bank-intro) - Calculate Sheba (IBAN) numbers and validate bank cards and Sheba numbers.
- [IranianBankLogos](https://github.com/amastaneh/IranianBankLogos) - Logos of Iranian banks in SVG and PNG for web and apps.

## SMS and OTP

- [Kavenegar SDKs](https://github.com/kavenegar) - Official clients for [Node.js](https://github.com/kavenegar/kavenegar-node), [Python](https://github.com/kavenegar/kavenegar-python), [PHP](https://github.com/kavenegar/kavenegar-php), [Laravel](https://github.com/kavenegar/kavenegar-laravel), [Go](https://github.com/kavenegar/kavenegar-go) and [.NET](https://github.com/kavenegar/kavenegar-dotnet).
- [tzsk/sms](https://github.com/tzsk/sms) - Laravel SMS package with drivers for several Iranian providers.
- [Kavenegar](https://kavenegar.com) - SMS, OTP and voice call API.
- [Ghasedak](https://ghasedak.me) - SMS and OTP API.
- [SMS.ir](https://sms.ir) - Bulk SMS and verification code API.

## Maps and Geographic Data

- [Neshan Platform](https://platform.neshan.org) - Maps, search, routing and geocoding APIs for Iran.
- [Map.ir](https://map.ir) - Iranian map tiles and location APIs.
- [react-neshan-map-leaflet](https://github.com/NeshanMaps/react-neshan-map-leaflet) - React component for Neshan maps with Leaflet.
- [iran-cities](https://github.com/ahmadazizi/iran-cities) - Database of provinces, counties, cities and villages of Iran.
- [list-of-cities-in-Iran](https://github.com/sajaddp/list-of-cities-in-Iran) - Up-to-date provinces and cities in JSON, SQL and more.
- [typhoon-iran-cities](https://github.com/SaliBhdr/typhoon-iran-cities) - Import Iranian provinces, counties and cities into Laravel.

## Cloud, Hosting and Mirrors

### Cloud and PaaS

- [ArvanCloud](https://www.arvancloud.ir) - CDN, cloud servers, object storage and container platform.
- [Liara](https://liara.ir) - Platform as a service for deploying apps and databases ([docs](https://docs.liara.ir)).
- [Hamravesh](https://hamravesh.com) - Kubernetes-based PaaS and managed services.
- [Runflare](https://runflare.com) - PaaS for apps, databases and object storage.
- [Chabokan](https://chabokan.net) - PaaS with one-click apps and databases.
- [Abrha](https://abrha.net) - Cloud servers and infrastructure.

### Mirrors

Package and image registries that are reachable from inside Iran.

- [ArvanCloud Docker mirror](https://docker.arvancloud.ir) - Docker Hub registry mirror.
- [Focker](https://focker.ir) - Docker Hub registry mirror.
- [HamDocker](https://hub.hamdocker.ir) - Docker Hub mirror by Hamravesh.
- [Runflare Linux mirror](https://mirror-linux.runflare.com) - Mirror for popular Linux distributions.
- [iran-docker](https://github.com/Linuxmaster14/iran-docker) - Bash script that sets up Docker to work with Iranian mirrors.
- [irdocker](https://github.com/matinsoleymni/irdocker) - Check which Iranian Docker mirrors have a given image.

## AI and NLP

- [Hazm](https://github.com/roshan-research/hazm) - The standard Persian NLP toolkit: normalization, tokenization, POS tagging and more.
- [Hezar](https://github.com/hezarai/hezar) - All-in-one Persian AI library with ready models for text, speech and vision.
- [ParsBERT](https://github.com/hooshvare/parsbert) - Transformer language model for Persian understanding.
- [Parsivar](https://github.com/ICTRC/Parsivar) - Persian language processing toolkit.
- [DadmaTools](https://github.com/Dadmatech/DadmaTools) - Persian NLP pipeline with modern models.
- [Shekar](https://github.com/amirivojdan/shekar) - Persian NLP for modern applications.
- [persian-stopwords](https://github.com/kharazi/persian-stopwords) - Persian stop word lists.
- [speech2text](https://github.com/shenasa-ai/speech2text) - Deep learning Persian speech recognition.
- [ManaTTS](https://github.com/MahtaFetrat/ManaTTS-Persian-Speech-Dataset) - Large open Persian speech dataset for text to speech.
- [iran-mcp](https://github.com/sepehr071/iran-mcp) - MCP servers that give AI agents access to Iranian web services.

## Desktop and Daily Tools

- [Persian Calendar](https://github.com/persian-calendar/persian-calendar) - Open-source Persian calendar app for Android.
- [gnome-shamsi-calendar](https://github.com/SCR-IR/gnome-shamsi-calendar) - Shamsi calendar extension for the GNOME desktop.
- [windows-persian-keyboard-for-linux](https://github.com/sinadarvi/windows-persian-keyboard-for-linux) - Windows-style Persian keyboard layout for Linux.
- [Time.ir](https://www.time.ir) - Official Iranian calendar with holidays and events.

## Learning

- [free-resources](https://github.com/barnamenevisi/free-resources) - Free programming learning resources in Persian.

## Related Lists

- [APIs made in Iran](https://github.com/Hameds/APIs-made-in-Iran) - Public APIs from Iranian services.
- [made-in-iran](https://github.com/mohebifar/made-in-iran) - Cool open-source projects made in Iran.
- [awesome-persian](https://github.com/rastikerdar/awesome-persian) - Persian links for development and design.
- [awesome-persian-nlp-ir](https://github.com/mhbashari/awesome-persian-nlp-ir) - Persian NLP and information retrieval resources.
- [awesome-Iran-datasets](https://github.com/MEgooneh/awesome-Iran-datasets) - Iranian and Persian datasets.
- [awesome-Persian-Speech](https://github.com/karim23657/awesome-Persian-Speech) - Persian speech datasets, models and tools.
- [awesome-iran-remote](https://github.com/iranremote/awesome-iran-remote) - Remote-friendly companies hiring Iranian developers.
- [awesome-persian-blogs](https://github.com/ohmydevops/awesome-persian-blogs) - Persian blogs in many fields.

---

<div dir="rtl" align="right">

<a id="farsi"></a>
<h3>فارسی</h3>

**Awesome Iran Dev** یک فهرست دست‌چین‌شده از ابزارها، کتابخانه‌ها و سرویس‌هایی است که برای ساختن نرم‌افزار برای کاربران ایرانی و فارسی‌زبان لازم دارید: تاریخ شمسی، پردازش متن فارسی، رابط کاربری راست‌چین، فونت، درگاه پرداخت، پیامک، نقشه، سرویس‌های ابری و آینه‌های داخلی، و هوش مصنوعی فارسی.

همه‌ی موارد قبل از اضافه شدن بررسی می‌شوند و پروژه‌های بایگانی‌شده یا رهاشده در این فهرست نیستند.

**مشارکت:** اگر ابزار خوبی می‌شناسید، با خواندن راهنمای مشارکت (فایل contributing.md) یک Pull Request بفرستید. اگر این فهرست به کارتان آمد، با دادن ⭐ به دیده‌شدنش کمک کنید.

</div>

## Contributing

Contributions are welcome. Please read the [contribution guidelines](contributing.md) first.
