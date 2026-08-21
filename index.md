# App Transfer Test — Universal Links host

이 사이트는 **앱 이관(App Transfer) 실험**에서 Universal Links가 언제 깨지는지 확인하기 위한 것입니다.

`/.well-known/apple-app-site-association` 에 `appID`(= `<TeamID>.<BundleID>`)가 들어 있습니다.
이관으로 Team ID가 바뀌면 이 파일이 앱과 맞지 않게 됩니다.

- 테스트 링크: [/memo/1](/memo/1)
- 앱 저장소: https://github.com/mobpa-jw/iOS_Transfer_app
