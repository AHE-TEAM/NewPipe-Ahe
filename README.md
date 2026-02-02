<h3 align="center">
Kod tabanının büyük bölümlerini <i>yeniden yazıyoruz</i> ve
<a href="https://newpipe.net/blog/pinned/announcement/newpipe-0.27.6-rewrite-team-states/#the-refactor">
modern ve kararlı bir NewPipe</a> oluşturuyoruz!
Gece derlemelerini
<a href="https://github.com/TeamNewPipe/NewPipe-refactor-nightly/releases">buradan</a>
indirebilirsiniz.
</h3>

<h4 align="center">
Yeni özellikler eklemek istiyorsanız lütfen <code>refactor</code> dalında çalışın.
Mevcut kod tabanı bakım modundadır ve yalnızca hata düzeltmeleri alacaktır.
</h4>

<p align="center">
<a href="https://newpipe.net">
<img src="assets/new_pipe_icon_5.png" width="150">
</a>
</p>

<h2 align="center"><b>NewPipe</b></h2>

<h4 align="center">Android için özgür ve hafif bir yayın izleme ön yüzü.</h4>

<p align="center">
<a href="https://f-droid.org/packages/org.schabi.newpipe/">
<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on-en.svg" width="206"/>
</a>
</p>

<p align="center">
<a href="https://github.com/TeamNewPipe/NewPipe/releases">
<img src="https://img.shields.io/github/release/TeamNewPipe/NewPipe.svg">
</a>
<a href="https://github.com/TeamNewPipe/NewPipe-nightly/releases">
<img src="https://img.shields.io/github/release/TeamNewPipe/NewPipe-nightly.svg?labelColor=purple&label=dev%20nightly">
</a>
<a href="https://github.com/TeamNewPipe/NewPipe-refactor-nightly/releases">
<img src="https://img.shields.io/github/release/TeamNewPipe/NewPipe-refactor-nightly.svg?labelColor=purple&label=refactor%20nightly">
</a>
<a href="https://www.gnu.org/licenses/gpl-3.0">
<img src="https://img.shields.io/badge/Lisans-GPL%20v3-blue.svg">
</a>
<a href="https://github.com/TeamNewPipe/NewPipe/actions">
<img src="https://github.com/TeamNewPipe/NewPipe/actions/workflows/ci.yml/badge.svg?branch=dev&event=push">
</a>
<a href="https://hosted.weblate.org/engage/newpipe/">
<img src="https://hosted.weblate.org/widgets/newpipe/-/svg-badge.svg">
</a>
</p>

<p align="center">
<a href="https://web.libera.chat/#newpipe">
<img src="https://img.shields.io/badge/IRC%20chat-%23newpipe-brightgreen.svg">
</a>
<a href="https://matrix.to/#/#newpipe:matrix.newpipe-ev.de">
<img src="https://img.shields.io/badge/Matrix%20chat-%23newpipe-blue">
</a>
</p>

---

<p align="center">
<a href="#ekran-görüntüleri">Ekran Görüntüleri</a> •
<a href="#desteklenen-servisler">Desteklenen Servisler</a> •
<a href="#açıklama">Açıklama</a> •
<a href="#özellikler">Özellikler</a> •
<a href="#kurulum-ve-güncellemeler">Kurulum ve Güncellemeler</a> •
<a href="#katkı">Katkı</a> •
<a href="#bağış">Bağış</a> •
<a href="#lisans">Lisans</a>
</p>

<p align="center">
<a href="https://newpipe.net">Web Sitesi</a> •
<a href="https://newpipe.net/blog/">Blog</a> •
<a href="https://newpipe.net/FAQ/">SSS</a> •
<a href="https://newpipe.net/press/">Basın</a>
</p>

---

*Bu belgeyi diğer dillerde okuyun:
Deutsch, English, Español, Français, हिन्दी, Italiano, 한국어, Português Brasil, Polski, ਪੰਜਾਬੀ, 日本語, Română, Soomaali, Türkçe, 正體中文, অসমীয়া, Српски, العربية*

---

> ⚠️ **BU UYGULAMA BETA AŞAMASINDADIR. HATALARLA KARŞILAŞABİLİRSİNİZ.  
HATA BULURSANIZ GITHUB DEPOSUNDA ISSUE AÇIN.**

> **NEWPIPE VEYA TÜREVLERİNİ GOOGLE PLAY STORE'A KOYMAK POLİTİKALARA AYKIRIDIR.**

---

## Ekran Görüntüleri

[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/00.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/00.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/01.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/01.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/02.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/02.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/03.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/03.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/04.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/04.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/05.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/05.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/06.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/06.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/07.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/07.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/08.png" width=160>](fastlane/metadata/android/en-US/images/phoneScreenshots/08.png)

---

## Desteklenen Servisler

- YouTube & YouTube Music  
- PeerTube  
- Bandcamp  
- SoundCloud  
- media.ccc.de  

---

## Açıklama

NewPipe, servislerin resmi API'lerinden veri çeker.  
API kısıtlıysa web sitesi ayrıştırılır veya dahili API kullanılır.  

Hesap gerekmez.  
Google servisleri gerekmez.  

---

## Özellikler

- 4K video  
- Arka planda ses  
- Açılır pencere (PiP)  
- Canlı yayın  
- Altyazı  
- Arama  
- Kuyruk  
- Abonelik  
- Bildirim  
- Oynatma listeleri  
- İndirme  
- Kodi desteği  
- Yaş kısıtı kontrolü  

---

## Kurulum ve Güncellemeler

1. F-Droid deposu  
2. GitHub APK  
3. F-Droid güncelleme  
4. Kaynaktan derleme  
5. PR APK

---

## APK Parmak İzi

CB:84:06:9B:D6:81:16:BA:FA:E5:EE:4E:E5:B0:8A:56:7A:A6:D8:98:40:4E:7C:B1:2F:9E:75:6D:F5:CF:5C:AB

---

## Katkı

https://github.com/TeamNewPipe/NewPipe/blob/dev/.github/CONTRIBUTING.md

---

## Bağış

https://newpipe.net/donate

---

## Gizlilik Politikası

https://newpipe.net/legal/privacy/

---

## Lisans

GNU GPLv3  
NewPipe özgür yazılımdır.
