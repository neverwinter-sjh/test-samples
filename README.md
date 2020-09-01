# Test Samples

Vanilla Javascript 내용 중 궁금하거나 실험이 필요한 내용을 테스트해 보는 저장소

### 1. promise-test.html

* ajax 통신 외에 promise 패턴을 사용할 필요가 있나 하는 궁금증으로 테스트해봄
* 0부터 59999까지 i를 1씩 증가시키고 계산이 끝나면 로그를 남긴다.
* while을 사용하여 i를 증가함
* i === 59999가 되면 resolve를 실행함.
* main 함수는 async를 사용함
* 결과: 계산이 모두 끝난 후에 로그가 실행되었다.
* 특정 계산이나 명령을 순서대로 실행할 필요가 있을 때 개별 함수는 promise 패턴으로
메인 함수는 async await으로 실행해 주면 깔끔한 코드가 나올 수 있다.

