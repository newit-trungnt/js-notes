# JS note

## Boolean trap

```js
// What does `false` stand for?
results.reload(false);

// What does `true` stand for?
const user = new User(true);
```

Xem xét ví dụ ở trên, chúng ta có thể thấy rằng đoạn code của tương đối khó hiểu.

- Đầu tiên, chúng ta xét function `reload`. Nó nhận vào một đối số giá trị là `false`. Tôi nghĩ rằng đa số chúng ta có thể đoán hoặc nghĩ rằng nó có nghĩa là không thưc hiện reload. Điều này cũng hợp lý. Tuy nhiên, một cách lý luận khác, chúng ta cũng có thể nghĩ rằng giá trị `false` ở đây biểu thị cho một flag để function không thực hiện một hành động nào đó, ví dụ như call api, thực hiện một annimation nào đó, ...


### What ?
