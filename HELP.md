```shell
adb install -r .\app\build\outputs\apk\debug\app-debug.apk
adb -s d6d268a3 install -r .\app\build\outputs\apk\debug\app-debug.apk

# 停止adb服务
adb kill-server

# 启动adb服务
adb start-server

# 构建Release版本
.\gradlew assembleRelease

# 构建Debug版本
.\gradlew assembleDebug
```
