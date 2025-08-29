# Min's 인테리어 & 쇼핑 웹사이트

## 프로젝트 소개
이 프로젝트는 온라인 **인테리어 쇼핑몰 웹사이트**입니다.  
사용자는 메인 페이지에서 상품과 인테리어 정보를 확인하고, 로그인 및 마이 페이지를 통해 개인화 서비스를 이용할 수 있습니다.

주요 기능:
- **메인 페이지**: 배너 슬라이드, 랜선 집들이, 추천 인테리어 조합
- **로그인 페이지**: 아이디/비밀번호 입력, SNS 간편 로그인
- **마이 페이지**: 계정 정보 확인 및 수정, 스탬프/쿠폰/좋아요 확인
- 검색 기능 및 카테고리 메뉴
- 장바구니 접근
- 푸터 고객센터 정보

---

## 설치 및 실행
1. 저장소 클론
```bash
git clone https://github.com/username/repo.git
open index.html   
open log.html    
open mypage.html   

project/
│
├─ index.html   
├─ log.html     
├─ mypage.html     
├─ css/
│   ├─ common.css
│   ├─ index.css
│   ├─ log.css
│   └─ mypage.css
├─ icon/
│   ├─ logo2.png
│   ├─ kakao.png
│   ├─ google.png
│   ├─ naver.png
│   └─ 기타 아이콘
├─ benner/       
├─ digin/    
└─ img/       


1️⃣ 메인 페이지 (index.html)

상단 로고 클릭 → 메인 페이지 이동

상단 메뉴: 베스트, 쇼핑, 인테리어, 1:1 문의, 고객센터

검색창 + 버튼

로그인 / 마이페이지 / 장바구니 아이콘

메인 배너 슬라이드

랜선 집들이 이미지 섹션

추천 인테리어 조합 이미지 섹션

푸터 고객센터 정보

2️⃣ 로그인 페이지 (log.html)

아이디/비밀번호 입력

로그인 버튼

로그인 정보 저장 체크박스

아이디/비밀번호 찾기, 회원가입 링크

SNS 간편 로그인: Kakao, Google, Naver

3️⃣ 마이 페이지 (mypage.html)

계정 정보 확인 및 수정

프로필 사진 및 닉네임 표시

스탬프, 좋아요, 쿠폰 현황 확인

결제수단, 연락처, 주소 입력 및 수정

정보 수정 버튼

사용 예시
메인 페이지

검색창에 키워드 입력 → 검색 수행

랜선 집들이, 추천 인테리어 이미지 클릭 → 상세 페이지 이동 (추후 구현)

로그인 페이지

아이디와 비밀번호 입력 → 로그인

SNS 아이콘 클릭 시 간편 로그인

마이 페이지

프로필 사진 확인

계정 정보 입력 및 수정

스탬프, 좋아요, 쿠폰 확인

기여 방법

저장소 Fork

브랜치 생성: git checkout -b feature/새기능

변경 사항 Commit: git commit -m 'Add 새로운 기능'

Push: git push origin feature/새기능

Pull request 생성