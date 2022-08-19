# FxMinerProxyV3
## zh
 
## en
 bash <(curl -s -L https://raw.githubusercontent.com/FxPool/FxMinerProxyV3/main/install_en.sh)
 
 # FXMinerProxyV3
<h4 align="center">基于Golang高性能Pow挖矿代理中转服务器软件.</h4>
<h4 align="center">支持ETH/ETC/BTC/LTC/RVN/CFX/TON/BEAM/ERG/BTG.</h4>
<h4 align="center">官网(http://www.fxpool.org).</h4>
<p align="center">
  <a>
    <img src="https://img.shields.io/badge/Release-8.0.2-orgin.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Last_Update-2022_06_02-orgin.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Language-GoLang-green.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/License-Apache-green.svg" alt="travis">
  </a>
</p>

  ![]https://raw.githubusercontent.com/FxPool/FxMinerProxyV3/main/image/home.png
  
## :sparkles: 特性

* :cloud: 支持ETC,ETH,BTC,LTC,RVN,BEAM,ERG,CFX等多币抽水,内置独家开发的加密混淆客户端 一键配置自动生成执行程序win和os都支持,API 开放 UI源码开放，独家任何币种双挖支持
* :zap: 高性能百万并发CPU占用极低，30万连接cpu占用10%
* 💻 自定义作者抽水模式(范围0.1-0.2%)，PID抽水算法稳定算力曲线减少切换损耗，实时统计抽水转换率
* 📚 原创抽水算法针对e池优化e池抽水效果最好，无矿机离线bug曲线完美，比其他软件高出几个点
* 💾 安全稳定，原创aes混淆加密，模拟物联网流量安全稳定，后台一键配置自动生成window和linux版本，传统TLS/SSL TCP也支持，防御CC攻击
* :gear: 前置代理模式，内部配置提高访问速度，延迟快速响应支持，让用户的显示的延迟是你当前代理服务器的延迟
* :outbox_tray: 芯片矿机实时计算算力，解决芯片级无法显示算力的问题
* :card_file_box: 配置热修改，决绝传统配置后需重启修改配置文件等繁琐步骤，支持一键导入导出配置文件
* :art: 精美UI，支持历史记录曲线管理详细到单台矿机支持
* :eye_speech_bubble: 多人社区交流支持，不懂的问题都有人解答，QQ群:809118996，Telegram讨论组:
* :gear: 实时系统错误日志显示，让你知道任何时候服务器工作状态
* :family_woman_girl_boy: 多系统支持，windows，linux一键安装运行

## :hammer_and_wrench: 部署
### linux一键管理脚本(需root权限)
* 如果没有curl命令请输入 apt-get install curl 安装
```shell
  bash <(curl -s -L https://raw.githubusercontent.com/FxPool/FxMinerProxyV3/main/install_zh.sh)
```
### windows直接下载解压运行run.exe
* 运行run.exe（可保证程序永不死机）
```shell
  https://raw.githubusercontent.com/FxPool/FxMinerProxyV3/main/fxminerproxyv3windows.zip
```  
## :alembic: 开发抽水  
* 固定0.27%  
