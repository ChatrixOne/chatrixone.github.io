---
title: Как да премахнем Google от личния ни живот?
date: 2024-04-22 13:30:00 +0300
categories: [Публикации, Инструкции]
tags: [android,андроид,google,гугъл,DeGoogle,privacy,лично пространство]
img_path: /assets/img/posts_images/degoogle-your-life/
pin: false
image:
  path: degoogle.jpg
  width: 800
  height: 500
  alt: Нямам какво да крия, но нямам и какво да ти покажа Google!
---

## От къде се идва понятието **deGoogle**?

**Google** е толкова разпространен, че името му е едновременно съществително и глагол. Но дали **Google** е нещо добро? През 2002г., отговорът беше категорично "ДА". Гаголът ***google*** беше избран за дума на годината от **American Dialect Society**!

Превъртете бързо напред към днешна дата и има вече нов глагол: ***deGoogle***. Това е актът да се отървете от всичко, свързано с **Google**.

## Защо бихме желали да премахна Google от нашия живот?

1. **Google** знае твърде много за нас!
От историята на местоположенията, през камерите на звънеца, нещата които търсим онлайн, та чак до всички теми от които се интересуваме. Всичко се проследява и записва!

2. **Google** използва тези данни, за да ни монетизира.
Това означава, че ние сме продуктът, а не клиентът, дори когато си плащаме.

3. **Google** работи с правителството като част от програмата за наблюдение **PRISM**!
Това означава, че те могат да споделят личните ни данни без нашето съгласие.

4. **Google** има лоша политика за защита на поверителността на потребителите.
**Google** събира много повече лични данни, отколкото някой може да си представи. Още по-лошо е, че не винаги е ясно кой има достъп и за какво се използват всички тези данни. Това, което знаем, че събират включва:

- Документи, които съхранявате в облака;
- Използвани приложения;
- История на търсенията;
- Взаимодействия с реклами;
- Нашите имейли;
- Видеоклипове, които гледаме;
- Къде сме били (данните от **GPS**);
- Информация за други устройства в близост до нас.

![Data Harvesting](data_harvesting.gif){: .shadow }
_Източник: Digital Content Next –  Prof. Douglas C. Schmidt, Vanderbilt University, August 2018_

Изводът е, че **Google** знае повече за нас, отколкото ние самите знаем за себе си! По подразбиране всички тези данни се запазват за неопределено време.

Със сигурност това са сериозни причина да премахнем **Google** от нашия живот.

## Устройства

Колкото и парадоксално да звучи, най-подходящи устройства са тези произведени от самите **Google** и по точно серията **Pixel**. В повечето случаи те не са заключени, а и софтуерът за външна намеса е добре документиран.

### Кои устройства да избягваме

- Брандирани от мобилен оператор;
- Без достъп до **fastboot** или изискващи създаване на акаунт;
- Притежаващи по-малко от **6GB** оперативна памет - **RAM**;
- Притежаващи по-малко от **64GB** вградена памет;
- Батерия с капацитет по-малко от **2000mAh**;
- Произведени преди 2017г.;
- Процесор различен от **Qualcomm/Tensor SoC**, например - **MediaTek/Exynos/Tegra/OMAP**;
- С версия на ядрото преди 4.4.

### Препоръчителни характеристики

- Оперативна памет (**RAM**) - поне **8GB**;
- Вградена памет - поне **128GB**;
- Процесор **SD845 SoC** или по-нов;
- Версия на ядрото 4.9 или по-нова.

### Препоръчителни устройства

- **Google Pixel 6a**;
- **Google Pixel 5a**;
- **Google Pixel 4**;
- **Google Pixel 4a**;
- **Google Pixel 3a**
- **Google Pixel 2 XL**;
- **Google Pixel 2**.

> **Внимание!
>
> ***Нито едно*** от посочените по-долу устройства не отговаря на вече изброените изисквания!
> **Google Pixel C (dragon)**
> **Google Nexus 9 (flounder)**
> **Google Nexus 7 2013 (flox)**
{: .prompt-warning }

## ОПЕРАЦИОННИ СИСТЕМИ

### DivestOS

***A mobile operating system divested from the norm. "take back (some) control of your device"***

Разработва се от 2014г. Основна цел на проекта е, удължаването на живота на устройства, за които производителите вече не предлагат актуализации. Сигурността също е приоритет.

> **Пример:**
> **Google Pixel 2XL (taimen)** - произведен 2017г., официално е поддържан от **Google** до декември 2020г., с Андроид версия 11.
> Благодарение на **DivestOS**, през 2024г. телефонът продължава да получава актуализации и работи безпроблемно под Андроид 13.

**DivestOS** предоставя опция за блокиране на достъпа до камерата и микрофона чрез едно докосване. Устройството е криптирано по подразбиране. С цел по-голяма сигурност, след инсталиране имате възможност да заключите отново **Bootloader**-а на устройството. Актуализациите са ежемесечни.

