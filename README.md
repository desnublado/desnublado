## Desnublado
### Not a single "cloud"!

`desnublado` resizes and converts your photos to [AVIF](https://en.wikipedia.org/wiki/AVIF) and videos to [AV1](https://en.wikipedia.org/wiki/AV1) making them about 50 to 100 times smaller than the originals, in a good enough quality so you can keep your entire collection on your Android device's local storage, without the need for an internet connection or any cloud storage service.

It defends users' freedom and sovereignty, so it has been deliberately created as a [bash](https://en.wikipedia.org/wiki/Bash) script to make it easy to inspect and modify without any special tools.

* Converts photo and video files from `DCIM/Camera` to `DCIM/Camera_mini` renamed into year/month folders
* Converts photo and video files from `DCIM/Camera_extra` as well, if the folder exists
* Moves processed original files to `DCIM/Camera_done`
* Imports converted photos and videos from another device if placed into `DCIM/Camera_import`
* Verifies the [SSHSIG](https://www.ietf.org/archive/id/draft-josefsson-sshsig-format-00.html) signature of updates to prevent tampering
* Has various path and behaviour [settings](https://desnublado.com/desnublado/en/#options)
* It is free, as in freedom, created entirely by a human and released to the [public domain](https://desnublado.com/#public-domain)
* It is free, as in gratis, yet you are welcome to [show me some love](https://desnublado.com/#show-me-some-love) if you like it :)

Install `Termux` preferably from [F-Droid](https://f-droid.org/en/packages/com.termux/), otherwise from [Google Play](https://play.google.com/store/apps/details?id=com.termux), and run this command to install it:

```
curl -fsSLO https://desnublado.com/desnublado && bash desnublado setup
```
***

To update to the latest version run this command in Termux:

```
desnublado update
```
***

See also [Aves](https://github.com/deckerst/aves), [Fossify Gallery](https://f-droid.org/en/packages/org.fossify.gallery/) and [Fossify File Manager](https://f-droid.org/en/packages/org.fossify.filemanager/) for privacy respecting open source gallery and files apps that support AVIF and AV1 formats.

For more information check the online [documentation](https://desnublado.com/).

Please note that this repository is a public mirror. All development is happening elsewhere.
