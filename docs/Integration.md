### Initialize BlueJeans SDK:
Create the object of BlueJeans SDK in application onCreate with help of application context and use it to access all the APIs

The minimum permission needed to join a meeting is permission for RECORD_AUDIO. Make sure the app requests this permission before calling Join API.

Sample Code:
```java
blueJeansSDK = new BlueJeansSDK(new BlueJeansSDKInitParams(this));
```
APIs are exposed through two major services, MeetingService and PermissionService. These objects can be accessed in code as

```java
blueJeansSDK.getMeetingService 
```
This takes care of all meeting related APIs (refer to the documentation for API set and details)

```java
blueJeansSDK.getPermissionService
```

This takes care of permission handling related APIs (refer to the documentation for API set and details)

#### Join a BlueJeans meeting:
- Provide Mic(RecordAudio) and Camera Permissions either by using BJN SDK permission service or by Android SDK APIs
- Get and add SelfVideoFragment and enableSelfVideoPreview to start the self video
- Get and use meeting service and invoke join APIs to join a meeting
- Observe for Join API result by subscribing to the Rx Single returned by the join API


#### Subscriptions (ObservableValue and Rx Single's):

**Single's:**

http://reactivex.io/RxJava/javadoc/io/reactivex/Single.html

**ObservableValues:**

Most of our subscriptions are stateful members called ObservableValues.

These are our BJN custom reactive stream elements carrying a value that can be accessed (READ only) at any point in time and also allows a subscription.

Through ObservableValue you can also access rxObservable(http://reactivex.io/RxJava/javadoc/io/reactivex/Observable.html) and subscribe.

Sample app depicts the usage of both the RxSingle and ObeservableValue

#### Managing Self Video:


##### Orientation handling:

If Meeting activity handles
**onConfigurationChanged:** Call *setSelfVideoOrientation*

If Meeting activity recreates on orientation change:
No need to call any additional API.


##### Mute:

*enableSelfVideoPreview* provides for enabling/disabling the camera capturer. Functional irrespective of meeting state.

*setVideoMuted* will mute the video stream flowing to the other endpoint. Functional when in a meeting.

The integrated app should use these APIs in combination to drive the self video mute.


##### Video device enumeration, selection:

*videoDevices* will provide a list of video/camera devices available on the hardware.

*currentVideoDevice* will provide for the current device selected. By default, the front camera is selected.

Use *selectVideoDevice* and choose the video device of your choice from the available *videoDevices* list.


##### Audio device enumeration, selection:

*audioDevices* will provide a list of audio devices available on the hardware.

*currentAudioDevice* will provide for the current audio device selected.

On dynamic change in audio devices, SDK's default order of auto selection is as below:

- BluetoothHeadset
- USBDevice
- USBHeadset
- WiredHeadsetDevice
- WiredHeadPhones
- Speaker

Use *selectAudioDevice* and choose the audio device of your choice from the available *audioDevices* list.

##### Video Layouts:

Represents how remote participant’s videos are composed
- **Speaker**: Only the most recent speaker is shown, taking up the whole video stream.
- **People**: The most recent speaker is shown as a larger video. A filmstrip of the next (up to) 5 most recent speakers is shown at the top.
- **Gallery**: A bunch of the most recent speakers is shown, arranged in a grid layout of equal sizes.

*videoLayout* provides for the current video layout *setVideoLayout* can be used to force a Video Layout of your choice.

Note that by default the current layout will be the People layout or it will be the one chosen by the meeting scheduler in his account’s meeting settings.


