---
layout: post
title: "Integrating razorpay into your webapp"
date: 2024-02-22 15:28:54 +0200
categories: About Me
---

새로운 도전을 마다하지 않는 개발자

멈춤 없는 성장을 위해 아는 지식에 국한되지 않고 겸허히 새로운 것을 받아들일 준비가 되어 있습니다!!

```javascript
const Razorpay = require("razorpay");

let rzp = Razorpay({
  key_id: "KEY_ID",
  secret: "name",
});

// capture request
rzp.capture(payment_id, cost).then(function (data) {
  return 2;
});
```

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
