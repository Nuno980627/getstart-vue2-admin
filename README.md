# getstart-vue2-admin

> 这是一个基于vue-admin-template,再度精简的模板,基于vue2与element的后台管理系统模板，并遵循原作者MIT LICENSE

## 项目由来
在vue2时代,本人经手的后台模板项目,均选择了vue-element-admin,能满足基本开发需求,原作者在继承模板基础之下,   
也整合了一个基础模板vue-element-template。   
为了做到后期项目做到"拎包入住",快速启动开发,本人在vue-element-template基础下,再度简化车轮,删掉了一些内容相关。   
取名getstart-vue2-amdin  快速启动、vue2、后台管理系统   
**遵循原作者MIT开源协议**
[getstart-vue2-amdin](https://github.com/Nuno980627/getstart-vue2-admin)
[vue-admin-template](http://panjiachen.github.io/vue-admin-template)
[vue-element-admin](https://github.com/PanJiaChen/vue-element-admin)



## 精简内容

- views 保留了原项目login、与dashboard,其余页面都删除
- mock 保留登入mock数据,原作者的index和mock-server还有一些utils方法,其余都删除
- vue router 保留基础的login、dashborad、404其余均删除
- vuex 全部保留,原项目也只有login模块,后期开发可做参考

## 使用
保留原项目基本架构
与模板没做任何改变

自己独特的一些理解与使用,后期有空自己也会写一个文档,将一些自己项目中的改变用法

更多信息请参考原作者 [使用文档](https://panjiachen.github.io/vue-element-admin-site/zh/)

## Build Setup

```bash
# 克隆项目
git clone https://github.com/PanJiaChen/vue-admin-template.git

# 进入项目目录
cd vue-admin-template

# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装以来，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

浏览器访问 [http://localhost:9528](http://localhost:9528)

## 发布

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```

## 其它

```bash
# 预览发布环境效果
npm run preview

# 预览发布环境效果 + 静态资源分析
npm run preview -- --report

# 代码格式检查
npm run lint

# 代码格式检查并自动修复
npm run lint -- --fix
```
## git
方便建立新的仓库，删除原有的git history
```bash
# 删除原有git
rm -rf .git

# 构建生产环境
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin YourProjectGithubUrl
git push -u origin main
```

## Browsers support

Modern browsers and Internet Explorer 10+.

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari |
| --------- | --------- | --------- | --------- |
| IE10, IE11, Edge| last 2 versions| last 2 versions| last 2 versions
## 联系方式
Nuno 
e-mail:952571278@qq.com
## License
保留原作者MIT license   

本项目也采用MIT license开源   

本项目协议[MIT](https://github.com/Nuno980627/getstart-vue2-admin/blob/main/LICENSE)   

原作者协议[MIT](https://github.com/PanJiaChen/vue-admin-template/blob/master/LICENSE) license.   

Copyright (c) 2020-present Nuno   

Copyright (c) 2017-present PanJiaChen
