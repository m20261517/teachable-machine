# teachable-machine

Teachable Machine으로 원기둥, 원뿔, 구를 구별하는 웹앱입니다.

## 실행에 필요한 파일

Teachable Machine에서 내보낸 모델 파일을 `my_model/` 폴더에 넣어야 합니다.

```text
my_model/
├── model.json
├── metadata.json
└── *.bin
```

## GitHub Pages 배포

1. 저장소의 **Settings → Pages**로 이동합니다.
2. **Deploy from a branch**를 선택합니다.
3. 브랜치 `main`, 폴더 `/ (root)`를 선택하고 저장합니다.
4. 생성된 Pages 주소에서 카메라 권한을 허용합니다.

`my_model` 폴더가 없으면 앱 화면은 열리지만 분류 모델은 실행되지 않습니다.
