# mmf-blog vuejs 2.0 v2版

demo: [http://vue2.mmxiaowu.com](http://vue2.mmxiaowu.com)

---

#### 其他版本

react版本: [https://github.com/lincenying/mmf-blog-react](https://github.com/lincenying/mmf-blog-react)

react(dva)版本: [https://github.com/lincenying/mmf-blog-dva](https://github.com/lincenying/mmf-blog-dva)

vue1版本: [https://github.com/lincenying/mmf-blog-vue](https://github.com/lincenying/mmf-blog-vue)

vue2版本: [https://github.com/lincenying/mmf-blog-vue2](https://github.com/lincenying/mmf-blog-vue2)

vue2(jsx语法)版本: [https://github.com/lincenying/mmf-blog-vue2-jsx](https://github.com/lincenying/mmf-blog-vue2-jsx)

vue2(jsx语法,leancloud)版本: [https://github.com/lincenying/mmf-blog-vue2-jsx-lc](https://github.com/lincenying/mmf-blog-vue2-jsx-lc)

vue2 服务端渲染版本: [https://github.com/lincenying/mmf-blog-vue2-ssr](https://github.com/lincenying/mmf-blog-vue2-ssr)

---

先安装 api server:

https://github.com/lincenying/mmf-blog-api-v2 (express版)

https://github.com/lincenying/mmf-blog-api-koa2-v2 (koa2版)

```bash
# 安装依赖
npm install  #or  yarn
# 注意: 不要用 cnpm 安装依赖

# 生产模式
npm run build

# 开发模式
npm run dev
```

首页
http://localhost:8080

登录
http://localhost:8080/admin.html

# 注意:
由于`babelrc`配置了
```
"presets": [
    ["env", {
        "targets": {
            "chrome": 52
        }
    }]
]
```
所以, 在开发环境下, 请用 chrome52+ 打开, 如果需要其他低版本浏览器, 请自行修改根目录的`.babelrc`文件