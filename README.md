# 혜택콕

청년 지원금·혜택을 내 조건에 맞게 찾아주는 웹앱 (PWA).

## 실행
`index.html`을 브라우저로 열면 됩니다. 서비스 워커는 https 또는 localhost에서만 동작합니다.

## GitHub Pages 배포
1. 저장소 Settings → Pages
2. Source: Deploy from a branch → main / (root)
3. 발급된 주소에서 휴대폰으로 열고 홈 화면에 추가하면 앱처럼 설치됩니다.

## 데이터 수정
정책 데이터는 `index.html`의 `P` 배열, 시·군·구 목록은 `SUB` 객체에 있습니다.
