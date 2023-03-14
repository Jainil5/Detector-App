
Realtime object and person detecting android app.



### How does app work?

[MobileNet SSD](https://tfhub.dev/tensorflow/lite-model/ssd_mobilenet_v1/1/metadata/2),
[EfficientDet Lite 0](https://tfhub.dev/tensorflow/lite-model/efficientdet/lite0/detection/metadata/1),
[EfficientDet Lite1](https://tfhub.dev/tensorflow/lite-model/efficientdet/lite1/detection/metadata/1),
or
[EfficientDet Lite2](https://tfhub.dev/tensorflow/lite-model/efficientdet/lite2/detection/metadata/1)
model trained on the [COCO dataset](http://cocodataset.org/). These instructions
walk you through building and running the demo on an Android device.

*   A physical Android device with a minimum OS version of SDK 24 (Android 7.0 -
    Nougat) with developer mode enabled. The process of enabling developer mode
    may vary by device. This device will also need to have the latest version of
    Google Play Services installed.

### Building

*   Open Android Studio. From the Welcome screen, select Open an existing
    Android Studio project.

*   From the Open File or Project window that appears, navigate to and select
    the tensorflow-lite/examples/object_detection/android_play_services
    directory. Click OK.

*   If it asks you to do a Gradle Sync, click OK.

*   With your Android device connected to your computer and developer mode
    enabled, click on the green Run arrow in Android Studio.

### Models used

Downloading, extraction, and placing the models into the assets folder is
managed automatically by the download.gradle file.

### Screenshots


![detector app screenshot](https://user-images.githubusercontent.com/96060948/222389050-98a09249-293b-4c82-8723-e0f4e82b7084.jpg)
