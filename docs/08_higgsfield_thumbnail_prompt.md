# Higgsfield 썸네일 생성 프롬프트

## 최종 프롬프트

아래 내용을 Higgsfield에 그대로 붙여넣는다.

```text
Create a 518x298px horizontal homepage thumbnail, approximately 1.74:1 aspect ratio, for a casual Korean youth board game meetup.

The design should feel warm, friendly, light, and beginner-friendly. Use a clean cream or light yellow background with soft shadows. Add a simple rounded table shape with 2-3 colorful board game cards and small game tokens or meeples. Keep the layout minimal and uncluttered so it reads clearly at small thumbnail size.

Text must be the main focus. Place the large Korean title in the safe center-left area:
"청년동 보드게임 번개모임"

Add a smaller subtitle below it:
"처음 해도 같이 배우며 가볍게 즐겨요"

Add a small rounded badge near the title:
"초보 환영"

Make the title the first thing viewers notice. Use high contrast, large readable Korean typography, generous spacing, and a simple friendly composition. No brand logos, no casino mood, no clutter.
```

## 네거티브 프롬프트

```text
dark background, neon colors, casino, gambling, poker casino table, money, alcohol, aggressive competition, cluttered board game table, too many tiny details, tiny unreadable text, distorted Korean text, misspelled Korean text, fake logo, brand logo, copyrighted board game box, scary mood, childish cartoon overload, crowded people, exaggerated facial expressions, low contrast typography
```

## 권장 비율

- 권장 크기: 518x298px
- 권장 비율: 약 1.74:1 가로 배너
- 생성 도구에서 정확한 픽셀 입력이 어렵다면 16:9보다 조금 더 낮은 가로형 배너로 생성 후 518x298px로 크롭한다.

## 텍스트 안전 영역 가이드

- 메인 문구는 중앙 또는 중앙-왼쪽에 크게 배치한다.
- 상하좌우 끝에서 최소 24px 이상 여백을 둔다.
- `청년동 보드게임 번개모임`이 가장 먼저 읽혀야 한다.
- 서브 문구와 배지는 메인 문구보다 작게 둔다.
- 카드, 말, 테이블 요소가 글자 뒤를 복잡하게 가리지 않게 한다.

## 생성 후 저장 위치

```text
assets/thumbnail/boardgame-meetup-thumbnail.png
```

## 생성 결과 체크리스트

- [ ] 이미지 크기 또는 크롭 결과가 518x298px이다.
- [ ] 작은 썸네일에서도 `청년동 보드게임 번개모임`이 먼저 읽힌다.
- [ ] 서브 문구 `처음 해도 같이 배우며 가볍게 즐겨요`가 깨지지 않았다.
- [ ] 배지 문구 `초보 환영`이 보인다.
- [ ] 보드게임 카드 또는 말이 보이지만 복잡하지 않다.
- [ ] 초보자도 부담 없이 신청할 수 있는 밝고 편안한 분위기다.
- [ ] 카지노, 도박, 특정 보드게임 상표 느낌이 없다.
- [ ] 한국어 글자가 틀리거나 뭉개지지 않았다.

## 이미지 저장 후 커밋할 파일 목록

실제 이미지 파일을 저장했다면 아래 파일을 함께 커밋한다.

```text
docs/08_higgsfield_thumbnail_prompt.md
assets/thumbnail/boardgame-meetup-thumbnail.png
```

이미지를 아직 만들지 않았다면 `docs/08_higgsfield_thumbnail_prompt.md`만 커밋한다.
