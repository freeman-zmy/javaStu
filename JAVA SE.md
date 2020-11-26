# JAVA SE J2EE
    Java SE（Java Standard Edition，Java 标准版）是Java技术的核心和基础，是Java ME和Java EE编程的基础 。
    Java SE是由Sun Microsystems公司于1995年5月推出的Java程序设计语言和Java平台的总称。
    用Java实现的Hot Java浏览器（支持Java applet）显示了Java的魅力：跨平台、动态的Web、Internet计算。
    从此，Java被广泛接受并推动了Web的迅速发展，常用的浏览器均支持Java applet。
## 目录

- [版本平台](#版本平台)
- [分类](#分类)
- [详细介绍](#详细介绍)
- [java技术之父](#java技术之父)

### 版本平台
  Java2平台有3个版本，它们是适用于小型设备和智能卡的Java2平台Micro版（Java2 Platform Micro Edition，JavaME）、适用于桌面系统的Java 2平台标准版（Java2 Platform Standard Edition，Java SE）、适用于创建服务器应用程序和服务的Java 2平台企业版（Java2 Platform Enterprise Edition，Java EE）
### 分类
#### 企业版(Java EE)
    Java EE是一种利用Java2平台来简化企业解决方案的开发、部署和管理相关的复杂问题的体系结构。J2EE技术的基础就是核心Java平台或Java2平台的标准版，Java EE不仅巩固了标准版中的许多优点，例如“编写一次、随处运行”的特性、方便存取数据库的JDBC API、CORBA技术以及能够在Internet应用中保护数据的安全模式等等，同时还提供了对 EJB（Enterprise JavaBeans）、Java Servlets API、JSP（Java Server Pages）以及XML技术的全面支持。其最终目的就是成为一个能够使企业开发者大幅缩短投放市场时间的体系结构。
    Java EE体系结构提供中间层集成框架用来满足无需太多费用而又需要高可用性、高可靠性以及可扩展性的应用的需求。通过提供统一的开发平台，J2EE降低了开发多层应用的费用和复杂性，同时提供对现有应用程序集成强有力支持，完全支持EJB，有良好的向导支持打包和部署应用，添加目录支持，增强了安全机制，提高了性能。
#### 标准版(Java SE)
    Java SE 是Java平台标准版的简称（Java Platform, Standard Edition） (also known as Java 2 Platform) ，用于开发和部署桌面、服务器以及嵌入设备和实时环境中的Java应用程序。Java SE包括用于开发Java Web服务的类库，同时，Java SE为Java EE和Java ME提供了基础。Java SE（Java Platform, Standard Edition，Java标准版）就是基于JDK和JRE，包含支持 Java Web 服务开发的类，并为 Java 企业级开发提供基础。
#### Micro版(Java ME)
    Java ME是Java微版的简称（Java Platform,Micro Edition），是一个技术和规范的集合，它为移动设备（包括消费类产品、嵌入式设备、高级移动设备等）提供了基于Java环境的开发与应用平台。Java ME分为两类配置，一类是面向小型移动设备的CLDC（Connected Limited Device Profile），一类是面向功能更强大的移动设备如智能手机和机顶盒，称为CDC（Connected Device Profile CDC）。
    Java ME有自己的类库，其中CLDC使用的是专用的Java虚拟机叫做JVM。
### 详细介绍
    JAVA SE是运行JAVA程序不可缺少的环境。一旦拥有Java软件，您即会进入一个全新的互动世界。
    Java语言恐怕是稳居网路应用程序语言的首选了，这都要归功于它高度的安全性以及跨平台的特性，几乎在所有的电脑平台上您都可以见得到Java的芳踪。过去很可能会有不少人抱怨Java虽然有着相当不错的跨平台以及安全防护等特性，但是它的执行速度远远不及C++等各种传统惯用的程序语言。
    不过这次SunMicrosystem可是有备而来的，不仅在执行速度上有大幅度的改革，而且在内容上也有做了一些修改以及增强。最新JAVA运行库，建立一个运行JAVA的环境。这一升级版对Java Plug-in进行了功能增强，提供了对Netscape 6OpenJVM整合支持等等。由于JRE新增的功能以及程序修正之处相当多，如果需要详尽资料的话不妨可以参考Sun的官方网页。多语系版，支持简体中文界面。
    Java是所有编程语言中最流行、发展最快的语言之一，随着Java SE 6.0的发布，Java也变得更加强大和易用。本书结合丰富的程序实例，为读者详细讲解了Java核心技术的各个方面，囊括了Java SE 6.0中提供的各种新特性。
    Java2平台有3个版本，它们是适用于小型设备和智能卡的Java 2平台Micro版（Java 2 Platform Micro Edition，J2ME）、适用于桌面系统的Java2平台标准版（Java 2 Platform Standard Edition，J2SE）、适用于创建服务器应用程序和服务的Java2平台企业版（Java 2 Platform Enterprise Edition，J2EE）。
    J2EE是一种利用Java2平台来简化企业解决方案的开发、部署和管理相关的复杂问题的体系结构。J2EE技术的基础就是核心Java平台或Java 2平台的标准版，J2EE不仅巩固了标准版中的许多优点，例如"编写一次、随处运行"的特性、方便存取数据库的JDBC API、CORBA技术以及能够在Internet应用中保护数据的安全模式等等，同时还提供了对EJB（Enterprise JavaBeans）、Java Servlets API、JSP（Java Server Pages）以及XML技术的全面支持。其最终目的就是成为一个能够使企业开发者大幅缩短投放市场时间的体系结构。
    J2EE体系结构提供中间层集成框架用来满足无需太多费用而又需要高可用性、高可靠性以及可扩展性的应用的需求。通过提供统一的开发平台，J2EE降低了开发多层应用的费用和复杂性，同时提供对现有应用程序集成强有力支持，完全支持Enterprise JavaBeans，有良好的向导支持打包和部署应用，添加目录支持，增强了安全机制，提高了性能。
    Java SE 是Java平台标准版的简称（Java Platform, Standard Edition） (also known as Java 2 Platform) ，用于开发和部署桌面、服务器以及嵌入设备和实时环境中的Java应用程序。Java SE包括用于开发Java Web服务的类库，同时，Java SE为Java EE提供了基础。
### java技术之父
    詹姆斯·高斯林 [2]  博士以“Java技术之父”闻名于世。他是Java技术的创始人， 作为Sun研究院院士，他亲手设计了Java语言，完成了Java技术的原始编译器和虚拟机。在他的带领下，Java现已成为互联网的标准编程模式以及分布式企业级应用的事实标准，其跨平台的技术优势为网络计算带来了划时代的变革。詹姆斯·高斯林博士积极致力于软件开发工具的研究，以使软件开发工具的功能更强大，更容易为开发人员所使用，确保应用、服务开发的迅速完成。
    Java技术是Sun公司在1995年5月正式推出的。十多年来，Java已从编程语言发展成为全球第一大通用开发平台。Java技术已为计算机行业主要公司所采纳，同时也被越来越多的国际技术标准化组织所接受。1999年，Sun推出了以Java 2平台为核心的J2EE、J2SE和J2ME三大平台。随着三大平台的迅速推进，在世界上形成了一股巨大的Java应用浪潮。同时，Java技术还引发了一场无法停止的大变革，为整个Java社团带来了巨大的潮水般的商业机会。
    Java技术及其应用将有更大的发展。据IDC预计，自2001年起的其后5年内，采用Java的IT产品的价值将翻番，在2006年将达到4.53亿美元，年增长率为14.9%。截止到2003年5月，注册Java Developer Connection (JDC)的Java开发商超过300万人，对JRE(Java运行环境)的下载达7,200万次。Sun在JavaOne 2003大会上确定的目标是，在3～5年内使Java技术开发商从300万发展到1,000万，以支持Java技术这一全球领先技术平台的显赫地位。
### 这是[百度百科](https://baike.baidu.com/item/JAVA%20SE/4662159)
