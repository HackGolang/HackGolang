# 《Go语言安全-只有Go安全才能拯救地球》

本项目是记录自己在学习研究Go安全过程中遇到的优秀内容，包括Go代码审计资源以及Go开发的应用程序组件协议等的安全内容。一个不会Go攻击的黑客不是一个好师傅，一个不懂Go安全的师傅不是一个好黑客！深入理解Go安全，手握众多重点Go应用高危0day漏洞！作者：[0e0w](https://github.com/0e0w)

本项目创建于2022年3月15日，最近的一次更新时间为2023年6月9日。本项目会持续更新，直到海枯石烂。

- [01-Go安全研究资源](https://github.com/HackGolang/HackGolang#01-go%E5%AE%89%E5%85%A8%E7%A0%94%E7%A9%B6%E8%B5%84%E6%BA%90)
- [02-Go安全研究工具](https://github.com/HackGolang/HackGolang#02-go%E5%AE%89%E5%85%A8%E7%A0%94%E7%A9%B6%E5%B7%A5%E5%85%B7)
- [03-Go语言漏洞环境](https://github.com/HackGolang/HackGolang#03-go%E8%AF%AD%E8%A8%80%E6%BC%8F%E6%B4%9E%E7%8E%AF%E5%A2%83)
- [04-Go语言漏洞分类](https://github.com/HackGolang/HackGolang#04-go%E8%AF%AD%E8%A8%80%E6%BC%8F%E6%B4%9E%E5%88%86%E7%B1%BB)
- [05-Go语言代码审计](https://github.com/HackGolang/HackGolang#05-go%E8%AF%AD%E8%A8%80%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1)
- [06-Go语言安全开发](https://github.com/HackGolang/HackGolang#06-go%E8%AF%AD%E8%A8%80%E5%AE%89%E5%85%A8%E5%BC%80%E5%8F%91)
- [07-Go安全参考资源](https://github.com/HackGolang/HackGolang#07-go%E5%AE%89%E5%85%A8%E5%8F%82%E8%80%83%E8%B5%84%E6%BA%90)

## 01-Go安全研究资源

一、优秀文章
- [ ] [go代码审计](https://wh0ale.github.io/2019/01/19/2019-1-19-go%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1/)@wh0ale
- [ ] [Go语言代码审计实战](https://forum.butian.net/share/928)@maoge
- [ ] [GOLANG 代码审计笔记](https://mp.weixin.qq.com/s?__biz=MzU5Mjk3MDA5Ng==&mid=2247484163&idx=1&sn=34c82b278c0c8f31bd44b79d16a008c3&chksm=fe16eb1cc961620a9507ac36c70cf1325df868868061d0ae8f348b8a3a96319f17125ae15dc8&scene=126&sessionid=1657718109&key=27ae555f89870204503f6d25629a133674312d58c0ce351c60d4b859e2ecfde65d4576ffdb50c67d7db252cbaf281077291f6f72c8e7516030f862fb8473bee4a36910dba070c5aff97dbea14584d7320f65f13e4c16f73c9b41cb0233b554ac464da932de8f1b85e669a2a83bd1ddfcf7d5f9a43a6a62d5cbf8d8dbf6b7eb75&ascene=15&uin=NTY2NTA4NjQ%3D&devicetype=Windows+Server+2016+x64&version=6307001e&lang=zh_CN&session_us=gh_e57baf46bdf5&exportkey=A4WiWQsFfs4f1vu3WkD3khM%3D&acctmode=0&pass_ticket=O9p3G7PdEr0a25dnjzPGoeACb%2B44QGGmi2QDvxRbLz3OQTA5VDMY0PAG%2B%2BeVSXtL&wx_header=0&fontgear=2)@军机故阁
- [ ] [Go 代码审计高危漏洞(sqli\cmd\ssrf)](http://zeo.cool/2022/10/30/Go%20%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1%E9%AB%98%E5%8D%B1%E6%BC%8F%E6%B4%9E(sqli!cmd!ssrf)/)@Zeo
- [ ] [Go 代码审计漏洞(File Operation\Redirect\Cors)](http://zeo.cool/2022/11/05/Go%20%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1%E6%BC%8F%E6%B4%9E(File%20Operation!Redirect!Cors)/)@Zeo
- [ ] [Go代码审计—Gorm框架常见SQL注入场景](https://sec-in.com/article/1316)@sec-in
- [ ] [Xcheck之Golang安全检查引擎](https://zhuanlan.zhihu.com/p/356381220)@Kg55nY
- [ ] [Golang审计 恶意 zip 文件导致目录穿越文件上传](https://bingbingzi.cn/post/golang-shen-ji-e-yi-zip-wen-jian-dao-zhi-mu-lu-chuan-yue-wen-jian-shang-chuan/)@bingbingzi
- [ ] [Go语言代码安全审计分享](https://www.freebuf.com/articles/web/224363.html)@mengz
- [ ] [Go代码审计：Gitea远程命令执行漏洞链](https://www.freebuf.com/articles/network/177699.html)@phithon
- [ ] [Go代码审计学习（一）](https://blog.csdn.net/weixin_49656607/article/details/128291716)@paidx0
- [ ] [Go代码审计学习（二）](https://blog.csdn.net/weixin_49656607/article/details/128291872?spm=1001.2014.3001.5502)@paidx0

二、优秀项目
- [ ] https://github.com/Firebasky/Go

三、其他资源
- [ ] https://github.com/madneal/sec-dog

## 02-Go安全研究工具

工欲善其事必先利其器，此处收集Go语言代码审计的工具。期待自己的代码审计工具能够早日发布！

一、SAST
- [ ] https://github.com/ASTTeam/SAST
- [ ] https://github.com/ASTTeam/DAST
- [ ] https://github.com/ASTTeam/IAST

二、Others
- [ ] https://github.com/quasilyte/go-ruleguard
- [ ] https://github.com/securego/gosec
- [ ] https://github.com/goer3/chang-e
- [ ] https://github.com/cyj19/go-web

## 03-Go语言漏洞环境

此处收集整理Go安全漏洞研究的一些环境，包括Web环境，应用框架漏洞环境等。

- [ ] https://github.com/0c34/govwa
- [ ] https://github.com/Hardw01f/Vulnerability-goapp
- [ ] https://github.com/leveryd/go-sec-code
- [ ] https://github.com/george518/PPGo_Job
- [ ] https://github.com/XM-GO/PandaX
- [ ] https://github.com/xiusin/pinecms
- [ ] https://github.com/gogs/gogs
- [ ] https://github.com/go-gitea/gitea

## 04-Go语言漏洞类型

- [ ] Go反序列化漏洞
- [ ] 任意命令执行漏洞
- [ ] 任意文件上传漏洞
- [ ] 任意文件写入漏洞
- [ ] 任意文件包含漏洞
- [ ] 任意文件删除漏洞
- [ ] SQL注入漏洞
- [ ] 业务逻辑漏洞
- [ ] 变量覆盖漏洞
- [ ] XSS漏洞
- [ ] XXE漏洞
- [ ] SSRF漏洞
- [ ] CSRF漏洞

## 05-Go语言代码审计

一、Go语言代码审计实战

## 06-Go语言安全开发

一、Go安全编码规范

二、Go安全漏洞修复

## 07-Go安全参考资源

本人在学习Go安全的过程中遇到了很多优秀的Go安全研究员，感谢这些研究者！排名不分先后。

[![Stargazers over time](https://starchart.cc//HackGolang/HackGolang.svg)](https://starchart.cc/HackGolang/HackGolang)