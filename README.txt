BRANCHES
Master: Has normal modules setup
install-app: Has instant-app modules setup

SDK tools -> Install Instant Apps Development SDK
Follow this steps: https://www.youtube.com/watch?v=9Jg1D07NgeI (starts at 17:55)
Definition of android links (navigation): Same video but starts at 14.50
Can instant app have minSDK 23 and feature/base minSDK 19? YES
Launch instant app from shell: adb shell am start -a android.intent.action.VIEW -c android.intent.category.BROWSABLE -d http://instantappexample.com/main -n "com.google.android.instantapps.supervisor/.UrlHandler"
Instant apps need gradle plugin 4.0 and gradle android wrapper 3.0.0, which don't have a stable release yet (no alpha/beta/snapshot)