# 创建API分组

API 分组是 API 的基础管理单元。SDK是基于该API分组生成的。需先创建 API 分组，然后在分组下创建 API。
- 分组具有 Region 属性，API 选定分组前需确定 Region，且一旦生成不可更改。
- 基于API分组进行流控、授权访问、后端签名、自定义域名。

![API分组创建流程](https://github.com/jdcloudcom/cn/blob/edit/image/Internet-Middleware/API-Gateway/flow-createApiGroup.png)


## 操作步骤
### STEP1:创建API分组
1. 登录 [API网关 控制台](https://apigateway-console.jdcloud.com/apiGroupList)。

 ![API分组管理](https://github.com/jdcloudcom/cn/blob/edit/image/Internet-Middleware/API-Gateway/apigroup-1.png)
 
 
2. 在“API分组管理”页面，点击 **新建API分组** ，进入“创建”页面。

![创建分组](https://github.com/jdcloudcom/cn/blob/edit/image/Internet-Middleware/API-Gateway/apigroup-addgroup.png)
    
    
3.填写分组信息后，点击保存，即新建分组。当首次新建时，系统会自动将其保存为版本号为0.0.1的版本。后续可在版本管理中进行多版本维护。
