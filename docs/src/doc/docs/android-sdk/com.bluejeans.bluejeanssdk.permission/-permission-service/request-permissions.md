//[android-sdk](../../../index.md)/[com.bluejeans.bluejeanssdk.permission](../index.md)/[PermissionService](index.md)/[requestPermissions](request-permissions.md)



# requestPermissions  
[androidJvm]  
Content  
final Single<[PermissionService.RequestStatus](-request-status/index.md)>[requestPermissions](request-permissions.md)([Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[PermissionService.Permission](-permission/index.md)>permissionsArray)  
  
More info  


Requests array of  permissions required for androidx [ComponentActivity](https://developer.android.com/reference/kotlin/androidx/activity/ComponentActivity.html).



#### Return  


Single of  [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) for result of permission grant to subscribe. check [listOfDeniedPermission](index.md#85092368%2FProperties%2F-435046686) for denied permissions list if result is false



## Parameters  
  
androidJvm  
  
| | |
|---|---|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/requestPermissions/#kotlin.Array[com.bluejeans.bluejeanssdk.permission.PermissionService.Permission]/PointingToDeclaration/"></a>permissionsArray| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/requestPermissions/#kotlin.Array[com.bluejeans.bluejeanssdk.permission.PermissionService.Permission]/PointingToDeclaration/"></a><br><br>instance of [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html) of [Permission](-permission/index.md) with valid permissions.<br><br>|
  
  



