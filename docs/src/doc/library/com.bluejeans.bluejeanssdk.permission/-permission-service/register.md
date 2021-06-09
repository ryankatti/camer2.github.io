//[library](../../../index.md)/[com.bluejeans.bluejeanssdk.permission](../index.md)/[PermissionService](index.md)/[register](register.md)



# register  
[androidJvm]  
Content  
fun [register](register.md)(componentActivity: [ComponentActivity](https://developer.android.com/reference/kotlin/androidx/activity/ComponentActivity.html))  
More info  


As per new behaviour change in activity result api. All result api register must call on every create of the activity. permissionService.registerForPermissionService do registerForActivityResult for given activity This method need to be called before using the permission service. Without registering permission service none of the api of this class will work. registration needs weak reference of activity



## Parameters  
  
androidJvm  
  
| | |
|---|---|
| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/register/#androidx.activity.ComponentActivity/PointingToDeclaration/"></a>componentActivity| <a name="com.bluejeans.bluejeanssdk.permission/PermissionService/register/#androidx.activity.ComponentActivity/PointingToDeclaration/"></a><br><br>instance of ComponentActivity<br><br>|
  
  



