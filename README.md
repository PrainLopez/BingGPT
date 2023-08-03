<p align="center">
  <img width="180" src="./icon.png" alt="BingGPT">
  <h1 align="center">BingGPT</h1>
  <p align="center">Desktop application of new Bing's AI-powered chat</p>
</p>

<p align="center">
  <a href="https://opensource.org/licenses/Apache-2.0">
    <img alt="License" src="https://img.shields.io/badge/license-Apache_2.0-green">
  </a>
  <a href="https://github.com/dice2o/BingGPT/releases">
    <img alt="Downloads" src="https://img.shields.io/github/downloads/dice2o/BingGPT/total?color=blue">
   </a>
</p>

## 说明
很显然，这是个fork。最新版可能没空打包，请自行编译。但你可以瞅一眼Release，能用就不必追求最新。
(2023.8.3)今日发现微软更新了ip检测，解决方法为更新`X-Forwarded-For`字段为“可靠”的IP地址（修改报头该字段代码位于`main.js line287`)
  ——本人从梯子上扒了一个日本家宽IP，实测正常，可能涉敏故没有push，闲得无事会考虑更新成JSON配置文件（自己凭脑子挖的坑凭什么填）

## 安装
1. `git clone`
2. `yarn install`
3. `yarn run make`

## 此fork已经解决的问题
1. 根治白屏问题。
2. 支持复制粘贴快捷键。
3. 根治落回中国区的问题。（每次启动时会解除cookie毒化。使用中落回请重启app解毒。）


## Screenshot

<img width="601" src="./screenshot.png" alt="BingGPT Screenshot">

## License

Apache-2.0 License
