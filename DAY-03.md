## Networking

# Using Fetch

**Making requests**

- 첫번째 단계 : 
- URL to fetch : fetch('https://mywebsite.com/mydata.json');

- 두번째
- 헤더를 지정하거나 POST 요청
fetch('https://mywebsite.com/endpoint/', {
  method: 'POST',
  headers: {
    Accept: 'application/json',
    'Content-Type': 'application/json',
  },
  body: JSON.stringify({
    firstParam: 'yourValue',
    secondParam: 'yourOtherValue',
  }),
});

**Handling the response**
- 결과는 비동기 방식으로 오므로 promise 통해 핸들링 한다.
- ES2017 async/await 지원 가능

**특이사항***
- 기본적으로 iOS는 SSL을 사용하여 암호화되지 않은 요청을 차단
- App Transport Security 예외를 추가

**Using Other Networking Libraries**
- XMLHttpRequest API or third party libraries such as frisbee or axios 를 사용 할 수 있다.
 
**WebSocket Support**
- 웹소켓 지원

## More Resources
- 누군가 많이 만들어 놓았다. 가져다 쓰자.
