# 032 Illustration Portfolio

032(공삼이)의 일러스트 포트폴리오 웹사이트예요.

## 구성
- `index.html`: 사이트 전체 (HTML, CSS, JS가 한 파일에 들어 있어요)
- `images/`: 작품 이미지(WebP), 캐릭터 영상(webm/mp4), 제작 과정 조각(`images/parts/`)
- `.nojekyll`: GitHub Pages가 파일을 그대로 올리도록 하는 빈 파일

## GitHub Pages로 올리기
1. 이 폴더 안의 파일을 저장소 맨 위(루트)에 올려요.
2. 저장소 **Settings → Pages**에서 Branch를 `main`, 폴더를 `/ (root)`로 고르고 저장해요.
3. 잠시 뒤 `https://아이디.github.io/저장소이름/` 주소로 열려요.

## 작품 추가하기
`index.html` 아래쪽 `<script>` 안의 `WORKS` 목록에 작품을 추가하고, `ROWS` 목록에 그 작품의 `area` 이름을 원하는 줄에 넣으면 돼요.
