SDK tools -> Install Instant Apps Development SDK
Follow this steps: https://www.youtube.com/watch?v=9Jg1D07NgeI (starts at 17:55)
Definition of android links (navigation): Same video but starts at 14.50
Can instant app have minSDK 23 and feature/base minSDK 19? YES
Launch instant app from shell: adb shell am start -a android.intent.action.VIEW -c android.intent.category.BROWSABLE -d http://instantappexample.com/main -n "com.google.android.instantapps.supervisor/.UrlHandler"
