# things-card-image
## It is a card-like component that represents image information in images and descriptions in a manner similar to business cards.

```html
<things-card-image-list
  items="[[items]]"
  use-file-service-url
  image-field="path"
  detail-fields="name,description,mimetype,tag"
  is-selector>
</things-card-image-list>
```



## 2. Development
### 2.1 Install Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### 2.2 Run Application

```
$ polymer serve
```

### 2.3 Build Application

```
$ polymer build
```

You can launch the server from `build/bundled` or `build/unbundled` with the following command:

```
$ polymer serve build/bundled
```

### 2.4 Run Tests

```
$ polymer test
```

The test has been set up as described in [web-component-tester](https://github.com/Polymer/web-component-tester).
You can run the test with the following command.
```
$ polymer test
```
