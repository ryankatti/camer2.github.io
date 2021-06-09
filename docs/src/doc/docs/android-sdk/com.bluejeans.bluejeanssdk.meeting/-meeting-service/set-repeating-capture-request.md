//[android-sdk](../../../index.md)/[com.bluejeans.bluejeanssdk.meeting](../index.md)/[MeetingService](index.md)/[setRepeatingCaptureRequest](set-repeating-capture-request.md)



# setRepeatingCaptureRequest  
[androidJvm]  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
final [MeetingService.CaptureRequestResult](-capture-request-result/index.md)[setRepeatingCaptureRequest](set-repeating-capture-request.md)<T extends [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>([CaptureRequest.Key](https://developer.android.com/reference/kotlin/android/hardware/camera2/CaptureRequest.Key.html)<[T](set-repeating-capture-request.md)>key, [T](set-repeating-capture-request.md)value, [CameraCaptureSession.CaptureCallback](https://developer.android.com/reference/kotlin/android/hardware/camera2/CameraCaptureSession.CaptureCallback.html)callBack)  
  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
final [MeetingService.CaptureRequestResult](-capture-request-result/index.md)[setRepeatingCaptureRequest](set-repeating-capture-request.md)<T extends [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>([CaptureRequest.Key](https://developer.android.com/reference/kotlin/android/hardware/camera2/CaptureRequest.Key.html)<[T](set-repeating-capture-request.md)>key, [T](set-repeating-capture-request.md)value)  
  
More info  


Sets repeating capture request on the current camera session. This internally will call [CameraCaptureSession.setRepeatingRequest](https://developer.android.com/reference/kotlin/android/hardware/camera2/CameraCaptureSession.html#setrepeatingrequest) with the preview builder's key value pair. This API will be useful to control camera zoom, exposure or any other capture requests as provided by the framework at [CaptureRequest.Key](https://developer.android.com/reference/kotlin/android/hardware/camera2/CaptureRequest.Key.html)



#### Return  


[CaptureRequestResult](-capture-request-result/index.md)



## Parameters  
  
androidJvm  
  
| | |
|---|---|
| <a name="com.bluejeans.bluejeanssdk.meeting/MeetingService/setRepeatingCaptureRequest/#android.hardware.camera2.CaptureRequest.Key[TypeParam(bounds=[kotlin.Any?])]#TypeParam(bounds=[kotlin.Any?])#android.hardware.camera2.CameraCaptureSession.CaptureCallback?/PointingToDeclaration/"></a>key| <a name="com.bluejeans.bluejeanssdk.meeting/MeetingService/setRepeatingCaptureRequest/#android.hardware.camera2.CaptureRequest.Key[TypeParam(bounds=[kotlin.Any?])]#TypeParam(bounds=[kotlin.Any?])#android.hardware.camera2.CameraCaptureSession.CaptureCallback?/PointingToDeclaration/"></a><br><br>: [CaptureRequest.Key](https://developer.android.com/reference/kotlin/android/hardware/camera2/CaptureRequest.Key.html)<br><br>|
| <a name="com.bluejeans.bluejeanssdk.meeting/MeetingService/setRepeatingCaptureRequest/#android.hardware.camera2.CaptureRequest.Key[TypeParam(bounds=[kotlin.Any?])]#TypeParam(bounds=[kotlin.Any?])#android.hardware.camera2.CameraCaptureSession.CaptureCallback?/PointingToDeclaration/"></a>value| <a name="com.bluejeans.bluejeanssdk.meeting/MeetingService/setRepeatingCaptureRequest/#android.hardware.camera2.CaptureRequest.Key[TypeParam(bounds=[kotlin.Any?])]#TypeParam(bounds=[kotlin.Any?])#android.hardware.camera2.CameraCaptureSession.CaptureCallback?/PointingToDeclaration/"></a><br><br>: value corresponding to the key set<br><br>|
| <a name="com.bluejeans.bluejeanssdk.meeting/MeetingService/setRepeatingCaptureRequest/#android.hardware.camera2.CaptureRequest.Key[TypeParam(bounds=[kotlin.Any?])]#TypeParam(bounds=[kotlin.Any?])#android.hardware.camera2.CameraCaptureSession.CaptureCallback?/PointingToDeclaration/"></a>callBack| <a name="com.bluejeans.bluejeanssdk.meeting/MeetingService/setRepeatingCaptureRequest/#android.hardware.camera2.CaptureRequest.Key[TypeParam(bounds=[kotlin.Any?])]#TypeParam(bounds=[kotlin.Any?])#android.hardware.camera2.CameraCaptureSession.CaptureCallback?/PointingToDeclaration/"></a><br><br>: [CameraCaptureSession.CaptureCallback](https://developer.android.com/reference/kotlin/android/hardware/camera2/CameraCaptureSession.CaptureCallback.html)<br><br>|
  
  



