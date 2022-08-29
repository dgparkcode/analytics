# analytics

## Firebase analytics

될 수 있는한 영어문서를 참고한다.(번역본은 최신문서가 아닐 경우가 많음)    

https://firebase.google.com/docs/analytics

## DebugView

네트워크 사용을 줄이기 위해 정보를 보내는 텀이 길지만,   
개발시 빠른 텀으로 데이터를 확인하기 위해 사용함

https://firebase.google.com/docs/analytics/debugview#android    

https://console.firebase.google.com/project/_/analytics/debugview


## 실행, 종료

adb shell setprop debug.firebase.analytics.app com.dgparkcode.analytics // 실행    
adb shell setprop debug.firebase.analytics.app .none. // 종료