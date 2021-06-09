//[Android SDK](../../../index.md)/[com.bluejeans.bluejeanssdk](../index.md)/[BlueJeansSDK](index.md)



# BlueJeansSDK  
 [androidJvm] class [BlueJeansSDK](index.md)(**initParams**: [BlueJeansSDKInitParams](../-blue-jeans-s-d-k-init-params/index.md))

BlueJeansSDK provides APIs for enabling real time BlueJeans audio and video communication.</br> Create this object in the onCreate of application class and use. provides for meetingService for all meeting related APIs and permissionService for permission handling.

   


#### Throws  
  
| | |
|---|---|
| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK///PointingToDeclaration/"></a>[kotlin.IllegalStateException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-illegal-state-exception/index.html)| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK///PointingToDeclaration/"></a><br><br>if multiple SDK instance creation is attempted<br><br>|
| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK///PointingToDeclaration/"></a>[java.lang.IllegalAccessError](https://developer.android.com/reference/kotlin/java/lang/IllegalAccessError.html)| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK///PointingToDeclaration/"></a><br><br>if SDK instance creation is attempted on OS level lesser than 8.0<br><br>|


## Constructors  
  
| | |
|---|---|
| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/BlueJeansSDK/#com.bluejeans.bluejeanssdk.BlueJeansSDKInitParams/PointingToDeclaration/"></a>[BlueJeansSDK](-blue-jeans-s-d-k.md)| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/BlueJeansSDK/#com.bluejeans.bluejeanssdk.BlueJeansSDKInitParams/PointingToDeclaration/"></a> [androidJvm] fun [BlueJeansSDK](-blue-jeans-s-d-k.md)(initParams: [BlueJeansSDKInitParams](../-blue-jeans-s-d-k-init-params/index.md))   <br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/meetingService/#/PointingToDeclaration/"></a>[meetingService](meeting-service.md)| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/meetingService/#/PointingToDeclaration/"></a> [androidJvm] val [meetingService](meeting-service.md): [MeetingService](../../com.bluejeans.bluejeanssdk.meeting/-meeting-service/index.md)   <br>|
| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/permissionService/#/PointingToDeclaration/"></a>[permissionService](permission-service.md)| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/permissionService/#/PointingToDeclaration/"></a> [androidJvm] val [permissionService](permission-service.md): [PermissionService](../../com.bluejeans.bluejeanssdk.permission/-permission-service/index.md)   <br>|

