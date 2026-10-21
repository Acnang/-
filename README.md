# 🎲 이론 뽑기

버튼 하나로 랜덤 사회과학 이론(깨진 유리창 이론, 넛지, 피그말리온 효과 등)을 뽑아주는 정적 웹사이트입니다.
서버 없이 `index.html` 하나로 동작합니다.

## GitHub Pages로 바로 배포하기

1. 새 저장소를 만들고 `index.html`, `README.md`를 업로드합니다.
2. 저장소의 **Settings → Pages**로 이동합니다.
3. **Source**를 `Deploy from a branch`, 브랜치를 `main`, 폴더를 `/ (root)`로 선택하고 Save.
4. 1~2분 뒤 `https://<내아이디>.github.io/<저장소이름>/` 에서 접속할 수 있습니다.

## 이론 추가하는 방법

`index.html` 안의 `THEORIES` 배열에 아래 형식으로 한 줄 추가하면 자동 반영됩니다.

```js
{c:'심리', n:'이론 이름', e:'English Name', w:'제안자 (연도)', s:'한 줄 설명', x:'예시'},
```

새 분류를 쓰려면 `COLORS`에 색상도 추가하세요.
