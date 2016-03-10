# Lu-Hire

陆金所大前端招聘！ *[职位描述](https://promo.lu.com/activity-pages/job-20150213/detail.html#box3)*

下面小题任选2~3道完成，时间不限，做法不限（可以使用任何类库或框架，比如 jQuery、Angular、React 等）。

1. [陆金所首页](https://www.lu.com/)的图片轮播块；

![slider](images/slider.png)

2. 实现可发送 JSONP 请求、获取 JSONP 返回结果的函数：

```javascript
JSONP(url, {
  data: {
    key1: value1
  },
  callback: function (data) {
    // data 是服务端返回的数据
  }
})
```

可以使用 [Flickr API](http://api.flickr.com/services/feeds/photos_public.gne?tags=cat&tagmode=any&format=json&jsoncallback=?) 作为测试接口。

3. 使用任意一种服务端语言或框架，实现包含注册、登录和退出的账户功能。

> **提示**：提交的数据可以是零时存储在内存中（不用落到数据库），注意 Cookie 和 Session 的运用。

4. 编写 Grunt/Gulp **插件**，可以将 [test.html](fixtures/test.html) 中的所有外链的 CSS 标签删除。

```html
// 删除前
...
<meta content="telephone=no" name="format-detection" />
<link rel="shortcut icon" href="//static.lufaxcdn.com/config/images/favicon-new.ico" />
<link type="text/css" rel="stylesheet" href="//static.lufaxcdn.com/lufax-public/base/base.1c52d4c1.css"/>
...


// 删除后
```
...
<meta content="telephone=no" name="format-detection" />
<link rel="shortcut icon" href="//static.lufaxcdn.com/config/images/favicon-new.ico" />
...
```

完成后可以打包发到我的邮箱，island205#gmail.com。
