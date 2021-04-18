# 소프트웨어마에스트로 카카오워크 챗봇 예제

이 프로젝트는 카카오워크 챗봇을 이용하여
워크스페이스 소속 유저들에게 설문 조사 메세지를 전송하고 모달을 띄워 설문을 받는 예제입니다.

## 예제 시나리오

1. [서버] 유저 조회
2. [서버] 조회된 모든 유저에게 각각 채팅방 생성 후 설문조사 메세지 전송
3. [유저] 메세지를 통해 설문조사 모달 띄움 (/request)
4. [유저] 설문조사 모달을 통해 설문조사를 하고 결과를 전송 (/callback)
5. [서버] 설문조사 결과를 받고 유저에게 결과 메세지를 전송

## 카카오워크 챗봇 개발 가이드

1. 유저 조회
2. 유저와 대화를 시도할 채팅방 생성
3. 생성된 채팅방으로 메세지 전송 (알림형, 반응형)
4. 대화 유형에 따라 유저와 상호작용
