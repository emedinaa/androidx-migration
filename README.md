## [COMING SOON] androidx-migration
Migration  of the android dependencies to androidx

## Table

| Library | Previous | Android X     |
| ------------- | ------------- |------------- |
| kotlin | com.android.support:support-compat  | androidx.core:core-ktx:1.0.0|
| appcompat  | com.android.support:appcompat-v7:28.0.0  | androidx.appcompat:appcompat:1.0.2 |
| support v13 |com.android.support:support-v13:28.0.0  | androidx.legacy:legacy-support-v13:1.0.0 |
| support v4 |com.android.support:support-v4:28.0.0  | androidx.legacy:legacy-support-v4:1.0.0 |
| recyclerview  | com.android.support:recyclerview-v7:28.0.0  | androidx.recyclerview:recyclerview:1.0.0 |
| cardview  | com.android.support:cardview-v7:28.0.0  | androidx.cardview:cardview:1.0.0|
| constraintlayout |com.android.support.constraint:constraint-layout:1.1.3|androidx.constraintlayout:constraintlayout:1.1.3|
| room | android.arch.persistence.room:runtime:1.0.0 | androidx.room:room-runtime:2.0.0-rc01 |
| room compiler | android.arch.persistence.room:compiler:1.0.0  | androidx.room:room-compiler:2.0.0-rc01 |
| lifecycle | android.arch.lifecycle:common:1.1.1 |androidx.lifecycle:lifecycle-common:2.0.0-rc01 |
| lifecycle extensions | android.arch.lifecycle:extensions:2.1.0-alpha02 |androidx.lifecycle:lifecycle-extensions:2.0.0-rc01|
| runner | com.android.support.test:runner :1.0.2 | androidx.test:runner :1.0.1 |
| espresso | com.android.support.test.espresso:espresso-core:3.0.2 | androidx.test.espresso:espresso-core:3.1.1|

## Android X

Add the following on gradle.properties file :

```
android.useAndroidX=true

android.enableJetifier=true

```

## References

- AndroidX https://developer.android.com/jetpack/androidx
