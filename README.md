# xray for CodeSandbox

在 CodeSandbox 部署 xray 节点

打开CodeSandbox官网：https://codesandbox.io/signin ，登陆自己的GitHub / 谷歌 / 苹果账号

具体操作方法请看教程：教程链接：https://blog.misaka.rest/2023/03/24/codesandbox-xray/

## 项目特点

* 本项目用于在任意一家PaaS云服务商部署xray ，采用的方案为 Nginx + WebSocket + VMess/Vless/Trojan/Shadowsocks + TLS
* vmess 和 vless 的 uuid 或 trojan 和 shadowsocks 的密码，路径既可以自定义，又或者使用默认值
* 部署完成如发现不能上网，请检查域名是否被墙，可使用 Cloudflare CDN 或者 worker 解决。

## 部署

* 注册 [CodeSandbox](https://codesandbox.io/)
* 项目用到的变量
  | 变量名 | 是否必须 | 默认值 | 备注 |
  | ------------ | ------ | ------ | ------ |
  | UUID         | 否 | de04add9-5c68-8bab-950c-08cd5320df18 | 可在线生成 https://www.uuidgenerator.net/ |
  | VMESS_WSPATH | 否 | /vmess | 以 / 开头 |
  | VLESS_WSPATH | 否 | /vless | 以 / 开头 |
  | TROJAN_WSPATH | 否 | /trojan | 以 / 开头 |
  | SS_WSPATH | 否 | /shadowsocks | 以 / 开头 |

## 鸣谢

ifeng 的 v2ray 项目：https://github.com/hiifeng/V2ray-for-Codesandbox

## 免责声明

* 本程序仅供学习了解, 非盈利目的，请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权, 如转载须注明来源。
* 使用本程序必循遵守部署免责声明。使用本程序必循遵守部署服务器所在地、所在国家和用户所在国家的法律法规, 程序作者不对使用者任何不当行为负责.

## 赞助

* https://afdian.net/a/Misaka-blog


