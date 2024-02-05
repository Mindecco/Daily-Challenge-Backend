# 데일리 챌린지

1일 1챌린지를 사용자들끼리 공유하거나 같이 도전하면서 사용자의 챌린지를 달성함으로써 더 나은 삶이 되도록 도와주는 애플리케이션입니다.

## 요구사항 분석
- 사용자는 네이버 / 구글 / github 등과 연동하여 로그인을 할 수 있다.(Oauth2.0)
- 사용자가 챌린지를 생성하거나 삭제할 수 있다.
- 챌린지 참여 희망 시, 로그인한 이메일 정보로 인증 코드를 받아서 참여할 수 있다.
- 마감시간 동안 인증 이미지 업로드가 없을 시, 자동으로 챌린지그룹에서 탈퇴된다.
- 현재 챌린지 리스트를 조회하거나, 내 인증 내역을 조회할 수 있다.
- 해당 챌린지의 참여자 정보와 인증정보를 조회할 수 있다.
## 기술 스택
- FE: html ( BE 토이프로젝트 이기 때문에 SSR 로 FE 개발을 최소화 )
- BE: java, spring boot, timeleft spring batch, spring security, jpa, QueryDSL
- infra: AWS( EC2, S3, CloudFront ), NginX
- RDB: postgresql
- cache: redis
- architecture: 레이어 아키텍처, 모놀리식 아키텍처
- 개발방법론: TDD
- 인증: OAuth2.0, JWT

## 시스템 구성도

![image](https://github.com/Mindecco/Daily-Challenge-Backend/assets/123062528/3e4a61ce-9332-46c1-bb81-ef0ae3fcb5d1)
<초기구성>



