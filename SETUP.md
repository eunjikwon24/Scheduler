# 하루 트랙 — GitHub Pages에 올리기

내용은 **내 계정의 비공개 Gist**에 저장됩니다. 어느 기기에서 접속하든 같은 기록이 보여요.

---

## 1. 페이지 올리기 (5분)

1. https://github.com/new 에서 새 저장소를 만드세요.
   - 이름: `haru-track` (아무거나 괜찮아요)
   - **Public** 으로 두세요. (Private은 GitHub Pages가 유료입니다)
   - 코드만 공개되고 **일기·할 일 내용은 절대 여기 들어가지 않습니다.**
2. 저장소 화면에서 **Add file → Upload files** 를 누르고 `index.html` 을 올린 뒤 **Commit changes**.
3. **Settings → Pages** 로 갑니다.
   - Source: `Deploy from a branch`
   - Branch: `main` / `/ (root)` → **Save**
4. 1~2분 뒤 주소가 나옵니다: `https://<내아이디>.github.io/haru-track/`

## 2. 토큰 만들기 (2분)

1. https://github.com/settings/personal-access-tokens/new (Fine-grained tokens)
2. **Token name**: `haru-track`
3. **Expiration**: 원하는 기간 (1년 등)
4. **Repository access**: `Public repositories (read-only)` 그대로 두세요 — 저장소는 안 씁니다.
5. **Permissions → Account permissions** 에서 **Gists** 를 찾아 **Read and write** 로 바꿉니다.
   - 다른 권한은 전부 건드리지 마세요.
6. **Generate token** → 나온 `github_pat_...` 를 복사합니다. **이 화면을 벗어나면 다시 볼 수 없어요.**

## 3. 연결하기

1. 위에서 나온 주소로 접속합니다.
2. 오른쪽 위 저장 표시 옆 **자세히** 를 누릅니다.
3. **GitHub로 자동 동기화** 칸에 토큰을 붙여넣고 **연결하기**.
4. "연결됐어요" 가 뜨면 끝입니다.

**폰에서도 같은 주소로 접속해서 같은 토큰을 한 번만 넣어주세요.** 그 뒤로는 자동입니다.

---

## 알아두실 것

- 토큰은 **그 기기의 브라우저에만** 저장되고 어디로도 전송되지 않습니다. 기기마다 한 번씩 넣어야 해요.
- 저장은 바꾼 뒤 **2.5초 뒤**에 자동으로 올라갑니다. 다른 기기는 화면을 볼 때마다, 그리고 45초마다 확인해요.
- 두 기기에서 각각 쓴 내용은 **합쳐집니다.** 지운 것은 되살아나지 않아요.
- 폰 Safari에서 **공유 → 홈 화면에 추가** 하면 앱 아이콘처럼 쓸 수 있습니다.
- 토큰을 잃어버리거나 만료되면 새로 만들어 다시 넣으면 됩니다. **기록은 Gist에 그대로 있어요.**
- 기록을 직접 보고 싶으면 https://gist.github.com 에서 `haru-track-data` 를 찾으면 됩니다.

## 혹시 문제가 생기면

`자세히` 창에 저장 방식, 마지막 동기화 시각, 오류 메시지가 다 나옵니다.
