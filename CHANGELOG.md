# CHANGELOG — Small Haus (smallhause-sample)

## v0.1 (2026-09-08) 최초 빌드 — 전주 반려견 동반 커피·디저트 카페
- **업종/컨셉**: 전주 완산구 간납로 작은 커피·디저트 카페(모찌샌드 시그니처). 톤=**화이트 바탕 + 블랙 + 베이지 포인트 · 얇은 손글씨 · 영어 위주 · 반려견 친화**.
- **색**: bg 순백 · panel #FAF7F1 · ink #1A1A1A · **beige 포인트 #C3AC85 / beige-d(텍스트) #7A6640(AA)** · line #E9E5DD.
- **폰트**: 손글씨=**Caveat**(헤딩·브랜드·액센트), 본문/라벨=**Jost**(얇은 지오메트릭·영문)+Pretendard(한글). CDN(납품 self-host). 집(haus) 모티프 SVG(로고·파비콘), 발바닥(paw) 아이콘.
- **구성**: 헤더(집로고+nav)→히어로(브랜드 손글씨+반려견 문구+**네이버 지도 카드 바로 노출**[주소·시간·네이버버튼]+모찌샌드 밴드)→About(작은집·반려견 환영)→Menu(커피3·논커피3 + 모찌샌드 6카드)→Space(갤러리7)→Visit(주소·시간·반려견·IG+네이버/IG)→블랙 푸터+모바일 퀵바(네이버·IG).
- **실데이터**: 전북 전주시 완산구 간납로 6. 영업 **화·수·금·토·일·월 11:00–19:00, 목 정기휴무**. place 2024658346. IG @small.haus_. ⚠️전화 미제공→CTA 네이버지도+IG. 반려견 동반 가능.
- **메뉴**: 커피(아메리카노4,000·카페라떼4,500·하우스라떼6,000 only ice) / 논커피(우지말차라떼6,000·나의라임에이드5,500·애플유자티5,000) / 모찌샌드(복숭아·샤인머스캣·멜론·키위·통귤8,000·황치즈7,000·오레오초코7,000·직접만든 시그니처/망고 변동·브라우니).
- **네이버 지도**: 히어로에 지도 카드(주소·영업시간·"네이버 지도로 찾아오기" 버튼) 즉시 노출. ⚠️인터랙티브 지도 임베드는 네이버 API 키(고객) 필요 → 현재는 place 링크 버튼. 원하면 정적지도/임베드 후속.
- **마감/안전**: color-scheme·text-size-adjust·overflow-x·keep-all, 리빌 html.js 게이팅+데스크톱전용+1.6s폴백+reduced-motion 폴백+noscript, 고정 퀵바 safe-area, a11y(aria·focus-visible·alt·@media hover), JSON-LD CafeOrCoffeeShop+openingHours. 폼 없음.
- **AA**: ink/white 17.4·ink2 5.76·beige-d 5.52·흰/ink 17.4·ink2/panel 5.39. 전부 ≥4.5.
- **이미지**: 실사진 16 webp(무드·모찌샌드) + 인라인SVG 파비콘. 원본 img/·미사용 sh-brand `.assetsignore` 제외. 죽은참조 0·핫링크 0.
- **도메인**: og·canonical·JSON-LD = smallhaus-sample.lgt3232.workers.dev(임시). 인계 시 치환.
- ⚠️미결: GitHub 업로드+CF, 라이브 검증(폰트·모바일·실기기), 폰트 self-host(납품), 반려견 실사진(현재 곰인형 사진으로 대체), 브라우니·통귤 등 추가 모찌샌드 가격.
