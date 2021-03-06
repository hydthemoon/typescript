# 타입스크립트 퀵스타트

<img src="https://github.com/happygrammer/typescript/blob/master/cover.jpg" width="250px">

* [예스24](http://www.yes24.com/24/goods/59719961?scode=029)
* [알라딘](http://www.aladin.co.kr/shop/wproduct.aspx?ItemId=141259576)
* [교보문고](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791186710302&orderClick=LAG&Kc=) [[미리보기]](http://preview.kyobobook.co.kr/preview.jsp?siteGb=INK&ejkGb=KOR&barcode=9791186710302&loginYn=N&orderClick=JAW)
* [반디앤루니스](http://www.bandinlunis.com/front/product/detailProduct.do?prodId=4167786)
* [인터파크](http://shopping.interpark.com/product/productInfo.do?prdNo=5618034908&dispNo=008001082&pis1=shop&pis2=product)

## 소스 코드 환경

- 타입스크립트 : 2.7.2
- Node.js : 8.9.4
- ts-node : 3.3.0

## 정오표
- 2쪽, 그림 1-1
	- ES6의 출시 년도 `2013` => `2015`
- 100쪽, 아래서 3번째 줄 중간
	- 40 (10 * 22) => 40 (10 * 2 * 2)
- 104쪽, 그림 3-8 마지막 줄
	- `number2.notExistMethod();` => `number.notExistMethod();`
- 174쪽, 예제 6-11 제목 (화살표 함수와 관계 없음)
	- 활살표 함수에서 this 사용 => 함수에서 this 사용
- 180쪽, 첫 예제 첫 줄 반환 타입 설정
	- `(message: string) => void;` => `(message: string) => string;`
- 180쪽, 예제 6-13 2번째 줄 반환 타입 설정
	- `(message: string) => void;` => `(message: string) => string;`
- 180쪽, 마지막 예제 첫 줄 반환 타입 설정
	- `(message: string) => void;` => `(message: string) => string;`
- 244쪽, 예제 7-25 두번째 줄 생성자
	- `private EagerLogger() { }` => `private constructor() { }`
- 245쪽, 예제 7-26 여섯번째 줄 생성자
	- `private EagerLogger() { }` => `private constructor() { }`
- 282쪽 두번째 예제 소스코드 경로
	- ch8/module/src/module/re-exports/my-cars.ts => ch8/module/src/module/re-exports/engine.ts
- 343쪽, 그림 10-1의 왼쪽 그림과 오른쪽 그림
	- `let myNum:any = "2017";` => `let myNum= "2017";`​
- 520쪽, 2번째 줄
	- "데이터를 있는 그대로 출력합니다." => "HTML을 제거해 데이터를 출력합니다"

- 520쪽, 3번째 줄
	- `<%=listHTML%>` => `<%-listHTML%>`
	
## 보완 설명

- 197쪽 [예제7-4](https://github.com/happygrammer/typescript/blob/master/ch7/class/src/class/modifier/super-this.ts)
	- get/set 접근자는 ES5로 표현되기 어려워 ES5이하로 컴파일이 지원되지 않습니다.
- 367쪽 [예제11-4](https://github.com/happygrammer/typescript/blob/master/ch11/generics/src/default/concat5.ts)
	- TS 2.0.0에서 concat4함수의 "return strs + strs2;"에 대한 주석을 해제하면 T+T 연산 오류가 있습니다.
	- 그러나 2.1 버전 이후에는 T+T 연산 오류가 없음을 안내드립니다.
	- 컴파일러 버전에따른 타입 검사 방식 변경이 있을 수 있는데 관련설명은 111쪽을 참고해 주시길 부탁드립니다.

## 타입스크립트 최근 소식
- `2020-02-20` [타입스크립트 3.8 출시](https://devblogs.microsoft.com/typescript/announcing-typescript-3-8/)
- `2020-01-10` [타입스크립트 3.8.beta 출시](https://devblogs.microsoft.com/typescript/announcing-typescript-3-8-beta)
- `2019-11-05` [타입스크립트 3.7 출시](https://devblogs.microsoft.com/typescript/announcing-typescript-3-7)
- `2019-08-28` [타입스크립트 3.6 출시](https://blogs.msdn.microsoft.com/typescript/2018/07/30/announcing-typescript-3-6)
- `2019-05-29` [타입스크립트 3.5 출시](https://devblogs.microsoft.com/typescript/announcing-typescript-3-5)
- `2019-03-29` [타입스크립트 3.4 출시](https://devblogs.microsoft.com/typescript/announcing-typescript-3-4)
- `2019-01-31` [타입스크립트 3.3 출시](https://devblogs.microsoft.com/typescript/announcing-typescript-3-3)
- `2018-11-29` [타입스크립트 3.2 출시](https://devblogs.microsoft.com/typescript/announcing-typescript-3-2)
- `2018-10-08` [타입스크립트 3.1 출시](https://devblogs.microsoft.com/typescript/announcing-typescript-3-1)
- `2018-07-30` [타입스크립트 3.0 출시](https://blogs.msdn.microsoft.com/typescript/2018/07/30/announcing-typescript-3-0/)
	- Typescript 3.0의 새로운 특징 [git](https://github.com/Microsoft/TypeScript/wiki/What%27s-new-in-TypeScript) [doc](https://www.typescriptlang.org/docs/handbook/release-notes/typescript-3-0.html)
- `2017-04-23` [타입스크립트 2.3 출시](https://blogs.msdn.microsoft.com/typescript/2017/04/27/announcing-typescript-2-3/)

## 타입스크립트와 관련해 읽을 만한 글
- [타입스크립트 언어 사양서](https://github.com/Microsoft/TypeScript/blob/master/doc/spec.md)
- 타입스크립트 요약 페이지
	- [https://hygull.github.io/](https://hygull.github.io/type-script/)
- 타입스크립트 공식 문서
	- [Module Resolution](https://www.typescriptlang.org/docs/handbook/module-resolution.html)

## 타입스크립트 주요 사이트
- [타입스크립트 트위터](https://twitter.com/typescriptlang)
- [타입스크립트 릴리즈노트](https://github.com/Microsoft/TypeScript/releases)
