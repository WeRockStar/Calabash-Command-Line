### Calabash Command Line
```shell

- Specific feature 
calabash-android run <APK_PATH>.apk features/TermsCondition.feature

- Run all feature files
calabash-android run <APK_PATH>.apk

- Run by Tags
calabash-android run <APK_PATH> —tags @tags

- Run Order by feature
calabash-android run <APK_PATH> features/TermsCondition.feature features/Login.feature

- Reports format
calabash-android run <APK_PATH>.apk --format JSON --out 
calabash-android run <APK_PATH>.apk --format HTML --out

- Specific emulator 
calabash-android run <apk>.apk ADB_DEVICE_ARG=<DEVICE_NAME>

```
