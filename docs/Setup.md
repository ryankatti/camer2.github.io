
#### Install BlueJeans Android SDK:

We distribute our SDK from the Maven Repository.

To add the SDK to your app, add the following dependency in your build.gradle files:
```xml
repositories {
        maven {
            url publishURL
            credentials(AwsCredentials) {
                accessKey AWSAccessKey
                secretKey AWSSecretKey
            }
        }
    }
```
```xml
implementation("com.bluejeans:sdk-android:1.0.0-alpha.1'") {
        transitive(true)
    }
```
URL and keys will be shared separately.