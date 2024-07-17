# 카드 뉴스 api 연동하기

## 1.1 비동기 작업

- Fetch API 기본형

```js
window.addEventListener("load", function () {
  // 1. json 호출하고 성공하면
  fetch("url")
    .then((response) => {
      console.log(response);
      return response.json();
    })
    .then((data) => {
      console.log(data);
    })
    .catch((error) => {
      console.log(error);
    });
});
```

## 1.2 두 줄 이상 말 줄임

```css
선택자 {
  -webkit-box-orient: vertical;
  overflow: hidden;
  text-overflow: ellipsis;
  -webkit-line-clamp: 3;
  line-height: 1.5;
  max-height: calc(1.5em * 3);
}
```
