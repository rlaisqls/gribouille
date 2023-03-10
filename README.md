# gribouille

[netty socketio](https://github.com/mrniko/netty-socketio)를 kotlin으로 재작성 및 개선해보는 프로젝트입니다.

## 목표

- netty 라이브러리를 직접 사용해봄으로써 낮은 추상화 수준의 자바 네트워킹 경험해보기
- java 코드를 kotlin으로 변환하며 마이그레이션 및 큰 리팩토링 경험해보기

## 앞으로 수정할 것

- [ ] HashedWheelTimer 코루틴으로 구현
- [ ] unchecked type cast 제네릭으로 개선
- 리팩토링 하기
  - [ ] docs 한글로 변환
  - [ ] open class 명시
  - [ ] 가독성 개선
  - [ ] 코드 단순화 (목적에 불필요한 코드 수정 혹은 삭제)
  - [ ] 보다 코틀린스러운 코드
  - [ ] 단정 연산자 줄이기 (변수 not null로 수정, 혹은 null safe하게 처리)

## 기간

- 전반적인 리팩토링 `~2023.04.30`
- 프로젝트 진행하다가 시간 남으면 작업, 추후 하고싶은거 더 생기면 추가될 예정입니다.

## 배운점 정리

- [netty 서버 예제](https://github.com/rlaisqls/TIL/blob/main/%EA%B0%9C%EB%B0%9C/netty/netty%E2%80%85server%E2%80%85%EC%98%88%EC%A0%9C.md)
- [자바<?>와 코틀린<*>](https://github.com/rlaisqls/TIL/blob/main/%EC%96%B8%EC%96%B4%E2%80%85Language/%EC%9E%90%EB%B0%94%3C%EF%BC%9F%3E%EC%99%80%E2%80%85%EC%BD%94%ED%8B%80%EB%A6%B0%3C*%3E.md)

## 참고 자료

- [책: 네티 인 액션](http://www.yes24.com/Product/Goods/25662949)
