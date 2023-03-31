# Docker Challenge 사전 미션

## 1. 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)

`컨테이너 기술`은 애플리케이션과 그 종속성을 격리된 환경에서 실행하도록 하는 가벼운 가상화 방식으로, 일관된 실행 및 배포를 가능하게 하며, 리소스 효율성과 유연성을 제공합니다.

## 2. 도커란 무엇입니까? (100자 이내로 요약)

`도커`는 컨테이너 기술을 기반으로 하는 오픈 소스 플랫폼으로, 애플리케이션 개발, 패키징, 배포를 쉽게 관리할 수 있게 해주며, 프로젝트 간의 환경 충돌 문제를 최소화합니다.

## 3. 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?

- `도커 파일(Dockerfile)`: 애플리케이션 실행에 필요한 환경과 설정을 정의한 텍스트 파일입니다. 도커 파일을 사용해 도커 이미지를 빌드합니다.

- `도커 이미지(Docker Image)`: 도커 파일에 정의된 환경과 설정을 포함하는 불변의 스냅샷입니다. 이 이미지를 사용해 도커 컨테이너를 생성할 수 있습니다.

- `도커 컨테이너(Docker Container)`: 도커 이미지를 기반으로 실행되는 격리된 프로세스입니다. 컨테이너는 이미지의 상태를 유지하며, 여러 인스턴스를 동시에 실행할 수 있습니다.

- `관계`: 도커 파일 -> 도커 이미지(빌드) -> 도커 컨테이너(실행) 순으로 연결됩니다.