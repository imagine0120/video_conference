## Introduction
오픈소스 WebRTC 인 MediaSOUP에 기반한 화상회의 솔루션을 도커 이미지로 구축하는 프로젝트입니다.

## Spec
* OS : Ubuntu 18.04 (WSL on Windows 10) 
* Docker Desktop
* MediaSoup (Node.js + React.js)

## Schedule
### week 1 : 4/4 - 4/10
* 일정 계획 및 개발 준비
   - [x] 레포지토리 생성 및 계획, to-do list 작성 (완료 : 4/4)
   - [x] 로컬에 도커 개발 환경 구성 : WSL2 지원하는 윈도우 버전업(빌드 19042) 및 도커 데스크탑 설치 (완료 : 4/4)
   - [x] 도커 및 쿠버네티스 개념 복습 (4/4 - 진행 중)
   - [x] MediaSOUP 공식 문서 읽고 요구되는 개발 환경 파악 : Linux OS -> Ubuntu:18.04
   
### week 2 : 4/11 - 4/17
   * 개발 시작
   - [x] 리눅스 도커 이미지 pull
   - [x] 리눅스 이미지 위에 MediaSOUP 데모 올리기

<hr/>

## 짧은 후기
* 가상화 기술과 화상통화 기술의 개념을 공부하고 간단하게나마 직접 사용해볼 수 있었습니다. 이 둘 모두 매우 흥미로운 기술입니다.
* 인프런에서 쿠버네티스 관련 강의를 들은 적이 있는데, 확실히 직접 도커를 사용해보니 팟과 이미지 등 추상적으로만 느껴지던 개념이 조금 더 구체적으로 와닿았습니다.
* 아쉬운 것은 업무가 바빠 단순히 도커 이미지 위에 MedaiSoup 데모 라이브러리를 올리는 데서 큰 진전이 없었단 것입니다. 이후 추가 개발을 진행할 예정입니다.
* 올해 안에 직접 줌 같은 화상회의 솔루션을 커스터마이징하여 구현해보고 싶습니다. 이를 위해서는 WebRTC와 네트워크(보안 접속 등)에 대한 이해가 더 필요할 것 같습니다.
