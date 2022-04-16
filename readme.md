# Hugo 案例

<toc>

<p align="center"><b> 中文 | <a href="./readme_en.md"> English </a>  </b></p>

- [快速开始](#快速开始)
    - [通过应用中心部署](#通过应用中心部署)
    - [通过命令行工具部署](#通过命令行工具部署)
- [应用详情](#应用详情)
- [相关链接](#相关链接)

</toc>

# 快速开始

- [:octocat: 源代码](https://github.com/liufangchen/start-hugo)
- [:earth_africa: 效果预览](http://start-hugo.testservice.1401662146685254.cn-hangzhou.fc.devsapp.net/)

## 通过应用中心部署

<appcenter>

您可以在阿里云 [:earth_asia: Serverless 应用中心](https://fcnext.console.aliyun.com/applications/create?template=website-hugo) ，快速体验该应用：   
[![Deploy with Severless Devs](https://img.alicdn.com/imgextra/i1/O1CN01w5RFbX1v45s8TIXPz_!!6000000006118-55-tps-95-28.svg)](https://fcnext.console.aliyun.com/applications/create?template=website-hugo) 

</appcenter>

## 通过命令行工具部署
> 在开始之前，需要先安装 Serverless Devs 开发者工具：`npm install @serverless-devs/s -g`，更多安装方法，可以参考[Serverless Devs 安装文档](https://www.serverless-devs.com/serverless-devs/install) ，针对阿里云还需要配置密钥信息，配置密钥信息的方法可以参考[阿里云密钥配置文档](https://www.serverless-devs.com/fc/config)
- 初始化项目：`s init website-hugo -d website-hugo`    
    > 涉及到确定密钥的选择、服务名称的确定、函数名称的确定以及容器镜像的确定    
- 进入项目：`cd website-hugo`
- 部署项目：`s deploy -y`
- 调用函数： 根据返回的`url`信息，在浏览器中进行请求即可

# 应用详情

本项目是利用静态网站构建框架 `hugo`，部署到阿里云 Serverless 平台（函数计算 FC）。

> Hugo 是最流行的开源静态站点生成器之一。凭借其惊人的速度和灵活性，Hugo 让搭建网站再次变得有趣。

通过 Serverless Devs 开发者工具，您只需要几步，就可以体验 Serverless 架构，带来的降本提效的技术红利。

部署完成之后，您可以看到系统返回给您的案例地址，例如：

![图片alt](https://github.com/liufangchen/Resource/raw/start-hugo/url.png)

此时，打开案例地址，就可以看到测试的应用详情：

![图片alt](https://github.com/liufangchen/Resource/raw/start-hugo/view.png)

# 相关链接
- Serverless Devs 工具：
    - 仓库：[https://www.github.com/serverless-devs/serverless-devs](https://www.github.com/serverless-devs/serverless-devs)    
    - 官网：[https://www.serverless-devs.com/](https://www.serverless-devs.com/)
- 阿里云函数计算组件：
    - 仓库：[https://github.com/devsapp/fc](https://github.com/devsapp/fc)
    - 帮助文档：[https://www.serverless-devs.com/fc/readme](https://www.serverless-devs.com/fc/readme)
- Hogo：
    - 仓库：[https://github.com/gohugoio/hugo](https://github.com/gohugoio/hugo)
    - 官网：[https://gohugo.io](https://gohugo.io)