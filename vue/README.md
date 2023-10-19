# 결제위젯 Vue.js 샘플 프로젝트

결제위젯 JavaScript SDK를 이용해서 간단한 주문서 페이지를 만들어 보는 샘플 프로젝트입니다. 자세한 연동 방법과 결제 과정은 [공식 연동 문서](https://docs.tosspayments.com/guides/payment-widget/integration)에서 확인하세요.

## 데모

[데모](https://codesandbox.io/s/payment-widget-vue-sample-ph0nvp)

## 시작하기

먼저 이 레포지토리를 클론합니다.

```
$ git clone https://github.com/tosspayments/payment-widget-sample # 샘플 프로젝트 클론
$ cd payment-widget-sample/vue
```

의존성 패키지를 다운로드하고 서버를 실행합니다.

```
npm install
npm run serve
```

## Q. 결제 요청 후 계속 로딩 중인 화면이 보인다면?

아직 결제 요청 중이에요. 이어서 요청 결과를 확인한 뒤, 결제 승인 API 호출까지 해야 결제가 완료돼요. iframe을 사용하면 요청 결과 페이지(`successUrl`, `failUrl`)로 이동할 수가 없으니 유의하세요.

## 더 알아보기

- 토스페이먼츠 개발 블로그 👉 [30분 안에 결제 페이지 개발하기 (ft. 결제위젯)](https://velog.io/@tosspayments/결제위젯으로-30분안에-결제-페이지-개발하기)

- 토스페이먼츠 연동 문서 👉 [결제위젯 이해하기](https://docs.tosspayments.com/guides/payment-widget/overview) | [결제위젯 연동 문서](https://docs.tosspayments.com/guides/payment-widget/integration)
