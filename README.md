# 👏👏👏最全空降golang资料补给包（满血战斗），包含文章，书籍，作者论文，理论分析，开源框架，云原生，大佬视频，大厂实战分享ppt

<div  align=center>
<img width="70%" height="70%" src="https://user-images.githubusercontent.com/87457873/128655088-7e2704a7-ce37-4e78-9b9c-a8865597f364.png"/>
  
## —— 未来服务器端编程语言
  
</div>

## 📥 [源码下载](https://github.com/0voice/Introduction-to-Golang/blob/main/%E6%BA%90%E7%A0%81/go1.16.7.src.tar.gz)

Go官网下载地址：https://golang.org/dl/

Go官方镜像站（推荐）：https://golang.google.cn/dl/

## 🏃‍♂ [开启Go语言学习之旅，从"Hello World"开始！](https://github.com/0voice/Introduction-to-Golang/blob/main/%E6%90%AD%E5%BB%BAGo%E8%AF%AD%E8%A8%80%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/%E4%BB%8E%E9%9B%B6%E5%BC%80%E5%A7%8B%E6%90%AD%E5%BB%BAGo%E8%AF%AD%E8%A8%80%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83.md)

<div  align=center>
  
![image](https://user-images.githubusercontent.com/87457873/128685884-d52fd32f-ed6e-4b7b-b9ef-a78bef3354a4.png)

</div>

### Step 1：了解源代码目录结构
  
<div  align=center>

![image](https://user-images.githubusercontent.com/87457873/128687226-8ac5bb7c-f09b-4cb3-afc0-cf18bff9d15a.png)
  
</div>

<br>

```
|– AUTHORS — 文件，官方 Go语言作者列表
|– CONTRIBUTORS — 文件，第三方贡献者列表
|– LICENSE — 文件，Go语言发布授权协议
|– PATENTS — 文件，专利
|– README — 文件，README文件，大家懂的。提一下，经常有人说：Go官网打不开啊，怎么办？其实，在README中说到了这个。
该文件还提到，如果通过二进制安装，需要设置GOROOT环境变量；如果你将Go放在了/usr/local/go中，则可以不设置该环境变
量（Windows下是C:\go）。当然，建议不管什么时候都设置GOROOT。另外，确保$GOROOT/bin在PATH目录中。
|– VERSION — 文件，当前Go版本
|– api — 目录，包含所有API列表，方便IDE使用
|– doc — 目录，Go语言的各种文档，官网上有的，这里基本会有，这也就是为什么说可以本地搭建”官网”。
这里面有不少其他资源，比如gopher图标之类的。
|– favicon.ico — 文件，官网logo
|– include — 目录，Go 基本工具依赖的库的头文件
|– lib — 目录，文档模板
|– misc — 目录，其他的一些工具，相当于大杂烩，大部分是各种编辑器的Go语言支持，还有cgo的例子等
|– robots.txt — 文件，搜索引擎robots文件
|– src — 目录，Go语言源码：基本工具（编译器等）、标准库
|– test — 目录，包含很多测试程序（并非_test.go方式的单元测试，而是包含main包的测试），包括一些fixbug测试。
可以通过这个学到一些特性的使用。
```
### Step 2：Golang开发后台掌握哪些知识点？

这里我给大家整理归纳为四大块，分别是**语法**、**中间件**、**后端开发**、**云原生**。

我们通过这个四个板块的学习，逐步进阶成一个可以从事后端服务器开发的工程师。

<div  align=center>
  
![image](https://user-images.githubusercontent.com/87457873/128867223-af882655-eaa7-4523-b737-b3de4c4f5b56.png)

</div>

下面我们简单介绍中间件和云原生：

#### 中间件

MySQL、Redis、MongoDB、Kafka这些常见的中间件，这里我们不做赘述。我们着重简述下Gin、etcd、ElasticSearch、gRPC。

* **Gin**<br>
Gin是一个用Go (Golang)编写的HTTP web框架。它具有一个类似martinii的API，性能要好得多——快了40倍。<br>
官方Github项目：https://github.com/gin-gonic/gin

* **etcd**<br>
Etcd是一种强一致性的分布式键值存储，它提供了一种可靠的方法来存储需要被分布式系统或机器集群访问的数据。它可以在网络分区期间优雅地处理leader选举，并且可以容忍机器故障，即使是leader节点。<br>
官网：https://www.elastic.co/cn/elasticsearch/

* **ElasticSearch**<br>
Elasticsearch 是一个分布式、RESTful 风格的搜索和数据分析引擎，能够解决不断涌现出的各种用例。 作为 Elastic Stack 的核心，它集中存储您的数据，帮助您发现意料之中以及意料之外的情况。<br>
官网：https://etcd.io/

* **gRPC**<br>
gRPC是一个现代的开源高性能远程过程调用(Remote Procedure Call, RPC)框架，可以在任何环境中运行。通过对负载平衡、跟踪、运行状况检查和身份验证的可插拔支持，它可以有效地连接数据中心内和跨数据中心的服务。它也适用于分布式计算的最后一英里，将设备、移动应用程序和浏览器连接到后端服务。<br>
官网：https://grpc.io/

#### 云原生

* **微服务**<br>
微服务是一种软件架构风格，它是以专注于单一责任与功能的小型功能区块为基础，利用模块化的方式组合出复杂的大型应用程序，各功能区块使用与语言无关的API集相互通信。

* **DevOps**<br>
DevOps是一种重视“软件开发人员”和“IT运维技术人员”之间沟通合作的文化、运动或惯例。透过自动化“软件交付”和“架构变更”的流程，来使得构建、测试、发布软件能够更加地快捷、频繁和可靠。 

* **持续部署**
持续部署，是一种软件工程方法，意指在软件开发流程中，以自动化方式，频繁而且持续性的，将软件部署到生产环境中，使软件产品能够快速的发展。

持续部署可以整合到持续整合与持续交付（Continuous delivery）的流程之中。

* **容器化**<br>
容器化是软件开发的一种方法，通过该方法可将应用程序或服务、其依赖项及其配置（抽象化为部署清单文件）一起打包为容器映像。 容器化应用程序可以作为一个单元进行测试，并可以作为容器映像实例部署到主机操作系统 (OS)。

### Step 3：如何高效地学习Go？

## 📚 资料包

<div  align=center>
  
![128686978-0d16ca8a-d070-4c3b-a4d9-640b265acc8d](https://user-images.githubusercontent.com/87457873/128688161-b51fbcb9-7e6e-4247-9911-4b94a35246b3.png)
  
</div>

---

### 📕 书籍

#### 入门

[《Go 入门指南》](https://github.com/0voice/Introduction-to-Golang/blob/main/%E7%94%B5%E5%AD%90%E4%B9%A6%E7%B1%8D/%E3%80%8AGo%20%E5%85%A5%E9%97%A8%E6%8C%87%E5%8D%97%E3%80%8B.pdf)

[《Go语言101》](https://github.com/0voice/Introduction-to-Golang/blob/main/%E7%94%B5%E5%AD%90%E4%B9%A6%E7%B1%8D/%E3%80%8AGo%E8%AF%AD%E8%A8%80101%E3%80%8B.pdf)

《Go语言趣学指南》

《Go语言从入门到进阶实战》

[《Go语言学习笔记》](https://github.com/0voice/Introduction-to-Golang/blob/main/%E7%94%B5%E5%AD%90%E4%B9%A6%E7%B1%8D/%E3%80%8AGo%E8%AF%AD%E8%A8%80%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E3%80%8B.pdf)

[《Go语言入门经典》:hdcy](https://pan.baidu.com/s/15eMLovSIrdCLoILMjr4vBQ)

[《Go语言编程》](https://github.com/0voice/Introduction-to-Golang/blob/main/%E7%94%B5%E5%AD%90%E4%B9%A6%E7%B1%8D/%E3%80%8AGo%E8%AF%AD%E8%A8%80%E7%BC%96%E7%A8%8B%E3%80%8B%E9%AB%98%E6%B8%85%E5%AE%8C%E6%95%B4%E7%89%88%E7%94%B5%E5%AD%90%E4%B9%A6.pdf)

[《Go语言实战》](https://github.com/0voice/Introduction-to-Golang/blob/main/%E7%94%B5%E5%AD%90%E4%B9%A6%E7%B1%8D/%E3%80%8AGo%E8%AF%AD%E8%A8%80%E5%AE%9E%E6%88%98%E3%80%8B.epub)

[《Go Web 编程》](https://github.com/0voice/Introduction-to-Golang/blob/main/%E7%94%B5%E5%AD%90%E4%B9%A6%E7%B1%8D/%E3%80%8AGo%20Web%20%E7%BC%96%E7%A8%8B%E3%80%8B.epub)

[《Go语言编程入门与实战技巧》:sgro](https://pan.baidu.com/s/1DlkBN8dRWmCHymyD4pJMCg)

#### 进阶

[《Go 语言圣经》](https://github.com/0voice/Introduction-to-Golang/blob/main/%E7%94%B5%E5%AD%90%E4%B9%A6%E7%B1%8D/%E3%80%8AGo%20%E8%AF%AD%E8%A8%80%E5%9C%A3%E7%BB%8F%E3%80%8B.pdf)

[《Go专家编程》](https://github.com/0voice/Introduction-to-Golang/blob/main/%E7%94%B5%E5%AD%90%E4%B9%A6%E7%B1%8D/%E3%80%8AGO%E4%B8%93%E5%AE%B6%E7%BC%96%E7%A8%8B%E3%80%8B.pdf)

[《Go 语法树入门》](https://github.com/0voice/Introduction-to-Golang/blob/main/%E7%94%B5%E5%AD%90%E4%B9%A6%E7%B1%8D/%E3%80%8AGo%E8%AF%AD%E6%B3%95%E6%A0%91%E5%85%A5%E9%97%A8%E3%80%8B.pdf)

[《Go语言程序设计》:flnj](https://pan.baidu.com/s/11WpEqd9Fa7Ur5dH1XJdGtg)

[《Go语言高级编程》](https://github.com/0voice/Introduction-to-Golang/blob/main/%E7%94%B5%E5%AD%90%E4%B9%A6%E7%B1%8D/%E3%80%8AGo%E8%AF%AD%E8%A8%80%E9%AB%98%E7%BA%A7%E7%BC%96%E7%A8%8B%E3%80%8B.pdf)

《Go语言核心编程》

《Go语言高并发与微服务实战》

[《Go并发编程实战》第2版：lsn0](https://pan.baidu.com/s/1fAjT7l16hY8ryXlknnSL-A)

[《Go语言并发之道》:6ppw](https://pan.baidu.com/s/1w6SbSkcjqFN1WiG2oS7XaA)

---

### 📖 文章

[Go语言之goroutine协程详解](https://github.com/0voice/Introduction-to-Golang/blob/main/%E6%96%87%E7%AB%A0/Go%E8%AF%AD%E8%A8%80%E4%B9%8Bgoroutine%E5%8D%8F%E7%A8%8B%E8%AF%A6%E8%A7%A3.md)

[Golang之sync.Pool对象池对象重用机制总结](https://github.com/0voice/Introduction-to-Golang/blob/main/%E6%96%87%E7%AB%A0/Golang%E4%B9%8Bsync.Pool%E5%AF%B9%E8%B1%A1%E6%B1%A0%E5%AF%B9%E8%B1%A1%E9%87%8D%E7%94%A8%E6%9C%BA%E5%88%B6%E6%80%BB%E7%BB%93.md)

[Golang的GC和内存逃逸](https://github.com/0voice/Introduction-to-Golang/blob/main/%E6%96%87%E7%AB%A0/Golang%E7%9A%84GC%E5%92%8C%E5%86%85%E5%AD%98%E9%80%83%E9%80%B8.md)

[GO语言之垃圾回收机制](https://github.com/0voice/Introduction-to-Golang/blob/main/%E6%96%87%E7%AB%A0/GO%E8%AF%AD%E8%A8%80%E4%B9%8B%E5%9E%83%E5%9C%BE%E5%9B%9E%E6%94%B6%E6%9C%BA%E5%88%B6.md)

[Go内存分配那些事，就这么简单](https://github.com/0voice/Introduction-to-Golang/blob/main/%E6%96%87%E7%AB%A0/Go%E5%86%85%E5%AD%98%E5%88%86%E9%85%8D%E9%82%A3%E4%BA%9B%E4%BA%8B%EF%BC%8C%E5%B0%B1%E8%BF%99%E4%B9%88%E7%AE%80%E5%8D%95%EF%BC%81.md)

[Go语言TCP Socket编程](https://github.com/0voice/Introduction-to-Golang/blob/main/%E6%96%87%E7%AB%A0/Go%E5%86%85%E5%AD%98%E5%88%86%E9%85%8D%E9%82%A3%E4%BA%9B%E4%BA%8B%EF%BC%8C%E5%B0%B1%E8%BF%99%E4%B9%88%E7%AE%80%E5%8D%95%EF%BC%81.md)

[从源码角度看 Golang 的调度](https://github.com/0voice/Introduction-to-Golang/blob/main/%E6%96%87%E7%AB%A0/%E4%BB%8E%E6%BA%90%E7%A0%81%E8%A7%92%E5%BA%A6%E7%9C%8B%20Golang%20%E7%9A%84%E8%B0%83%E5%BA%A6.md)

---

### 💽 视频

<br>

<div align=center>
  
title | Link
:------ | :------:
Go (Golang) Tutorial - Go语言入门教程 #1 ~ #22 | [百度网盘：btjy](https://pan.baidu.com/s/1gOHgMWDkJnDkMYtsg7fwGg)
GopherCon 2017- Russ Cox - The Future of Go | [百度网盘：zx1w](https://pan.baidu.com/s/1pFP8QbNxV6sBYZAPNelnRw)
GopherCon 2018- George Tankersley - Micro optimizing Go Code | [百度网盘：tzau](https://pan.baidu.com/s/1r7C6wsmQVnQkiWpWnDnLxA)
GopherCon 2018- Kat Zien - How Do You Structure Your Go Apps | [百度网盘：qmrq](https://pan.baidu.com/s/1BuM-Fd1_3NOawMpleB_cSA)
GopherCon 2018 Lightning Talk- Aidan Coyle - Lazy JSON Parsing | [百度网盘：g4f5](https://pan.baidu.com/s/1axakvOf4Yvk4VZX0nvOIDg)
GopherCon 2018 Lightning Talk- Alan Braithwaite - Web Session Management in Go | [百度网盘：2ibm](https://pan.baidu.com/s/16vqxJ4CDp3kXQEWgoQQZOQ)
GopherCon 2018 Lightning Talk- Hugo Torres - Talking to the Docker Socket | [百度网盘：unlh](https://pan.baidu.com/s/10y_32K0tV2l_LAe_ifE38w)
GopherCon 2019- Dave Cheney - Two Go Programs, Three Different Profiling Techniques | [百度网盘：kgjj](https://pan.baidu.com/s/1sbgzy7YFs_GbLcro299r2Q)
Let's Go - Why I'm moving to Go Programming Language - Why GoLang has a Promising Future | [百度网盘：ewon](https://pan.baidu.com/s/1HXRrbIQkkftU3x0KZymUpw)
Golang's Garbage - USENIX | [百度网盘：kkl4](https://pan.baidu.com/s/18HzVf2jLrgoTmbwCjRR0LA)
Golang REST API With Mux | [百度网盘：el4d](https://pan.baidu.com/s/1TrsNS6sgxFb8nj09HcP3rw)
Golang Crash Course | [百度网盘：v4jw](https://pan.baidu.com/s/1QXJW21hm-hOJ1hxMzkQoog)
Brad Fitzpatrick Go 1 11 and beyond | [百度网盘：yg9r](https://pan.baidu.com/s/1RsZHVCH3xI6hLfyCxCPS2g)
dotGo 2015 - Rob Pike - Simplicity is Complicated | [百度网盘：594c](https://pan.baidu.com/s/1RcfgpuCzYToBnaHMwfhjIw)
  
</div>

---

### ☁ 云原生

---

### 📄 论文与理论分析

---

### 🏗 开源框架

---

### 🖼 大厂实战分享ppt



























