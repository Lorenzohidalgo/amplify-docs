Expand **Gradle Scripts**, open **build.gradle (Module: app)**. You will already have configured Amplify by following the steps in the [Project Setup walkthrough](~/lib/project-setup/create-application.md).

Add these libraries into the `dependencies` block:
```groovy
dependencies {
    implementation 'com.amplifyframework:core:1.0.0'
    implementation 'com.amplifyframework:aws-api:1.0.0'
}
```

Click **Sync Now**.