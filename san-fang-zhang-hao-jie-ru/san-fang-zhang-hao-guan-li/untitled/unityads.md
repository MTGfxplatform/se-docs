# Unityads

## 添加账户

在 资产管理-三方账号管理-投放平台 页面，点击右上角添加账户，选择Unityads进入账户添加页面

![](<../../../.gitbook/assets/image (159).png>)

Unityads平台需要输入的字段为：

* Organization Name：组织名称，标识您此账号所属的组织
* Organization ID：调用报表接口和管理接口的必需字段
* Organization core ID：调用部分管理接口的必需字段
* Report Key：报表接口的API key，调用报表接口的必需字段
* API key\_id：管理接口的API key，调用管理接口的必需字段
* API secret：管理接口的secret，调用管理接口的必需字段

对应在Unityads后台各字段的位置：

左上角菜单项中选择Acquire-Settings，进入投放的管理页面，拿到如下字段

* Organization->Organization Name
* Organization ID
* Organization core ID
* API key-> Report Key

![](<../../../.gitbook/assets/image (8).png>)

左上角菜单项中选择Setting-Service Accounts，进入服务账号管理页面，创建Service Account，如下图所示，输入一个您可识别的名称后创建账号；注意，当前Service Accouts服务需要单独申请，请联系您在Unity侧的联系人

![](<../../../.gitbook/assets/image (9).png>)

生成账号后，您需要将每一项权限通过右侧编辑按钮，修改为Enabled

![](<../../../.gitbook/assets/image (11).png>)

在最下方Keys部分生成API key，**特别注意**，secret需要生成的时候就复制保存下来，该key只在生成时展示，后续在平台中是查询不到的

* Key ID-> API key\_id
* Secret Key-> API secret

![](<../../../.gitbook/assets/image (10).png>)