- [Уеб сайт](https://divestos.org/)
- [Инструкции](https://divestos.org/pages/bootloader)
- [Поддържани устройства](https://divestos.org/pages/devices)
- [Сорс код в Github](https://github.com/divested-mobile)
- [Сорс код в Gitlab](https://gitlab.com/divested-mobile)
- [Сорс код в Codeberg](https://codeberg.org/divested-mobile)

### GrapheneOS

***The private and secure mobile operating system with Android app compatibility. Developed as a non-profit open source project.***

Ако поставяте сигурността на първо място, вероятно **GrapheneOS** е най-добрият избор за Вас! Разработчикът се е постарал да премахнат всичко излишно от основния инсталационен пакет. Целта е, по този начин да намали полето за изява на голям набор от хакерски атаки.

- [Уеб сайт](https://grapheneos.org/)
- [Видео презентация](https://youtu.be/yIZmUINSvQ4?feature=shared)
- [Инструкции](https://grapheneos.org/install/)
- [Поддържани устройства](https://grapheneos.org/releases)
- [Сорс код в Github](https://github.com/GrapheneOS)

### CalyxOS

***Your Phone Should Be Private. Everyone needs a phone. Not everyone wants to be spied on. Reclaim your privacy with CalyxOS.***

Операционната система се разработва от **Calyx Institute**. Тук също фокусът е върху защита на личното пространство и сигурността.

- [Уеб сайт](https://calyxos.org/)
- [Видео презентация](https://youtu.be/qTtgzNGRAfA?feature=shared)
- [Инструкции](https://calyxos.org/docs/guide/getting-started/)
- [Поддържани устройства](https://calyxos.org/docs/guide/device-support/)
- [Сорс код в GitLab](https://gitlab.com/CalyxOS)

### /e/OS

***Your data is YOUR data! We build desirable, open source, privacy-enabled smartphone operating systems.***

Основната идея на проекта е освен операционна система, да предлага и онлайн услуги, целящи защита на личното пространство. Проектът **/e/OS** е получил академично признание, от изследователи от Университета в Единбург и Тринити Колидж в Дъблин.

- [Уеб сайт](https://e.foundation)
- [Видео презентация](https://youtu.be/aNjnMEMWMLY?feature=shared)
- [Инструкции](https://doc.e.foundation/devices)
- [Поддържани устройства](https://doc.e.foundation/devices)
- [Сорс код в GitLab](https://gitlab.e.foundation/e)

### iode

***Take back control of your data. Combine Open Source, Security, and Sustainability, right in your hands.***

По-различното при този проект е, че предлага закупуването на устройства с предварително инсталирана **iode** операционна система. Отново е фокусирана върху защита на сигурността и личното пространство. Предлага още вграден родителски контрол и защита от тракери.

- [Уеб сайт](https://iode.tech/)
- [Видео презентация](https://youtu.be/ujJciKxvn6g?feature=shared)
- [Инструкции](https://iode.tech/iodeos-installation/)
- [Поддържани устройства](https://iode.tech/iodeos-installation/)
- [Сорс код в Github](https://gitlab.com/iode/)

## Софтуер

### Критерии при избора

- Отворен код с публичен достъп;
- Да не зависи от **Google Play Services, Google Cloud Messaging (GCM)**;
- Тестван;
- Наличен в **F-Droid** или **Aurora Store**;
- Без излишни разрешения (**Permissions**).

> Внимание!
>
> Инсталирайте колкото се може по-малко допълнителен софтуер. Избягвайте даването на излишни разрешения за достъп на инсталираните от Вас приложения.
{: .prompt-warning }

### Алтернатива на **Google Play Services**

- [**MicroG**](https://microg.org/) | [Сорс код](https://github.com/microg)

> Инсталирайте само, ако наистина се нуждаете от услуги изискващи достъп до Вашия профил в **Google**!

### Магазини за приложения

- [**F-Droid**](https://f-droid.org/) | [Сорс код](https://gitlab.com/fdroid)

- [**Aurora Store**](https://auroraoss.com/) | [Сорс код](https://gitlab.com/AuroraOSS/AuroraStore)

### Начален екран (**Launcher**)

- **Trebuchet** | [Сорс код](https://github.com/LineageOS/android_packages_apps_Trebuchet)

- [**Lawnchair**](https://lawnchair.app/) | [Сорс код](https://github.com/LawnchairLauncher/lawnchair)

### Клавиатура

> Внимание!
>
> Съветвам Ви да **НЕ** използвайте приложения за клавиатура, които са патентовани и/или изискват достъп до Интернет! Няма значение колко добре работи автоматичното попълване. Разберете, че е недопустимо то да изпраща всичко което въвеждате, на нечий сървър, с единствената цел да бъдат извлечени Вашите данни. Дори няма значение дали има "*добра*" политика за поверителност и дали имате доверие на разработчика. Изпращането на данните крие вероятност, те да бъдат прихванати от по-малко доверена страна.
{: .prompt-warning }

### Уеб браузър и добавки

- **Mull** | [Сорс код](https://codeberg.org/divested-mobile/mull-fenix)
  - [**uBlock Origin**](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) | [Сорс код](https://github.com/gorhill/uBlock)

- [**Firefox**](https://www.mozilla.org/en-US/firefox/)
  - [**uBlock Origin**](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) | [Сорс код](https://github.com/gorhill/uBlock)

### Сигурност

- [**NetGuard**](https://netguard.me/) | [Сорс код](https://github.com/M66B/NetGuard)

- [**PCAPdroid**](https://emanuele-f.github.io/PCAPdroid/) | [Сорс код](https://github.com/emanuele-f/PCAPdroid)

- **Shelter** | [Сорс код](https://gitea.angry.im/PeterCxy/Shelter)

- **Scrambled Exif** | [Сорс код](https://gitlab.com/juanitobananas/scrambled-exif/tree/HEAD)

- [**Exodus**](https://exodus-privacy.eu.org/en/) | [Сорс код](https://github.com/Exodus-Privacy/exodus-android-app)

### Мениджър на пароли и двуфакторно удостоверяване (**2FA**)

- [**Bitwarden**](https://bitwarden.com/) | [Сорс код](https://github.com/bitwarden/mobile)

- [**Aegis**](https://getaegis.app/) | [Сорс код](https://github.com/beemdevelopment/Aegis)

### **VPN**

- [**Wireguard**](https://www.wireguard.com/) | [Сорс код](https://github.com/WireGuard/wireguard-android)

### Навигация

- [**Organic Maps**](https://organicmaps.app/) | [Сорс код](https://github.com/organicmaps/organicmaps)

- [**OpenStreetMap**](https://www.openstreetmap.org) | [Сорс код](https://github.com/osmandapp/Osmand)

- **GPSTest** | [Сорс код](https://github.com/barbeau/gpstest)

### Спорт и здраве

- [**Inner Breeze**](https://inner-breeze.app/) | [Сорс код](https://github.com/naoxio/inner_breeze)

- **Passeo** | [Сорс код](https://gitlab.com/pardomi/paseo/tree/HEAD)

### Четене

- [**Book Reader**] | [Сорс код](https://gitlab.com/axet/android-book-reader/tree/HEAD)

- [**LibreOffice Viewer**](https://www.libreoffice.org/download/download-libreoffice/) | [Сорс код](https://cgit.freedesktop.org/libreoffice/core/tree)

- [**Feeder**](https://news.nononsenseapps.com/) | [Сорс код](https://github.com/spacecowboy/Feeder)

- **Quote Unquote** | [Сорс код](https://github.com/jameshnsears/QuoteUnquote)

### Водене на записки

- [**Joplin**](https://joplinapp.org/) | [Сорс код](https://github.com/laurent22/joplin/)

### Синхронизация - Файлове, Календари, Контакти

- [**Nextcloud**](https://nextcloud.com/) | [Сорс код](https://github.com/nextcloud)

- [**DAVx<sup>5</sup>**](https://www.davx5.com/) | [Сорс код](https://github.com/bitfireAT/davx5-ose)

### Електронна поща

- [**K-9 Mail**](https://k9mail.app/) | [Сорс код](https://github.com/k9mail)

### Незабавни съобщения

- [**Conversations**](https://conversations.im/) | [Сорс код](https://codeberg.org/inputmice/Conversations)

- [**Gotify**](https://gotify.net/) | [Сорс код](https://github.com/gotify)

### Социални мрежи

- [**Element**](https://element.io/) | [Сорс код](https://github.com/element-hq/element-android)

### Прогноза за времето

- **Breezy Weather** | [Сорс код](https://github.com/breezy-weather/breezy-weather)

### Галерия - снимки

- [**Fossify Gallery**](https://www.fossify.org/) | [Сорс код](https://github.com/FossifyOrg/Gallery)

### Клиентски карти

- [**Catima**](https://catima.app/) | [Сорс код](https://github.com/CatimaLoyalty)

### Медия - Аудио/Видео

- [**VLC**](https://www.videolan.org/vlc/download-android.html) | [Сорс код](https://code.videolan.org/videolan/vlc-android)

- [**NewPipe**](https://newpipe.net/) | [Сорс код](https://github.com/TeamNewPipe/NewPipe)

## Допълнителни ресурси

- [Още приложения с отворен код](https://divestos.org/pages/recommended_apps)

- [**Digital Defense - Mobile Devices**](https://digital-defense.io/checklist/mobile-devices/)

- [Мобилни устройства - добри практики](https://media.defense.gov/2021/Sep/16/2002855921/-1/-1/0/MOBILE_DEVICE_BEST_PRACTICES_FINAL_V3%20-%20COPY.PDF)

- [Социални медии - добри практики](https://media.defense.gov/2021/Sep/16/2002855950/-1/-1/0/CSI_KEEPING_SAFE_ON_SOCIAL_MEDIA_20210806.pdf)
