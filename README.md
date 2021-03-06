# Project Overview

This is a project for investigating the Toast API.

[日本語版_README](https://github.com/LeoAndo/android-toast-samples/blob/main/readme/README_JP.md)

# development enveroment
<img width="686" alt="127751156-0638bd97-e532-43e9-be12-e758a7118141" src="https://user-images.githubusercontent.com/16476224/128230885-30d23c7f-5714-4590-9592-ec3f733b39e0.png">

# Conclusion (alternative)
Toast uses a Only  [makeText](https://developer.android.com/reference/kotlin/android/widget/Toast?hl=ja#maketext).<br>
or Use [Snackbar](https://developer.android.com/reference/com/google/android/material/snackbar/Snackbar), which can be displayed only when the app is in the foreground.

# refs

## [Toast-specification-changes-OS:11](https://developer.android.com/about/versions/11/behavior-changes-11?hl=ja#toasts)

## Toast-specification-changes-OS:12
- can put up to 2 lines of text message in Toast. <br>
  - https://youtu.be/D2cU_itNDAI?t=714

- Limited the number of Toasts that can be displayed.
  -  https://youtu.be/D2cU_itNDAI?t=727

# Capture (Android View)

| Pixel 4 OS10 | Pixel 4 OS11 |
|:---|:---:|
| <img src="https://user-images.githubusercontent.com/16476224/117284945-5f325080-aea2-11eb-8278-c68feb8765a6.gif" width=320 /> | <img src="https://user-images.githubusercontent.com/16476224/117284926-58a3d900-aea2-11eb-9179-1294d8b03caf.gif" width=320 /> |

# Capture (Compose)

| Pixel 4 OS: 8 | Pixel 4 OS: 12 |
|:---|:---:|
| <img src="https://user-images.githubusercontent.com/16476224/151012930-1a1b1253-a715-4a35-abee-cc08a73c9b8a.gif" width=320 /> | <img src="https://user-images.githubusercontent.com/16476224/151012648-6a99b81d-0cd2-4bf4-9d6c-b05ab34a4ad6.gif" width=320 /> |

# For Compose
https://github.com/LeoAndo/android-toast-samples/tree/main/ToastComposeSample

# For Kotlin code
https://github.com/LeoAndo/android-toast-samples/tree/main/ToastKotlinSample

# For Java code
https://github.com/LeoAndo/android-toast-samples/tree/main/ToastJavaSample

