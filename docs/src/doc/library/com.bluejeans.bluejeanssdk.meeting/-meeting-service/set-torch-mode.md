//[library](../../../index.md)/[com.bluejeans.bluejeanssdk.meeting](../index.md)/[MeetingService](index.md)/[setTorchMode](set-torch-mode.md)



# setTorchMode  
[androidJvm]  
Content  
fun [setTorchMode](set-torch-mode.md)(videoDevice: [VideoDevice](../../com.bluejeans.bluejeanssdk.selfvideo/-video-device/index.md), enabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  
More info  


Set the flash unit's torch mode of the camera of the given ID without opening the camera device.[CameraManager.setTorchMode](https://developer.android.com/reference/kotlin/android/hardware/camera2/CameraManager.html#settorchmode) setTorchMode doesn't work when the camera is ON, so using [setRepeatingCaptureRequest](set-repeating-capture-request.md) to handle torch state.



## Parameters  
  
androidJvm  
  
| | |
|---|---|
| <a name="com.bluejeans.bluejeanssdk.meeting/MeetingService/setTorchMode/#com.bluejeans.bluejeanssdk.selfvideo.VideoDevice#kotlin.Boolean/PointingToDeclaration/"></a>videoDevice| <a name="com.bluejeans.bluejeanssdk.meeting/MeetingService/setTorchMode/#com.bluejeans.bluejeanssdk.selfvideo.VideoDevice#kotlin.Boolean/PointingToDeclaration/"></a><br><br>: video device that supports torch<br><br>|
| <a name="com.bluejeans.bluejeanssdk.meeting/MeetingService/setTorchMode/#com.bluejeans.bluejeanssdk.selfvideo.VideoDevice#kotlin.Boolean/PointingToDeclaration/"></a>enabled| <a name="com.bluejeans.bluejeanssdk.meeting/MeetingService/setTorchMode/#com.bluejeans.bluejeanssdk.selfvideo.VideoDevice#kotlin.Boolean/PointingToDeclaration/"></a><br><br>: {@code true} to turn on the torch mode. Set to {@code false} to turn off the torch mode.<br><br>|
  
  



