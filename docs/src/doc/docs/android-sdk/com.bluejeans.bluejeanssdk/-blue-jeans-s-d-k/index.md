//[android-sdk](../../../index.md)/[com.bluejeans.bluejeanssdk](../index.md)/[BlueJeansSDK](index.md)



# BlueJeansSDK  
 [androidJvm] public final class [BlueJeansSDK](index.md)

BlueJeansSDK provides APIs for enabling real time BlueJeans audio and video communication.</br> Create this object in the onCreate of application class and use. provides for meetingService for all meeting related APIs and permissionService for permission handling.

   


#### Throws  
  
| | |
|---|---|
| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK///PointingToDeclaration/"></a>[kotlin.IllegalStateException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-illegal-state-exception/index.html)| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK///PointingToDeclaration/"></a><br><br>if multiple SDK instance creation is attempted<br><br>|
| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK///PointingToDeclaration/"></a>[java.lang.IllegalAccessError](https://developer.android.com/reference/kotlin/java/lang/IllegalAccessError.html)| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK///PointingToDeclaration/"></a><br><br>if SDK instance creation is attempted on OS level lesser than 8.0<br><br>|


## Constructors  
  
| | |
|---|---|
| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/BlueJeansSDK/#com.bluejeans.bluejeanssdk.BlueJeansSDKInitParams/PointingToDeclaration/"></a>[BlueJeansSDK](-blue-jeans-s-d-k.md)| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/BlueJeansSDK/#com.bluejeans.bluejeanssdk.BlueJeansSDKInitParams/PointingToDeclaration/"></a> [androidJvm] [BlueJeansSDK](index.md)[BlueJeansSDK](-blue-jeans-s-d-k.md)([BlueJeansSDKInitParams](../-blue-jeans-s-d-k-init-params/index.md)initParams)  <br>   <br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/meetingService/#/PointingToDeclaration/"></a>[meetingService](index.md#-1983433095%2FProperties%2F-435046686)| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/meetingService/#/PointingToDeclaration/"></a> [androidJvm] private final [MeetingService](../../com.bluejeans.bluejeanssdk.meeting/-meeting-service/index.md)[meetingService](index.md#-1983433095%2FProperties%2F-435046686)  <br>   <br>|
| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/permissionService/#/PointingToDeclaration/"></a>[permissionService](index.md#1588265825%2FProperties%2F-435046686)| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/permissionService/#/PointingToDeclaration/"></a> [androidJvm] private final [PermissionService](../../com.bluejeans.bluejeanssdk.permission/-permission-service/index.md)[permissionService](index.md#1588265825%2FProperties%2F-435046686)  <br>   <br>|


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/getMeetingService/#/PointingToDeclaration/"></a>[getMeetingService](get-meeting-service.md)| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/getMeetingService/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>final [MeetingService](../../com.bluejeans.bluejeanssdk.meeting/-meeting-service/index.md)[getMeetingService](get-meeting-service.md)()  <br>  <br><br><br>|
| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/getPermissionService/#/PointingToDeclaration/"></a>[getPermissionService](get-permission-service.md)| <a name="com.bluejeans.bluejeanssdk/BlueJeansSDK/getPermissionService/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>final [PermissionService](../../com.bluejeans.bluejeanssdk.permission/-permission-service/index.md)[getPermissionService](get-permission-service.md)()  <br>  <br><br><br>|


## Inherited functions  
  
|  Name |  Summary | 
|---|---|
| <a name="kotlin/BlueJeansSDK/equals/#kotlin.Any?/PointingToDeclaration/"></a>[equals](index.md#1990162204%2FFunctions%2F-435046686)| <a name="kotlin/BlueJeansSDK/equals/#kotlin.Any?/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>[Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[equals](index.md#1990162204%2FFunctions%2F-435046686)([Object](https://developer.android.com/reference/kotlin/java/lang/Object.html)other)  <br>  <br><br><br>|
| <a name="kotlin/BlueJeansSDK/hashCode/#/PointingToDeclaration/"></a>[hashCode](index.md#-1278672310%2FFunctions%2F-435046686)| <a name="kotlin/BlueJeansSDK/hashCode/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>[Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)[hashCode](index.md#-1278672310%2FFunctions%2F-435046686)()  <br>  <br><br><br>|
| <a name="kotlin/BlueJeansSDK/toString/#/PointingToDeclaration/"></a>[toString](index.md#-1456838375%2FFunctions%2F-435046686)| <a name="kotlin/BlueJeansSDK/toString/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>[String](https://developer.android.com/reference/kotlin/java/lang/String.html)[toString](index.md#-1456838375%2FFunctions%2F-435046686)()  <br>  <br><br><br>|

