# Virtual Office

![image](https://user-images.githubusercontent.com/1011232/79879948-52bf8f00-842a-11ea-9b5b-53676965855a.png)

# Kantor Virtual

![image](https://user-images.githubusercontent.com/1011232/79879948-52bf8f00-842a-11ea-9b5b-53676965855a.png)

## Motivasi

Saat ini, dalam mencari cara kerja dari rumah yang nyaman, saya merasa perlu membuat ini.

Panggilan Slack terasa terlalu formal untuk menghubungi rekan kerja saat ingin beristirahat sejenak. Sementara itu, tren "masuk kantor" menggunakan Discord semakin populer, namun karena kami menggunakan Slack sebagai alat utama, rasanya fungsinya akan terlalu banyak yang tumpang tindih. Berdasarkan penelitian, remo dan [Online Town](https://hn.town.siempre.io/) tampaknya cocok, jadi saya ingin membuat sesuatu yang serupa.

Ini bukan untuk manajer mengawasi pekerjaan bawahannya. 🙅‍♂️

## Ketergantungan

+ Bagian WebRTC akan diimplementasikan dengan cepat menggunakan SkyWay.
+ Berbagi informasi pengguna akan diimplementasikan menggunakan SignalR.

## Cara Menggunakan

Deploy ke Azure WebApps atau platform serupa.

### Menulis tangan pada berbagi layar desktop

**Pihak yang melihat berbagi layar**: Anda dapat menulis dengan tangan pada video berbagi layar menggunakan mouse. Konten yang ditulis akan dibagikan.
**Pihak yang berbagi layar**: Untuk memproyeksikan konten yang ditulis oleh peserta lain ke layar Anda, Anda perlu menjalankan aplikasi desktop terpisah ([screen drawer](https://github.com/iwate/screen-drawer/)).

## LISENSI

MIT

## Motivation

快適なWork From Homeを模索中の現在、ほしいと思ったので作り始めました。

Slackのコールは一息付きたくて同僚にかけるには敷居が高い。巷ではDiscord出社がはやっている用だが、Slackをメインツールとして使っているため機能がかぶり過ぎる感じがする。調べた限りではremoや[Online Twon](https://hn.town.siempre.io/)がフィットしそうなので、似たようなものを目指します。

これはマネージャーが部下の仕事ぶりを監視するためのものではありません。🙅‍♂️

## Dependencies

+ WebRTC部分はとりあえずSkyWayでサクッと実装します。
+ ユーザ情報の共有はSignalRで実装します。

## How to use

Azure WebAppsなどにデプロイ。

### Hand write on desktop share

**画面共有を見てる側**：画面共有の動画上をマウスでぐりぐりすると手書きが可能です。書いた内容は共有されます。  
**画面共有をしてる側**：他の参加者によってかかれたないようをスクリーン上に投影するには別途デスクトップアプリ（[screen drawer](https://github.com/iwate/screen-drawer/)）を立ち上げる必要があります。

## LICENSE

MIT
