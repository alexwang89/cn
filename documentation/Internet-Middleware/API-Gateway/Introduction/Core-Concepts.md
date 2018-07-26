# 核心概念
以下是API网关帮助文档中使用到的概念及其解释，请参考。

| 概念 | 解释 |
| :- | :- |
|  访问密钥  |  用户需要创建访问密钥, 作为调用 API 时的身份 。 |	
| APIKey/APISecret | API调用者的密钥用于API提供者使用API时，网关校验API调用者的访问时使用。加密计算后放入请求中作为签名信息。 |
| AK/SK | Access Key/Access Key Secret京东云用户的密钥.通常为API定义者使用，用于校验网关与API提供者服务器的通信。|
| API定义者 | API的提供方。定义API，并通过授权将API开放给调用方使用。 |
| API调用者 | API的调用方。通过已被授权的AK或者APIIKey，可调用API。 |
|  授权  |  授予某个API调用者，调用某个 API 的权限，由 API 服务方完成。 APP 被授权后才能调用 API。  |
|  API 生命周期  |   API 服务方分阶段的管理 API ，包括 API 的创建、测试、发布、下线、版本切换等。 |
|  API 定义  |  API 服务方创建 API 时，设置的 API 的后端服务、请求格式、接收格式、返回格式等规则内容 。 |
|  参数映射  |   用户实际请求的参数与 API 服务后端参数不一致时，支持 API 服务方配置参数映射。 |
|  参数校验  |  API 服务方对入参设置校验规则，由网关根据规则对无效请求进行过滤。 |
|  常量参数  |  不需要用户传入的，但是后端服务需要始终接收的常量参数 。 |
|   系统参数 |   您可以设置网关向您后端抛请求时，附带一些系统参数，如CaClientIp，即请求IP等。 |
|   API 分组 |  API 服务方管理 API 的单元。创建 API 需要先创建分组 。 |
|  自定义域名  |  开放 API 服务，需要为分组绑定独立域名。客户通过访问该独立域名调用 API。 |
|  流控策略  | 用于 API 服务方对 API 、用户、 APP 按天、小时、分钟进行流量限制。|
| 访问授权 |   。 |
| 后端签名   |   。 |
| 版本修订   |   。 |
| 部署列表   |  服务发布的目标。在服务内 API 配置完成后，进行发布到具体环境后才可对外提供服务。现有环境包括：测试、预发布、发布。 。 |
| 请求方法   |  HTTP method，包括 GET、POST、PUT、PATCH、DELETE、HEAD。 |
| 发布   |   暴露 API 以便外部能够进行访问的过程。发布的对象是服务，以当前的 API 配置为准。进行发布后，API 才可被外部访问到。|



## 相关参考

- [产品概述](../Introduction/Overview.md)
- [产品规格](../Introduction/Specification.md)
- [价格总览](../Pricing/Price-Overview.md)
- [创建实例](../Getting-Started/Create-Instance.md)