# things-card-image
## 이미지 정보를 이미지와 설명형태로 명함과 비슷한 모양으로 표현하는 카드형태의 컴포넌트

```html
<things-card-image-list
  items="[[items]]"
  use-file-service-url
  image-field="path"
  detail-fields="name,description,mimetype,tag"
  is-selector>
</things-card-image-list>
```



## 2. 개발
### 2.1 Polymer-CLI 설치

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### 2.2 Application 수행

```
$ polymer serve
```

### 2.3 Application 빌드

```
$ polymer build
```

아래 명령어로 ` build/bundled`나 ` build/unbundled`에서 서버를 띄울수 있다.

```
$ polymer serve build/bundled
```

### 2.3 Running Tests

```
$ polymer test
```

테스트는 [web-component-tester](https://github.com/Polymer/web-component-tester)에서 설명한데로 설정완료됨.
아래 명령어로 테스트를 수행할 수 있다.
```
$ polymer test
```
