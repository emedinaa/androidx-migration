# androidx-migration
Migration  of the android dependencies to androidx


## Table

| Library | Previous | Android X     |
| ------------- | ------------- |------------- |
| kotlin | -  | androidx.core:core-ktx:1.0.0|
| appcompat  | com.android.support:appcompat-v7:28.0.0  | androidx.appcompat:appcompat:1.0.2 |
| recyclerview  | com.android.support:recyclerview-v7:28.0.0  | androidx.recyclerview:recyclerview:1.0.0 |
| cardview  | com.android.support:cardview-v7:28.0.0  | androidx.cardview:cardview:1.0.0|
| constraintlayout |com.android.support.constraint:constraint-layout:1.1.3|androidx.constraintlayout:constraintlayout:1.1.3|

## Android X

Add the following on gradle.properties file :

``
android.useAndroidX=true
android.enableJetifier=true
``

## References

- AndroidX https://developer.android.com/jetpack/androidx
