# ELIM G REDIRECT PLAN v1.0

업데이트: 2026-09-30

## 원칙
- 동일 서비스의 구버전은 301 Redirect를 권장.
- 외부 Netlify 사이트의 Redirect는 각 사이트 저장소/Netlify 설정에서 개별 적용해야 한다.
- elimg.kr 저장소의 _redirects는 elimg.kr 내부 경로만 직접 제어한다.
- 콘텐츠 이전 확인 전에는 Redirect를 먼저 걸지 않는다.

## 우선 Redirect 목록

| 기존 사이트 | 목적지 | 우선순위 |
|---|---|---|
| elimg-com-main.netlify.app | https://elimg.com | 1 |
| elimgbridge.netlify.app | https://elimg.kr | 1 |
| elimgbridge2.netlify.app | https://elimg.kr | 1 |
| elimgbridge-dark.netlify.app | https://elimg.kr | 1 |
| elimgbridge-dark2.netlify.app | https://elimg.kr | 1 |
| elimgbridge-light.netlify.app | https://elimg.kr | 1 |
| elimg-bridge.netlify.app | https://elimg.kr | 1 |
| elimg-bridge1.netlify.app | https://elimg.kr | 1 |
| glocalbridge-fusion.netlify.app | https://elimg.kr | 1 |
| cbmc-hanmaeum-v3.netlify.app | https://gimhae-cbmc.netlify.app | 2 |
| cbmc-gimhae.netlify.app | https://gimhae-cbmc.netlify.app | 2 |
| cbmc-gimhae-hanmaeum.netlify.app | https://gimhae-cbmc.netlify.app | 2 |
| cbmc-gimhae-hanmaeum1.netlify.app | https://gimhae-cbmc.netlify.app | 2 |
| cbmc-hanmaeum-v2.netlify.app | https://gimhae-cbmc.netlify.app | 2 |
| elimgimpact-genesis01.netlify.app | https://elimgimpact-genesis.netlify.app | 3 |
| impact-leviticus.netlify.app | https://elimgimpact-leviticus.netlify.app | 3 |
| green4-mission.netlify.app | https://green-mission.netlify.app | 3 |
| glocalbridg-vn.netlify.app | https://glocalbridge-vn.netlify.app | 3 |
| glocalbridge-thai01.netlify.app | https://glocalbridge-thai.netlify.app | 3 |
| elimgw01.netlify.app | https://elimg.kr | 4 |
| elimggmmc1.netlify.app | https://elimg.kr | 4 |
| elimg-han01.netlify.app | learn.elimg.kr (구축 후) | 5 |
| gimhae1.netlify.app | elimg.kr/regions/gimhae/ (구축 후) | 5 |

## Netlify 예시
각 구사이트의 _redirects 파일:
```
/* https://TARGET.example.com/:splat 301!
```

주의: 실제 적용 전 해당 사이트의 저장소와 배포 연결을 확인해야 한다.
