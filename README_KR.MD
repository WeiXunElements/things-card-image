# things-card-image
## 이는 명함과 비슷한 방법으로, 이미지 및 설명으로 이미지 정보를 표현하는 카드 형태의 컴포넌트이다.

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

먼저 [Polymer CLI](https://www.npmjs.com/package/polymer-cli)가 설치되어 있는지 확인한다. 다음, `polymer serve`를 실행하여 로컬에서 응용 프로그램을 제공한다.

### 2.2 Application 실행

```
$ polymer serve
```

### 2.3 Application 빌드

```
$ polymer build
```

아래 명령어로 `build/bundled`나 `build/unbundled`에서 서버를 띄울 수 있다.

```
$ polymer serve build/bundled
```

### 2.4 Tests 실행

```
$ polymer test
```

[web-component-tester](https://github.com/Polymer/web-component-tester)에서 설명한 대로, 테스트 설정은 이미 완료되어 있다.
아래 명령어로 테스트를 실행할 수 있다.
```
$ polymer test
```
