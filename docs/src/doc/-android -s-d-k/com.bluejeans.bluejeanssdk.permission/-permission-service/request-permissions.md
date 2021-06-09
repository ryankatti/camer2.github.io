//[Android SDK](../../../index.md)/[com.bluejeans.bluejeanssdk.permission](../index.md)/[PermissionService](index.md)/[requestPermissions](request-permissions.md)



# requestPermissions  
[androidJvm]  
Content  
fun [requestPermissions](request-permissions.md)(permissionsArray: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[PermissionService.Permission](-permission/index.md)>): Single<[PermissionService.RequestStatus](-request-status/index.md)>  
More info  


Requests array of  permissions required for androidx [ComponentActivity](https://developer.android.com/reference/kotlin/androidx/activity/ComponentActivity.html).



#### Return  


Single of  [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) for result of permission grant to subscribe. check [listOfDeniedPermission](list-of-denied-permission.md) for denied permissions list if result is false



## Parameters  
  
androidJvm  
  
| | |
|---|---|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/requestPermissions/#kotlin.Array[com.bluejeans.bluejeanssdk.permission.PermissionService.Permission]/PointingToDeclaration/"></a>permissionsArray| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/requestPermissions/#kotlin.Array[com.bluejeans.bluejeanssdk.permission.PermissionService.Permission]/PointingToDeclaration/"></a><br><br>instance of [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html) of [Permission](-permission/index.md) with valid permissions.<br><br>|
  
  



