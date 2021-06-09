//[Android SDK](../../../index.md)/[com.bluejeans.bluejeanssdk.permission](../index.md)/[PermissionService](index.md)



# PermissionService  
 [androidJvm] class [PermissionService](index.md)(**context**: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html))

PermissionService provides the functionality to check and request the [Permission](-permission/index.md)s required for the BlueJeans SDK. This service is an optional service, you can choose to use your own permission mechanism.</p>



BlueJeans SDK requires two permissions [Manifest.permission.RECORD_AUDIO](https://developer.android.com/reference/kotlin/android/Manifest.permission.html#record_audio) and [Manifest.permission.CAMERA](https://developer.android.com/reference/kotlin/android/Manifest.permission.html#camera) to join a call.</p>



The app needs to have mandatory permission [android.Manifest.permission.RECORD_AUDIO](https://developer.android.com/reference/kotlin/android/Manifest.permission.html#record_audio) in application manifest out of two permissions that need to be requested.</p>



Note : Registering the service in onCreate of an activity is mandatory before calling request permissions within that activity.</p>

   


## Constructors  
  
| | |
|---|---|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/PermissionService/#android.content.Context/PointingToDeclaration/"></a>[PermissionService](-permission-service.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/PermissionService/#android.content.Context/PointingToDeclaration/"></a> [androidJvm] fun [PermissionService](-permission-service.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html))   <br>|


## Types  
  
|  Name |  Summary | 
|---|---|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService.Permission///PointingToDeclaration/"></a>[Permission](-permission/index.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService.Permission///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>sealed class [Permission](-permission/index.md)  <br>More info  <br>Represents various types of permission required for calling experience.  <br><br><br>|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService.RequestStatus///PointingToDeclaration/"></a>[RequestStatus](-request-status/index.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService.RequestStatus///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>sealed class [RequestStatus](-request-status/index.md)  <br>More info  <br>This sealed class will use to notify about permission service api result  <br><br><br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/listOfDeniedPermission/#/PointingToDeclaration/"></a>[listOfDeniedPermission](list-of-denied-permission.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/listOfDeniedPermission/#/PointingToDeclaration/"></a> [androidJvm] val [listOfDeniedPermission](list-of-denied-permission.md): [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>Represents the list of denied permission in case multiple permissions are requested.   <br>|


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/hasAllPermissions/#/PointingToDeclaration/"></a>[hasAllPermissions](has-all-permissions.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/hasAllPermissions/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>fun [hasAllPermissions](has-all-permissions.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>More info  <br>Checks whether all permission granted for a complete audio video calling experience.  <br><br><br>|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/hasMinimumPermissions/#/PointingToDeclaration/"></a>[hasMinimumPermissions](has-minimum-permissions.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/hasMinimumPermissions/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>fun [hasMinimumPermissions](has-minimum-permissions.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>More info  <br>Checks for minimum permissions required to join a meeting  <br><br><br>|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/hasPermission/#com.bluejeans.bluejeanssdk.permission.PermissionService.Permission/PointingToDeclaration/"></a>[hasPermission](has-permission.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/hasPermission/#com.bluejeans.bluejeanssdk.permission.PermissionService.Permission/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>fun [hasPermission](has-permission.md)(permission: [PermissionService.Permission](-permission/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>More info  <br>Checks the individual permission if already granted.  <br><br><br>|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/register/#androidx.activity.ComponentActivity/PointingToDeclaration/"></a>[register](register.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/register/#androidx.activity.ComponentActivity/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>fun [register](register.md)(componentActivity: [ComponentActivity](https://developer.android.com/reference/kotlin/androidx/activity/ComponentActivity.html))  <br>More info  <br>As per new behaviour change in activity result api.  <br><br><br>|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/requestAllPermissions/#/PointingToDeclaration/"></a>[requestAllPermissions](request-all-permissions.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/requestAllPermissions/#/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>fun [requestAllPermissions](request-all-permissions.md)(): Single<[PermissionService.RequestStatus](-request-status/index.md)>  <br>More info  <br>Requests for all mandatory permissions which are required for the SDK.  <br><br><br>|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/requestPermissions/#kotlin.Array[com.bluejeans.bluejeanssdk.permission.PermissionService.Permission]/PointingToDeclaration/"></a>[requestPermissions](request-permissions.md)| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/requestPermissions/#kotlin.Array[com.bluejeans.bluejeanssdk.permission.PermissionService.Permission]/PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>fun [requestPermissions](request-permissions.md)(permissionsArray: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[PermissionService.Permission](-permission/index.md)>): Single<[PermissionService.RequestStatus](-request-status/index.md)>  <br>More info  <br>Requests array of  permissions required for androidx [ComponentActivity](https://developer.android.com/reference/kotlin/androidx/activity/ComponentActivity.html).  <br><br><br>|

