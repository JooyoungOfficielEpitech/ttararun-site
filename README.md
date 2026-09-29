# ttararun-site

따라런(Ttararun) 소개 및 약관 정적 사이트. GitHub Pages로 배포됩니다.

| 페이지 | 파일 | 근거 |
|---|---|---|
| 소개 (랜딩) | `index.html` | — |
| GPX 만드는 법 | `how-to-gpx.html` | 앱 내 `HowToGpxScreen` 미러 |
| 위치기반서비스 이용약관 | `terms-location.html` | 위치정보법 §18, §12(공개 의무) |
| 개인위치정보 처리방침 | `location-policy.html` | 위치정보법 §21의2 |
| 개인정보처리방침 | `privacy.html` | 개인정보 보호법 §30 |
| 문의 · 지원 | `support.html` | 저작권법 §103 신고 창구 포함 |

- 스타일: `style.css` (외부 의존성 없음). 다크 배경 `#0B0F0C`, 라임 악센트 `#C5F277`.
- 스크린샷: `shots/01~05.png` (앱 스토어 제출본과 동일).

## 배포 전에 반드시 채워야 하는 값

`class="todo"` 로 표시된 부분입니다. `grep -rn 'class="todo"' *.html` 으로 전부 찾을 수 있습니다.

- 상호 / 대표자 성명 / 사업장 주소 / 사업자등록번호 / 전화번호
- 위치기반서비스사업 신고번호 및 신고일 (방송미디어통신위원회)
- 통신판매업 신고번호 (해당하는 경우)
- 위치정보관리책임자 · 개인정보 보호책임자 성명·직위
- 각 문서의 시행일
- PostHog 인스턴스 리전 (국외이전 표의 이전 국가)

문의: 2000jooyoung@gmail.com
