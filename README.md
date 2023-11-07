# Migration Youreca Project From ReactJS to NextJS
ReactJS -> NextJS 13 마이그레이션 도전입니다.

현재 굉장히 지저분한 Youreca 프로젝트의 코드들을 마이그레이션 해야하기 때문에 엄청난 시간을 투자할 생각입니다.

기존 Youreca 프로젝트 Repository : [Youreca](https://github.com/JunhOpportunity/youreca)

## 문제점
1. 디렉토리 구조 엉망
2. 컴포넌트 간 너무 많은 의존성
3. 구 버전 Firebase 문법 사용
4. 코드의 복잡도가 굉장히 높음

## 구현 과정
1. 디렉토리 구조 정립 (다이어그램)
2. Firebase 신버전 API 함수 정리
3. 원본 코드 리팩토링
4. 마이그레이션
  a. git flow 활용한 브랜치 관리
  b. commit 컨벤션 기반으로 commit 관리
  c. issues 적극 활용
5. Redux 적용

### 다이어그램
- Firebase-Firestore 데이터 구조 정리

  ![image](https://github.com/JunhOpportunity/youreca-nextjs-migration/assets/89464762/cd7fb355-af4c-496b-87c8-394d8fcf3464)
