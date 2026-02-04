# 구글 애드센스 승인 가이드

> 출처: [WebToolUSA](https://www.webtoolusa.com/2024/11/google-adsense-approval-checklist.html), [ToxiGon](https://toxigon.com/adsense-approval-tips) 등 참고 (Content was rephrased for compliance with licensing restrictions)

---

## 📋 필수 요건

### 1. 기본 조건
- **나이**: 만 18세 이상 (미만일 경우 부모 계정으로 신청)
- **도메인**: 최상위 도메인 사용 (.com, .net, .org 등) - 무료 도메인 X
- **도메인 나이**: 최소 6개월 이상 권장

### 2. 콘텐츠 요건
- **최소 게시물 수**: 20~30개 이상의 고유 콘텐츠
- **글 길이**: 게시물당 1,000~2,000 단어 권장
- **독창성**: AI 생성 콘텐츠, 복사/표절 콘텐츠 절대 금지
- **가치 제공**: 사용자에게 유용하고 흥미로운 정보 제공

### 3. 필수 페이지 (반드시 포함)
- About Us (소개)
- Contact Us (연락처)
- Privacy Policy (개인정보처리방침)
- Terms and Conditions (이용약관)
- Disclaimer (면책조항)

---

## 🎯 승인 전 체크리스트

### 웹사이트 기술 요건
- [ ] 빠르고 가벼운 테마 사용
- [ ] 모바일 반응형 디자인
- [ ] Google PageSpeed Insights 점수 양호
- [ ] 깔끔한 UI/UX, 명확한 네비게이션
- [ ] 헤더 메뉴에 카테고리 구성
- [ ] 관련 게시물 내부 링크 연결
- [ ] 쿠키 동의 배너 표시

### Google 연동
- [ ] Google Search Console 연결 및 사이트맵 제출
- [ ] Google Analytics 연결
- [ ] 소셜 미디어 계정 연결 (Facebook, Instagram 등)

### 트래픽
- [ ] 최소 일일 50~100 페이지뷰 확보
- [ ] 자연 검색(SEO) 트래픽 확보 노력

---

## 🚫 금지 사항 (거절 사유)

1. **콘텐츠 관련**
   - 복사/표절 콘텐츠
   - AI로 생성한 콘텐츠
   - 저작권 침해 자료
   - 오해를 유발하는 콘텐츠
   - 불법적인 내용

2. **기술적 문제**
   - 공사 중인 웹사이트
   - 깨진 링크, 빈 페이지
   - 부적절한 네비게이션
   - 다른 광고 네트워크 코드 (신청 전 제거)

3. **정책 위반**
   - 개인정보 수집 미고지
   - 아동 개인정보 보호법(COPPA) 위반
   - 스팸성 행위

---

## 📝 신청 과정 체크리스트

### 신청 전
- [ ] 위 체크리스트 모두 완료 확인
- [ ] 예약 게시물 2~3개 준비 (심사 중 꾸준히 발행)
- [ ] 다른 광고 네트워크 코드 제거

### 신청 시
1. ads.txt 파일 추가
2. 애드센스 코드를 `<head>` 태그에 삽입
3. 사이트 등록 신청

### 신청 후 (심사 기간: 1~14일)
- [ ] 평소처럼 게시물 발행 유지
- [ ] 웹사이트 디자인/구조 변경 금지
- [ ] 비정상적인 트래픽 유도 금지 (친구/가족에게 방문 요청 X)
- [ ] 인내심 유지

---

## ✅ 현재 사이트 적용 상태

| 항목 | 상태 | 비고 |
|------|------|------|
| 애드센스 스크립트 | ✅ 추가됨 | index.html `<head>` |
| ads.txt | ✅ 생성됨 | 루트 디렉토리 |
| Publisher ID | ⚠️ 교체 필요 | `ca-pub-XXXXXXXXXXXXXXXX` → 실제 ID |
| Privacy Policy | ✅ 생성됨 | privacy-policy.html |
| Terms of Service | ✅ 생성됨 | terms.html |
| About Us | ✅ 생성됨 | about.html |
| Contact Us | ✅ 생성됨 | contact.html |
| 쿠키 동의 배너 | ✅ 추가됨 | index.html 하단 |
| Footer 링크 | ✅ 업데이트됨 | 필수 페이지 링크 포함 |

---

## 🔧 추가 권장 작업

1. ~~**필수 페이지 추가**~~: ✅ 완료 (Privacy Policy, Terms, About, Contact)
2. **콘텐츠 보강**: 사이트 관련 유용한 글 20개 이상 작성 (블로그 섹션 추가 권장)
3. **Google 연동**: Search Console, Analytics 설정
4. **트래픽 확보**: SEO 최적화, 소셜 미디어 홍보
5. **Publisher ID 교체**: 애드센스 승인 후 실제 ID로 교체

---

*마지막 업데이트: 2026년 2월*
