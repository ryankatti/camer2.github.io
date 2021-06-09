//[android-sdk](../../../index.md)/[com.bluejeans.bluejeanssdk.permission](../index.md)/[PermissionService](index.md)/[requestAllPermissions](request-all-permissions.md)



# requestAllPermissions  
[androidJvm]  
Content  
final Single<[PermissionService.RequestStatus](-request-status/index.md)>[requestAllPermissions](request-all-permissions.md)()  
  
More info  


Requests for all mandatory permissions which are required for the SDK.</br> All required permission are specified in "permissions" map.



#### Return  


Rx Single of  [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) for result of permission check [listOfDeniedPermission](index.md#85092368%2FProperties%2F-435046686) for denied permissions list if result is false

  



