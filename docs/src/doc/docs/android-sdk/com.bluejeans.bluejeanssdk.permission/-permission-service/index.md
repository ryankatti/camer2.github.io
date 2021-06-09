//[android-sdk](../../../index.md)/[com.bluejeans.bluejeanssdk.permission](../index.md)/[PermissionService](index.md)



# PermissionService  
 [androidJvm] public final class [PermissionService](index.md)

PermissionService provides the functionality to check and request the [Permission](-permission/index.md)s required for the BlueJeans SDK. This service is an optional service, you can choose to use your own permission mechanism.</p>



BlueJeans SDK requires two permissions [Manifest.permission.RECORD_AUDIO](https://developer.android.com/reference/kotlin/android/Manifest.permission.html#record_audio) and [Manifest.permission.CAMERA](https://developer.android.com/reference/kotlin/android/Manifest.permission.html#camera) to join a call.</p>



The app needs to have mandatory permission [android.Manifest.permission.RECORD_AUDIO](https://developer.android.com/reference/kotlin/android/Manifest.permission.html#record_audio) in application manifest out of two permissions that need to be requested.</p>



Note : Registering the service in onCreate of an activity is mandatory before calling request permissions within that activity.</p>

   


## Constructors  
  
| | |
|---|---|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/PermissionService/#android.content.Context/PointingToDeclaration/"></a>[PermissionService](-permission-service.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/PermissionService/#android.content.Context/PointingToDeclaration/"></a> [androidJvm] [PermissionService](index.md)[PermissionService](-permission-service.md)([Context](https://developer.android.com/reference/kotlin/android/content/Context.html)context)  <br>   <br>|


## Types  
  
|  Name |  Summary | 
|---|---|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService.Permission///PointingToDeclaration/"></a>[Permission](-permission/index.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService.Permission///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>public class [Permission](-permission/index.md)  <br>More info  <br>Represents various types of permission required for calling experience.  <br><br><br>|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService.RequestStatus///PointingToDeclaration/"></a>[RequestStatus](-request-status/index.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService.RequestStatus///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>public class [RequestStatus](-request-status/index.md)  <br>More info  <br>This sealed class will use to notify about permission service api result  <br><br><br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/listOfDeniedPermission/#/PointingToDeclaration/"></a>[listOfDeniedPermission](index.md#85092368%2FProperties%2F-435046686)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/listOfDeniedPermission/#/PointingToDeclaration/"></a> [androidJvm] private final [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)<[String](https://developer.android.com/reference/kotlin/java/lang/String.html)>[listOfDeniedPermission](index.md#85092368%2FProperties%2F-435046686)  <br>Represents the list of denied permission in case multiple permissions are requested.   <br>|


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/getListOfDeniedPermission/#/PointingToDeclaration/"></a>[getListOfDeniedPermission](get-list-of-denied-permission.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/getListOfDeniedPermission/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>final [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)<[String](https://developer.android.com/reference/kotlin/java/lang/String.html)>[getListOfDeniedPermission](get-list-of-denied-permission.md)()  <br>  <br>More info  <br>Represents the list of denied permission in case multiple permissions are requested.  <br><br><br>|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/hasAllPermissions/#/PointingToDeclaration/"></a>[hasAllPermissions](has-all-permissions.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/hasAllPermissions/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[hasAllPermissions](has-all-permissions.md)()  <br>  <br>More info  <br>Checks whether all permission granted for a complete audio video calling experience.  <br><br><br>|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/hasMinimumPermissions/#/PointingToDeclaration/"></a>[hasMinimumPermissions](has-minimum-permissions.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/hasMinimumPermissions/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[hasMinimumPermissions](has-minimum-permissions.md)()  <br>  <br>More info  <br>Checks for minimum permissions required to join a meeting  <br><br><br>|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/hasPermission/#com.bluejeans.bluejeanssdk.permission.PermissionService.Permission/PointingToDeclaration/"></a>[hasPermission](has-permission.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/hasPermission/#com.bluejeans.bluejeanssdk.permission.PermissionService.Permission/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>final [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[hasPermission](has-permission.md)([PermissionService.Permission](-permission/index.md)permission)  <br>  <br>More info  <br>Checks the individual permission if already granted.  <br><br><br>|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/register/#androidx.activity.ComponentActivity/PointingToDeclaration/"></a>[register](register.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/register/#androidx.activity.ComponentActivity/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>final [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)[register](register.md)([ComponentActivity](https://developer.android.com/reference/kotlin/androidx/activity/ComponentActivity.html)componentActivity)  <br>  <br>More info  <br>As per new behaviour change in activity result api.  <br><br><br>|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/requestAllPermissions/#/PointingToDeclaration/"></a>[requestAllPermissions](request-all-permissions.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/requestAllPermissions/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>final Single<[PermissionService.RequestStatus](-request-status/index.md)>[requestAllPermissions](request-all-permissions.md)()  <br>  <br>More info  <br>Requests for all mandatory permissions which are required for the SDK.  <br><br><br>|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/requestPermissions/#kotlin.Array[com.bluejeans.bluejeanssdk.permission.PermissionService.Permission]/PointingToDeclaration/"></a>[requestPermissions](request-permissions.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/requestPermissions/#kotlin.Array[com.bluejeans.bluejeanssdk.permission.PermissionService.Permission]/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>final Single<[PermissionService.RequestStatus](-request-status/index.md)>[requestPermissions](request-permissions.md)([Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[PermissionService.Permission](-permission/index.md)>permissionsArray)  <br>  <br>More info  <br>Requests array of  permissions required for androidx [ComponentActivity](https://developer.android.com/reference/kotlin/androidx/activity/ComponentActivity.html).  <br><br><br>|


## Inherited functions  
  
|  Name |  Summary | 
|---|---|
| <a name="kotlin/PermissionService/equals/#kotlin.Any?/PointingToDeclaration/"></a>[equals](index.md#-1136210277%2FFunctions%2F-435046686)| <a name="kotlin/PermissionService/equals/#kotlin.Any?/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>[Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)[equals](index.md#-1136210277%2FFunctions%2F-435046686)([Object](https://developer.android.com/reference/kotlin/java/lang/Object.html)other)  <br>  <br><br><br>|
| <a name="kotlin/PermissionService/hashCode/#/PointingToDeclaration/"></a>[hashCode](index.md#-1696829461%2FFunctions%2F-435046686)| <a name="kotlin/PermissionService/hashCode/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>[Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)[hashCode](index.md#-1696829461%2FFunctions%2F-435046686)()  <br>  <br><br><br>|
| <a name="kotlin/PermissionService/toString/#/PointingToDeclaration/"></a>[toString](index.md#-1874995526%2FFunctions%2F-435046686)| <a name="kotlin/PermissionService/toString/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>[String](https://developer.android.com/reference/kotlin/java/lang/String.html)[toString](index.md#-1874995526%2FFunctions%2F-435046686)()  <br>  <br><br><br>|

