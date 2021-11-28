---
title: Rekomendasi Extension Theme Font Visual Studio Code
date: 2020-05-24T16:06:58.000+07:00
tags:
- editor
- vs code
- 'extensions  '
images:
- https://i.ibb.co/2h6Qc6T/featured.png
- https://i.ibb.co/Kxj4Ly8/flutter-bloc.png
- https://i.ibb.co/HLcL2hJ/dart-import.png
- https://github.com/aaron-bond/better-comments/raw/master/images/better-comments.PNG
- https://i.ibb.co/q03RnGs/todo-tree.png
- https://i.ibb.co/0hHPvnT/image-preview.png
- https://i.ibb.co/FDXvR9x/material-icon.png
- https://i.ibb.co/6mjkgbf/theme-dracula.png
- https://i.ibb.co/CJQgSMh/theme-one-dark.png
- https://github.com/tonsky/FiraCode/raw/master/extras/logo.svg

---
Jika teman-teman semua adalah pengguna IDE/text editor [VS Code](https://code.visualstudio.com/), teman-teman pasti butuh yang namanya extension, theme, font, etc. Baca sampai selesai Saya akan membahas tentang **Rekomendasi tentang beberapa Extensions, Theme, Font** yang saya gunakan di VS Code sehari-hari sebagai pendukung produktifitas saya.

Yang pertama saya akan bahas tentang Extensions yang saya gunakan, brikut penjelasanya.

## Extensions

**Apa sih itu Extensions?** Dalam context para developer / programmer, **Extensions** yaitu sebuah tool/alat yang digunakan sebagai pembantu kita untuk lebih produktif, lebih cepat dalam pengembangan, lebih konsisten, dan juga lebih bersih dalam penulisan kode.

Dan pada kali saya membahas Extensions yang saya pakai saja, mungkin jika teman-teman yang kurang sependapat dengan saya, boleh cek beberapa extensions di VS Code, di situs [**Visual Studio Code Extension**](https://marketplace.visualstudio.com/VSCode). Berikut beberapa extension VS Code yang saya gunakan sehari-hari untuk menunjang produktifitas saya.

## 1. Dart/Flutter

Dikarenakan saya adalah programmer yang menekuni Flutter, pastilah wajib sebagai programmer tersebut menginstall sebuah extenstion [Dart](https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code) dan [Flutter](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter). Extension dart dan Flutter ini sebagai pembantu saya untuk menulis sebuah code yang menggunakan bahasa Dart. Extensions ini sangat diperlukan jika teman-teman adalah sebagai penulis code Dart. Fitur-fitur yang tersedia di extensions ini banyak sekali, misal: sebagai pengecekan penulisan typo code, sebagai tool debugging, sebagai refaktoring kode, dan masih banyak lagi.

Untuk Dart dan Flutter ini adalah sebagai extenstions sama saya yang utama, karena Dart dan Flutter ini langsung berhubungan dengan SDK. Jika teman-teman adalah sebagai Programmer Web, bisa gunakan extensions seperti Live Server, Vue, Node JS, etc. Atau teman-teman sebagai backend developer bisa gunakan extension PHP, Go, etc.

{{< button url="https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code" text="Dart" >}}
{{< button url="https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter" text="Flutter" >}}

## 2. Bloc

![Flutter Bloclibrary generator](https://i.ibb.co/Kxj4Ly8/flutter-bloc.png)

Yang kedua yaitu extension Bloc, Bloc ini langsung dibuat oleh [Felix Angelov](//github.com/felangel/), seorang pembuat library Flutter [flutter_bloc](//bloclibrary.dev/). Extensions Bloc ini sangat mudah digunakan misal sebagai simple generate bloc, snippet-snippet pada library flutter_bloc. Jadi jika teman-teman adalah pengguna library flutter_bloc extensions ini sangat berguna sekali. Bisa menghemat banyak waktu teman-teman. Berikut contoh preview tinggal **klik kanan** > `Bloc: New Bloc`.

{{< button url="https://marketplace.visualstudio.com/items?itemName=FelixAngelov.bloc" text="Show Detail" >}}

## 3. Dart-Import

![Flutter Dart Import](https://i.ibb.co/HLcL2hJ/dart-import.png)

Extensions ini bagi saya sangat berguna sekali untuk membuat code kita lebih rapi, dan lebih terstruktur dalam import suatu file dart. Bisa teman-teman tekan shortcut **Ctrl + Shift + P** > erus Cari **Fix Import**, Atau mau capat bisa custom shortcut di VS Code. Berikut contoh preview simple:

{{< button url="https://marketplace.visualstudio.com/items?itemName=luanpotter.dart-import" text="Show Detail" >}}

## 4. Pubspec Assist

Pada extensions ini kita bisa menginstall berbagai dependency dart tanpa harus ke situsnya dependency dart. Kita juga bisa upgrade, cari, refresh, dan install dependency dart semua bisa di extensions ini.

{{< button url="https://marketplace.visualstudio.com/items?itemName=jeroen-meijer.pubspec-assist" text="Show Detail" >}}

## 5. Better Comments

![Better Comments VS Code](//github.com/aaron-bond/better-comments/raw/master/images/better-comments.PNG)

Extensions ini saya sangat suka sekali, dan sangat berguna sekali dalam menulis suatu code. Kita bisa memberi komentar dengan ragam variasi. Bisa TODO, Alert, Highlights, Queries. Dengan warna comment yang sesuai. Jadi dalam penulisan kode kita bisa terstruktur, mana yang harus dikerjakan terlebih dahulu, dan mana yang dikerjakan belakangan.

{{< button url="https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments" text="Show Detail" >}}

## 6. TODO Tree

![Extensions Todo Tree in VS Code](https://i.ibb.co/q03RnGs/todo-tree.png)

Extensions ini sangat berguna sekali, jika teman-teman coding dengan banyak sekali file/ project yang besar, Extensions ini itu bisa membantu kita untuk mengorganizer apa saja yang harus kita lakukan, di dalam file tersebut, dan extensions ini itu bisa mendeteksi semua file yang ada comment `TODO` di dalam workspace folder. Untuk penggunaan buat comment code, terus diawali dengan TODO, terus pesan apa yang anda isi. Contoh:

```dart
// TODO: Kerjakan ini setelah semua selesai
```

Perlu diperhatikan format comment tidak semua sama, format tergantung pada bahasa pemrograman yang teman-teman gunakan.

## 7. Image Preview

![VS Code Image Preview Extensions](https://i.ibb.co/0hHPvnT/image-preview.png)

Extensions ini bisa membantu kita melihat preview gambar url atau path. DI extensions **Image Preview** ini bisa support dari lokal, maupun internet. Jadi mungkin kita dalam menulis sebuah kode tapi kita input sebuah url/path image tapi tidak tahu itu gambar apa, kita tidak perlu melihat di browser, cukup melihat di samping line number VS code aja.

{{< button url="https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview" text="Show Detail" >}}

## 8. Material Icon Theme

![VS Code Material Icon Theme](https://i.ibb.co/FDXvR9x/material-icon.png)

Material Icon Theme ini suatu extension yang cukup menarik, kita bisa melihat suatu folder, dan file dengan warna dan icon yang beragam yang sangat menarik. Dan juga kita bisa custom sendiri nama folder dan file yang akan dicustom iconnya.

{{< button url="https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme" text="Show Detail" >}}

## 9. YAML

Extensions YAML ini saya gunakan untuk meminimalisir kasalahan penulisan Kode dalam file YAML, karena di Flutter semua setting, seperti dependency, project name, ect.

## 10. Bracket Pair Colorizer 2

![VS Code Bracket Pari Colorizer 2](https://github.com/CoenraadS/BracketPair/raw/master/images/example.png)

Extensions ini bisa membuat kita lebih, teliti dalam penulisan kode, dengan pemisahan kode dengan indicator yang berwarna-warna.

{{< button url="https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2" text="Show Detail" >}}

## 11. Markdown All in One

Extensions ini berguna bila kita menulis sebuah text di dalam file markdown. Sangat berguna sekali jika teman-teman masih pemula menggunakan markdown, extensions ini sangat bagus, dan juga kita bisa membuat dan langsung melihat preview yang telah kita buat.

{{< button url="https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one" text="Show Detail" >}}

## 12. Error Lens

![](https://raw.githubusercontent.com/usernamehw/vscode-error-lens/master/img/demo.png)

Extension ini berguna untuk memberitahukan apa saja kesalahan pada kode yang Anda tulis dengan sangat jelas. Biasanya ketika ada kesalahan kode, warning atau perlu improve pada Visual Studio Code itu sering tidak terlihat, jadi sering terabaikan. Dengan adanya extensi ini Saya bisa terbantu untuk memperbaiki kualitas dari kode Saya.

{{< button url="https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens" text="Show Detail" >}}

## 13. Thunder Client

![](https://github.com/rangav/thunder-client-support/blob/master/images/thunder-client.gif?raw=true)

Extensi ini bagi Saya juga berguna dapat meningkatkan produktifitas dalam mengerjakan sebuah pekerjaan yang berhubungan dengan coding yang komunikasi dengan API. Jika Anda sebelumnya sering melakukan pengetesan API lewat Postman atau sejenisnya, pasti Anda tidak akan asing lagi dalam penggunaan Thunder Client ini karena secara fungsi sama persis.

Tapi ada kelebihan jika Anda pakai Thunder Client yaitu sudah satu program dengan text editor jadi tidak perlu bolak-balik ke app lain dalam pengetesan API. 

{{< button url="https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client" text="Show Detail" >}}

## Theme

Theme atau tema di text editor bagi saya sangatlah penting, dan tema berfungsi memperindah IDE / Text Editor kita, supaya kita tidak mudah bosan melihat Text Editor nya. Berikut beberapa tema yang pernah dan sering saya gunakan.

## 1. Dracula Official

![VS Code Theme Dracula](https://i.ibb.co/6mjkgbf/theme-dracula.png)

Theme Dracula ini adalah salah satu Theme terfavorit saya, dengan style yang menarik, dan tidak mudah buat bosan bagi saya.

{{< button url="https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula" text="Show Detail" >}}

## 2. Darcula IntelliJ Theme

Mungkin diatara teman-teman banyak yang pernah atau kebiasaan di IDE platform Jetbrains seperti: Intellij IDEA, GoLand, PHP Strom, Android Studio, etc. Pasti sudah kenal dengan tema Dracula nya Jetbrains. Dan di VS Code ini temanya juga tersedia.

{{< button url="https://marketplace.visualstudio.com/items?itemName=trinm1709.dracula-theme-from-intellij" text="Show Detail" >}}

## 3. One Dark Pro

![VS Code Theme One Dark Pro](https://i.ibb.co/CJQgSMh/theme-one-dark.png)

Tema ini menurut saya bagus sih, bagi keseharian menemani teman-teman menulis code.

{{< button url="https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme" text="Show Detail" >}}

## Font

Tidak cuma Extensions, Theme saja Font juga perlu sekali, bila teman-teman menulis sebuah kode tapi font nya tidak sesuia dan kurang nyaman pasti akan cepat bosan. Berikut font-font yang saya gunakan.

## 1. Fira Code

![Fira Code font overview](https://github.com/tonsky/FiraCode/raw/master/extras/logo.svg "Fira Code font overview")

Font Fira Code ini adalah font pada VS Code yang saya gunakan setiap hari. Dan di font ini yang cukup menarik yaitu tersedia ligatures font yang menggabungkan beberapa simbol jadi kesatuan, yang bisa membuat kita lebih mudah dimengerti.

{{< button url="https://github.com/tonsky/FiraCode" text="Show Detail" >}}

## 2. Jetbrains Mono

Dan Font Jetbrains Mono ini saya gunakan sebagai alternatif dari Fira Code, font ini juga sama bagusnya dengan Fira code.

{{< button url="https://www.jetbrains.com/lp/mono/" text="Show Detail" >}}

Sekian dari saya, ada masukan atau kesalahan bisa comment dibawah atau [contact](/contact) Saya, dan juga jangan lupa share, Thanks.